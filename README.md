[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/HLEvEf24)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23071140&assignment_repo_type=AssignmentRepo)

# EBU6305

## Group Number: 2020EBU6305G18

## Project Title: C.Orbit

## Members:

Pengqi Sun, 2024213531, 241118429, sunpengqi@bupt.edu.cn

Linxian Gao, 2024213575, 241118050, jp2024213575@qmul.ac.uk

Qingyang Li, 2024213551, 241118186, rainstone7423@qq.com

## Task Allocation

1. Homepage - Linxian Gao
2. Game - Pengqi Sun
3. Quiz - Qingyang Li

## Assigned TA: Wenyue Tong

## Overview

Have you ever wondered why we look up at the stars for answers? The galaxy itself is one of the finest demonstrations of geometry. C.Orbit is an interactive educational website about **circle geometry**, featuring lessons, quizzes, and a draggable geometry game that helps learners understand circle theorems in an intuitive way.

## Project Structure

```
├── index.html    # Home — Knowledge intro, video section, contact form, AI chat assistant
├── quiz.html     # Quiz — Three-level multiple-choice quiz
├── game.html     # Game — Interactive Canvas-based theorem demonstrations
├── script.js     # Global script — Theme toggle, language switch, font scaling, scroll reveal
├── style.css     # Global styles — Responsive layout, light/dark themes, colour-blind safe palette
└── README.md
```

## Features

### Home Page (index.html)
- **Hero Section**: Guides users to the quiz or game
- **Key Theorem Cards**: Introduces three core circle theorems — Angle at the Centre, Angle in a Semicircle, Tangent–Radius
- **Video / Slideshow Area**: Placeholder for embedded video content
- **Contact Form**: Client-side validation with real-time error feedback
- **AI Study Assistant**: Simulated chatbot that answers circle geometry questions

### Quiz Page (quiz.html)
- **Three Difficulty Levels**: Beginner (basic definitions), Intermediate (theorem application), Advanced (multi-step proofs)
- **Randomised Questions**: 5 questions per level, randomly selected from a question bank
- **Instant Feedback**: Correct/incorrect answers highlighted in real time
- **Progress Bar**: Visual progress tracking throughout the quiz
- **Results Screen**: Animated circular ring showing score percentage

### Game Page (game.html)
- **Interactive Canvas Demo**: Drag control points on the circle to explore theorems
- **Three Theorem Tabs**:
  - Inscribed Angle Theorem
  - Angles in the Same Segment
  - Angle in a Semicircle
- **Live Measurements**: Angle values and theorem descriptions update dynamically as points are dragged

### Accessibility & Inclusive Design
- **Light / Dark Theme Toggle**: Preference saved to localStorage
- **Bilingual Support (English ↔ Chinese)**: Full-site translation via `data-i18n` attributes
- **Font Size Controls**: Adjustable from 75% to 150%
- **Colour-Blind Friendly Palette**: Based on Wong (2011) safe colour recommendations
- **Semantic HTML**: ARIA labels, breadcrumb navigation, screen-reader friendly
- **Responsive Layout**: Mobile-friendly with hamburger menu
- **Scroll Reveal Animations**: Powered by IntersectionObserver

## Tech Stack

| Category | Technology |
|----------|------------|
| Markup | HTML5 semantic elements |
| Styling | CSS3 (custom properties, Flexbox/Grid, animations, glassmorphism) |
| Scripting | Vanilla JavaScript (ES5/ES6, no framework dependencies) |
| Fonts | Google Fonts — Inter, Space Grotesk |
| Graphics | HTML Canvas 2D API, inline SVG |

## Getting Started

This is a purely static website with no build step required.

1. Clone the repository:
   ```bash
   git clone https://github.com/PengqiSun/interactive-media-coursework.git
   ```
2. Open `index.html` in a browser, or use any local server (e.g. the Live Server extension in VS Code).

## Privacy

This website does not collect, store, or share any personal data. No cookies or tracking technologies are used.

## License

© 2026 Circle Geometry. Built for learning by everyone, for everyone.
