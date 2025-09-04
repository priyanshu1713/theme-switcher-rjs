React + Tailwind Theme Switcher

A simple light/dark mode theme switcher built with React, Context API, and Tailwind CSS (Vite setup).

✨ Features

Toggle between light and dark mode.

Uses React Context API for global theme management.

Compatible with Tailwind’s new Vite plugin setup (2025).

Responsive card component with theme-aware styling.

🚀 Setup

Clone the repo and install dependencies:

git clone https://github.com/your-username/theme-switcher.git
cd theme-switcher
npm install


Run the dev server:

npm run dev

⚙️ Tailwind Dark Mode (Vite Setup)

Since Tailwind removed tailwind.config.js in the new Vite plugin setup, add this to your index.css:

@custom-variant dark (&:where(.dark, .dark *));


This enables dark: classes to work when .dark is applied to <html>.

🛠️ File Structure
src/
 ├── components/
 │   ├── Card.jsx        # Example card component
 │   └── ThemeBtn.jsx    # Toggle switch
 ├── contexts/
 │   └── theme.js        # Theme context + hook
 ├── App.jsx             # Main app, wraps with ThemeProvider
 ├── index.css           # Tailwind base + dark variant
 └── main.jsx            # React entry


📄 License

MIT
