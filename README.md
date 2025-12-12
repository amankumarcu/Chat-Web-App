# Pulse Messenger — Web Components Chat Demo

A lightweight, frontend-only real-time chat demo built with **Web Components** (custom elements), plain **HTML/CSS/JavaScript**, and client-side simulated events. The app demonstrates UI patterns for chat applications (chat list, active chat, message composer, simulated incoming messages) without requiring a backend.

**Live Demo:** https://chat-web-app-tawny.vercel.app/  
**Source:** (this repository)

---

## Tech Stack (actual)
- **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6)
- **Components:** Web Components / Custom Elements
- **Styling:** Plain CSS (`styles/styles.css`)
- **Real-time:** Client-side simulation using `setInterval` (no WebSocket)
- **Deployment:** Static site (suitable for Vercel, Netlify, GitHub Pages)
- **Data:** In-memory / simulated — no database or server required

---

## Features
- Single-page chat UI built from reusable Web Components:
  - Chat list, active chat view, message composer, new message component
- Simulated users and messages (fake data generator) to demo:
  - Incoming message events
  - Unread counts, last seen, online indicators
- Responsive and lightweight UI using plain CSS and custom elements
- Easy to extend with a real backend (WebSockets / Socket.IO) if desired

