# E-Commerce-Website
This is about platform of E-Commerce side website for buying modern clothes.  
<div align="center">

<br/>

<img src="img/logo.png" alt="Tech2etc Logo" width="200"/>

<br/><br/>

# 🛍️ Tech2etc — E-Commerce Website

**A modern, fully responsive e-commerce storefront built from scratch with pure HTML, CSS & JavaScript.**

<br/>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)](https://fontawesome.com)
[![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://fonts.google.com)

<br/>

![Status](https://img.shields.io/badge/Status-Active-22c55e?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-8b5cf6?style=flat-square)
![Responsive](https://img.shields.io/badge/Responsive-Yes-06b6d4?style=flat-square)
![No Framework](https://img.shields.io/badge/Framework-None-f97316?style=flat-square)

<br/>

[Live Demo](#-live-demo) · [Features](#-features) · [Pages](#-pages) · [Getting Started](#-getting-started) · [Project Structure](#-project-structure) · [Contributing](#-contributing)

<br/>

</div>

---

## 🌟 Overview

**Tech2etc** is a clean, elegant, and fully responsive e-commerce frontend built entirely with **vanilla HTML, CSS, and JavaScript** — no frameworks, no dependencies, just pure web fundamentals. It showcases product listings, promotional banners, newsletter signup, and a shopping cart experience with a polished dark-and-teal aesthetic.

> Perfect for developers learning frontend e-commerce design, or as a solid foundation for a real online store.

---

## ✨ Features

<table>
<tr>
<td width="50%">

**🏠 Hero Section**
Full-screen banner with compelling call-to-action and product promotion text

**🛒 Product Cards**
Featured products and new arrivals displayed in a responsive grid with ratings and pricing

**🎯 Promotional Banners**
Full-width and split promotional banners with overlay text and CTA buttons

</td>
<td width="50%">

**📦 Feature Highlights**
Six value-proposition icons — Free Shipping, Online Order, Save Money, Promotions, Happy Sell, Support

**📧 Newsletter Signup**
Email capture section with dark background and inline input/button form

**📱 Fully Responsive**
Fluid layouts and flexbox-based grid that adapts to all screen sizes

</td>
</tr>
</table>

---

## 📄 Pages

| Page | File | Description |
|------|------|-------------|
| 🏠 Home | `index.html` | Hero, featured products, banners, newsletter |
| 🛍️ Shop | `shop.html` | Full product listing with filters |
| 📝 Blog | `blog.html` | Articles and editorial content |
| ℹ️ About | `about.html` | Brand story and team |
| 📬 Contact | `contact.html` | Contact form and information |
| 🛒 Cart | `Cart.html` | Shopping cart and order summary |

---

## 🗂️ Project Structure

```
tech2etc-ecommerce/
│
├── 📄 index.html               ← Homepage
├── 📄 shop.html                ← Shop / product listing
├── 📄 blog.html                ← Blog page
├── 📄 about.html               ← About page
├── 📄 contact.html             ← Contact page
├── 📄 Cart.html                ← Shopping cart
│
├── 📄 style.css                ← Global stylesheet (Spartan font + teal theme)
├── 📄 script.js                ← JavaScript interactions
│
└── 📂 img/
    ├── logo.png                ← Brand logo
    ├── hero4.png               ← Hero background image
    ├── button.png              ← Hero CTA button asset
    │
    ├── 📂 features/
    │   ├── f1.png – f6.png     ← Feature section icons
    │
    ├── 📂 products/
    │   ├── f1.jpg – f8.jpg     ← Featured product images
    │   └── n1.jpg – n8.jpg     ← New arrival product images
    │
    └── 📂 banner/
        ├── b2.jpg, b4.jpg      ← Promotional banner images
        └── b14.png ...         ← Newsletter & other banners
```

---

## 🎨 Design System

| Token | Value | Usage |
|-------|-------|-------|
| **Primary Color** | `#088178` | Buttons, links, accents, product price |
| **Background** | `#E3E6F3` | Header / navbar background |
| **Dark Text** | `#222222` | Headings |
| **Body Text** | `#465b52` | Paragraph text |
| **Card Border** | `#cce7d0` | Product and feature card borders |
| **Font** | `Spartan` (Google Fonts) | All text — weights 100–900 |

---

## 🚀 Getting Started

No build tools, no package manager, no setup required.

### Option 1 — Open Directly in Browser

```bash
# Clone the repository
git clone https://github.com/your-username/tech2etc-ecommerce.git

# Navigate into the folder
cd tech2etc-ecommerce

# Open in browser
open index.html
```

### Option 2 — VS Code + Live Server *(Recommended)*

1. Open the project folder in **VS Code**
2. Install the **Live Server** extension by Ritwick Dey
3. Right-click `index.html` → **Open with Live Server**
4. Your browser opens at `http://127.0.0.1:5500/`

> Changes to HTML/CSS/JS are reflected instantly in the browser — no manual refresh needed.

---

## 📱 Responsive Design

The layout is built with **CSS Flexbox** and fluid widths, making it fully adaptive:

| Breakpoint | Layout |
|------------|--------|
| Desktop `> 1200px` | Full multi-column grid, large hero |
| Tablet `768px – 1200px` | Adjusted columns, scaled typography |
| Mobile `< 768px` | Single column, stacked sections |

---

## 🔧 Customization

### Change the Brand Color
Find and replace the primary teal across `style.css`:
```css
/* Replace this */
color: #088178;

/* With your brand color */
color: #your-color;
```

### Add a New Product
In `index.html`, duplicate a `.pro` block inside `.pro_container`:
```html
<div class="pro">
    <img src="img/products/your-image.jpg" alt="Product Name">
    <div class="des">
        <span>Brand</span>
        <h5>Product Name</h5>
        <div class="star">
            <i class="fa-solid fa-star"></i>
            <!-- repeat for rating -->
        </div>
        <h4>$99</h4>
    </div>
    <a href="Cart.html"><i class="fa-solid fa-cart-shopping cart"></i></a>
</div>
```

### Swap the Hero Banner
Replace the background image in `style.css`:
```css
#hero {
    background-image: url("img/your-hero-image.png");
}
```

---

## 🤝 Contributing

All contributions are welcome — bug fixes, improvements, new features, or additional pages.

```bash
# 1. Fork the repository

# 2. Create a feature branch
git checkout -b feature/your-feature-name

# 3. Make your changes and commit
git commit -m "feat: describe your change here"

# 4. Push your branch
git push origin feature/your-feature-name

# 5. Open a Pull Request on GitHub
```

---

## 📄 License

Released under the **MIT License** — free to use, modify, and distribute.
See the [LICENSE](LICENSE) file for details.

---

<div align="center">

<br/>

Crafted with passion for the web development community.

**Tech2etc E-Commerce** — Learn. Build. Ship.

<br/>

⭐ **If this project helped you, please give it a star!** ⭐

<br/>

[↑ Back to Top](#️-tech2etc--e-commerce-website)

</div>
