# Gautam Portfolio

A responsive React portfolio with a warm neutral palette, lime accents, CSS artwork, project filters, and accessible native project dialogs.

## Development

Run `npm install` if dependencies are missing, then `npm run dev`.

Run `npm run build` to create the production site in `dist`. Run `npm run preview` to preview the production build.

## Personalize

Edit `profile` and `projects` at the top of `src/App.jsx`. The portfolio includes Gautam Bari’s supplied biography, Sleep Universe experience at My Invented, RAI-Buddy internship work at KMITL, email, and GitHub profile. LinkedIn is omitted until a profile URL is supplied. Sleep Universe features the supplied website screenshot in a browser-style frame and a link to https://mysleepuniverse.com/. RAI-Buddy features a captured welcome screen and links to https://rai-buddy.onrender.com/. Update the page title and description in `index.html` when changing the profile.

Project thumbnails and the hero illustration are rendered in CSS. Fonts use Google Fonts with local sans-serif fallbacks. No backend or contact form service is required.

## Verification

Production build passes. Local preview returns HTTP 200. Project filtering and opening/closing the project detail dialog were checked in the browser.

## Resume

The original supplied resume is served from `public/Gautam_Bari_Resume.pdf`. Visitors can view it in a new tab from the hero or download it from the contact section. Replace this file with your latest resume to keep both links current.
