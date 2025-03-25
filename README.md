# 🐾 Pet Shelter Web App

### **Developed by:** Oshan Maharjan & Denver Hogan

---

## 🚀 Overview

This project is a **responsive front-end web application** built to streamline the management of pet records in a shelter. It provides a clean, intuitive interface for displaying, searching, and viewing detailed information about each pet—including their **breed, age, health status, and adoption availability**.

The app features a **main listing page** with pet cards and an individual **detail page** for deeper insights on each animal.

---

## 🔄 Recent Updates

### ✅ Key Changes
- **Replaced `data.json` with `data.js`**: Static data is now stored directly in a JavaScript file for improved efficiency.
- **Updated `scripts.js`**: Refactored to access the `petsData` variable directly from `data.js`.
- **Removed JSON Fetching**: Eliminated the need for `fetch()` since data is now accessible as a global variable.

### 💡 Why Use `data.js` Instead of `data.json`?
- **Direct Access**: No need to fetch — use the data right away.
- **Faster Load Time**: Immediate rendering without async delays.
- **Simplified Codebase**: Fewer error-handling scenarios.
- **Greater Flexibility**: Easily manipulate data directly within JavaScript.

---

## ✨ Features

### 🏠 Main Page
- Displays pet records in a **responsive grid** (2 rows × 3 cards).
- Each pet card includes:
  - Pet name, type, age, and gender.
  - A local image from the `images/` folder.
  - Gender/age icons for visual aid.
  - Clickable link to view detailed pet info.

### 📄 Detail Page
- **Two-column layout** with:
  - Large image of the pet.
  - Detailed info: breed, gender, microchip number, and more.
  - A button to navigate back to the main page.

### 🔍 Interactivity
- **Search by Breed**: Live search filters pets by breed name.
- **Type Filter**: Filter pets by type (e.g., dog, cat).
- **Error Handling**: Displays a **"No Results Found"** message with a GIF if nothing matches.
- **Fully Responsive**: Optimized for desktops, tablets, and mobile devices.

---

## 🛠 Technologies Used

### 💻 Front-End
- **HTML5**: Semantic structure.
- **CSS3**: Custom styling and layout.
- **Bootstrap 5**: For responsive and mobile-first design.
- **JavaScript (ES6)**: Dynamic DOM manipulation and interactivity.

---

## 📄 License

This project is licensed under the **Apache License 2.0**, allowing free use, modification, and distribution.

---

## 🎥 Video Walkthrough

[Click to Watch](https://github.com/user-attachments/assets/1ed034c3-bb76-4f3b-9a2a-99d60937cab1)

---
