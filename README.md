# 🌍 My Travel Journal

A responsive, component-driven travel journal web application built with **React**. This project displays curated travel destinations using dynamic data rendering and reusable UI components.

---

## 📌 Features

- **Component-Driven Architecture:** Modular structure utilizing reusable React components (`Header`, `Entry`).
- **Dynamic Data Rendering:** Uses JavaScript array methods (`.map()`) to render destination cards dynamically from a centralized dataset.
- **Props & Spread Syntax:** Demonstrates passing data into components using props and object spread syntax (`{...entry}`).
- **Interactive Links:** Direct integration to view destination locations on Google Maps.
- **Clean Styling:** Styled with modular, mobile-friendly CSS.

---

## 🛠️ Tech Stack

- **React** (v19)
- **JavaScript (ES6+)**
- **HTML5 & CSS3**

---

## 📂 Project Structure

```text
├── components/
│   ├── Header.jsx       # Top navigation header with site branding
│   └── Entry.jsx        # Reusable card component for each travel entry
├── images/
│   ├── globe.png        # Header globe icon
│   └── marker.png       # Map pin icon for destination entries
├── App.jsx              # Main parent component handling data mapping
├── data.js              # Array of destination objects (title, location, dates, etc.)
├── index.css            # Global styling and layout rules
├── index.html           # Root HTML template
└── index.jsx            # Application entry point
