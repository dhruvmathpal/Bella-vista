🌅 Bella Vista

A clean, minimal static website crafted with HTML & CSS

Bella Vista is a lightweight static website designed as a practice project for web layout, styling, and responsive design.
This repository contains all the source code for experimenting, learning, and customizing your own simple static website.

Perfect for beginners exploring front-end basics or anyone wanting a clean starting point for landing pages.

✨ Features

Minimal & well-organized structure — only index.html, style.css, and an images/ folder.

Responsive layout with optimized background images and hero sections.

Clean typography & layout easy to modify for any use case.

Zero dependencies — runs on any browser, no frameworks required.

Ready for deployment on GitHub Pages, Netlify, Vercel, or any static hosting.

🚀 Live Preview / Demo

You can preview the site in two ways:

1️⃣ Open the file directly
index.html

2️⃣ Recommended: Run a local server

Helps avoid browser CORS issues with images.

python -m http.server 8000
# Now open http://localhost:8000

🛠️ Quick Start
Clone the repository
git clone https://github.com/dhruvmathpal/Bella-vista.git
cd Bella-vista

Open the site
Start-Process index.html   # Windows
open index.html            # macOS
xdg-open index.html        # Linux

📂 Project Structure
Bella-vista/
│
├── index.html      # Main HTML entry page
├── style.css       # Primary stylesheet
├── thankyou.html   # submit action page
├── images/         # Assets & backgrounds
└── README.md       # Documentation

🎨 Customization Guide
🔹 Change the hero background

Open style.css and edit:

.hero {
  background-image: url("images/your-image.jpg");
  background-size: cover;
  background-position: center;
}

🔹 Replace images

Drop your files in the images/ folder (WebP recommended for performance).

🔹 Update content

All text and sections are inside index.html. Modify headings, paragraphs, and layout as needed.

💡 Development Tips

Use DevTools to test layouts and responsive behavior.

Compress images to improve performance.

Prefer WebP for backgrounds.

Add loading="lazy" for non-critical images.

Use min() / max() units or CSS clamp() for smooth responsive typography.

Example:

h1 {
  font-size: clamp(2rem, 5vw, 3rem);
}

🌍 Deployment Options
GitHub Pages

Go to Settings → Pages

Select branch: main

Save

Your site will be live within minutes

Netlify / Vercel

Drag & drop the folder

Or connect directly to the GitHub repo

Auto-deployment on each push

Any static host

Just upload the folder — no backend required.

🤝 Contributing

Feel free to submit PRs for:

UI improvements

Responsive design enhancements

Additional pages

Bug fixes or optimizations

All contributions are welcome.

📜 License

Let me know if you want to publish this as MIT, Apache-2.0, GPL, or custom — I can generate a proper LICENSE file for you.

📬 Contact

Need help customizing Bella Vista (animations, sections, responsiveness, deployment)?
Just tell me what improvements you want — I can generate code updates for you.