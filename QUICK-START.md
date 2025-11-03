# ⚡ Quick Start - Solanke Themes

Get started in 30 seconds!

---

## 🚀 1. Add to Your HTML

```html
<!DOCTYPE html>
<html lang="en" data-color-theme="luxury">
<head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/YOUR-USERNAME/solanke-themes@v1.0.0/solanke-themes.css">
</head>
<body data-theme-enabled>
  <!-- Your content here -->
</body>
</html>
```

---

## 🎨 2. Use Theme Classes

```html
<!-- Buttons -->
<button class="btn-theme-primary">Primary</button>
<button class="btn-theme-secondary">Secondary</button>
<button class="btn-theme-accent">Accent</button>

<!-- Cards -->
<div class="card-theme hover-lift">
  <h3 class="text-gradient-theme">Card Title</h3>
  <p class="text-theme-dark">Card content</p>
</div>

<!-- Glass Effect -->
<div class="glass-theme">
  Liquid glass design
</div>

<!-- Colors -->
<div class="bg-theme-sage text-theme-cream">
  Colored box
</div>

<!-- Badges -->
<span class="badge-theme-primary">New</span>
```

---

## 🌙 3. Add Theme Switcher

```html
<button onclick="switchTheme('luxury')">🌿 Luxury Green</button>
<button onclick="switchTheme('corporate')">💼 Corporate Blue</button>
<button onclick="toggleDark()">🌙 Dark Mode</button>

<script>
  function switchTheme(theme) {
    document.documentElement.setAttribute('data-color-theme', theme);
    localStorage.setItem('color-theme', theme);
  }

  function toggleDark() {
    document.documentElement.classList.toggle('dark');
  }

  // Load saved preferences
  const savedTheme = localStorage.getItem('color-theme') || 'luxury';
  document.documentElement.setAttribute('data-color-theme', savedTheme);
</script>
```

---

## 📦 npm Installation

```bash
npm install solanke-themes
```

```javascript
import 'solanke-themes/solanke-themes.css';
```

---

## 🎯 Available Themes

| Theme | HTML Attribute |
|-------|---------------|
| Luxury Green | `data-color-theme="luxury"` |
| Corporate Blue | `data-color-theme="corporate"` |

---

## 🎨 Quick Color Reference

### Luxury Green Theme
- `bg-theme-darkest` - `#0D2B1D` (Deep forest)
- `bg-theme-dark` - `#345635` (Dark green)
- `bg-theme-sage` - `#6B8F71` (Sage)
- `bg-theme-mint` - `#AEC3B0` (Mint)
- `bg-theme-cream` - `#E3EFD3` (Cream)

### Corporate Blue Theme
- `bg-theme-darkest` - `#2E4053` (Blue-gray)
- `bg-theme-dark` - `#AAB7B8` (Steel)
- `bg-theme-sage` - `#BFC9CA` (Silver)
- `bg-theme-mint` - `#D5D8DC` (Cloud)
- `bg-theme-cream` - `#F8F9FA` (Light)
- `bg-theme-accent` - `#F1C40F` (Gold)

---

## 📚 Full Documentation

- [Complete Documentation](README-THEME-LIBRARY.md)
- [Setup Guide for Publishing](SETUP-GUIDE.md)
- [Live Demo](demo.html)

---

## ✨ Examples

### Example 1: Hero Section
```html
<div class="glass-theme" style="padding: 4rem 2rem; border-radius: 2rem;">
  <h1 class="text-gradient-theme">Welcome!</h1>
  <p class="text-theme-dark">Beautiful themed hero section</p>
  <button class="btn-theme-primary">Get Started</button>
</div>
```

### Example 2: Card Grid
```html
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem;">
  <div class="card-theme hover-lift">
    <span class="badge-theme-primary">Featured</span>
    <h3 class="text-theme-darkest">Card 1</h3>
  </div>
  <div class="card-theme hover-lift">
    <span class="badge-theme-accent">New</span>
    <h3 class="text-theme-darkest">Card 2</h3>
  </div>
</div>
```

### Example 3: Navigation
```html
<nav class="glass-theme" style="padding: 1rem; display: flex; gap: 1rem;">
  <a href="#" class="btn-theme-secondary">Home</a>
  <a href="#" class="btn-theme-secondary">About</a>
  <a href="#" class="btn-theme-primary">Contact</a>
</nav>
```

---

## 🔥 Pro Tips

1. **Always pin versions in production:**
   ```html
   <link rel="stylesheet" href="...@v1.0.0/solanke-themes.css">
   ```

2. **Use preload for better performance:**
   ```html
   <link rel="preload" href="...solanke-themes.css" as="style">
   ```

3. **Combine with your own CSS:**
   ```css
   .my-custom-card {
     @apply glass-theme hover-lift;
     /* Your custom styles */
   }
   ```

---

That's it! You're ready to create beautiful themed websites! 🎉

For advanced usage, check out the [full documentation](README-THEME-LIBRARY.md).

