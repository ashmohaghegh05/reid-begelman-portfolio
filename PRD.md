# Product Requirements Document

## Project

Reid Begelman Professional Portfolio Website

## Client

Reid Begelman

## Project Summary

This project is a professional personal portfolio website for Reid Begelman, a senior at Babson College pursuing a Bachelor of Science in Business Administration with dual concentrations in Marketing and Strategy and Consulting.

The website will give Reid a professional online presence where recruiters, employers, academic contacts, and other professional connections can quickly understand his background, view his resume, learn about his experience, and contact him.

The website will contain three main pages:

1. About
2. Resume
3. Contact

---

## Product Goal

The goal is to create a professional, responsive, and easy-to-navigate portfolio that presents Reid's academic and professional background clearly.

The site should feel more like a professional personal brand than a digital copy of a resume.

---

## Primary Audience

The primary users are:

- Recruiters
- Potential employers
- Professional contacts
- Academic contacts
- People interested in Reid's professional background

---

## Five-Second Goal

Within the first five seconds of opening the homepage, a visitor should understand:

- Reid's name
- That he is a senior at Babson College
- That his professional interests include Marketing, Strategy, and Consulting
- That he has experience at Restaurant Brands International
- That his resume is available
- That there are clear ways to contact him

---

## Primary User Action

The most important action is:

**View Reid's resume.**

The Resume button should therefore be visible near the top of the homepage.

---

## Secondary User Actions

Visitors should also be able to:

- Visit Reid's LinkedIn profile
- Email Reid
- Call Reid
- Learn more about his professional experience

---

# Information Architecture

The website will contain three pages.

## 1. About / Home

Filename:

`index.html`

Purpose:

Introduce Reid and provide an overview of his academic background, professional interests, and experience.

## 2. Resume

Filename:

`resume.html`

Purpose:

Make Reid's resume easy to view and open.

## 3. Contact

Filename:

`contact.html`

Purpose:

Give visitors clear ways to contact Reid.

---

# Navigation

Every page should use the same navigation:

- About
- Resume
- Contact

The current page should be visually identifiable.

The navigation should remain simple and consistent across all pages.

---

# Homepage Requirements

## Hero Section

The homepage should begin with a strong introductory section.

It must contain:

- Reid Begelman's name
- Marketing • Strategy • Consulting
- Short professional description
- Reid's professional photograph
- View Resume button
- LinkedIn button

### Introductory Copy

The homepage should communicate that Reid is a Babson College senior interested in:

- Marketing
- Strategy
- Consulting
- Entrepreneurship
- Customer experiences

---

## Profile Section

The Profile section should explain Reid's academic and professional background.

It should include:

- Babson College
- Bachelor of Science in Business Administration
- Marketing concentration
- Strategy and Consulting concentration
- Restaurant Brands International internship
- Accepted return offer
- Full-time start beginning in July 2027

### Client Biography

Use the following real content:

> Hello, my name is Reid Begelman. I am a senior at Babson College pursuing a Bachelor of Science in Business Administration with dual concentrations in Marketing and Strategy and Consulting. During the summer of 2026, I interned at Restaurant Brands International (RBI), where I accepted my return offer and will be pursuing a full-time job there beginning in July 2027.

---

## Areas of Interest Section

The homepage should contain three professional focus areas.

### Marketing

Explain Reid's interest in:

- Understanding customers
- Brand positioning
- Customer experiences
- Building lasting relationships

### Strategy

Explain Reid's interest in:

- Solving business problems
- Evaluating opportunities
- Growth
- Decision-making

### Consulting

Explain Reid's interest in:

- Analysis
- Communication
- Problem-solving
- Helping organizations make stronger decisions

On larger screens, these should appear in three columns.

On smaller screens, they should stack vertically.

---

## Experience Section

Create a simple timeline showing Reid's professional progression.

### NOW — Babson College

B.S. in Business Administration

