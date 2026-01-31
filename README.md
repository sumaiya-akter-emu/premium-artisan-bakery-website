# 🥐 Boulangerie - Premium Artisan Bakery Website

A visually stunning, high-performance 5-page website for an artisan bakery. This project demonstrates advanced front-end development skills, focusing on semantic architecture, accessibility, and a premium user experience through modern CSS and JavaScript.

## 🚀 Live Demo
[View Live Project](https://sumaiya-akter-emu.github.io/premium-artisan-bakery-website/)

## 📸 Screenshots

<table width="100%">
  <tr>
    <td width="33.33%" align="center">
      <img src="https://raw.githubusercontent.com/sumaiya-akter-emu/premium-artisan-bakery-website/main/sumaiya-akter-emu.github.io_premium-artisan-bakery-website-Home-Page.png" alt="Home Page" style="border-radius: 8px;">
      <br><b>Home Page</b>
    </td>
    <td width="33.33%" align="center">
      <img src="https://raw.githubusercontent.com/sumaiya-akter-emu/premium-artisan-bakery-website/main/sumaiya-akter-emu.github.io_premium-artisan-bakery-website-Menu-Page.png" alt="Menu Page" style="border-radius: 8px;">
      <br><b>Menu Page</b>
    </td>
    <td width="33.33%" align="center">
      <img src="https://raw.githubusercontent.com/sumaiya-akter-emu/premium-artisan-bakery-website/main/sumaiya-akter-emu.github.io_premium-artisan-bakery-website-About-Page.png" alt="About Page" style="border-radius: 8px;">
      <br><b>About Page</b>
    </td>
  </tr>
  <tr>
    <td width="33.33%" align="center">
      <img src="https://raw.githubusercontent.com/sumaiya-akter-emu/premium-artisan-bakery-website/main/sumaiya-akter-emu.github.io_premium-artisan-bakery-website-Gallery-Page.png" alt="Gallery Page" style="border-radius: 8px;">
      <br><b>Gallery Page</b>
    </td>
    <td width="33.33%" align="center">
      <img src="https://raw.githubusercontent.com/sumaiya-akter-emu/premium-artisan-bakery-website/main/sumaiya-akter-emu.github.io_premium-artisan-bakery-website-Contact-Page.png" alt="Contact Page" style="border-radius: 8px;">
      <br><b>Contact Page</b>
    </td>
  </tr>
</table>
---

## ✨ Features

### 🎨 Design & User Experience
- **Premium Aesthetic**: A curated warm color palette (Cream, Caramel, Rose) paired with elegant typography (Playfair Display & Lato).
- **Micro-Animations**: Subtle, high-quality transitions and hover effects that enhance engagement without distracting from content.
- **Visual Excellence**: High-resolution imagery with custom-styled overlays and shadow systems.

### 🛠️ Technical Implementation
- **Intersection Observer API**: Used for efficient, scroll-triggered animations that keep the site performant.
- **Dynamic Filtering**: A seamless, zero-reload category filtering system for both the Menu and Gallery pages.
- **Custom Lightbox**: A bespoke, performant JavaScript image viewer for the gallery, avoiding heavy external libraries.
- **Responsive Layouts**: Built from the ground up using **CSS Grid** and **Flexbox** for a fluid experience on all devices.

### 🌐 Accessibility & SEO
- **Semantic HTML5**: Native elements used throughout for better screen reader support.
- **A11y Optimized**: ARIA labels on interactive elements and logical heading hierarchies (H1-H4).
- **SEO Best Practices**: Optimized meta descriptions, image alt tags, and performant asset loading.

---

## 📱 Responsive Design
The website is fully optimized for a flawless experience across:
- **Desktop**: 1200px and above (Wide layouts with rich spacing)
- **Tablet**: 768px - 1199px (Reflowed grids for touch interaction)
- **Mobile**: 320px - 767px (Simplified navigation and optimized tap targets)

---

## 🛠️ Tech Stack

- **Core**: HTML5, Modern CSS3, ES6+ JavaScript
- **API**: Intersection Observer API (for animations)
- **Icons**: [Lucide Icons](https://lucide.dev/) (Inline SVG for performance)
- **Typography**: [Google Fonts](https://fonts.google.com/) (Playfair Display / Lato)
- **Assets**: High-quality imagery from Unsplash

---

## 🎨 Design Inspiration
- **European Boulangeries**: Inspired by contemporary French bakery branding.
- **Modern Minimalism**: Focus on whitespace and visual hierarchy.
- **Contemporary UI Trends**: Glassmorphism effects in the header and subtle card elevations.

---

## 📁 Project Structure

```text
├── index.html      # Home page (Brand story & highlights)
├── menu.html       # Product catalog with dynamic filtering
├── about.html      # Values, story, and team showcase
├── gallery.html    # Visual portfolio with interactive lightbox
├── contact.html    # Form validation & business info
├── styles.css      # Modular design tokens & components
└── script.js       # Core logic, animations & UI interaction
```

---

## 🧩 Technical Challenges & Optimization

### 1. Performance vs. Animations
- **Challenge**: Initially, using traditional scroll listeners for animations risked "jank" (stuttering) on mobile devices by overloading the main thread.
- **Solution**: I implemented the **Intersection Observer API**. This offloads the work to the browser's internal engine, ensuring animations only trigger exactly when they enter the viewport, keeping the site performant and energy-efficient.

### 2. Bespoke Gallery Experience
- **Challenge**: I wanted a high-quality gallery experience without the performance overhead or dependency "bloat" of external libraries.
- **Solution**: I built a custom JavaScript viewer from scratch. Key optimizations included:
    - **Context Preservation**: Automatically locking the background scroll when the viewer is active.
    - **Natural Navigation**: Implementing a global `Escape` key listener for a more intuitive desktop user interface.

---

## 🔧 Installation & Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sumaiya-akter-emu/premium-artisan-bakery-website.git
   ```
2. **Launch**: Open `index.html` in your browser or use a Live Server extension in VS Code.

---

Crafted with ❤️ by Sumaiya.
