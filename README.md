A Private Keepsake
A bespoke digital experience designed as a romantic gesture and narrative portfolio. This project serves as a high-end editorial keepsake, featuring interactive elements, fluid typography, and a minimalist design language.

📜 Overview
This is a single-page website built with a focus on sophisticated UX and "Quiet Luxury" aesthetics. It was created to house a personal narrative and a 3D interactive postcard, ensuring a seamless experience across all devices from desktop to mobile.

✨ Key Features
Interactive 3D Postcard: A CSS-driven 3D flip effect allowing users to interact with a virtual letter (Front and Back).

Fluid Typography: Uses CSS clamp() and viewport units to ensure headers and text never break onto unwanted lines, regardless of screen width.

Scroll-Triggered Animations: Implements the Intersection Observer API for elegant, high-performance fade-in reveals of narrative blocks.

Premium Typography: Integrated Google Fonts (Cinzel for headings and Spectral for body text) to evoke a classic, editorial feel.

Responsive Architecture: Specifically optimized for mobile devices with strict "non-wrap" protection for key titles and signatures.

🛠️ Tech Stack
HTML5: Semantic structure for accessibility and SEO.

CSS3: Custom properties (variables), 3D transforms, hardware-accelerated animations, and Flexbox/Grid layouts.

Vanilla JavaScript: Lightweight Intersection Observer implementation for scroll effects (Zero dependencies).

📂 Project Structure
Plaintext

├── index.html          # Main entry point
├── Assets/
│   ├── Letter Front.png # Postcard front image
│   ├── Letter Back.png  # Postcard back image
│   ├── favicon.ico      # Browser icon
│   ├── site.webmanifest # PWA/Mobile manifest
│   └── apple-touch-icon.png
└── README.md
🚀 Setup & Deployment
Clone the repository:

Bash

git clone https://github.com/your-username/private-keepsake.git
Asset Placement: Ensure your high-resolution images are placed in the Assets/ folder and named exactly as specified in the HTML (Letter Front.png and Letter Back.png).

Local Preview: Open index.html in any modern browser. No build steps or local servers are required as it uses vanilla technologies.

🎨 Creative Credits
Narrative & Vision: [Chatura]

Technical Assistance: Developed with structural and grid assistance from Gemini (Google).

License
This project is a personal creative work. All narrative content and visual designs are proprietary.
