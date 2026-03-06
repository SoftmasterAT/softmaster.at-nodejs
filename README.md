# Softmaster.at Node.js Version

[![Deploy to Render](https://api.render.com/deploy/srv-d6lab37kijhs73b1dlq0)](https://api.render.com/deploy/srv-d6lab37kijhs73b1dlq0) 
![Status](https://shields.io)

[![Website Status](https://shields.io)](https://node.softmaster.at/)

This is the Node.js/Express implementation of [softmaster.at](https://softmaster.at). 
The project features a dynamic EJS-based templating system with multi-language support.

## Live Demo
- **Primary:** [https://node.softmaster.at/](https://node.softmaster.at/)
- **Fallback:** [https://softmaster-at-nodejs.onrender.com/](https://softmaster-at-nodejs.onrender.com/)

## Latest Updates
- ✅ **SSL & Custom Domain:** Fully configured with Let's Encrypt via Render.
- ✅ **Error Handling:** Added custom 404 page for better UX and build stability.
- ✅ **Email Integration:** Optimized SMTP transport for production environments.
- ✅ **Security:** Cloudflare Turnstile integrated for spam protection.

## Tech Stack
- **Backend:** Node.js, Express.js
- **Frontend:** EJS (Embedded JavaScript), Vanilla JS, Tailwind CSS, CSS3
- **Mailing:** Nodemailer with SMTP
- **Infrastructure:** Hosted on Render.com

## Features
- **Engine:** Express.js & EJS
- **SEO:** Dynamic meta tags and canonical URLs generated via middleware.
- **Languages:** German (default) and English via JSON localization files.
- **Performance:** Optimized LCP and reduced layout thrashing (Canvas/Slider).
- **Contact:** Secure nodemailer integration using environment variables.

## Setup
1. `npm install`
2. Create a `.env` file (see `.env.example`)
3. `npm start`
