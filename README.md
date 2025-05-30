# Viewfinder Photography – Responsive Website

## Overview

This project transforms a previously desktop-only photography website into a fully **mobile-friendly** layout using **CSS media queries**. The aim is to ensure optimal viewing across devices, especially on screens with a **maximum width of 768px**, such as smartphones and tablets.

---

## Objective

**Task 4: Make a Website Mobile-Friendly Using CSS Media Queries**

### Goals:
- Convert a static, fixed-width layout into a responsive design.
- Ensure all text, images, navigation, and sections adapt to various screen sizes.
- Eliminate horizontal scrolling and layout overflow on mobile devices.
- Use Chrome DevTools for testing and debugging responsive behavior.

---

## Key Features & Changes

### ✅ 1. **Responsive Header and Navigation**
- The header now adapts to smaller screens.
- Added a **hamburger menu** that toggles visibility of navigation links on mobile.
- Used ARIA attributes for improved accessibility.
- Navigation stacks **vertically** on small screens and collapses into a dropdown.

### ✅ 2. **Flexible Hero Section**
- Hero image scales automatically to fit mobile screens.
- Font sizes are reduced for mobile using media queries.
- Ensured text remains readable without horizontal scrolling.

### ✅ 3. **Media Queries for Layout Adjustments**
Used media queries at `max-width: 767px` to:
- Stack content vertically in the navigation and gallery.
- Reduce paddings and margins for better mobile fit.
- Resize text headers and body content for mobile readability.

```css
@media (max-width: 767px) {
  header {
    paddin
