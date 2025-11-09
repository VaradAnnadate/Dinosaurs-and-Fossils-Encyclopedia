# 🦕 Dinosaurs and Fossils Encyclopedia
My submission for the S&W (Structures of the Web) INDIVIDUAL PROJECT at NST. This is a static, multi-page website built using only HTML5 and CSS3, focusing on modern layout techniques and responsive design.

## ✨ Features
* Multi-Page Navigation: A clean header navigating between the Home, Gallery, and Fossils pages.

* Interactive Gallery: Two horizontally-scrolling carousels (using CSS Flexbox) for "Terrestrial" and "Aquatic" creatures.

* Advanced CSS Hover Effects: Gallery cards feature a smooth opacity transition on a ::before pseudo-element to reveal the image and hide the text.

* Modern "Glassmorphism" Design: Content cards use backdrop-filter: blur() to create a sleek, frosted-glass look.

* CSS Grid Layout: The Fossils page uses CSS Grid to create an organized, two-column responsive layout for images and text.

* Purely Static: Built with 100% HTML and CSS, with no JavaScript or external libraries.

## 🛠️ Tech Stack
* HTML5: Used for the core structure and semantic content.

* CSS3: Used for all styling, including:
    * Flexbox (for the navigation bar and carousels)

    * Grid (for the Fossils page layout)
    
    * Transitions & Pseudo-elements (for the card hover effects)

## 🧠 What I Learned
This project was a deep dive into pure CSS. I learned:

* How to build complex, modern layouts without relying on a framework.

* The proper way to animate properties that aren't animatable (like background-image) by using opacity on a ::before pseudo-element.

* How to create horizontally-scrolling sections using overflow-x: auto and flex: 0 0 [width].
