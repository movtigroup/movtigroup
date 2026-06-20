# Accessibility Audit Skill

## Overview

This skill provides a checklist and procedures for ensuring WCAG 2.1 compliance in MOVTIGROUP templates.

## WCAG 2.1 Principles

### 1. Perceivable
- Information must be presentable in ways users can perceive
- Provide text alternatives for non-text content
- Provide captions and alternatives for multimedia
- Create content that can be presented in different ways

### 2. Operable
- Interface components must be operable
- Make all functionality available from a keyboard
- Provide users enough time to read and use content
- Don't design content that causes seizures

### 3. Understandable
- Information and operation must be understandable
- Make text readable and understandable
- Make content appear and operate in predictable ways
- Help users avoid and correct mistakes

### 4. Robust
- Content must be robust enough for reliable interpretation
- Maximize compatibility with current and future tools

## Audit Checklist

### HTML Structure
- [ ] Semantic HTML5 elements used
- [ ] Proper heading hierarchy (h1-h6)
- [ ] Landmark roles defined
- [ ] Language attributes set

### Images & Media
- [ ] All images have alt text
- [ ] Decorative images have empty alt
- [ ] Complex images have long descriptions
- [ ] Videos have captions
- [ ] Audio has transcripts

### Color & Contrast
- [ ] Text contrast ratio >= 4.5:1 (normal text)
- [ ] Text contrast ratio >= 3:1 (large text)
- [ ] UI components contrast >= 3:1
- [ ] Color is not the only indicator

### Keyboard Navigation
- [ ] All interactive elements are focusable
- [ ] Focus order is logical
- [ ] Focus indicator is visible
- [ ] No keyboard traps
- [ ] Skip links provided

### Forms
- [ ] Labels associated with inputs
- [ ] Error messages are descriptive
- [ ] Required fields indicated
- [ ] Instructions provided
- [ ] Error prevention for legal/financial

### Responsive Design
- [ ] Content reflows at 400% zoom
- [ ] No horizontal scrolling
- [ ] Touch targets >= 44x44px
- [ ] Viewport meta tag set

## Testing Tools

- WAVE Browser Extension
- axe DevTools
- Lighthouse
- NVDA / JAWS (screen readers)
- Color contrast analyzers

## Common Issues

- Missing alt text
- Insufficient color contrast
- Poor focus indicators
- Missing form labels
- Auto-playing media
- Inaccessible custom widgets
