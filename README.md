# 🌿 Paradise Nursery - E-Plant Shopping Application

Welcome to **Paradise Nursery**, a beautiful, modern, and highly responsive React web application designed for plant lovers! Shop for your favorite house plants with ease and elegance.

Live Demo: **[https://KElgenidy.github.io/e-plantShopping/](https://KElgenidy.github.io/e-plantShopping/)**

---

## ✨ Features

- **🌸 Welcome Landing Page**: An elegant landing page introducing the mission and passion of Paradise Nursery with a smooth transition into the store.
- **🌱 Curated Plant Categories**: Explore diverse, healthy collections categorized for your needs:
  - *Air Purifying Plants* (Snake Plant, Peace Lily, Spider Plant, etc.)
  - *Aromatic Fragrant Plants* (Lavender, Rosemary, Jasmine, etc.)
  - *Insect Repellent Plants* (Marigold, Basil, Catnip, etc.)
  - *Medicinal Plants* (Aloe Vera, Echinacea, Chamomile, etc.)
  - *Low Maintenance Plants* (ZZ Plant, Pothos, Succulents, etc.)
- **🛒 Dynamic Shopping Cart**:
  - Live item quantity badge on the persistent header.
  - Interactive "Add to Cart" state which disables and styles the button to "Added to Cart" once selected.
  - Full controls inside the Cart component to **increment**, **decrement**, or **remove** items completely in real-time.
  - Automatic unit cost, item subtotal, and grand total calculations.
- **🎨 Polished UI & Transitions**: Modern, soft card styling, custom-designed pill-shaped SALE badges, forest green thematic price tags, hover lift animations, and clean, responsive layout.

---

## 🛠️ Tech Stack

- **Framework**: [React](https://react.dev/) (v18)
- **State Management**: [Redux Toolkit](https://redux-toolkit.js.org/) & [React Redux](https://react-redux.js.org/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Package Manager**: [Bun](https://bun.sh/)
- **Deployment**: [GitHub Pages](https://pages.github.com/)

---

## 🚀 Running Locally

Follow these steps to run the project in your local development environment:

### 1. Prerequisites
Ensure you have [Bun](https://bun.sh/) installed:
```bash
bun --version
```

### 2. Install Dependencies
Restore and install all required packages:
```bash
bun install
```

### 3. Run Development Server
Start the local server:
```bash
bun run dev
```
Open **`http://localhost:5173/e-plantShopping/`** in your browser to view the app!

### 4. Build and Compile
Generate the highly optimized production build:
```bash
bun run build
```

### 5. Deploy to GitHub Pages
To publish updates to GitHub Pages:
```bash
bun run deploy
```
