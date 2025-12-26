# 🦊 Focus Companion

A cozy, "Lofi" inspired Pomodoro web application designed to help students and professionals maintain focus through a companion-based productivity system.

## 🌟 Overview
Focus Companion combines a functional Pomodoro timer with a virtual pet and task management system. Built as a lightweight, single-file solution, it emphasizes a minimalist aesthetic to reduce cognitive load while providing the essential tools for a deep-work session.

## ✨ Features

### 🐾 Interactive Pet Companion
* **State-Based Reactions:** The pet changes its emoji and animation state based on your activity.
    * **Sleeping (😴):** Default state when the app is idle.
    * **Focused (😎):** Animated "bouncing" state during active countdowns.
    * **Happy (🥳):** Celebration state triggered upon successful session completion.

### ⏲️ Pomodoro Timer
* **Fixed Intervals:** Set to the standard 25-minute focus period.
* **Control Suite:** Fully functional Start, Pause, and Reset controls.
* **Dynamic Tab Title:** View your remaining time directly in the browser tab title.
* **Audio Notifications:** A soft chime plays when the timer reaches zero to signal a break.

### 📝 Integrated Task Management
* **Persistent To-Do List:** Tasks are saved to `LocalStorage`, ensuring your list remains intact even after refreshing the page or closing the browser.
* **Toggle Completion:** Click tasks to apply a strike-through effect.
* **Bulk Actions:** A "Clear All" feature to reset your task list for a new day.

## 🎨 Design Aesthetic
* **Lofi Vibes:** Utilizes a pastel color palette (lavender, mint, and soft coral).
* **Responsive Layout:** A centered, card-based interface that works beautifully on both desktop and mobile screens.
* **Smooth Transitions:** Gentle CSS animations for pet movements and button interactions.

## 🛠️ Technical Stack
* **HTML5:** Semantic structure.
* **CSS3:** Custom properties (variables) and Keyframe animations.
* **JavaScript (Vanilla):** Logic for the timer engine, DOM manipulation, and LocalStorage integration.

## 🚀 Quick Start
Since this is a single-file application, no installation is required:
1. Copy the code into a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Start your task and stay focused!

## 📜 License
This project is open-source and free to use for educational and personal productivity purposes.
