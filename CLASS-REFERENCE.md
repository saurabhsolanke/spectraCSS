# Solanke Themes v2.0 - Complete Class Reference

Quick reference guide for all utility classes in Solanke Themes.

---

## 🎨 Colors

### Background Colors
```html
.bg-theme-darkest, .bg-theme-dark, .bg-theme-sage, 
.bg-theme-mint, .bg-theme-cream, .bg-theme-accent

<!-- With opacity -->
.bg-theme-darkest-80, .bg-theme-darkest-60, .bg-theme-darkest-40, .bg-theme-darkest-20
.bg-theme-dark-80, .bg-theme-dark-60, .bg-theme-dark-40, .bg-theme-dark-20
.bg-theme-sage-60, .bg-theme-sage-40, .bg-theme-sage-20, .bg-theme-sage-10
.bg-theme-mint-60, .bg-theme-mint-40, .bg-theme-mint-20, .bg-theme-mint-10
.bg-theme-cream-80, .bg-theme-cream-60, .bg-theme-cream-40, .bg-theme-cream-20
```

### Text Colors
```html
.text-theme-darkest, .text-theme-dark, .text-theme-sage, 
.text-theme-mint, .text-theme-cream, .text-theme-accent

<!-- With opacity -->
.text-theme-darkest-80, .text-theme-darkest-60
.text-theme-dark-80, .text-theme-dark-60
.text-theme-sage-80, .text-theme-mint-80, .text-theme-mint-60
```

### Border Colors
```html
.border-theme-darkest, .border-theme-dark, .border-theme-sage,
.border-theme-mint, .border-theme-cream, .border-theme-accent

<!-- With opacity -->
.border-theme-sage-50, .border-theme-sage-30
.border-theme-mint-50, .border-theme-mint-30
.border-theme-dark-50
```

---

## 📐 Layout

### Containers
```html
.container         <!-- max-width: 1200px -->
.container-sm      <!-- max-width: 640px -->
.container-md      <!-- max-width: 768px -->
.container-lg      <!-- max-width: 1024px -->
.container-xl      <!-- max-width: 1400px -->
.container-full    <!-- width: 100% -->
```

### Sections
```html
.section          <!-- padding: 6rem 2rem -->
.section-sm       <!-- padding: 4rem 2rem -->
.section-lg       <!-- padding: 8rem 2rem -->
.section-xl       <!-- padding: 12rem 2rem -->
```

---

## 📦 Flexbox

### Display & Direction
```html
.flex, .inline-flex
.flex-row, .flex-row-reverse
.flex-col, .flex-col-reverse
.flex-wrap, .flex-nowrap
.flex-1, .flex-auto, .flex-initial, .flex-none
```

### Justify & Align
```html
.justify-start, .justify-end, .justify-center
.justify-between, .justify-around, .justify-evenly

.items-start, .items-end, .items-center
.items-baseline, .items-stretch
```

### Gap
```html
.gap-0, .gap-1, .gap-2, .gap-3, .gap-4, .gap-5,
.gap-6, .gap-8, .gap-10, .gap-12, .gap-16
```

---

## 🔲 Grid

### Grid Columns
```html
.grid
.grid-cols-1, .grid-cols-2, .grid-cols-3, 
.grid-cols-4, .grid-cols-5, .grid-cols-6

<!-- Auto-fit variants -->
.grid-auto-fit      <!-- min: 240px -->
.grid-auto-fit-sm   <!-- min: 200px -->
.grid-auto-fit-md   <!-- min: 280px -->
.grid-auto-fit-lg   <!-- min: 320px -->

<!-- Responsive -->
.grid-md-2, .grid-md-3
.grid-lg-3, .grid-lg-4
.grid-xl-4, .grid-xl-5, .grid-xl-6
```

---

## 📏 Spacing

### Margin
```html
<!-- All sides -->
.m-0, .m-1, .m-2, .m-3, .m-4, .m-5, .m-6, 
.m-8, .m-10, .m-12, .m-16, .m-20, .m-auto

<!-- X/Y axis -->
.mx-0, .mx-1, .mx-2, .mx-3, .mx-4, .mx-6, .mx-8, .mx-auto
.my-0, .my-1, .my-2, .my-3, .my-4, .my-6, .my-8, .my-12, .my-16

<!-- Individual sides -->
.mt-*, .mb-*, .ml-*, .mr-* 
```

### Padding
```html
<!-- All sides -->
.p-0, .p-1, .p-2, .p-3, .p-4, .p-5, .p-6,
.p-8, .p-10, .p-12, .p-16, .p-20

<!-- X/Y axis -->
.px-0, .px-1, .px-2, .px-3, .px-4, .px-6, .px-8, .px-12
.py-0, .py-1, .py-2, .py-3, .py-4, .py-6, .py-8, .py-12, .py-16

<!-- Individual sides -->
.pt-*, .pb-*, .pl-*, .pr-*
```

