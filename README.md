# 🖼️ SnapSearch – Image Search Engine Web App

## 📽️ Demo

> Discover the seamless image browsing experience with **SnapSearch**:

https://github.com/user-attachments/assets/8e54145c-accd-4b1a-86f4-e9d1e891dc2c

---

## 🧾 Overview

**SnapSearch** is a minimal and responsive image search engine that allows users to search and explore high-quality images in real-time using the **Unsplash API**. Designed using **HTML**, **CSS**, and **JavaScript**, the app showcases results dynamically with smooth transitions, making photo discovery intuitive and engaging.

---

## ✨ Features

- 🔎 Real-time image search using the **Unsplash API**
- 📥 Fetches results in **pages** using `client_id` and `query` parameters
- ♾️ **Infinite scrolling** via "Show More" button with page tracking
- 💡 Clear UI feedback: hides button when not needed, resets layout on new search
- 📱 Fully responsive grid layout using **CSS Grid**
- ✨ Minimal, elegant UI styled with custom CSS and hover animations

---

## 🔐 API Setup

This project uses the [Unsplash API](https://unsplash.com/documentation) to fetch image results. To make it work:

1. Create a free account on [Unsplash Developers](https://unsplash.com/developers)
2. Create a new app to get your **Access Key**
3. Replace the key in `script.js`:

```js
const accessKey = "YOUR_ACCESS_KEY_HERE";

```

## 🛠️ Built With

![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=flat-square)  
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white&style=flat-square)  
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square)  
![Unsplash API](https://img.shields.io/badge/-Unsplash_API-000000?logo=unsplash&logoColor=white&style=flat-square)

---

## 📁 Folder Structure

```plaintext
Image-Search-Engine/
├── index.html           # Main page layout
├── style.css            # Styling for layout and responsiveness
├── script.js            # Logic for fetching and displaying images
├── spinner.gif          # Loader animation
├── README.md            # Documentation
```

---

## 💻 Installation

1. **Clone the repository:**

```bash
$ git clone https://github.com/UrstrulyBhavana/Image-Search-Engine.git
$ cd Image-Search-Engine
```

2. **Run the App:**

Simply open `index.html` in your browser — no server required.

3. **Configure API Key (Optional):**

If using your own Unsplash API key, replace it inside `script.js` where the `access_key` is defined.

---

## 🧩 Functionalities Recap

1. Users can input search queries and see related photos.
2. Fetches dynamic photo results in real-time using the Unsplash API.
3. Spinner shown during data load to improve UX.
4. Responsive photo grid layout adjusts for all screen sizes.
5. Minimalistic design focused on the image display experience.

---

## 🙋‍♀️ Author

**Linga Bhavana** – Frontend Developer

- 📧 **Email**: [urstrulybhavana1432@gmail.com](mailto:urstrulybhavana1432@gmail.com)  
- 🐙 **GitHub**: [UrstrulyBhavana](https://github.com/UrstrulyBhavana)

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for full details.
