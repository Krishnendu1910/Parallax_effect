# Parallax Effect

An illustrated, scroll-driven parallax experience built with **HTML, CSS, SVG, and GSAP**. As you scroll, layered scenery and decorative elements move at different speeds to create depth and a cinematic sequence of animated scenes.

<p align="center">
  <strong>A front-end project exploring SVG illustration and scroll-linked animation.</strong>
</p>

## Overview

This project uses a full-screen SVG illustration as its visual canvas. GSAP timelines and ScrollTrigger connect animation progress to the page's scroll position, moving scenery, clouds, text, and other illustrated elements through the composition.

The implementation is intentionally lightweight: there is no build system or package manager required for the current source.

## Features

- **Scroll-driven animation** — timeline progress follows the user's scroll position.
- **Layered parallax movement** — foreground and background elements move at different rates to suggest depth.
- **SVG-based artwork** — gradients, shapes, and illustrated elements are defined directly in the HTML.
- **Scene transitions** — separate GSAP timelines animate elements at different scroll ranges.
- **Animated environment** — the implementation includes moving clouds, sun/background color changes, and animated illustrated details.
- **Responsive adjustments** — viewport metadata and a small-screen CSS media query provide layout adjustments on narrow screens.

## Tech Stack

| Technology | Role |
| --- | --- |
| HTML5 | Page structure and inline SVG illustration |
| CSS3 | Layout and responsive styling |
| JavaScript | Animation setup and scroll interactions |
| SVG | Scalable scenery, gradients, and illustrated shapes |
| [GSAP](https://gsap.com/) | Animation timelines and property transitions |
| [ScrollTrigger](https://gsap.com/docs/v3/Plugins/ScrollTrigger/) | Synchronizes animations with scroll position |

## Project Structure

```text
Parallax_effect/
├── index.html    # HTML document and inline SVG artwork
├── style.css     # Layout and responsive styles
└── script.js     # GSAP timelines and ScrollTrigger logic
```

## Run Locally

This project uses plain HTML, CSS, and JavaScript. You do not need Node.js or a package installation for the current setup.

1. Clone the repository:

   ```bash
   git clone https://github.com/Krishnendu1910/Parallax_effect.git
   ```

2. Open the project directory:

   ```bash
   cd Parallax_effect
   ```

3. Open `index.html` in a modern browser.

For a consistent local development experience, you can serve the folder using an editor extension such as **Live Server**. An internet connection is required for the GSAP and ScrollTrigger scripts currently loaded from the UNPKG CDN.

## How It Works

1. **SVG scene:** `index.html` defines the visual composition using SVG groups, shapes, and gradients.
2. **Animation setup:** `script.js` registers GSAP's ScrollTrigger plugin and creates timelines for groups of SVG elements.
3. **Scroll synchronization:** ScrollTrigger maps scroll progress to each timeline; `scrub` settings make animation progress track scrolling.
4. **Styling:** `style.css` keeps the SVG fixed across the viewport while a tall scroll element provides the scroll range for the animation.

## Learning Highlights

This project is useful for practicing:

- Building detailed illustrations with inline SVG.
- Animating SVG attributes and transforms with JavaScript.
- Coordinating multiple animation timelines.
- Using scroll position as an animation control.
- Making a fixed visual composition adapt to different viewport sizes.

## Notes

- GSAP and ScrollTrigger are loaded from a CDN, so those scripts will not load offline unless you provide local copies.
- The visual artwork is embedded in `index.html`; there is no separate image-assets directory in the current repository.
- The page's animation is designed around scrolling, so use a mouse wheel, trackpad, or touch scrolling to experience it.

## Credits

The HTML page title references **@coding.stella**. If you reuse or adapt the original artwork or animation, review the source project's license and attribution requirements and retain appropriate credits.

---

Built as a front-end experiment in SVG illustration and scroll-based motion.
