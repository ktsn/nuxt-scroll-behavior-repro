# nuxt-scroll-behavior-repro

## Steps to reproduce

1. Clone this repository
2. `npm install`
3. `npm run dev`, then open `http://localhost:3000` with browser.
4. Scroll to the bottom of the page, then click `Another Page`.
5. Scroll position does not updated to top.
6. Scroll to the top of the another page, then back to the previous page with browser's back button.
7. Scroll position does not restored to previous position.