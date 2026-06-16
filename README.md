# 🎨 Theme Switcher Pro

A modern and responsive Theme Switcher built entirely with **HTML** and **CSS**. This project demonstrates how to create multiple visual themes using **CSS Variables (Design Tokens)** and **Modern CSS Selectors** without relying on JavaScript.

The application allows users to switch between **Light**, **Dark**, and **Aurora** themes while keeping the same UI structure and component markup.

---

## 🚀 Features

- 🌞 Light Theme
- 🌙 Dark Theme
- ✨ Aurora Theme
- 🎨 CSS Variables (Design Tokens)
- 🧩 Modern CSS `:has()` Selector
- ⚡ No JavaScript Required
- 📱 Fully Responsive Design
- ♿ Keyboard Accessible Controls
- 🖥️ Professional UI Layout
- 🔄 Single Card with Dynamic Theme Switching

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- CSS Variables
- Modern CSS Selectors (`:has()`)
- Responsive Design

---

## 📸 Preview

The application includes:

- Theme selection controls
- Dynamic theme switching
- Professional preview card
- Responsive layout for desktop, tablet, and mobile devices

---

## 📂 Project Structure

```text
theme-switcher-pro/
│
├── index.html
└── style.css
```

---

## 🎯 Learning Objectives

This project helps developers learn:

- CSS Variable Management
- Design Token Architecture
- Modern CSS State Management
- Theme Switching Without JavaScript
- Responsive UI Design
- CSS Organization Best Practices
- Accessibility-Friendly Form Controls

---

## 🎨 Theme Architecture

The application uses a centralized token system:

```css
:root {
  --color-bg;
  --color-surface;
  --color-text;
  --color-muted;
  --color-accent;
}
```

Each theme overrides the same set of variables:

```css
.theme-system:has(#light:checked) { ... }

.theme-system:has(#dark:checked) { ... }

.theme-system:has(#aurora:checked) { ... }
```

This ensures every component automatically updates when the active theme changes.

---

## 📱 Responsive Design

The interface is optimized for:

- Desktop
- Tablet
- Mobile

Flexible layouts and scalable typography ensure a consistent experience across all screen sizes.

---

## ♿ Accessibility

The project follows accessibility best practices:

- Keyboard-accessible theme controls
- Semantic HTML structure
- Visible focusable form elements
- Proper label associations

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/yourusername/theme-switcher-pro.git
```

### Open the project

Simply open:

```text
index.html
```

in your browser.

No build tools, frameworks, or dependencies are required.

---

## 📌 Requirements Fulfilled

- At least three themes defined
- No JavaScript used
- CSS Variables used as design tokens
- Theme switching with `:has()` selector
- Same token names across all themes
- Keyboard-accessible controls
- Single preview card shared across all themes
- Responsive layout

---

## 📄 License

This project is open-source and available under the MIT License.

---

### Built with HTML & CSS
