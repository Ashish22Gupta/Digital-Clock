# ⏰ Digital Clock
### Real-Time Date & Time Display

> ⚠️ **DISCLAIMER:** This is a **personal learning and portfolio project**. It demonstrates real-time JavaScript date handling, 12-hour time conversion, and responsive UI design. All logic runs entirely in the browser — no data is collected or transmitted.

A minimal, elegant digital clock that displays the current day, date, and live time — updating every second. Built with vanilla JavaScript and pure CSS, it features automatic 12-hour AM/PM conversion, zero-padded digits, and a polished glassmorphism card that adapts seamlessly from desktop to mobile.

![Version](https://img.shields.io/badge/Version-1.0.0-4361ee)
![Status](https://img.shields.io/badge/Status-Portfolio%20Project-F4B400)
![Responsive](https://img.shields.io/badge/Responsive-Desktop%20%26%20Mobile-2D6A4F)

---

## 🔗 Live Links

- **Live Demo:** [timekeeper-digital-clock.netlify.app](https://timekeeper-digital-clock.netlify.app/)
- **Source Code:** [github.com/Ashish22Gupta/Digital-Clock](https://github.com/Ashish22Gupta/Digital-Clock)

---

## ✨ Implemented Features

### 🕐 Real-Time Clock
- **Live Second Updates** - `setInterval(showTime, 1000)` keeps the clock ticking in sync every second.
- **12-Hour Format with AM/PM** - Automatically converts 24-hour time, handles midnight (`0 → 12 AM`) and afternoon (`13 → 1 PM`) edge cases.
- **Zero-Padded Digits** - Hours, minutes, and seconds always display two digits (e.g., `09:05:03`).

### 📅 Custom Date Display
- **Full Day Name** - Displays the weekday (Sunday–Saturday) from a custom lookup array.
- **Full Month Name** - Shows the month spelled out (January–December) instead of a number.
- **Formatted String** - Renders as `Wednesday, 25 November 2026` for instant readability.

### 🎨 Visual Design
- **Glassmorphism Card** - Semi-transparent dark container with a soft shadow floating over a purple gradient background.
- **Gold Time Accent** - Clock text in `#ffd700` with subtle text-shadow for depth.
- **Hidden Cursor** - `cursor: none` on the container for a clean kiosk/display feel.
- **Viewport-Scaled Typography** - Font sizes use `vh` units so text scales naturally with screen height.

### 📱 Fully Responsive Design
- **Desktop:** Large `6vh` date and `5.5vh` clock text.
- **Tablet (≤768px):** Text and padding scale down for mid-size screens.
- **Mobile (≤480px):** Compact `4vh` / `3.5vh` typography with reduced padding.
- **Fluid Height:** `100dvh` keeps the clock perfectly centered on mobile browsers with dynamic toolbars.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic, minimal markup structure |
| **CSS3** | Gradient background, glassmorphism card, responsive media queries, viewport-scaled typography |
| **Vanilla JavaScript** | Real-time `Date` API handling, interval timer, 12-hour conversion logic |
| **Netlify** | Static hosting and deployment |

---

## 📁 Project Structure

```text
Digital-Clock/
├── index.html          # Markup: date and clock display containers
├── styles.css          # Gradient theme, card layout, responsive rules
└── script.js           # Time logic, date formatting, interval updates
