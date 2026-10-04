# BRAND, version 3 (public summary)

## Posture
The product checks invoices. It must look like the thing you would put in front of the other side: paper, ink, an instrument. It must not look like the vendors it checks. So: no gradients on text or backgrounds, no glass or blur panels, no glowing blobs, no illustrated people, no dark mode, no animated backgrounds, no mesh or particle heroes. Depth comes from imagery and one shadow token; motion comes from films, not from CSS tricks.

## Palette roles
Four roles, each a token in `tokens.css`: paper (the page background, cream), ink (text), accent (one terracotta, used for the single primary action), hairline (rules and table lines). Nothing else is coloured. The accent appears once per screen at most.

## Typography
Three families, loaded from the site itself, never from a third party: a serif for headings and the document, a sans for interface text, a monospace for figures and ids. Tabular figures everywhere a number appears. Body measure capped at about 65 characters; the measure never widens on a desk.

## Spacing
One spacing scale, in rem, from `tokens.css`. Section spacing is one step larger than it feels necessary. A phone gets a 16 px side gutter and no horizontal scroll at any width from 320 to 1920.

## Corners and shadow
Buttons and inputs 10 px; cards, panels and menus 14 px; image and film frames 18 px; the printed document 4 px (it is paper, not a card). One elevation token, a soft two-layer shadow at low alpha, on cards, the document and image plates. Nothing else casts a shadow. Nothing casts a shadow in print.

## Motion
Micro-transitions on opacity and transform only, 150 to 220 ms, easing `cubic-bezier(0.2, 0, 0, 1)`. Menus open with a fade and a 6 px slide; disclosures fade their content in; links, buttons and inputs transition colour, underline and shadow on hover and focus; the primary button lifts 1 px. A short crossfade between pages where the browser supports cross-document view transitions, nothing where it does not. Reduced-motion turns all of it off. Refused: parallax, scroll-triggered reveals, anything longer than 220 ms outside a film.

## Imagery
See `imagery.md`. Every page must read identically with every image and film removed.
