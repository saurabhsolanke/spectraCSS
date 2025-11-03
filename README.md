# 🎨 Solanke Themes - Professional Color Theme Library

A beautiful, professional theme system with **Luxury Green** and **Corporate Blue** color palettes. Perfect for portfolios, landing pages, and web applications.

---

## 🚀 Quick Start

### Option 1: CDN (Recommended)

```html
<!DOCTYPE html>
<html lang="en" data-color-theme="luxury">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Project</title>
  
  <!-- Include Solanke Themes -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/solanke-themes@1.0.0/solanke-themes.css">
</head>
<body data-theme-enabled>
  <h1 class="text-gradient-theme">Hello World!</h1>
  <button class="btn-theme-primary">Get Started</button>
</body>
</html>
```

### Option 2: Download and Self-Host

1. Download `solanke-themes.css`
2. Include in your project:
```html
<link rel="stylesheet" href="path/to/solanke-themes.css">
```

### Option 3: npm Package

```bash
npm install solanke-themes
```

---

## 🎨 Available Themes

### Luxury Green Theme (Default)
```html
<html data-color-theme="luxury">
```
- **Darkest**: `#0D2B1D` - Deep forest green
- **Dark**: `#345635` - Dark green
- **Sage**: `#6B8F71` - Sage green
- **Mint**: `#AEC3B0` - Mint green
- **Cream**: `#E3EFD3` - Light cream
- **Accent**: `#6B8F71` - Sage green

### Corporate Blue Theme
```html
<html data-color-theme="corporate">
```
- **Darkest**: `#2E4053` - Deep blue-gray
- **Dark**: `#AAB7B8` - Steel gray
- **Sage**: `#BFC9CA` - Silver
- **Mint**: `#D5D8DC` - Cloud gray
- **Cream**: `#F8F9FA` - Light gray
- **Accent**: `#F1C40F` - Gold

---

## 🌙 Dark Mode

Add the `dark` class to enable dark mode:

```html
<html data-color-theme="luxury" class="dark">
```

Toggle dark mode with JavaScript:

```javascript
// Toggle dark mode
document.documentElement.classList.toggle('dark');

// Set dark mode
document.documentElement.classList.add('dark');

// Set light mode
document.documentElement.classList.remove('dark');
```

---

## 📚 Available Classes

### Background Colors

```html
<div class="bg-theme-darkest">Darkest background</div>
<div class="bg-theme-dark">Dark background</div>
<div class="bg-theme-sage">Sage background</div>
<div class="bg-theme-mint">Mint background</div>
<div class="bg-theme-cream">Cream background</div>
<div class="bg-theme-accent">Accent background</div>

<!-- With opacity -->
<div class="bg-theme-sage-60">60% opacity</div>
<div class="bg-theme-mint-40">40% opacity</div>
```

### Text Colors

```html
<p class="text-theme-darkest">Darkest text</p>
<p class="text-theme-sage">Sage text</p>
<p class="text-theme-accent">Accent text</p>
<p class="text-gradient-theme">Gradient text</p>

<!-- With opacity -->
<p class="text-theme-dark-80">80% opacity</p>
```

### Border Colors

```html
<div class="border-theme-sage border-2">Bordered element</div>
<div class="border-theme-mint-30 border">30% opacity border</div>
```

### Buttons

```html
<button class="btn-theme-primary">Primary Button</button>
<button class="btn-theme-secondary">Secondary Button</button>
<button class="btn-theme-accent">Accent Button</button>
```

### Cards

```html
<div class="card-theme">
  <h3>Card Title</h3>
  <p>Card content with glass effect</p>
</div>
```

### Glass Effect

```html
<div class="glass-theme">
  Liquid glass design element
</div>
```

### Badges

```html
<span class="badge-theme-primary">Primary</span>
<span class="badge-theme-secondary">Secondary</span>
<span class="badge-theme-accent">Accent</span>
```

### Alerts

```html
<div class="alert-theme-info">Info alert message</div>
<div class="alert-theme-success">Success alert message</div>
<div class="alert-theme-warning">Warning alert message</div>
```

### Gradients

```html
<div class="gradient-theme-primary">Primary gradient background</div>
<div class="gradient-theme-secondary">Secondary gradient background</div>
<h1 class="text-gradient-theme">Gradient text</h1>
```

### Shadows

```html
<div class="shadow-theme-sm">Small shadow</div>
<div class="shadow-theme-md">Medium shadow</div>
<div class="shadow-theme-lg">Large shadow</div>
<div class="shadow-theme-xl">Extra large shadow</div>
```

### Animations

```html
<div class="animate-fade-in">Fades in</div>
<div class="animate-slide-in">Slides in</div>
<div class="hover-lift">Lifts on hover</div>
```

---

## 🎯 Complete Example

