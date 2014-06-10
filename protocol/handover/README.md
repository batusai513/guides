Asset Handover
===

Design Review
---

When receiving design comps, review to make sure they include:

- Versions of full screen backgrounds that are either 1920px wide or fade/repeat gracefully to fill the entire screen
- Tablet and phone versions of background images
- Content for every Carousel slide
- Files for all fonts used, no usar demasiadas fuentes si no es estrictamente necesario (con un maximo optimo de 3)
- Favicon and Apple touch icons
  - tratar de entregar los favicons en tamaños 16x16, 32x32, 48x48 (24x24, 64x64, opcionales) en formato png o bmp, para luego ser compuestas en el .ico
  - apple touch-icons: 152x152, 144x144,x 120x120, 114x114, 72x72, 57x57
- Behavior and states for every UI module (popups, pullovers, etc)
  - Hover and active states for clickable items like links and buttons
- Empty states for all views
- Form validation and error and messages (human and compelling ones)
  - form states (active, disabled) for every form element in use
  - forgot password link, form and related emails
  - registration relared emails
- Flash and notification messages (human and compelling ones)
  - login
  - logout
  - global errors
  - after submit forms
- Error pages
  - the error pages should have at least a back to previous page and index page
- Base color palette
- Descriptive color palette
  - at least with primary font color, title font color, success, warning, info, error and grays colors
- Icon manifest
- Typography guidelines
  - font sizes, weigths and line heights for titles (h1 to h6)
  - font sizes, weigths and line heights for main text
- if it's posible reponsive behavior for each component on main breakpoints(decided by the designer)
Also, check the following:

- The use of filters such as multiply and overlay are limited to elements with a non-transparent background
- All fonts used are either web safe or can be embed with @font-face
- All fonts used are free to use or have the required license
- Pages exist for all the links in the design
