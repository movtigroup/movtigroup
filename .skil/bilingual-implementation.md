# Bilingual Implementation Skill

## Overview

This skill provides guidelines for implementing RTL (Persian/Farsi) and LTR (English) layouts correctly in MOVTIGROUP templates.

## Key Concepts

### RTL (Right-to-Left)
- Used for: Persian (Farsi), Arabic, Hebrew
- Text alignment: right
- Layout direction: right-to-left

### LTR (Left-to-Right)
- Used for: English, most European languages
- Text alignment: left
- Layout direction: left-to-right

## Implementation Guidelines

### 1. HTML Structure
```html
<!-- Use dir attribute -->
<html dir="rtl" lang="fa">
<!-- or -->
<html dir="ltr" lang="en">
```

### 2. CSS Logical Properties
Use logical properties instead of physical ones:

| Physical | Logical |
|----------|---------|
| `margin-left` | `margin-inline-start` |
| `margin-right` | `margin-inline-end` |
| `padding-left` | `padding-inline-start` |
| `padding-right` | `padding-inline-end` |
| `text-align: left` | `text-align: start` |
| `text-align: right` | `text-align: end` |
| `float: left` | `float: inline-start` |
| `float: right` | `float: inline-end` |

### 3. Flexbox & Grid
Modern layout systems handle RTL/LTR automatically when using logical properties.

### 4. Icons & Images
- Some icons need to be flipped in RTL
- Use CSS transforms when needed:
```css
[dir="rtl"] .icon-arrow {
  transform: scaleX(-1);
}
```

### 5. Typography
- Persian: Vazirmatn, IRANSans
- English: Inter, system-ui
- Ensure proper font fallbacks

### 6. Testing
- Test both RTL and LTR layouts
- Check text overflow and wrapping
- Verify form inputs and labels
- Test navigation and menus

## Common Pitfalls

- Don't use `left`/`right` for positioning
- Don't hardcode text alignment
- Don't forget icon flipping
- Don't assume LTR is default
