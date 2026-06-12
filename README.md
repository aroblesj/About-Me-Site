# Adrian Robles Jr. | Professional Portfolio

This is my personal portfolio website, featuring a dark glassmorphic design and a highly interactive client-side layout. I designed and built this portfolio in collaboration with Google's Antigravity AI assistant, directing the code architecture and style changes to match my vision.

Live Site: [aroblesj.github.io](https://aroblesj.github.io)

---

## 🚀 Key Features

* **Hybrid Navigation Layout:** 
  * **Desktop:** Slides snap smoothly between full-screen sections using a custom physics-driven snapping system (supports wheel scroll, swipes, and arrow keys).
  * **Mobile & Tablet:** Snapping disables automatically under `1024px` to allow native fluid scrolling, while the navigation links update dynamically as you scroll.
* **Glassmorphic Aesthetic:** A black background offset by linear gradients, neon accents, and frosted glass cards. A subtle background paper and noise texture overlay adds visual depth.
* **Responsive Components:** Includes a custom SVG monogram logo, clean section layouts, and interactive project cards with click-to-zoom fullscreen lightboxes.

---

## 🛠️ Tech Stack & Architecture

I built this site using native web technologies to ensure fast load times and clean code:

* **Markup & Styling:** Semantic HTML5 and Vanilla CSS3 using custom design tokens and HSL variables.
* **Logic:** Vanilla ES6 Javascript organized into dynamic modular components (`Header`, `Hero`, `Skills`, `Projects`, `Contact`, `ThemeToggle`).
* **Graphics:** Inline Vector SVGs for crisp, resolution-independent rendering.