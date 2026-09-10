Theme Explosion Clone — Tailwind CSS

A responsive e-commerce landing page built from scratch using HTML and Tailwind CSS, cloning the "Theme Explosion" fashion store template. Built as a practice project to strengthen real-world Tailwind skills — responsive layouts, hover interactions, custom animations, and component-based design.

🔗 Live Demo

🌐 View Live Site

📸 Preview

<img width="1886" height="985" alt="image" src="https://github.com/user-attachments/assets/11338c55-a554-4e8f-84ce-3de87ea9adc9" />
<img width="1859" height="934" alt="image" src="https://github.com/user-attachments/assets/1b4f0a9a-7f91-4021-b501-d8330a9f76d0" />
<img width="1889" height="695" alt="image" src="https://github.com/user-attachments/assets/3e4b2ebe-b0da-4537-b3bb-13bf18ee47c9" />
<img width="1771" height="892" alt="image" src="https://github.com/user-attachments/assets/a37debf0-024c-4205-b29d-bdd6b35ea1b7" />
<img width="1694" height="941" alt="image" src="https://github.com/user-attachments/assets/153b5a15-0bb8-46e4-87c5-95a7fb34b604" />

md
![Preview](src/Imgs/preview.png)
✨ Features
Fully responsive layout (mobile, tablet, desktop breakpoints)
Multi-level hover dropdown navigation (mega menu style)
Animated notification dot (custom @keyframes + @theme animation)
Ribbon-style "New" / "Sale" badges using clip-path
Image zoom-on-hover effect using object-cover + scale
Deal-of-the-day countdown section
Product grid with pricing, discounts, and color swatches
Instagram lookbook gallery with hover zoom
Newsletter subscription section
Custom Tailwind theme tokens (primary, backg, custom fonts)
🛠️ Built With
Tailwind CSS (v4 — @theme syntax)
HTML5
Font Awesome for icons
📂 Project Structure
├── src/
│   ├── Imgs/          # All images used in the project
│   └── output.css     # Compiled Tailwind CSS
├── Index.html          # Main page
├── package.json
└── README.md
🚀 Getting Started
Clone the repo
bash
   git clone https://github.com/Husnainawm/ThemeExplosionClone-Tailwinds.git
Install dependencies
bash
   npm install
Run the Tailwind build (watch mode)
bash
   npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
Open Index.html in your browser (or use a Live Server extension)
📚 What I Practiced

This project was built while learning Tailwind CSS concepts including:

Flexbox & Grid layouts (flex-wrap, grid-cols-*, col-span-*)
Responsive design with breakpoint prefixes (sm:, md:, lg:)
group/group-hover for interactive dropdowns
Custom animations via @theme and @keyframes
clip-path for custom badge shapes
object-fit/object-cover for consistent image sizing
Absolute/relative positioning for overlays and badges
🙋 Author

Husnain Ali

GitHub: @Husnainawm
📄 License

This project is for educational/practice purposes. Original design credit belongs to the original "Theme Explosion" template authors.
