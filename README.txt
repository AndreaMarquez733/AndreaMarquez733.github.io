================================================================================
  Portfolio
  CMI 3315: Introduction to Web Design | Portfolio | Spring 2026
  Instructor: Obada Kraishan | Texas Tech University
================================================================================

STUDENT INFORMATION
-------------------
Name:         Andrea Marquez
Student ID:   R11981454


PROJECT OVERVIEW
----------------
A complete professional portfolio website showcasing three projects:
1. Wanderlust Magazine (Web Design — Project 2)
2. Young Adults Worry About Guns, Push for Reform (News 3 Revised)
3. Local Pickleball Business Hosts Alzheimer's Fundraiser (News 2)

PAGES
-----
index.html     — Homepage with hero, skills ticker, project grid
about.html     — Biography, skills, experience timeline
work.html      — Projects overview grid
contact.html   — Contact info and message form
case-studies/
  project-one.html    — Wanderlust Magazine case study
  project-two.html    — Campus Gun Violence case study
  project-three.html  — Pickleball & Alzheimer's case study

FONTS
-----
- Cormorant Garamond (Google Fonts) — Display headings
- Lora (Google Fonts) — Body text
- DM Mono (Google Fonts) — Navigation, labels, UI

COLOR PALETTE
-------------
- Off-White:    #f7f4ef (Page background)
- Accent Red:   #c0392b (Primary accent — links, labels, CTAs)
- Near-Black:   #1c1c1c (Body text, footer)
- Border:       #d8d3cb (Dividers)
- Muted:        #e8e4de (Card backgrounds)

AI CREDIT
---------
Claude (Anthropic) was used to assist with two specific technically
complex structures in this project:

1. CSS Grid editorial layout (projects-grid)
   Claude helped design the 12 column asymmetric CSS Grid system
   that allows the projects gallery to display in a magazine-style
   layout with large, small, and full-width card variants.
   See: assets/css/style.css section 9: PROJECTS GRID
   Also flagged with inline comments in HTML files.

2. Sticky sidebar layout (case-layout)
   Claude helped design the CSS Grid + position: sticky approach
   used on all three case study pages to keep the sidebar visible
   while the user scrolls through the article body.
   See: assets/css/style.css — section 12: CASE STUDY PAGES
   Also flagged with inline comments in HTML files.

All other code — typography, color system, spacing, layout structure,
navigation, animations, responsive breakpoints, footer, and all
page content — was written by Andrea Marquez.

TECHNICAL FEATURES
------------------
- Semantic HTML5 throughout
- Single external CSS file (assets/css/style.css)
- CSS Grid + Flexbox layout on all pages
- CSS custom properties (design system variables)
- Scroll-triggered reveal animations (IntersectionObserver)
- Skills ticker animation (CSS keyframes)
- Sticky header with scroll shadow
- Responsive hamburger nav at 768px and 480px
- Lazy loading on all non-hero images
- ARIA labels and semantic landmarks for accessibility
- Descriptive alt text on all images

NOTE ON IMAGES
--------------
Placeholder images have been used in assets/images/projects/.
Before final submission, replace with real screenshots of:
- wanderlust-thumb.jpg → Screenshot of Wanderlust Magazine homepage
- news3-thumb.jpg     → Any image representing the gun violence story
- news2-thumb.jpg     → Photo of the pickleball event or courts

VALIDATORS
----------
- HTML: https://validator.w3.org/
- CSS:  https://jigsaw.w3.org/css-validator/
- Performance: Google Lighthouse (Chrome > Inspect > Lighthouse)

================================================================================
