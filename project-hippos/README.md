# Project: Multi-page Website

## Goal

To create reate a website made of several HTML pages and related CSS.

The website is about an animal of my choice.

This webpage can be viewed and used by running:
- `npm install` (only required once on any given computer)
- `node server.js` (starts the server, Ctrl-C to stop running the server)
- Visiting `http://localhost:3000/` in the browser

## Functional Requirements

The website will consist of these pages (created inside the `public/` directory):

- `index.html` ( a "Homepage")
- `about.html` ( an "About" page )
- `register.html` (a Registration page to register a detail about an animal)

Each page will consist of a `<header>`, `<main>` and `<footer>` that are semantically correct. 

## Header/Footer Appearance

- The visual header/footer for each page is identical
  - Hint: There is no way to automatically do this with just HTML, so you will have repeated content in each HTML file
  - Exception: If the page identifying header (`<h1>` or `<h2>`) is visually in the header, it will be unique on each page
- The header/footer is visually distinct from the main content of the page
- The header/footer have the same color background from each other (distinct from the main content of the page)
- The header will include a "logo" image (of your choice, subject to the image restrictions given in this file)
  - The logo image will be a link to the home page
  - The logo image will have an alt attribute of ""

### Homepage Appearance

The home page will include at least 3 UI Cards. 

Each card will contain at least:
  - a visible and semantic heading title
    - Hint: Remember not to skip numbers in h1-h6 elements!
  - A call-to-action link

Each card will have at least one of:
  - A background color that makes it visually unique from the other cards
  - A image that makes the card visually unique from the other cards

The links in the cards to not need to link to actual pages

The Home Page should make it obvious what Animal the site is about

### About Contents

The About page will include at least 3 paragraphs of text that each contain at least 3 sentences.  
At least 1 sentence must be real text saying in more detail what animal the site is about and something about that animal. The remaining text may be lorem-ipsum like text.

### Registration Contents

The Register page will include a form

The form will submit via POST to `/register` 

The form will ask for (at minimum):
- name
- email
- one piece of info using a checkbox
- one piece of info using a dropdown

- The form must be usable at the required viewport sizes, but there is no specific requirement for adaptive behavior of the form

At least 1 field is required and should be visibly marked as required

The page/form should make it clear what information it is requesting and why

## Responsive/Adaptive Appearance

The page is primarily laid out according to a 12-column grid
- Exceptions are allowed (example: a horizontal menu bar), but the page should mostly align to the 12 column grid with no exceptions that take up significant space

The page must be pleasant to read from 360px+ (at standard font-size), with no cut-off content, overlapping text, or awkwardly wrapped text.
- You may contain the page contents with expanding gutters, but the page should be responsive until 1000px
- There must be at least one adaptive breakpoint (exact size is your choice) on at least one page
- Adaptive breakpoints should use rem as their unit
- You must have text/boxes that are easily seen to be responsive (wrapping text as the browser resizes)

## Accessibility Appearance

All forms, menus, buttons, and links must be usable with keyboard as well as mouse

No information should be conveyed through color differences only

All form fields should be associated with a `<label>` element that contains useful text

Any form fields that are required should be visibly and textually marked as required

All images will have descriptive `alt` attributes
- These alt attributes should describe what the picture is

Any icons are not required to understand and use the page with a screen reader
- This means there must be text to explain what happens, icons can only add to the experience, not be the only means to understand it

## Demonstrated Skills
- Semantic HTML
- Semantic Class names
- CSS Grid
- CSS Flexbox
- 12 column grid layout
- A non-static position property
- Responsive HTML
- Adaptive HTML
- HTML Forms