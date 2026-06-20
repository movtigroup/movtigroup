ki# DESIGN.md - Design System Documentation

## Design Philosophy

MOVTIGROUP's visual identity is built on principles of modernity, clarity, and functionality. The design system ensures consistency across all touchpoints while maintaining flexibility for customization.

## Core Principles

### 1. Modern & Clean
- Minimalist approach with ample white space
- Clear visual hierarchy
- Focus on content over decoration

### 2. Responsive First
- Mobile-first design approach
- Fluid layouts that adapt to all screen sizes
- Touch-friendly interactive elements

### 3. Accessibility
- WCAG 2.1 AA compliance
- Sufficient color contrast ratios
- Keyboard navigation support
- Screen reader friendly markup

### 4. Performance
- Optimized assets and code
- Minimal dependencies
- Fast load times

## Color Palette

### Primary Colors
- **Primary Blue:** `#2563EB` - Main brand color, CTAs, links
- **Primary Dark:** `#1E40AF` - Hover states, emphasis
- **Primary Light:** `#DBEAFE` - Backgrounds, highlights

### Neutral Colors
- **Gray 900:** `#111827` - Headings, primary text
- **Gray 700:** `#374151` - Body text
- **Gray 500:** `#6B7280` - Secondary text
- **Gray 300:** `#D1D5DB` - Borders, dividers
- **Gray 100:** `#F3F4F6` - Backgrounds
- **White:** `#FFFFFF` - Cards, containers

### Semantic Colors
- **Success:** `#10B981` - Success messages
- **Warning:** `#F59E0B` - Warnings
- **Error:** `#EF4444` - Errors, destructive actions
- **Info:** `#3B82F6` - Informational messages

## Typography

### Font Families
- **Primary (Persian):** Vazirmatn, IRANSans
- **Primary (English):** Inter, system-ui, -apple-system
- **Monospace:** JetBrains Mono, Fira Code

### Type Scale
- **H1:** 3rem (48px) - Page titles
- **H2:** 2.25rem (36px) - Section titles
- **H3:** 1.875rem (30px) - Subsection titles
- **H4:** 1.5rem (24px) - Card titles
- **Body:** 1rem (16px) - Default text
- **Small:** 0.875rem (14px) - Captions, labels

### Line Heights
- **Headings:** 1.2
- **Body:** 1.6
- **Compact:** 1.4

## Spacing System

Based on 8px grid:

- **xs:** 4px (0.25rem)
- **sm:** 8px (0.5rem)
- **md:** 16px (1rem)
- **lg:** 24px (1.5rem)
- **xl:** 32px (2rem)
- **2xl:** 48px (3rem)
- **3xl:** 64px (4rem)

## Layout

### Container Widths
- **Mobile:** 100% (with 16px padding)
- **Tablet:** 768px
- **Desktop:** 1200px
- **Wide:** 1440px

### Grid System
- 12-column grid
- 24px gutters
- Responsive breakpoints:
  - Mobile: 0 - 767px
  - Tablet: 768px - 1023px
  - Desktop: 1024px+

## Components

### Buttons
- **Primary:** Filled with primary color
- **Secondary:** Outlined with border
- **Ghost:** Transparent with hover state
- **Sizes:** sm, md, lg
- **States:** default, hover, active, disabled, loading

### Cards
- White background with subtle shadow
- 8px border radius
- 16px padding
- Hover elevation effect

### Forms
- Clear labels above inputs
- 8px border radius
- Focus ring with primary color
- Error states in red
- Success states in green

### Navigation
- Sticky header on scroll
- Mobile hamburger menu
- Active state indicators
- Dropdown support

## RTL/LTR Support

### Persian (RTL)
- Text alignment: right
- Layout mirroring
- Icon flipping where needed
- Proper font rendering

### English (LTR)
- Text alignment: left
- Standard layout
- Icon orientation

## Animation & Transitions

- **Duration:** 150ms - 300ms
- **Easing:** ease-out for entrances, ease-in for exits
- **Properties:** transform, opacity (avoid layout-triggering properties)
- **Reduced Motion:** Respect `prefers-reduced-motion`

## Icons

- Consistent 24x24px grid
- 2px stroke weight
- Rounded line caps and joins
- SVG format for scalability

## Images & Media

- WebP with fallbacks
- Lazy loading
- Responsive srcset
- Alt text for accessibility
- Maximum width constraints

## Dark Mode (Optional)

- Dark background: `#111827`
- Light text: `#F9FAFB`
- Adjusted color palette for contrast
- Smooth transition between modes
