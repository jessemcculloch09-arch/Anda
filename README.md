# Andá Launch Page

A simple static storefront that works with GitHub Pages.

## Fastest setup

1. Create a free GitHub account at github.com.
2. Click **New repository**.
3. Name it `anda`.
4. Make it **Public**.
5. Click **Create repository**.
6. Click **uploading an existing file**.
7. Upload everything inside this folder:
   - `index.html`
   - `styles.css`
   - `script.js`
   - the entire `assets` folder
8. Click **Commit changes**.
9. Open the repository's **Settings**.
10. Click **Pages** in the left menu.
11. Under **Build and deployment**, choose:
    - Source: `Deploy from a branch`
    - Branch: `main`
    - Folder: `/ (root)`
12. Click **Save**.

Your site will appear at:

`https://YOUR-GITHUB-USERNAME.github.io/anda/`

It may take a few minutes the first time.

## Change products

Open `index.html` and edit each product card:

- Product name
- Price
- Image path
- Buy button link

Replace every `https://example.com` with your real checkout link.

Good beginner checkout choices:
- Shopify Buy Button
- Square Payment Links
- Stripe Payment Links
- Big Cartel product links

## Replace images

Put new images inside `assets/`, then update the matching filename in `index.html`.

Example:

```html
<img src="assets/my-new-shirt.jpg" alt="My New Shirt">
```
