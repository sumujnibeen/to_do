<div align = "center">
  
# To Do

A minimal, futuristic **Progressive Web App (PWA)** for managing everyday tasks with deadlines.

Designed to feel more like a small personal dashboard than a traditional to-do list.

<p align="center">
  <a href="https://sumujnibeen.github.io/to_do/">
    <img src="https://img.shields.io/badge/Live-Demo-000000?style=for-the-badge" alt="Live Demo">
  </a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white" alt="PWA">
</p>
</div>
<p align="center">
  <a href="https://github.com/sumujnibeen/to_do">
    <img src="https://img.shields.io/github/stars/sumujnibeen/to_do?style=flat-square" alt="GitHub Stars">
  </a>
  <a href="https://github.com/sumujnibeen/to_do/network/members">
    <img src="https://img.shields.io/github/forks/sumujnibeen/to_do?style=flat-square" alt="GitHub Forks">
  </a>
  <a href="https://github.com/sumujnibeen/to_do/issues">
    <img src="https://img.shields.io/github/issues/sumujnibeen/to_do?style=flat-square" alt="GitHub Issues">
  </a>
  <img src="https://img.shields.io/github/last-commit/sumujnibeen/to_do?style=flat-square" alt="Last Commit">
</p>

## Live Demo

**https://sumujnibeen.github.io/to_do/**

## Overview

I wanted a to-do app that felt simple enough for everyday use without becoming another complicated productivity system.

So I built one.

The interface combines a minimal task manager with a custom animated clock, deadline indicators, sorting controls, and PWA support — all inside a dark, compact interface designed primarily for mobile use.

This project was also created as an exploration of **Progressive Web Apps and modern browser capabilities**.

## Features

* Add tasks with a title and deadline
* Custom futuristic clock interface
* Automatic task urgency indicators
* Deadline and remaining-days display
* Mark tasks as completed
* Edit existing tasks
* Delete tasks
* Restore completed tasks
* Permanently remove tasks
* Reorder tasks
* Sort tasks using different sorting options
* Undo recently deleted actions
* Empty-state interface
* Responsive mobile-first design
* Installable as a PWA
* Custom app icons
* Service worker support
* Standalone app-like experience

## Design

The UI follows a dark, minimal and futuristic visual style.

The main screen is built around a custom clock surrounded by date, month and day indicators. Tasks appear below it as compact cards with color-coded deadline status.

### Task Status

* 🔴 **Urgent**
* 🟡 **Approaching deadline**
* 🟢 **Safe**
* ⚪ **Completed**

## Progressive Web App

This project is built as a **Progressive Web App**, allowing it to behave more like a native application while remaining web-based.

It includes:

* `manifest.json`
* Service worker
* App icons
* Standalone display configuration
* Mobile web app metadata
* Install prompt

The app can be installed on supported devices and used as an app-like experience directly from the browser.

## Technologies

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square\&logo=pwa\&logoColor=white)

No frontend framework is used.

The project was intentionally kept lightweight and built with standard web technologies.

## Project Structure

```text
to_do/
├── index.html
├── index-1.html
├── manifest.json
├── sw.js
├── icon-192.png
├── icon-192.svg
├── icon-512.png
├── icon-512.svg
└── .github/
    └── workflows/
```

## Why I Built It

Most productivity apps try to do everything.

I wanted to explore the opposite approach:

**Keep the interaction simple, make the interface feel good, and build only what I actually need.**

This project started primarily as an experiment with PWAs and gradually turned into a usable personal to-do application.

## Future Ideas

* Task categories
* Recurring tasks
* Notifications and reminders
* Better data persistence and backup
* More customization options
* Improved offline capabilities
* Additional PWA features
* More advanced task filtering

## Author

**Shafiul Mujnibeen**

Built while exploring **JavaScript, Progressive Web Apps, and browser-based application development**.

---

