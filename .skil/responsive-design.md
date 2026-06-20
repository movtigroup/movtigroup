# Responsive Design Skill

## Overview

This skill provides best practices for ensuring responsive behavior across all devices and screen sizes in MOVTIGROUP templates.

## Breakpoints

| Name | Width | Description |
|------|-------|-------------|
| Mobile | 0 - 767px | Default, mobile-first |
| Tablet | 768px - 1023px | Tablet devices |
| Desktop | 1024px+ | Desktop and larger |

## Guidelines

### 1. Mobile-First Approach
- Start with mobile styles as default
- Use `min-width` media queries for larger screens
- Test on real devices when possible

### 2. Fluid Layouts
- Use relative units (%, rem, vw/vh)
- Avoid fixed widths where possible
- Use CSS Grid and Flexbox

### 3. Touch Targets
- Minimum touch target: 44x44px
- Adequate spacing between interactive elements
- Large enough text for readability

### 4. Images & Media
- Use `srcset` for responsive images
- Implement lazy loading
- Use WebP with fallbacks

### 5. Typography
- Use `clamp()` for fluid font sizes
- Maintain readable line lengths (45-75 characters)
- Adjust line height for different screen sizes

## Testing Checklist

- [ ] Test on mobile (320px - 767px)
- [ ] Test on tablet (768px - 1023px)
- [ ] Test on desktop (1024px+)
- [ ] Test landscape orientation
- [ ] Test with browser zoom (100%, 125%, 150%)
- [ ] Test with reduced motion preference
