# Van-Darshan
# 🌿 Van Darshan – Safari Zoo Online Ticket Booking Portal

A premium, dark-themed wildlife safari ticket booking platform built entirely with **HTML5, CSS3, and Vanilla JavaScript**. Van Darshan offers a cinematic jungle experience with glassmorphism UI, 3D animal cards, floating fireflies, and a complete ticket booking flow—from visitor details to digital QR ticket generation.

![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/van-darshan)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/van-darshan)
![License](https://img.shields.io/badge/license-MIT-green)

> **Live Demo:** [https://yourusername.github.io/van-darshan](https://yourusername.github.io/van-darshan) *(replace with your deployed link)*

---

## 📌 Overview

**Van Darshan** (meaning "Forest View") is designed to let visitors explore wildlife and book safari tickets online. It guides users through a smooth booking journey—login, select date/time, enter visitor details, auto-calculate ticket price (Adults ₹200, Children ₹100), complete a demo payment, and instantly receive a digital ticket with a QR code placeholder.

The project is ideal for educational demonstrations, UI/UX portfolios, or as a frontend foundation for a real‑world zoo ticketing system.

---

## 🎯 Project Vision

> **“Experience Wildlife Like Never Before.”**

Van Darshan combines the thrill of a safari with a modern, intuitive digital experience, making ticket booking as effortless as a walk in the jungle.

---

## 🎨 Design Philosophy

- **Premium Dark Theme** – Deep forest background (`#08120A`) with neon green accents.
- **Jungle‑Inspired Colors** – Emerald green (`#2ECC71`), golden yellow (`#F1C40F`), and earthy tones.
- **Glassmorphism** – Semi‑transparent, blurred cards that layer beautifully over the dark background.
- **3D Motion UI** – Tilt‑sensitive animal cards, floating fireflies, and parallax backgrounds.
- **Wildlife Atmosphere** – Animated fireflies, bouncing paw loader, and leaf‑like floating elements.
- **Smooth Animations** – Fade‑ins, slide transitions, counters, and ripple buttons.

---

## 🎨 Color Palette

| Role          | Hex Code  | Usage                             |
|---------------|-----------|-----------------------------------|
| Primary       | `#2ECC71` | Buttons, headings, active states  |
| Secondary     | `#27AE60` | Hover effects, secondary accents  |
| Accent        | `#F1C40F` | Highlights, ticket CTA, counter numbers |
| Background    | `#08120A` | Main background                   |
| Card          | `#16231B` | Base for glass‑morphism panels    |
| Text          | `#FFFFFF` | Primary text                      |

**Typography:** `Poppins` (headings) and `Montserrat` (body) for a clean, modern look.

---

## 🛠️ Technology Stack

| Category         | Technology                                |
|------------------|-------------------------------------------|
| **Frontend**     | HTML5, CSS3, Vanilla JavaScript           |
| **Animations**   | CSS Keyframes, `requestAnimationFrame`, Intersection Observer |
| **3D Effects**   | CSS `perspective`, JS mouse‑tracking tilt |
| **Fireflies**    | Canvas API (interactive floating particles) |
| **No frameworks**| Pure vanilla – no Bootstrap, Tailwind, or React |

---

## ✨ Key Features

- **10 Interconnected Pages** – Home, Login, Register, Dashboard, Safari Info, Gallery, Booking, Payment, Digital Ticket, About/Contact.
- **Complete Booking Flow** – Login → Dashboard → Select date/time → Enter visitor details → Auto‑calculate total (₹200/adult, ₹100/child) → Demo payment → Digital ticket with QR.
- **Digital Ticket Generation** – Dynamic ticket with Booking ID, visitor name, date, time slot, number of persons, total amount, and a QR code placeholder (8×8 grid). Printable via `window.print()`.
- **3D Animal Cards** – Gallery and home page cards tilt with mouse movement.
- **Floating Fireflies Canvas** – Atmospheric background particles that react to movement.
- **Animated Counters** – Visitors, species, years of service, and satisfaction rate count up on load.
- **Safari Information** – Timings, rules, and safety instructions.
- **About & Contact** – Developer profile (Md Shamim Akhter), contact details, FAQ accordion.
- **Responsive Design** – Adapts seamlessly to desktop, tablet, and mobile.
- **Glassmorphism Navigation** – Sticky, blurred navbar with active states.
- **Custom Loader** – Bouncing paw animation before page content appears.

---

## 📄 Pages & Sections

| Page               | Description |
|--------------------|-------------|
| **Home**           | Hero with video overlay, stats, popular animals, about snippet |
| **Login**          | Email/password form with demo validation |
| **Register**       | Full registration form (static demo) |
| **Dashboard**      | Quick‑access cards for booking, history, profile, and last ticket |
| **Safari Info**    | Timings, rules, safety guidelines |
| **Gallery**        | All 9 animal species displayed as 3D tilt cards |
| **Booking**        | Visitor details, adult/child counters, date/time, auto‑calculated total |
| **Payment**        | Demo payment options (UPI, Card, Net Banking) – success triggers ticket |
| **Digital Ticket** | Full ticket with QR placeholder, print button |
| **About & Contact**| Developer info, contact form, FAQ accordion |

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge)
- No server or build tools required.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/van-darshan.git
   cd van-darshan