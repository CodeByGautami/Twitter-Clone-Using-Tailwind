# 🐦 Twitter Clone using Tailwind CSS

This is a responsive **Twitter clone frontend UI** built using **Tailwind CSS**. It mimics the layout and design of the official Twitter web app — including sidebar icons, tweet composer, search bar, trending topics, and suggested users.

## 🌐 Live Demo

🔗 [Click here to view the live site](https://twitter-clone-using-tailwind-vblg.vercel.app/)

## ✨ Features

- Clean layout with **3-column structure**:
  - 📌 Left sidebar with interactive Material icons
  - 📝 Middle section for composing tweets and viewing posts
  - 🔍 Right section with trending topics and follow suggestions
- Interactive **hover effects**
- Responsive layout (works well on different screen sizes)
- Integrated **Google Material Symbols** for icons
- Realistic design: trending topics, reply settings, user suggestions, subscribe button, and more

## 🛠 Tech Stack

- ✅ HTML5
- ✅ TailwindCSS
- ✅ Material Symbols (Google Fonts Icons)


## ## 🚀 Setup & How to Run

step 1 - Run the following Commands
```
npm install -D tailwindcss
npx tailwindcss init
```
Step 2 - Update tailwind.conf.file to include this line :

content: ["./html"],

step 3 - Create srx/input.css to include :

@tailwind base;
@tailwind components;
@tailwind utilities;

step 4- Include the src/outpt.css file to your html

step 5- Run the following :
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```
add this line in package.json - scripts

"dev": "tailwindcss -i ./src/input.css -o ./dist/output.css --watch"\

Run :
```
npm run dev
```

## 🖼️ Screenshots

<img width="1918" height="834" alt="image" src="https://github.com/user-attachments/assets/40ad1f0d-dbde-4294-a8ae-b26ba49e12c0" />







