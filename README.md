# Syarip Muhammad Abdillah - Engineering Portfolio & Technical Blog

> **Live Website:** [https://syarifabdillah.my.id](https://syarifabdillah.my.id)

A minimalist, high-precision, and responsive **Top-Global Engineering Portfolio** built with [Hugo](https://gohugo.io/). Designed specifically for a Senior Lead System Engineer / Platform & DevOps Specialist.

---

## ⚡ Key Highlights & Features

- **Futuristic Editorial Design System:** A clean, high-contrast Pure White & Electric Blue palette (`#2563eb` / `#388bfd`) featuring typography powered by `Inter` and `Fira Code`.
- **Dynamic Dark/Light Mode:** Seamless theme toggle with automatic CLI logo color switching (Black on Light Mode, White on Dark Mode).
- **Interactive CLI Terminal Cursor:** Animated blinking blue prompt cursor (`> $ cd ~`).
- **Instant Documentation Search:** Client-side real-time filtering for technical articles on `/posts/`.
- **Table of Contents (TOC):** Collapsible accordion dropdown for long technical documentation.
- **Copy Code Buttons:** One-click code snippet copying with visual feedback.
- **Social Share Bar:** Quick sharing to LinkedIn, X/Twitter, WhatsApp, and Copy Link on all articles.
- **Clean ATS Resume Print Support:** Custom `@media print` rules for clean, ATS-compliant CV exports when printing (`Ctrl + P`).
- **Reading Progress Indicator:** Top floating blue progress bar for reading experience.
- **100% Mobile & Desktop Responsive:** Fully optimized layout for mobile, tablet, and desktop viewports.
- **100% SEO Compliance:** Includes OpenGraph, Twitter Cards, and JSON-LD Structured Data for search engine discoverability.

---

## 🛠️ Tech Stack

- **Static Site Generator:** Hugo (Extended v0.164.0+)
- **Theme Base:** Hello Friend NG (Customized)
- **Styling:** Custom CSS Grid & Flexbox (`static/custom.css`)
- **Fonts:** Inter & Fira Code (via Google Fonts)
- **Icons:** SVG Icons & Custom Terminal SVG Favicon

---

## 🚀 Local Development

To run the site locally for development:

```bash
# Clone the repository
git clone https://github.com/sectenzorg/personal-website.git
cd personal-website

# Start Hugo local server
hugo server -D
```

Open [http://localhost:1313](http://localhost:1313) in your browser.

---

## 📦 Production Build

To build the static site for production deployment:

```bash
hugo --gc --minify
```

The optimized static files will be generated in the `public/` directory, ready to be deployed to Netlify, Vercel, GitHub Pages, or any web server.

---

## 📄 License

Content © [Syarip Muhammad Abdillah](https://syarifabdillah.my.id). Theme based on Hello Friend NG.