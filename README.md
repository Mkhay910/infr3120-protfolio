# Mustafa Khan — INFR3120 Portfolio

Personal portfolio website built for INFR3120 Assignment 1 using HTML5 and CSS3.

## Pages
- `index.html` — Home page and navigation
- `about.html` — Biography, personal photo, and introductory video
- `projects.html` — Selected coursework and lab projects
- `contact.html` — Contact form with browser-side validation

## Folder structure
```text
infr3120-portfolio/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/
│   ├── laptop.css
│   ├── tablet.css
│   └── mobile.css
├── images/
│   ├── mustafa-photo.jpg       
│  
└── video/
    └── introduction.mp4        
```

## Responsive design
The site links three separate CSS files on each page. The files use media queries and fluid widths; no Flexbox is used.
- **Mobile: 480px and below.** Small screens need stacked content, shorter headings, and full-width form controls.
- **Tablet: 481px–960px.** Medium screens use two-column project cards and reduced spacing.
- **Laptop/desktop: 961px and above.** The base stylesheet uses a wider content area and multi-column cards.

The viewport meta tag is included on every page so the layout uses the device's CSS viewport.

## Color scheme
Palette used in this starter: dark navy `#17243B`, teal `#087F8C`, off-white `#F5F7FB`, white `#FFFFFF`, and coral `#F28C6B`. The intent is a calm technology palette with teal as the accent and coral for contrast. Before submission, open Adobe Color, choose/create a scheme that matches or replace these colors with your chosen scheme, then record the **scheme name/type and Adobe Color URL** here.

## Gradients
- `css/laptop.css`: `.hero` uses `linear-gradient(115deg, #17243b 0%, #087f8c 100%)`, an angled linear gradient.
- The same hero gradient satisfies the angled-gradient requirement; to clearly demonstrate a second standard linear gradient, add/use another element with `linear-gradient(to right, ...)` and document its selector here. For example, you can apply it to a project card heading or section accent.

## Contact form validation
The contact form uses built-in HTML constraints: required name/email/message, email input type, minimum/maximum lengths, and a phone-number pattern. It is a front-end demonstration only. A static GitHub Pages site cannot send or store submissions without a backend or form service; do not claim messages are delivered.


## Testing checklist
- [ ] Open each HTML file locally and click every navigation link.
- [ ] Test the pages at mobile, tablet, and desktop widths.
- [ ] Test form validation with empty fields, an invalid email, and a valid submission.
- [ ] Validate each HTML file with the W3C Markup Validation Service: https://validator.w3.org/
- [ ] Validate each CSS file with the W3C CSS Validation Service: https://jigsaw.w3.org/css-validator/
- [ ] Check links with the W3C Link Checker: https://validator.w3.org/checklink
- [ ] Run an accessibility check with WAVE: https://wave.webaim.org/
- [ ] Spell-check all text and fix any warnings/errors you can.
- [ ] After testing, record actual results here. Do not claim a validator or WAVE pass unless you ran it.

