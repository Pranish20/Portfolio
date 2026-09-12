# Pranish Katta — UX / Product Design Portfolio

Complete static portfolio package for Netlify, Vercel or GitHub Pages.

## Folder structure

```text
index.html
assets/
  pranish-photo.jpg
  wallcue-preview.webp
  hum-preview.webp
  skills-preview.webp
  mallicks-preview.webp
case-studies/
  wallcue.html
  hum-discordance-decoder.html
  skills-platform.html
  mallicks-kitchen.html
README.md
```

## Navigation

- The **Pranish Katta · UX** logo on every case study links to the portfolio homepage.
- The **← Back** button on every case study returns to the portfolio homepage.

## Typography

The portfolio and case studies use **Inter** consistently. Heading letter spacing and line heights have been normalised so the typography reads as one system.

## Homepage photo

The portrait has been repositioned into the lower part of the hero copy area to use the previously empty space more intentionally.

## Deployment

Upload the **contents of this folder** to the root of your static hosting project. Do not upload the ZIP itself.

No build command is required.

For Netlify/Vercel, the deployed root must contain `index.html` plus the `assets` and `case-studies` folders.


## Responsive update

The portfolio has been refined for mobile and tablet:
- Hero typography scales down without overflowing.
- Portrait, interactive object and selected-work cards use compact proportions.
- Project cards stack vertically on narrow screens.
- Section spacing and card padding are reduced for mobile.
- Case-study navigation remains compact with a persistent logo/home link and Back button.
- Case-study grids and galleries collapse cleanly to one column.
- Large headings, quotes and metrics scale down to avoid disproportionate layouts.
