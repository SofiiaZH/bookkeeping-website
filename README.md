# North Shore Bookkeeping website

This is a free static website designed for GitHub Pages.

## Included files

- `index.html` — all website text and page structure
- `styles.css` — colours, layout and mobile design
- `script.js` — mobile menu, scroll animations and automatic footer year
- `.nojekyll` — tells GitHub Pages to serve the files directly

## Before publishing

Open `index.html` and replace:

1. `North Shore Bookkeeping` with your final business name.
2. `VK` with your initials.
3. `your@email.co.nz` with your email.
4. `021 000 0000` with your phone number.
5. `YOUR-EMAIL@example.com` in the contact form with the email that should receive enquiries.
6. Sample prices with your real prices.
7. Sample testimonials with genuine testimonials only.
8. Photo placeholders with your image.

## How to add a photo

Put your image in this folder, for example:

`profile.jpg`

Replace this block in `index.html`:

```html
<div class="portrait-placeholder">
  ...
</div>
```

with:

```html
<img class="portrait-placeholder" src="profile.jpg" alt="Valeriia, bookkeeper">
```

For the About section, replace:

```html
<div class="about-photo-placeholder">
  ...
</div>
```

with:

```html
<img class="about-photo-placeholder" src="profile.jpg" alt="Valeriia, bookkeeper">
```

You may also add this to `styles.css` if needed:

```css
.portrait-placeholder,
.about-photo-placeholder {
  width: 100%;
  object-fit: cover;
}
```

## Publish free with GitHub Pages

1. Create a GitHub account.
2. Click **New repository**.
3. Name it, for example, `bookkeeping-website`.
4. Make it **Public**.
5. Upload all files from this folder.
6. Open the repository’s **Settings**.
7. Open **Pages**.
8. Under **Build and deployment**, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
9. Click **Save**.
10. Your site will appear at:
   `https://YOUR-GITHUB-USERNAME.github.io/bookkeeping-website/`

## Contact form

The template uses FormSubmit, a third-party service. Replace:

`YOUR-EMAIL@example.com`

with your email address.

When someone submits the form for the first time, FormSubmit normally sends an activation email. The form will work after you confirm it.

Do not publish sensitive client or financial information on this static website.

## Custom domain

You can later buy a `.co.nz` domain and connect it to GitHub Pages. The hosting can remain free.

## Local preview

Double-click `index.html` to open it in a browser. Some form functions require the website to be online.