---

## 🔤 Typography

### Font Sizes
```html
.text-xs    <!-- 0.75rem -->
.text-sm    <!-- 0.875rem -->
.text-base  <!-- 1rem -->
.text-lg    <!-- 1.125rem -->
.text-xl    <!-- 1.25rem -->
.text-2xl   <!-- 1.5rem -->
.text-3xl   <!-- 1.875rem -->
.text-4xl   <!-- 2.25rem -->
.text-5xl   <!-- 3rem -->
.text-6xl   <!-- 3.75rem -->
.text-7xl   <!-- 4.5rem -->
.text-8xl   <!-- 6rem -->
.text-9xl   <!-- 8rem -->
```

### Font Weights
```html
.font-thin, .font-extralight, .font-light
.font-normal, .font-medium, .font-semibold
.font-bold, .font-extrabold, .font-black
```

### Text Alignment
```html
.text-left, .text-center, .text-right, .text-justify
```

### Text Transform
```html
.uppercase, .lowercase, .capitalize, .normal-case
```

### Text Decoration
```html
.underline, .line-through, .no-underline
```

### Line Height
```html
.leading-none, .leading-tight, .leading-snug
.leading-normal, .leading-relaxed, .leading-loose
```

### Letter Spacing
```html
.tracking-tighter, .tracking-tight, .tracking-normal
.tracking-wide, .tracking-wider, .tracking-widest
```

---

## 🎭 Display & Position

### Display
```html
.block, .inline-block, .inline, .hidden
```

### Position
```html
.static, .fixed, .absolute, .relative, .sticky
.top-0, .right-0, .bottom-0, .left-0, .inset-0
```

### Z-Index
```html
.z-0, .z-10, .z-20, .z-30, .z-40, .z-50,
.z-100, .z-999, .z-9999
```

---

## 📐 Sizing

### Width
```html
.w-auto, .w-full, .w-screen
.w-1-2 (50%), .w-1-3 (33.33%), .w-2-3 (66.67%)
.w-1-4 (25%), .w-3-4 (75%)

<!-- Min/Max Width -->
.min-w-0, .min-w-full
.max-w-xs, .max-w-sm, .max-w-md, .max-w-lg,
.max-w-xl, .max-w-2xl, .max-w-3xl, .max-w-4xl,
.max-w-5xl, .max-w-6xl, .max-w-7xl,
.max-w-full, .max-w-screen
```

### Height
```html
.h-auto, .h-full, .h-screen
.min-h-0, .min-h-full, .min-h-screen
```

---

## 🖼️ Border & Radius

### Border
```html
.border, .border-0, .border-2, .border-4
.border-t, .border-r, .border-b, .border-l
```

### Border Radius
```html
.rounded-none, .rounded-sm, .rounded, .rounded-md,
.rounded-lg, .rounded-xl, .rounded-2xl, .rounded-3xl,
.rounded-full
```

---

## 🎨 Gradients

### Background Gradients
```html
.gradient-theme-primary
.gradient-theme-secondary
.gradient-theme-accent
.gradient-theme-vertical
.gradient-theme-radial
.gradient-theme-subtle
.gradient-overlay
```

### Text Gradients
```html
.text-gradient-theme
.text-gradient-accent
.text-gradient-vertical
```

---

## ✨ Animations

```html
.animate-fade-in
.animate-slide-in
.animate-slide-in-right
.animate-slide-up
.animate-bounce
.animate-float
.animate-pulse
.animate-spin
.animate-scale-up
.animate-shake
```

---

## 🎯 Effects

### Shadows
```html
.shadow-theme-sm, .shadow-theme-md
.shadow-theme-lg, .shadow-theme-xl
```

### Hover Effects
```html
.hover-lift, .hover-scale, .hover-rotate
.hover-brightness, .hover-shadow
```

### Opacity
```html
.opacity-0, .opacity-10, .opacity-20, .opacity-30,
.opacity-40, .opacity-50, .opacity-60, .opacity-70,
.opacity-80, .opacity-90, .opacity-100
```

### Backdrop
```html
.backdrop-blur, .backdrop-blur-lg, .backdrop-blur-xl
```

---

## 🧩 Components

### Buttons
```html
<!-- Base buttons -->
.btn-theme-primary
.btn-theme-secondary
.btn-theme-accent

<!-- Sizes -->
.btn-sm, .btn-lg, .btn-xl

<!-- Variants -->
.btn-outline, .btn-ghost

<!-- Button group -->
.btn-group, .btn-group-center
```

### Cards
```html
.card-theme
.glass-theme
```

### Badges
```html
.badge-theme-primary
.badge-theme-secondary
.badge-theme-accent
```

### Alerts
```html
.alert-theme-info
.alert-theme-success
.alert-theme-warning
```