```html
<!DOCTYPE html>
<html lang="en" data-color-theme="luxury">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Solanke Themes Example</title>
  <link rel="stylesheet" href="solanke-themes.css">
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      margin: 0;
      padding: 2rem;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
    }
  </style>
</head>
<body data-theme-enabled>
  <div class="container">
    <!-- Hero Section -->
    <div class="glass-theme animate-fade-in" style="padding: 3rem; margin-bottom: 2rem; border-radius: 1.5rem;">
      <h1 class="text-gradient-theme" style="font-size: 3rem; margin: 0 0 1rem 0;">
        Welcome to Solanke Themes
      </h1>
      <p class="text-theme-dark" style="font-size: 1.25rem; margin: 0 0 2rem 0;">
        Beautiful, professional color themes for your projects
      </p>
      <button class="btn-theme-primary" style="margin-right: 1rem;">
        Get Started
      </button>
      <button class="btn-theme-secondary">
        Learn More
      </button>
    </div>

    <!-- Cards Grid -->
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem;">
      <div class="card-theme hover-lift">
        <span class="badge-theme-primary">Featured</span>
        <h3 class="text-theme-darkest" style="margin: 1rem 0 0.5rem 0;">Card Title</h3>
        <p class="text-theme-dark-80">Beautiful card with glass effect and hover animation.</p>
      </div>
      
      <div class="card-theme hover-lift">
        <span class="badge-theme-accent">New</span>
        <h3 class="text-theme-darkest" style="margin: 1rem 0 0.5rem 0;">Another Card</h3>
        <p class="text-theme-dark-80">Responsive and accessible design components.</p>
      </div>
    </div>

    <!-- Theme Switcher -->
    <div style="margin-top: 2rem; text-align: center;">
      <button onclick="switchTheme('luxury')" class="btn-theme-secondary">
        Luxury Green
      </button>
      <button onclick="switchTheme('corporate')" class="btn-theme-secondary">
        Corporate Blue
      </button>
      <button onclick="toggleDark()" class="btn-theme-accent">
        Toggle Dark Mode
      </button>
    </div>
  </div>

  <script>
    function switchTheme(theme) {
      document.documentElement.setAttribute('data-color-theme', theme);
      localStorage.setItem('color-theme', theme);
    }

    function toggleDark() {
      document.documentElement.classList.toggle('dark');
      const isDark = document.documentElement.classList.contains('dark');
      localStorage.setItem('dark-mode', isDark);
    }

    // Load saved preferences
    const savedTheme = localStorage.getItem('color-theme') || 'luxury';
    const isDark = localStorage.getItem('dark-mode') === 'true';
    
    document.documentElement.setAttribute('data-color-theme', savedTheme);
    if (isDark) document.documentElement.classList.add('dark');
  </script>
</body>
</html>
```

---

## 🔧 JavaScript Helper Functions

```javascript
// Solanke Themes Helper Functions

const SolankeThemes = {
  // Switch color theme
  setColorTheme: (theme) => {
    document.documentElement.setAttribute('data-color-theme', theme);
    localStorage.setItem('solanke-color-theme', theme);
  },

  // Get current theme
  getColorTheme: () => {
    return document.documentElement.getAttribute('data-color-theme') || 'luxury';
  },

  // Toggle dark mode
  toggleDarkMode: () => {
    document.documentElement.classList.toggle('dark');
    const isDark = document.documentElement.classList.contains('dark');
    localStorage.setItem('solanke-dark-mode', isDark);
    return isDark;
  },

  // Set dark mode
  setDarkMode: (enabled) => {
    if (enabled) {
      document.documentElement.classList.add('dark');
    } else {
      document.documentElement.classList.remove('dark');
    }
    localStorage.setItem('solanke-dark-mode', enabled);
  },

  // Initialize from localStorage
  init: () => {
    const savedTheme = localStorage.getItem('solanke-color-theme') || 'luxury';
    const isDark = localStorage.getItem('solanke-dark-mode') === 'true';
    
    SolankeThemes.setColorTheme(savedTheme);
    SolankeThemes.setDarkMode(isDark);
  }
};

// Auto-initialize
document.addEventListener('DOMContentLoaded', () => {
  SolankeThemes.init();
});
```

---

## 📦 Publishing to CDN

### Using jsDelivr (Free CDN)

After publishing to npm, your package is automatically available via jsDelivr:

```html
<!-- Latest version -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/solanke-themes@latest/solanke-themes.css">

<!-- Specific version (recommended) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/solanke-themes@1.0.0/solanke-themes.css">
```

Or use GitHub CDN:
```
https://cdn.jsdelivr.net/gh/saurabhsolanke/spectraCSS@main/solanke-themes.css
```

### Using unpkg (npm-based CDN)

1. Publish to npm:
```bash
npm publish
```

2. Use this URL:
```
https://unpkg.com/solanke-themes@latest/solanke-themes.css
```

---

## 🎨 Customization

You can override any CSS variable:

```css
:root[data-color-theme="custom"] {
  --theme-darkest: #your-color;
  --theme-dark: #your-color;
  --theme-sage: #your-color;
  --theme-mint: #your-color;
  --theme-cream: #your-color;
  --theme-accent: #your-color;
}
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Add new color themes

---

## 📄 License

MIT License - Feel free to use in personal and commercial projects!

---

## 👨‍💻 Author

**Saurabh Solanke**
- Portfolio: [saurabhsolanke.com](https://www.saurabhsolanke.com)
- GitHub: [@saurabhsolanke](https://github.com/saurabhsolanke)
- LinkedIn: [Saurabh Solanke](https://www.linkedin.com/in/saurabh-solanke/)

---

## 🌟 Show Your Support

If you find this theme library helpful, please give it a ⭐ on [GitHub](https://github.com/saurabhsolanke/spectraCSS)!

---

Made with ♥ by Saurabh Solanke

