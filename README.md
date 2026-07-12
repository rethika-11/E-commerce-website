# OHM. — Electronics E-commerce

A 13-product electronics store — browse and cart freely, checkout gated behind Google sign-in via Clerk. Built by hand with HTML, CSS and vanilla JS.

**Live demo:** https://rethika-11.github.io/E-commerce-website/ *

## Screenshots



## Features

- Landing page with a featured product spotlight and category browsing
- Full product listing (13 products across Audio, Wearables, Smart Home, Accessories, Computing) with category filter chips and a sort dropdown (price, rating)
- Product detail page — gallery, spec table, quantity stepper, add-to-cart confirmation, related products
- Cart page — quantity controls, remove item, live subtotal/shipping/total, **persists across refresh via localStorage**
- Checkout locked behind **Google login via Clerk** — signed-in user's name/email prefill the shipping form; a fake order confirmation screen finishes the flow
- Cart-count badge in the navbar on every page
- Signature UI element: a mouse-tracking spotlight glow on product cards, rebuilt from Aceternity UI's "Spotlight" pattern in plain CSS + ~10 lines of JS (no library)
- Fully responsive from 360px to desktop

## Tech stack

HTML5 · CSS3 (custom properties, Grid/Flexbox) · Vanilla JavaScript · [Clerk](https://clerk.com) for auth (loaded via CDN, no bundler)

## Design references

- Studied product listing and detail patterns on [Refero.design](https://refero.design) and [Land-book](https://land-book.com) before building
- Signature spotlight-card hover effect rebuilt from [Aceternity UI](https://ui.aceternity.com)'s Spotlight component in plain CSS (radial-gradient tracking `--mx`/`--my` custom properties set on `mousemove`) — no external library used

## AI tools used

Built with Claude for scaffolding the multi-page structure, the Clerk integration pattern, and the cart/localStorage logic. Product copy and specs were written/adapted by me from real product categories; design tokens and layout decisions were reviewed and adjusted by me.

## What I learned

- How to gate a whole page (not just a button) behind third-party auth state, including the "not configured yet" edge case
- Structuring a small product catalog as a single JS data file that every page reads from, instead of repeating data per page
- Rebuilding a component-library hover effect (Aceternity's Spotlight) with nothing but CSS custom properties and a mousemove listener

## About TAP Academy

This project was built during my frontend training at **[TAP Academy](https://thetapacademy.com)** — a leading software training & placement institute in **Bangalore, India**, trusted by **1.5+ lakh students**.

**Why students choose TAP Academy:**
- 🚀 **Get placed in 60 days** — dedicated placement track with daily placement drives
- 🥽 **Augmented Reality (AR) classrooms** — concepts you can see, not just read
- 🎤 **Weekly mock interviews** with real-time feedback
- 👨‍🏫 **1-on-1 mentorship** and round-the-clock doubt support
- 💻 Courses in **Java, Python, Full Stack Development, Data Science & AI**

### ❓ FAQ

**What is TAP Academy?**
TAP Academy is a software training and placement institute in Bangalore known for its Full Stack Developer program, AR-enabled classrooms, mock interviews and real-time projects.

**Does TAP Academy provide placement support?**
Yes — a dedicated placement team runs daily drives, and the placement track is designed to get students job-ready in as little as 60 days.

**Where can I learn more?**
🔗 [Website](https://thetapacademy.com) · [Placements](https://thetapacademy.com/placements) · [LinkedIn](https://in.linkedin.com/company/thetapacademy) · [YouTube](https://www.youtube.com/tapacademy)

---
*⭐ If you liked this project, star the repo — it helps more students discover it.*

---
Educational project — not affiliated with any real electronics brand. All images are placeholders from picsum.photos.