### Forms
```html
.input-theme
.textarea-theme
.select-theme
.label-theme
.checkbox-theme, .radio-theme
```

### Navigation
```html
.nav, .nav-item, .nav-item.active
.nav-container, .nav-links
.header-fixed, .header-scrolled
```

### Loading & Progress
```html
.spinner, .spinner-sm, .spinner-lg
.progress-bar, .progress-bar-fill
.skeleton, .skeleton-text, .skeleton-title, .skeleton-avatar
```

### Utility Components
```html
.tooltip, .tooltip-text
.notification
.modal-overlay, .modal-content
.divider, .divider-vertical
.scroll-indicator
.code-block, .code-inline
```

---

## 🖼️ Images
```html
.img-fluid, .img-cover, .img-contain
.img-rounded, .img-circle
```

---

## 📋 Lists & Links
```html
.list-none, .list-disc, .list-decimal
.link-theme, .link-unstyled
```

---

## 🔄 Transitions
```html
.transition-none, .transition-all
.transition-fast, .transition-slow
.transition-colors, .transition-transform, .transition-opacity
```

---

## 🖱️ Cursor
```html
.cursor-auto, .cursor-pointer, .cursor-not-allowed
.cursor-move, .cursor-grab, .cursor-grabbing
```

---

## 📱 Responsive

### Visibility
```html
.hidden-xs    <!-- Hidden on mobile -->
.hidden-sm    <!-- Hidden on small screens -->
.hidden-md    <!-- Hidden on tablets -->
.hidden-lg    <!-- Hidden on desktops -->
.hidden-xl    <!-- Hidden on large desktops -->
```

### Responsive Utilities
```html
.text-xs-center, .text-sm-center
.flex-sm-col
.gap-sm-2
.px-sm-4, .py-sm-8
```

---

## ♿ Accessibility
```html
.sr-only      <!-- Screen reader only -->
```

---

## 🎨 Pre-built Layouts

### Hero Section
```html
.hero
.hero-title
.hero-subtitle
```

### Section Layouts
```html
.section-title
.section-subtitle
.feature-card
.feature-icon
.feature-title
.stat-number
```

### Navigation Layouts
```html
.logo
.theme-btn
.theme-controls
```

---

## 🎯 Overflow
```html
.overflow-auto, .overflow-hidden
.overflow-visible, .overflow-scroll
.overflow-x-auto, .overflow-y-auto
.overflow-x-hidden, .overflow-y-hidden
```

---

## 💡 Usage Examples

### Quick Hero Section
```html
<section class="hero">
  <div class="max-w-3xl mx-auto text-center px-4">
    <h1 class="hero-title text-gradient-theme">
      Welcome
    </h1>
    <p class="hero-subtitle text-theme-dark">
      Your subtitle here
    </p>
    <div class="btn-group-center">
      <button class="btn-theme-primary">Get Started</button>
      <button class="btn-theme-secondary">Learn More</button>
    </div>
  </div>
</section>
```

### Card Grid
```html
<div class="grid grid-auto-fit-md gap-6">
  <div class="card-theme hover-lift">
    <span class="badge-theme-primary">New</span>
    <h3 class="text-2xl font-bold text-theme-darkest mt-4 mb-2">Title</h3>
    <p class="text-theme-dark-80">Content here</p>
  </div>
</div>
```

### Form
```html
<form class="max-w-md mx-auto p-6">
  <div class="mb-4">
    <label class="label-theme">Name</label>
    <input type="text" class="input-theme" placeholder="Your name">
  </div>
  <div class="mb-4">
    <label class="label-theme">Message</label>
    <textarea class="textarea-theme" placeholder="Your message"></textarea>
  </div>
  <button class="btn-theme-primary w-full">Submit</button>
</form>
```

### Navigation
```html
<nav class="header-fixed glass-theme">
  <div class="nav-container">
    <a href="#" class="logo text-gradient-theme">Brand</a>
    <ul class="nav-links list-none">
      <li><a href="#" class="nav-item active">Home</a></li>
      <li><a href="#" class="nav-item">About</a></li>
      <li><a href="#" class="nav-item">Contact</a></li>
    </ul>
  </div>
</nav>
```

---

## 🚀 Tips

1. **Combine classes** for powerful layouts:
   ```html
   <div class="flex items-center justify-between p-4 glass-theme rounded-xl">
   ```

2. **Use responsive grids**:
   ```html
   <div class="grid grid-auto-fit-md gap-6">
   ```

3. **Layer animations**:
   ```html
   <div class="card-theme hover-lift animate-fade-in">
   ```

4. **Stack utilities**:
   ```html
   <div class="max-w-4xl mx-auto px-4 py-12 text-center">
   ```

---

**Version:** 2.0.0  
**Author:** Saurabh Solanke  
**License:** MIT

For full documentation, see `README-THEME-LIBRARY.md`

