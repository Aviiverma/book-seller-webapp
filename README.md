# book-seller-webapp
# ChapterLane Book Marketplace

A lightweight **book seller marketplace** built with **React 19**, **Vite**, and **Bootstrap**. Users can browse, search, filter, and purchase books, while sellers can add new listings through a dedicated portal. The app features a modern UI with animated login/background effects.

---

## ✨ Features
- **Book browsing** with category filtering, sorting, and search.
- **Cart** management with quantity controls and checkout flow.
- **Seller portal** for adding new books (price, stock, cover, etc.).
- **Authentication** (simple client‑side login/signup) with animated login page.
- **Responsive design** for desktop and mobile.
- **Persisted state** via `localStorage` (books, cart, session).

---

## 🛠️ Tech Stack
- **React** 19 (hooks, functional components)
- **Vite** 8 (fast dev server & bundler)
- **Bootstrap** 5 (UI components & styling)
- **React‑Bootstrap** for native Bootstrap components
- **CSS** custom styles with gradients, animations, and responsive tweaks.

---

## 📦 Installation
```bash
# Clone the repo (if applicable)
git clone <repo-url>
cd build-a-book-seller-website-having

# Install dependencies
npm install
```

## ▶️ Development
```bash
npm run dev     # Starts Vite dev server (http://127.0.0.1:5173)
```
Open the URL in your browser. The login page displays first; use `admin / password` for the demo or sign up a new account.

## 📦 Build for Production
```bash
npm run build   # Generates static assets in the ./dist folder
npm run preview # Serves the built app locally
```

---

## 📂 Project Structure
```
src/
├─ components/        # Reusable UI components (Home, CartPage, CheckoutPage, etc.)
├─ resources/         # Static data (starterBooks, emptyForm)
├─ utils/             # Helper functions (localStorage wrappers)
├─ Auth.jsx           # Login/Signup page with animated background
├─ App.jsx            # Main application layout & routing logic
├─ App.css            # Global styles, including login animations
├─ main.jsx           # Entry point, mounts <AuthPage> or <App>
└─ index.html         # Root HTML file
```

---

## 🎨 Styling & Animations
- **Login page** uses a gradient background with a floating radial pattern (`.login-bg-pattern`).
- Card slides up on load (`slideUp` keyframe) and inputs have focus transitions.
- Buttons have subtle lift effects.

---

## 🧪 Testing
> No test suite is currently included. Feel free to add Jest/React Testing Library for component/unit tests.

---

## 🚀 Future Improvements
- Replace client‑side auth with a real backend (JWT, OAuth).
- Add server‑side persistence (database) for books & users.
- Implement unit/integration tests.
- Enhance accessibility and SEO.

---

## 📄 License
This project is **private** (see `package.json` – `private: true`).
