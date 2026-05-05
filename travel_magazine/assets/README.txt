================================================================================
  WANDERLUST MAGAZINE
  CMI 3315: Introduction to Web Design | Project 2 | Spring 2026
  Instructor: Obada Kraishan | Texas Tech University
================================================================================

STUDENT INFORMATION
-------------------
Name:         Andrea Marquez
Student ID:   R11981454


PROJECT OVERVIEW
----------------
Publication Title: Wanderlust Magazine

Wanderlust Magazine is a fictional travel publication designed for the curious,
independent traveler who wants more than a list of tourist attractions. Inspired
by print magazines like Condé Nast Traveler and Afar, the site focuses on
long-form storytelling, striking photography, and in-depth destination coverage.
The design uses a forest green and white color palette with classic serif
typography to reflect the editorial, print-inspired aesthetic of the brand.


PAGES
-----
1. index.html — Homepage
   Includes a full-screen hero section with a featured article, a two-column
   featured stories grid showing three articles total, and a newsletter signup
   banner at the bottom.

2. article.html — Full Article Page
   A complete feature article about the hidden valleys of the Swiss Alps.
   Includes a hero image, headline, byline, pull quote, article tags, and a
   sticky sidebar with related articles and an author bio.

3. category.html — Destinations Page
   A browseable grid of nine article cards organized by destination. Includes
   a category header, region filter buttons, and pagination at the bottom.

4. about.html — About & Author Page
   Covers the publication's mission and values, a single author profile for
   Andrea with a photo placeholder, and a contact information section.

5. gallery.html — Photography Gallery
   An asymmetric CSS Grid photo gallery with hover captions, followed by a
   three-column destination spotlight section.


SKETCHING & PLANNING PROCESS
-----------------------------
Before writing any code, I sketched each page on paper to plan the layout and content hierarchy. I started
with the homepage and worked outward from there, deciding how pages would link
to each other.


FONTS
-----
- Playfair Display (Google Fonts) — Headings and display text
- Source Serif 4 (Google Fonts) — Body text
- DM Sans (Google Fonts) — Navigation, labels, and UI elements


COLOR PALETTE
-------------
- Forest Green:   #2d4a3e  (Primary — headers, footer, buttons)
- Dark Green:     #1e3329  (Button hover states)
- Off-White:      #f5f5f5  (Page background)
- White:          #ffffff  (Card backgrounds)
- Near-Black:     #1a1a1a  (Body text)
- Medium Gray:    #555555  (Captions and secondary text)
- Light Gray:     #dddddd  (Borders and dividers)


IMAGE SOURCES
-------------
All photos from Unsplash.com


CHALLENGES & SOLUTIONS
-----------------------

One challenge was getting the article page sidebar to stay visible while
scrolling through the main article text. I solved this using position: sticky
with a top offset that accounts for the fixed navigation bar height.


SPECIAL FEATURES
----------------
- CSS custom properties (variables) used for all colors, fonts, and spacing
- Both CSS Grid and Flexbox used throughout all five pages
- Responsive design with breakpoints at 768px (tablet) and 480px (mobile)
- Hamburger navigation menu for mobile screens
- Keyframe animations on page load and hover transitions on interactive elements
- Lazy loading applied to all images below the fold
- Semantic HTML5 structure and ARIA labels for accessibility


VALIDATORS & TESTING
--------------------
- HTML validated using: https://validator.w3.org/
- CSS validated using: https://jigsaw.w3.org/css-validator/
- Performance tested using Google Lighthouse (Chrome DevTools)
- Tested on desktop, tablet, and mobile screen sizes


================================================================================
