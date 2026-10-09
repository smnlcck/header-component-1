# header-component-1

A header variant for the section-by-section [simonalcock.ie](https://simonalcock.ie) homepage redesign, built from the "header" frame in the General Design Asks Figma file (State=Loading and State=Loaded).

- Opens full screen with the `.simon` logo centred at 64px and an animated mouse scroll prompt
- As the page scrolls, the logo scales down to 24px and moves into the top-left corner of an 80px header
- Nav links (home, about, case studies, work) and the Contact button fade in on the right as the logo docks; the bar fills in once it has
- The animation is tied to scroll position, so scrolling back up reverses it
- Below 760px only the logo and Contact show
- With reduced motion turned on, the logo snaps between the two states instead of gliding

The grey blocks below the header are placeholders for the other homepage sections, in build order.

Open `index.html` in a browser to view it.

## Fonts

Aeonik Fono Regular is a licensed font, so it is not in this repo. The page loads it from simonalcock.ie. Browsers only allow that if simonalcock.ie sends an `Access-Control-Allow-Origin` header for its font files; without it, the text falls back to DM Mono from Google Fonts.