Marketing • Strategy & Consulting

### 2026 — Restaurant Brands International

Summer Internship

Accepted return offer.

### 2027 — Restaurant Brands International

Full-time position beginning July 2027.

---

## Homepage Closing Section

At the bottom of the homepage, include a clear call to action.

Text:

**Explore my experience or get in touch.**

Buttons:

- Resume
- Contact

---

# Resume Page Requirements

The Resume page should include:

- Consistent navigation
- Resume heading
- Short introduction
- Open Resume PDF button
- Embedded resume PDF
- Footer

The resume PDF filename should be:

`reid-begelman-resume.pdf`

The direct button should open the PDF in a new tab.

If the browser does not display the embedded PDF, the direct PDF button should still allow the visitor to access it.

---

# Contact Page Requirements

The Contact page should contain three contact methods.

## Phone

(215) 347-3875

The number should use a clickable `tel:` link.

## Email

rbegelman1@babson.edu

The email should use a clickable `mailto:` link.

## LinkedIn

https://www.linkedin.com/in/reidbegelman

The LinkedIn link should open in a new tab.

---

# Content Requirements

The website must use real information provided by Reid.

Do not use placeholder text.

Required real content includes:

- Reid's name
- Professional photograph
- Babson College
- Degree information
- Concentrations
- RBI internship
- RBI return offer
- Resume
- Phone
- Email
- LinkedIn

---

# Design Direction

The design should feel:

- Professional
- Modern
- Editorial
- Confident
- Clean
- Appropriate for recruiters
- Distinctive without being distracting

The site should not look like a generic AI-generated portfolio.

---

# Inspiration

The main design inspiration is the personal website of Ameer Hamza:

https://ameerhamzastrategist.com/

The useful ideas taken from this reference are:

- Immediate professional positioning
- Prominent personal identity
- Strong opening section
- Professional photograph
- Clear calls to action
- Clear visual hierarchy
- Easy-to-scan sections

The final site should use these ideas as inspiration without copying the original site's exact design or content.

---

# Design System

Use the following color system.

## Primary Navy

`#111827`

Use for:

- Navigation
- Dark cards
- Footer
- Primary buttons
- Major text

## Background Cream

`#f4efe6`

Use for:

- Main page background

## Accent Orange

`#d97732`

Use for:

- Highlights
- Section accents
- Active navigation
- Important visual details

## Dark Orange

`#b65f26`

Use for:

- Small labels
- Timeline years
- Secondary accent text

## Main Text

`#172033`

## Secondary Text

`#485366`

## Light Text

`#cdd3dc`

## Border

`#cec5b8`

---

# Typography

Use a simple system font stack:

`Arial, Helvetica, sans-serif`

The website should rely on size, spacing, weight, and hierarchy rather than decorative typography.

---

# Layout

Use CSS Grid and Flexbox.

## Homepage Hero

Desktop:

- Two columns
- Text on left
- Photograph on right

Mobile:

- One column
- Text first
- Photograph underneath

## Areas of Interest

Desktop:

- Three columns

Mobile:

- One column

## Contact Page

Desktop:

- Three contact cards

Mobile:

- One column

---

# Responsive Design Requirements

The website must be readable on a phone.

At approximately 800px and below:

- Hero changes to one column
- Interest cards stack vertically
- Contact cards stack vertically
- Navigation remains readable
- Images resize properly
- Text stays within the screen
- No horizontal scrolling should appear

At smaller phone widths:

- Reduce horizontal padding
- Reduce large heading sizes
- Keep buttons usable
- Keep contact information readable

---

# Semantic HTML Requirements

Use semantic HTML elements where appropriate:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<article>`
- `<footer>`

Avoid using unnecessary `<div>` elements when a semantic element is more appropriate.

---

# CSS Requirements

Use one external stylesheet:

`style.css`

Every HTML page must include:

```html
<link rel="stylesheet" href="style.css">
