# ShiftBite — Frontend Demo

A responsive, interactive frontend demo for the ShiftBite food delivery application project.

## Included
- Food discovery with category filters and search
- Sample menu cards with demo prices in Indian rupees
- Interactive cart with quantity controls and subtotal/delivery-fee calculation
- Checkout form with a clearly labelled demo-only order flow
- Demo order tracking states
- Sign-in modal UI
- Responsive layout for desktop and mobile

## Important limitation
This is a **frontend-only demo**. It does not connect to a Python/FastAPI backend, MySQL database, real authentication, live maps, restaurant accounts, or a payment gateway. Cart and order behaviour runs in the browser only. No real payment is taken.

## Run locally
Open `index.html` in a modern browser. No build step is required.

## Publish on GitHub Pages
1. Create a new repository on GitHub, for example `shiftbite-frontend`.
2. Extract this ZIP on your computer.
3. Upload **the files inside the folder** (`index.html`, `styles.css`, `app.js`, `README.md`) to the root of the repository. Do not upload only the ZIP.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then click **Save**.
7. Wait for GitHub Pages to publish. Your site URL will appear in the Pages section, usually in the form `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Customizing
- Edit menu items and sample prices in `app.js` in the `foods` array.
- Change colours and layout in `styles.css`.
- Update the page text and structure in `index.html`.

## Technology note
This package uses HTML, CSS and vanilla JavaScript so it can be published directly as a static GitHub Pages site. The project proposal mentions React, FastAPI and MySQL for the full application; those are not included in this static demo.
