<div align="center">

# 📊 Chart.js Interactive Bar Chart Component

An interactive, responsive, and fully customizable bar chart visualization prototype built using **Chart.js**, **HTML5 Canvas**, and **JavaScript (ES6)**.

![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

</div>

---

## 📖 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Quick Start](#-quick-start)
- [Code Structure & Customization](#-code-structure--customization)
- [License](#-license)

---

## 🎯 Overview

This project is a lightweight, high-performance data visualization component designed for web applications. It demonstrates how to initialize, configure, and dynamically style an interactive bar chart using **Chart.js** over an **HTML5 Canvas** surface.

> 💡 **Note:** Created as part of a front-end UI component library prototype.

---

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| 🎨 **Custom Color Palette** | Configured with RGBA color values for bar background fills and borders. |
| 🔍 **Interactive Tooltips** | Hovering over bars displays precise category labels and dataset counts (`# of Votes`). |
| 📏 **Calibrated Scaling** | Configured with `beginAtZero: true` on the Y-axis for precise proportional rendering. |
| ⚡ **Zero External Dependencies** | Runs natively in the browser with only the Chart.js library CDN included. |

---

## 🛠️ Tech Stack

- [<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="16" height="16" /> **HTML5**](https://developer.mozilla.org/en-US/docs/Web/HTML) – Canvas rendering element base.
- [<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" width="16" height="16" /> **CSS3**](https://developer.mozilla.org/en-US/docs/Web/CSS) – Layout alignment and container styling.
- [<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="16" height="16" /> **JavaScript (ES6)**](https://developer.mozilla.org/en-US/docs/Web/JavaScript) – DOM manipulation and Chart instantiation logic.
- [<img src="https://www.chartjs.org/favicon.ico" width="16" height="16" /> **Chart.js**](https://www.chartjs.org/) – Flexible JavaScript charting library.

---

## 📁 Project Structure

├── index.html        # HTML structure & Chart.js canvas element
├── styles.css        # Layout, spacing, and custom CSS styles
├── script.js        # Chart instantiation logic & dataset config
└── README.md         # Repository documentation
