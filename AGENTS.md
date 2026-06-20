# AGENTS.md - AI Assistant Guidelines

This file provides guidelines for AI assistants (like Claude, Cursor, Copilot, etc.) working with the MOVTIGROUP repository.

## Project Overview

MOVTIGROUP is a modern website template repository showcasing the visual design and layout of the MOVTIGROUP company website. This is a **template-only** repository - operational code and backend logic are maintained privately.

## Repository Structure

```
movtigroup/
├── .github/
│   ├── FUNDING.yml
│   └── workflows/
│       └── jekyll-gh-pages.yml
├── .gitignore
├── .dockerignore
├── AGENTS.md
├── CHANGELOG
├── CLAUDE.md
├── CONTRIBUTING.md
├── DESIGN.md
├── LICENSE
├── PASS.md
├── PHILOSOPHY.md
├── README.md
├── README.en.md
└── [template files and assets]
```

## Key Principles

1. **Template-Only Focus**: This repository contains only visual design templates and layout components. Do NOT add backend logic, API endpoints, or operational code.

2. **Design Consistency**: All changes must maintain the existing design language - modern, clean, and responsive.

3. **Documentation First**: Any new features or changes must be documented in both Persian (README.md) and English (README.en.md).

4. **Bilingual Support**: The project supports both Persian (Farsi) and English. All user-facing content should consider both languages.

## Allowed Actions

- Update and improve visual design templates
- Add new layout components and pages
- Modify CSS/SCSS styles
- Update documentation
- Fix responsive design issues
- Add new template variations

## Prohibited Actions

- Adding backend code, API logic, or database connections
- Modifying GitHub Actions workflows without approval
- Changing the LICENSE terms
- Adding third-party dependencies without discussion
- Exposing any credentials or secrets

## Coding Standards

- Use semantic HTML5
- Follow BEM or similar CSS naming conventions
- Ensure mobile-first responsive design
- Maintain accessibility standards (WCAG 2.1)
- Keep file sizes optimized for web performance

## Communication

When making changes:
1. Update relevant documentation
2. Follow the existing code style
3. Test responsiveness across devices
4. Consider both Persian and English layouts (RTL/LTR)
