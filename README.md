React + Tailwind Theme Switcher

A minimal light/dark mode switcher built with React, Context API, and Tailwind CSS (Vite setup).

🚀 Setup
git clone https://github.com/your-username/theme-switcher.git
cd theme-switcher
npm install
npm run dev

⚙️ Dark Mode Fix (Vite)

Add this line to index.css to enable dark mode:

@custom-variant dark (&:where(.dark, .dark *));
