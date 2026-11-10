# Birthday Book

A 3D digital scrapbook birthday card: one self-contained HTML page. Click the book, the cover flips open, and hand-drawn pressed flowers rise off the left page while the letter appears on the right.

## Files

- `Birthday-Book.html` — the whole site. CSS and JS are inline; nothing else to build.
- `assets/` — the hand-drawn artwork (daisy, poppy, buds, leaf sprig, blue flower, butterfly, wreath, doodles) and the self-hosted handwriting fonts.

## Open it

Open `Birthday-Book.html` in a browser and keep the `assets/` folder next to it — images and fonts are loaded by relative path, so the two have to travel together.

## Editing the letter

Search for `<!-- EDIT HERE -->` in the HTML. The greeting paragraph sits between that marker and `<!-- /EDIT -->`; replace it and the page keeps its layout.

## Details

- Desktop shows the whole letter on one page. On a phone the card is too small for a long letter, so the letter page scrolls inside the paper with a soft fade at the bottom edge: swipe (or tap) to read on, and tap once you reach the end to close the book.
- The book can be dragged open, clicked open, and closed again; flowers fold away with it.
- Sound is off by default on phones and only starts after a real click; the doodle speaker in the top right toggles it and remembers your choice.
- With reduced motion enabled the page renders the opened state without the flip animation.
