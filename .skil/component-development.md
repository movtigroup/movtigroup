# Component Development Skill

## Overview

This skill provides standards for creating new reusable components within the MOVTIGROUP design system.

## Component Structure

### HTML
- Use semantic HTML5 elements
- Follow BEM naming convention
- Include proper ARIA attributes
- Ensure keyboard accessibility

### CSS
- Use CSS custom properties (variables)
- Follow mobile-first approach
- Use logical properties for RTL/LTR
- Maintain consistent spacing

### JavaScript
- Keep functionality minimal
- Use event delegation where possible
- Ensure progressive enhancement
- Avoid inline event handlers

## Naming Conventions

### BEM (Block Element Modifier)
```css
/* Block */
.card { }

/* Element */
.card__title { }
.card__body { }

/* Modifier */
.card--featured { }
.card--dark { }
```

### File Naming
- Use kebab-case: `component-name.css`
- Group related files in directories
- Use index files for organization

## Checklist

- [ ] Component is responsive
- [ ] Works in both RTL and LTR
- [ ] Accessible (keyboard, screen reader)
- [ ] Documented with examples
- [ ] Tested across browsers
- [ ] Performance optimized
