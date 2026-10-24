# 🌄 Parallax Effect — A Scroll-Driven Visual Journey

<p align="center">
  <strong>Scroll through a world of layered mountains, drifting clouds, changing skies, and atmospheric night scenes.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white" alt="GSAP" />
  <img src="https://img.shields.io/badge/SVG-FFB13B?style=for-the-badge&logo=svg&logoColor=black" alt="SVG" />
</p>

---

## ✨ About the Project

**Parallax Effect** is a creative front-end experiment that transforms ordinary scrolling into an immersive visual experience.

The page features an illustrated landscape built with inline SVG. As you scroll, different layers move independently, clouds drift across the sky, the scenery transforms, and the atmosphere shifts between vibrant daylight colors and mysterious nighttime tones.

Instead of relying on a collection of static images, the experience uses **GSAP timelines and ScrollTrigger** to synchronize animations with the user's scrolling.

## 🎬 Visual Experience

The animation explores several visual elements:

- 🌅 **Colorful skies and distant mountains** — layered landscapes create a sense of depth.
- ☁️ **Drifting clouds** — animated elements add movement to the environment.
- 🌲 **Layered forest silhouettes** — multiple scenery layers move at different speeds.
- 🌞 **Dynamic lighting and gradients** — the background evolves as the animation progresses.
- 🌌 **A starry nighttime scene** — darker colors and mountain silhouettes create a contrasting atmosphere.
- 🦴 **Illustrated dinosaur fossils and details** — decorative elements add character to the scene.
- 🖱️ **Scroll-controlled storytelling** — scroll through the animation to experience the transitions.

## 🛠️ Built With

| Technology | How it is used |
|---|---|
| **HTML5** | Structures the page and contains the inline SVG artwork. |
| **CSS3** | Controls layout, viewport behavior, and responsive adjustments. |
| **JavaScript** | Coordinates animation logic and scene transitions. |
| **SVG** | Creates scalable landscapes, shapes, and gradient effects. |
| **GSAP** | Animates SVG elements, transforms, and visual properties. |
| **ScrollTrigger** | Synchronizes animation timelines with scroll progress. |

## 🧠 How the Parallax Effect Works

The illusion of depth comes from moving different visual layers at different rates.

1. **🎨 Draw the scene:** SVG elements and gradients define the illustrated environment.
2. **⚙️ Create timelines:** GSAP animates the position, scale, opacity, and other properties of selected elements.
3. **📜 Connect scrolling:** ScrollTrigger controls when animations begin and end, while `scrub` links animation progress to scrolling.
4. **🌄 Transform the environment:** Multiple timelines coordinate scenery, clouds, lighting, and other details to create a continuous visual journey.

## 📁 Project Structure

```text
Parallax_effect/
├── index.html    # Page structure and SVG landscape artwork
├── style.css     # Layout, positioning, and responsive styling
├── script.js     # GSAP animations and ScrollTrigger logic
└── README.md     # Project documentation
```

## 🚀 Run It Locally

No build tools or package installation are required for the current project.

**1. Clone the repository**

```bash
git clone https://github.com/Krishnendu1910/Parallax_effect.git
```

**2. Enter the project folder**

```bash
cd Parallax_effect
```

**3. Launch the experience**

Open `index.html` in your browser, or launch it through the **Live Server** extension in VS Code.

> 💡 **Tip:** The project loads GSAP and ScrollTrigger from a CDN, so an internet connection is required for those libraries unless you configure local copies.

## 📱 Responsive Design

The page includes viewport configuration and a small-screen CSS adjustment. For the best visual experience, try it in a modern desktop browser and scroll gradually through the scene.

## 🎯 What I Practiced

This project explores practical front-end animation techniques:

- Working with inline SVG illustrations and gradients.
- Animating SVG attributes and transforms.
- Building and coordinating GSAP timelines.
- Using ScrollTrigger and scrub-based animation.
- Creating depth through layered movement.
- Adjusting a fixed visual composition for narrower screens.

## 🔮 Possible Improvements

- [ ] Add a dedicated reduced-motion experience for accessibility.
- [ ] Optimize animation behavior for touch devices and different screen sizes.
- [ ] Add a loading state for external animation libraries.
- [ ] Improve keyboard accessibility and scroll guidance.
- [ ] Add a lightweight animated preview to the repository README.

## 🙌 Credits

The HTML document title references **@coding.stella**. If this project adapts their original artwork or animation, please review the original source and its license for applicable attribution requirements.

## 👨‍💻 Author

**Krishnendu Sarkar**

- 💼 [LinkedIn](https://www.linkedin.com/in/krishnendu-sarkar-087bba257/)
- 🐙 [GitHub](https://github.com/Krishnendu1910)

---

<p align="center">
  <em>Built to explore the creative side of front-end development, one scroll at a time.</em>
</p>
