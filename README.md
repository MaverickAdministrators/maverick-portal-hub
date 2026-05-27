# Maverick Administrators — Internal Resource Hub

Internal static landing hub for the Maverick Administrators team. Provides quick access to the three broker-specific Newborn Medical Contractual Liability Insurance Portals (IFI, ART Risk, Whillock) and the Trackers & Reports repository links.

## Contents

- `index.html` — single-file static page (embedded CSS, no JS, no build step)
- `logo_maverick.png` — brand mark

## Design

- Cream `#f5f0e8` background, navy `#0d1f35`, gold `#c8a96e` accents
- DM Serif Display (headings) + DM Sans (UI/body) via Google Fonts
- Responsive 3-column portal card grid on desktop; stacked on mobile
- Compact tracker grid below the portal cards
- Accessible: semantic HTML, skip link, visible focus states, large click targets

## Portals

| Broker     | URL                                                                |
| ---------- | ------------------------------------------------------------------ |
| IFI        | https://maverickadministrators.github.io/maverick-form-portal/      |
| ART Risk   | https://maverickadministrators.github.io/maverick-form-portal-art/  |
| Whillock   | https://maverickadministrators.github.io/maverick-form-portal-whillock/ |

## Trackers & Reports

Seven Excel/SharePoint tracker cards are listed beneath the portal cards in `index.html`.

## Deployment

Intended for GitHub Pages. Push the contents of this directory to the target repository's Pages branch — no build step required.
