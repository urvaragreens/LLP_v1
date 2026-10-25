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

- `assets/images/logo.png` is a crop of the supplied signboard photograph, preserving the original mint-green wordmark and mushroom mascot. The signboard photograph itself is not copied into the public site.
- The GSTIN, Udyam number and CIN-like signboard identifier are intentionally not published. Add a registration identifier only after the owner has verified it and explicitly approved publication.
- Confirm phone numbers, email, postal address and enquiry wording with the business before launch.
- The only product card is for oyster mushrooms. Add other product varieties or claims only after the owner confirms them.
- The cultivation copy is a general overview, not a statement of NOT JUST FUNGI LLP's specific process.

## Photography

The supplied project does not include farm photographs. Images currently used are representative reference imagery, not photographs of this business or farm. Replace them with owner-supplied photographs before presenting a farm gallery:

| Local file | Source and credit | License |
| --- | --- | --- |
| `assets/images/hero-mushrooms.jpg` | [Close-up of Oyster Mushrooms in West Java, Indonesia](https://www.pexels.com/photo/close-up-of-oyster-mushrooms-in-west-java-indonesia-35992234/), Ruyat Supriazi | [Pexels license](https://www.pexels.com/license/) |
| `assets/images/mushroom-cluster.jpg` | [White oyster mushroom detail](https://www.pexels.com/photo/petals-of-white-blooming-flowers-12586615/), Rizky Sabriansyah | [Pexels license](https://www.pexels.com/license/) |
| `assets/images/cultivation-detail.jpg` | [Button mushrooms growing in an indoor farm setting](https://www.pexels.com/photo/button-mushrooms-growing-in-indoor-farm-setting-31243424/), Airam Dato-on | [Pexels license](https://www.pexels.com/license/) |
| `assets/images/harvest-detail.jpg` | [A person harvesting oyster mushrooms](https://www.pexels.com/photo/a-person-harvesting-white-mushrooms-2478421/), Mark Stebnicki | [Pexels license](https://www.pexels.com/license/) |
| `assets/images/wild-oyster-detail.jpg` | [Close-up of Oyster Mushrooms at a Farmer's Market](https://www.pexels.com/photo/closeup-of-oyster-mushrooms-at-farmer-s-market-36045832/), Tim Mossholder | [Pexels license](https://www.pexels.com/license/) |

Each photograph is stored locally in `assets/images/`; the site does not request image files from a third-party host at runtime. Keep the relevant credit information if retaining these files. Optimize replacement images for the displayed crop, preserve descriptive alt text, and update this list when assets change.

## Editable content

Update business copy and links in `index.html`, styles and breakpoints in `css/style.css`, and the mobile menu interaction in `js/main.js`. Keep images in `assets/images/` and continue using relative paths.
