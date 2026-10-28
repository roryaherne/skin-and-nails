# Skin And Nails – GitHub Pages site

A German-language, static site for Skin And Nails in Stans, Tirol. It uses plain HTML and CSS only; no server-side code, build step, or JavaScript dependencies.

## Pages

- `/` – home
- `/services/`, `/services/feet/`, `/services/nails/`
- `/news/`, `/news/article1/`, `/news/article2/`
- `/gallery/`, `/about/`, `/contact/`

Each route is a directory containing `index.html`, so it works with GitHub Pages directory URLs. The stylesheet uses native CSS nesting and follows the visitor's `prefers-color-scheme` setting.

## Before publishing

- Replace the clearly labeled demo contact information in `contact/index.html` with actual telephone, email, opening-hours, and social profile details.
- Replace Lorem ipsum demo articles and review the service/about copy.
- Verify the postal address: the site currently uses `6500 Stans` as requested.
- The image assets currently use JPG/PNG; paths can be updated after converting images to WebP.

To publish, enable GitHub Pages for the repository's deployment branch/root in the repository settings.
