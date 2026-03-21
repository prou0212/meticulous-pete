Meticulous Pete — A Man of Many Trades

Description: A static multi-page website for Meticulous Petes, a professional contractor and handyman service. Built with plain HTML, CSS, and vanilla JavaScript. No frameworks and no build step.
Author: Jesse Proulx
Year: October 2025 - March 2026

Program Software:
Visual Studio Code

Project Structure

meticulous-peter/
│
├── index.html # Homepage
├── services.html # Services offered
├── about-us.html # About the team/owner
├── reviews.html # Customer reviews
├── gallery.html # Project photo gallery
│
├── css/
| ├── about-us.css # properties exclusive to about-us page (sections)
│ ├── base.css # Global styles: header, footer, layouts, buttons, contact section, titles/descriptions, left/right sections, picture headers, hamburger section, transitional elements and fonts (consolidated)
│ ├── gallery.css # Properties exclusive to gallery page (containers, scrollbar, lightbox)
│ ├── index.css # Properties exclusive to index page (slideshow, sections)
│ ├── reviews.css # Properties exclusive to reviews page (containers)
│ └── services.css # Properties exclusive to services page (image size)
|
├── pictures/
| ├── about-us/ # Images exclusive to about-us page (banner, peters truck)
| | ├── about-us-2.jpeg
| | ├── about-us.jpeg
| | └── peter_truck.jpg
│ ├── gallery/
| | ├── bathroom-gallery/ # pictures of bathrooms
| | | ├── bathroom-1.jpeg
| | | ├── bathroom-2.jpeg
| | | ├── bathroom-3.jpeg
| | | ├── bathroom-4.jpeg
| | | └── bathroom-5.jpeg
| | ├── before-after-gallery/ # pictures before a project and after a project
| | | ├── before-after-1.jpeg
| | | ├── before-after-2.jpeg
| | | ├── before-after-3.jpeg
| | | ├── before-after-4.jpeg
| | | ├── before-after-5.jpeg
| | | ├── before-after-6.jpeg
| | | ├── before-after-7.jpeg
| | | ├── before-after-8.jpeg
| | | ├── before-after-9.jpeg
| | | └── before-after-10.jpeg
| | ├── deck-gallery/ # pictures of decks
| | | ├── decking-1.jpeg
| | | ├── decking-2.jpeg
| | | └── decking-3.jpeg
| | ├── kitchen-gallery/ # pictures of kitchens
| | | ├── kitchen-1.jpeg
| | | ├── kitchen-2.jpeg
| | | ├── kitchen-3.jpeg
| | | ├── kitchen-4.jpeg
| | | └── kitchen-5.jpeg
| | ├── stonework-gallery/ # pictures of stonework
| | | ├── stonework-1.jpeg
| | | ├── stonework-2.jpeg
| | | ├── stonework-3.jpeg
| | | └── stonework-4.jpeg
| | └── gallery-header-mod.jpg
│ ├── icon/ # Icon for browser
| | └── hammer.png
│ ├── index/ # Project category images (drywall, flooring, etc.)
| | ├── projects/ # Project category images (drywall, flooring, etc.)
| | | ├── bathrooms.jpeg
| | | ├── decking.jpeg
| | | ├── fencing.jpg
| | | ├── flooring-OG.jpeg
| | | ├── flooring.jpeg
| | | ├── kitchens.jpeg
| | | └── stonework.jpeg
| | ├── slideshow/
| | | ├── slideshow-4.jpeg
| | | ├── slideshow-5.jpeg
| | | └── slideshow-6.jpeg
| | └── about-us-default.jpg
| | └── about-us.jpeg
│ ├── reviews/ # Review images (banner, stars)
| | └── header-review-mod.jpg
| | └── stars.png
│ ├── services/ # Services category images (drywall, flooring, etc.)
| | └── basement.jpg
| | └── bathroom.jpeg
| | └── decking.jpeg
| | └── drywalling.jpg
| | └── flooring.jpg
| | └── kitchen.jpeg
└ └ └── services-header.jpg

Page & Description
index.html: Homepage with hero slideshow, project categories, about blurb, and contact section
services.html: Detailed breakdown of services offered
about-us.html: Story and background of Peter Rousseau and the team
reviews.html: Customer testimonials and reviews
gallery.html: Photo gallery of completed projects

CSS Architecture
The stylesheets are split by concern and shared across all pages:
base.css — Global stylesheet consolidating header (nav bar, logo, hamburger menu, mobile overlay), footer (background, height, copyright), and font utility classes (.stencil-text, .lato-regular, .bodoni-moda-sc-regular, .inter-regular)
index.css — Homepage body layout, hero slideshow, project category cards, about-us section, contact section, and responsive breakpoints
about-us.css — About Us page layout and styles
gallery.css — Gallery page grid and image styles
reviews.css — Reviews page layout and testimonial styles
services.css — Services page layout and content styles

Technologies & Fonts

HTML5 / CSS3 / Vanilla JavaScript
Stencil — Logo and headline display font
Bodoni Moda SC — Elegant serif used for section titles and nav links (Google Fonts)
Lato — Clean sans-serif for body text and descriptions (Google Fonts)
Inter — Utility font class available for secondary use

Features

Hero Image Slideshow — Auto-advances every 10 seconds, with previous/next buttons and smooth opacity transitions
Mobile Hamburger Menu — Full-screen overlay nav that slides in from the right on screens under 1260px
Responsive Design — Layout adjusts at 1260px (nav) and 1400px (content sections)
Project Category Grid — Two rows of image cards with hover scale effect and text overlay
Anchor-based Contact Navigation — "Contact Us" nav link scrolls to the contact section on the homepage

Getting Started
This is a fully static site — no installation or build process required.
Option 1 — Open directly:
Open index.html in any modern browser
Option 2 — Local Server (Live Server Extension)
Install the Live Server Extension in Visual Studio Code for hot swapping in the browser.
