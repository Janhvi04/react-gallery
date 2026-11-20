# 🖼️ React Gallery App

A simple and responsive image gallery application built using **React.js, Axios, and Tailwind CSS**. The application fetches images from the Picsum Photos API and displays them in a gallery with pagination functionality.

## 🚀 Features

- Fetch images dynamically using Axios.
- Display images in a clean gallery layout.
- Pagination with Previous and Next buttons.
- Dynamic page navigation.
- Reusable Card component.
- Loading message while fetching images.
- Responsive UI with Tailwind CSS.

## 🛠️ Technologies Used

- **React.js** – Frontend library
- **JavaScript (ES6+)** – Application logic
- **Axios** – API requests
- **Tailwind CSS** – Styling
- **Picsum Photos API** – Image data source
- **Vite** – Development environment

## 📸 API Used

This project uses the Picsum Photos API to fetch images.

API endpoint:

`https://picsum.photos/v2/list?page=1&limit=14`

## 📂 Project Structure

```text
react-gallery/
│
├── public/
├── src/
│   ├── components/
│   │   └── Card.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
└── README.md
```

## 📖 How It Works

1. The application fetches image data from the Picsum Photos API using Axios.
2. React's `useState` manages the image data and current page number.
3. React's `useEffect` fetches new images whenever the page number changes.
4. Images are displayed using a reusable Card component.
5. Previous and Next buttons allow users to navigate between pages.

## 👩‍💻 Author

**Janhvi Goythale**

GitHub: [Janhvi04](https://github.com/Janhvi04)

---

⭐ If you like this project, consider giving it a star!
