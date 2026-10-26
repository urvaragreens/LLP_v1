# NOT JUST FUNGI LLP

A lightweight, responsive static website for NOT JUST FUNGI LLP. It uses semantic HTML, CSS and a small vanilla JavaScript file for the mobile navigation and copyright year. There is no build step or package installation.

## Run locally

Open `index.html` in a browser, or serve this folder with any static file server. All website assets are referenced with relative paths.

## Publish with GitHub Pages

This repository includes a GitHub Actions workflow at `.github/workflows/pages.yml`. It publishes the static site automatically when changes are pushed to `main`.

1. Create a GitHub repository and add the contents of this folder at its root.
2. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
3. Push to the `main` branch, or run **Deploy static site to GitHub Pages** from the repository's **Actions** tab.
4. Once the workflow completes, open the Pages URL shown in the deployment job. Relative asset paths work for project pages and custom domains.
5. Once the final domain is known, uncomment and update the canonical URL in `index.html`.

## Brand and business details

- `assets/images/logo.png` is cropped from the owner-supplied `logo.jpeg` and used in the header and footer.
- Contact links use `+91 63616 45820` and `contactus@notjustfungi.com`; the address and GSTIN shown on the site were provided by the owner.
- Product categories and varieties are owner-provided. Availability, prices and packaging are not stated; visitors are invited to enquire.
- The cultivation copy is a general overview, not a statement of NOT JUST FUNGI LLP's specific process.

## Photography

The hero banner and cultivation gallery use photographs supplied by the owner. The copies are stored locally in `assets/images/` and use relative URLs.

| Website file | Supplied source |
| --- | --- |
| `assets/images/hero-banner.jpeg` | `hero_banner.jpeg` |
| `assets/images/grow-01.jpeg` | `grow_image_1.jpeg` |
| `assets/images/grow-02.jpeg` | `grow_image2.jpeg` |
| `assets/images/grow-03.jpeg` | `grow_image3.jpeg` |
| `assets/images/grow-04.jpeg` | `grow_image4.jpeg` |
| `assets/images/grow-05.jpeg` | `grow_image5.jpeg` |
| `assets/images/grow-06.jpeg` | `grow_image6.jpeg` |
| `assets/images/grow-07.jpeg` | `grow_image7.jpeg` |
| `assets/images/grow-08.jpeg` | `grow_image8.jpeg` |
| `assets/images/grow-09.jpeg` | `grow_image9.jpeg` |

## Editable content

Update business copy and links in `index.html`, styles and breakpoints in `css/style.css`, and the mobile menu interaction in `js/main.js`. Keep images in `assets/images/` and continue using relative paths.
