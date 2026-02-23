# BSIT Web Developer Portfolio

A complete, modern, dark-themed portfolio website for a BSIT (Bachelor of Science in Information Technology) student specializing in Web Development.

## File Structure

```
portfolio/
├── index.html          ← Home page with hero, stats, featured projects
├── about.html          ← Bio, skills with progress bars, certifications
├── projects.html       ← All projects with filter buttons (All / Web / UI / Backend)
├── project1.html       ← E-Commerce Platform detail page
├── project2.html       ← Task Management App detail page
├── project3.html       ← Student Portal System detail page
├── contact.html        ← Contact form with validation + social links
├── resume.html         ← Resume preview + PDF download
│
├── css/
│   └── style.css       ← All styles (responsive, dark theme, animations)
│
├── js/
│   └── script.js       ← Hamburger menu, scroll animations, form validation, etc.
│
├── images/             ← Place your profile photo and project screenshots here
│   └── (add images here)
│
└── resume/
    └── resume.pdf      ← Place your actual resume PDF here
```

## How to Personalize

1. **Name & Info** — Search and replace "Alex Rivera" with your real name across all HTML files
2. **Profile Photo** — Add `images/profile.jpg` and uncomment the `<img>` tags in `index.html` and `about.html`
3. **Project Screenshots** — Add images to the `images/` folder and update `<img>` src in project detail pages
4. **Resume PDF** — Replace `resume/resume.pdf` with your actual resume file
5. **Links** — Update all `href="#"` placeholder links with real GitHub, LinkedIn, and live demo URLs
6. **Contact Email** — Update `alex.rivera@email.com` with your real email
7. **School/Location** — Update school name and location in `about.html`, `contact.html`, and `resume.html`

## Features

- ✅ Responsive (Desktop, Tablet, Mobile)
- ✅ Dark professional theme with cyan/blue glow accents
- ✅ Sticky navbar with hamburger menu for mobile
- ✅ Smooth scroll + fade-in animations on scroll
- ✅ Animated skill progress bars
- ✅ Animated stat counters
- ✅ Project filter buttons (by category)
- ✅ Contact form with JavaScript validation
- ✅ Animated hero with floating badges
- ✅ Rotating glow effect on profile image
- ✅ Glassmorphism-style cards with glow on hover
- ✅ Background CSS grid pattern
- ✅ No frameworks — pure HTML, CSS, Vanilla JS

## Getting Started

Simply open `index.html` in your browser. No server or build tools needed!
