# The CVNHS Gazette — revised PWA prototype

A responsive Progressive Web App prototype for **Catubig Valley National High School's THE CVNHS GAZETTE**, revised to follow the supplied desktop/mobile website mockup.

## Revised layout
- Green upper banner with the school name, school motto, and social-style icons
- Masthead with the DepEd logo, CVNHS Gazette publication logo, school name/tagline, and CVNHS school seal
- Green navigation bar with Home, News, Features, Opinion, School Life, Sports, Arts & Culture, Cartoons, search, and Admin
- Large featured campus story beside a Latest News column
- Yellow Learners' Voices panel and green Stakeholders' Forum panel
- Additional story cards, mission section, and branded footer
- Mobile-responsive layout with stacked content on small screens

## Content and admin tools
- Feature Stories page with searchable sample stories, article details, author/date, full story, and photo caption
- Editorial Cartooning page with placeholder art, captions, and messages
- Browser-based Admin CMS to add, edit, and delete stories and cartoons
- JSON backup export/import
- Poppins typography, green/golden-yellow branding, rounded cards, and PWA manifest/service worker

## Run locally
Use a local web server for the best PWA experience (service workers require localhost or HTTPS):

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` from this folder.

## Important prototype limitations
This is a front-end prototype. CMS changes are stored in local browser storage on the current device only; there is no login, shared database, or server publishing. For a live school publication, connect a secure backend, configure authentication and editorial permissions, and deploy over HTTPS. Sample story content and imagery are illustrative placeholders and should be replaced with approved publication content.
