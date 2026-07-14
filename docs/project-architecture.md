# Project Architecture

## Project

ATIKUL WEBSITE

Official Website of **Atikul Islam Rabbi**

Version: 1.0

---

# Purpose

This document defines the architecture of the project.

Every new file, page, component, stylesheet, image, and JavaScript module should follow these rules.

The architecture should remain simple, scalable, maintainable, and compatible with GitHub Pages.

---

# Technology Stack

Frontend

* HTML5
* CSS3
* Vanilla JavaScript (ES6)

Hosting

* GitHub Pages

Version Control

* Git

Development

* Visual Studio Code
* GitHub Copilot

No frameworks.

No build process.

No package managers.

---

# Root Folder

```
atikul-website/

README.md

AGENTS.md

.copilot-instructions.md

index.html

about.html

services.html

portfolio.html

reviews.html

blog.html

contact.html

privacy-policy.html

terms.html

disclaimer.html

cookie-policy.html

404.html

robots.txt

sitemap.xml

favicon.ico

assets/

blog/

docs/
```

---

# Assets Folder

```
assets/

css/

js/

images/

icons/

fonts/

downloads/
```

Never place assets in the project root.

---

# CSS Architecture

```
assets/css/

style.css

layout.css

components.css

utilities.css

responsive.css

animations.css
```

### Responsibilities

style.css

Global variables

Typography

Basic styling

layout.css

Grid

Containers

Sections

Header

Footer

components.css

Buttons

Cards

Forms

Navigation

Badges

FAQ

Testimonials

utilities.css

Spacing

Display

Alignment

Helper classes

responsive.css

Media queries

Responsive layouts

animations.css

Transitions

Hover effects

Fade animations

Avoid large monolithic CSS files.

---

# JavaScript Architecture

```
assets/js/

main.js

navigation.js

theme.js

blog.js

search.js

contact.js

faq.js

utils.js
```

### Responsibilities

main.js

Global initialization

navigation.js

Desktop/mobile menu

theme.js

Future dark mode

blog.js

Blog filtering

Reading time

Categories

search.js

Search logic

contact.js

Form validation

faq.js

Accordion

utils.js

Shared helper functions

Never place all JavaScript in one file.

---

# Images

```
assets/images/

profile/

blog/

portfolio/

services/

logos/

backgrounds/
```

Naming example

facebook-page-recovery-guide.webp

meta-business-manager.webp

knowledge-panel-example.webp

Avoid spaces.

Use lowercase.

Use hyphens.

Prefer WebP for new images.

---

# Icons

```
assets/icons/

social/

services/

ui/
```

Maintain a consistent icon style.

---

# Fonts

```
assets/fonts/
```

Use system fonts by default.

Only include custom fonts if they provide a clear benefit.

---

# Downloads

```
assets/downloads/
```

Examples

PDF Guides

Checklists

Templates

Resources

---

# Blog Structure

```
blog/

index.html

posts/

categories/
```

Each article should have:

```
blog/posts/

meta-business-verification.html

facebook-page-security.html

google-knowledge-panel-guide.html
```

Use descriptive filenames.

---

# Documentation

```
docs/

brand.md

design-system.md

pages.md

services.md

blog.md

seo.md

project-architecture.md
```

Documentation should always be updated when the architecture changes.

---

# Navigation

Navigation must remain identical across every page.

Desktop

Home

About

Services

Portfolio

Reviews

Blog

Contact

Mobile

Same order.

Never remove navigation consistency.

---

# Component Strategy

Build reusable components.

Examples

Primary Button

Secondary Button

Service Card

Review Card

Blog Card

Portfolio Card

FAQ Item

Statistic Card

Contact Card

Avoid duplicating component styles.

---

# File Naming

Always use:

lowercase

hyphen-separated

Examples

facebook-security.html

business-manager-guide.html

review-card.css

contact-form.js

Never use spaces.

Never use camelCase for file names.

---

# HTML Standards

Use semantic HTML.

Every page must include:

header

main

section

footer

Every page should contain:

Title

Meta Description

Canonical URL

Open Graph

Twitter Card

Favicon

Navigation

Footer

---

# CSS Standards

Prefer reusable classes.

Avoid inline CSS.

Keep selectors simple.

Avoid !important whenever possible.

Group related styles.

---

# JavaScript Standards

Use modular files.

Keep functions short.

Use descriptive names.

Avoid global variables.

Comment only when necessary.

---

# Performance

Optimize:

Images

Fonts

CSS

JavaScript

Lazy-load non-critical images.

Avoid unnecessary requests.

---

# Accessibility

Support:

Keyboard navigation

Visible focus

Alt text

ARIA where appropriate

Logical heading hierarchy

High contrast

---

# SEO Integration

Every page should support:

Meta tags

Structured data placeholders

Breadcrumbs (where applicable)

Internal links

Descriptive URLs

robots.txt

sitemap.xml

---

# Future Expansion

The architecture should support future additions without requiring major refactoring.

Examples

Newsletter

Dark Mode

Knowledge Base

Downloads

Advanced Search

Filtering

Case Studies

Resource Library

Language Support

Analytics

---

# Copilot Rules

Before generating code:

* Review the repository structure.
* Reuse existing files whenever possible.
* Do not create duplicate stylesheets or scripts.
* Follow the documentation in the `docs/` directory.
* Maintain consistency with existing naming conventions.
* Prefer reusable components over page-specific code.
* Keep HTML, CSS, and JavaScript separated by responsibility.
* Ensure every new page follows the same architecture.

---

# Definition of Success

A successful implementation is one where:

* The project is easy to understand.
* New pages can be added with minimal effort.
* CSS and JavaScript remain organized.
* Components are reusable.
* The website is fast, accessible, SEO-friendly, and easy to maintain.
* The repository remains a professional, scalable codebase suitable for long-term growth.
