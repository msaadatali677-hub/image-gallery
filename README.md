# 🖼️ Image Gallery — CodeWithSaadat

A modern, responsive **Image Gallery Website** built with **HTML, CSS, and JavaScript**.

The project provides a clean gallery interface where users can explore images, search by title/category, filter images, and open images in a full-screen lightbox with navigation controls.

## 🚀 Live Demo

👉 **[View Live Demo](https://image-gallery-silk-phi.vercel.app/)**

> Replace `#` with your GitHub Pages, Netlify, Vercel, or other live website URL.

---

## 📌 Features

* 🖼️ Responsive image gallery
* 🔍 Image search functionality
* 🏷️ Category-based image filtering
* 🌿 Nature category
* 🏙️ City category
* 🐾 Animals category
* 💻 Technology category
* 🔎 Full-screen lightbox view
* ⬅️ Previous image navigation
* ➡️ Next image navigation
* ❌ Close lightbox button
* ⌨️ Keyboard navigation
* ✨ Smooth hover effects
* 🎨 Modern dark-themed UI
* 📱 Mobile-friendly responsive design
* ⚡ Smooth transitions and animations
* 🖥️ Responsive layout for desktop, tablet, and mobile

The gallery uses a responsive CSS grid and adapts its layout for smaller screens.

---

## 🛠️ Technologies Used

| Technology | Purpose                                        |
| ---------- | ---------------------------------------------- |
| HTML5      | Website structure                              |
| CSS3       | Styling, layout, animations and responsiveness |
| JavaScript | Gallery functionality and interactions         |
| Unsplash   | Demo image sources                             |

---

## 📂 Project Structure

```text
Image-Gallery/
│
├── index.html
└── README.md
```

The project is currently designed as a simple **single-page website**, with HTML, CSS, and JavaScript contained in `index.html`.

---

## 🎯 Main Functionality

### 🔍 Search Images

Users can search images by their **title or category** using the search box.

Example:

```text
Mountain
City
Animals
Technology
Programming
```

The JavaScript checks the image title and category while the user types.

---

### 🏷️ Image Categories

The gallery includes multiple categories:

* All
* Nature
* City
* Animals
* Technology

Users can click a category button to display matching images.

---

### 🔎 Lightbox

Clicking an image opens it in a large **lightbox view**.

The lightbox includes:

* Previous button
* Next button
* Close button
* Image title
* Full-size image display

---

### ⌨️ Keyboard Controls

When the lightbox is open, users can control the gallery using the keyboard:

| Key   | Action         |
| ----- | -------------- |
| `←`   | Previous image |
| `→`   | Next image     |
| `Esc` | Close lightbox |

---

## 🎨 UI & Design

The website uses a modern dark interface with:

* Dark background
* Cyan accent color
* Rounded gallery cards
* Image zoom hover effect
* Gradient overlays
* Smooth transitions
* Responsive grid layout

The image cards use a hover zoom effect and animated overlay to display the image title and category.

---

## 📱 Responsive Design

The gallery is designed to work across different screen sizes.

### Desktop

Images are displayed in a multi-column responsive grid.

### Tablet

The grid automatically adjusts according to available space.

### Mobile

The gallery changes to a smaller two-column layout, while very small screens use a single-column layout.

---

## ⚙️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Image-Gallery.git
```

### 2. Open the project

```bash
cd Image-Gallery
```

### 3. Run the website

Open:

```text
index.html
```

You can also use **VS Code Live Server** for development.

---

## 🖼️ Adding Your Own Images

You can replace the existing image URLs inside `index.html`.

Example:

```html
<img
  src="images/my-photo.jpg"
  alt="My Photo"
>
```

You can create an `images` folder:

```text
Image-Gallery/
│
├── index.html
├── README.md
│
└── images/
    ├── photo1.jpg
    ├── photo2.jpg
    ├── photo3.jpg
    └── photo4.jpg
```

---

## 📚 Learning Objectives

This project was created to practice:

* HTML page structure
* CSS Grid
* Responsive web design
* CSS hover effects
* CSS transitions
* JavaScript DOM manipulation
* JavaScript event listeners
* Array manipulation
* Search functionality
* Category filtering
* Lightbox implementation
* Keyboard events

---

## 🔮 Future Improvements

Possible future updates:

* 📤 Upload your own images
* ❤️ Like/favorite images
* ⬇️ Download image button
* 🌙 Dark/Light mode
* 📊 Image counter
* 🖼️ Masonry gallery layout
* 🔗 Share image button
* ❤️ Favorites stored with LocalStorage
* 🗂️ Custom image categories
* 📱 Swipe navigation for mobile
* 🖥️ Full-screen mode

---

## 👨‍💻 Developer

**CodeWithSaadat**

Frontend Developer | Web Developer | AI Learner

### Connect With Me

* 🌐 Portfolio: https://codewithsaadat.netlify.app/
* 💻 GitHub: https://github.com/msaadatali677-hub
* 📸 Instagram: https://instagram.com/code_with_saadat
* 💼 LinkedIn: https://linkedin.com/in/saadat-ali-3021ab3a5

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ **Star** on GitHub.

Your support motivates me to build more projects and continue learning web development.

---

## 📄 License

This project is created for **learning and educational purposes** by **CodeWithSaadat**.

Feel free to explore and modify the code for your own learning.
