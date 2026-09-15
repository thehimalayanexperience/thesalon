# THE Salon — GitHub Pages

A lightweight, responsive static website for THE Salon | The Himalayan Experience.

## Deploy

1. Upload the contents of this folder to a GitHub repository.
2. In GitHub: **Settings → Pages → Deploy from a branch**.
3. Select the branch containing `index.html` and the `/root` folder.
4. Save. GitHub Pages will publish the site.

No build step or npm installation is required.

## Before publishing

- Replace/update the exact address if the full street address is available.
- Confirm the WhatsApp number and Instagram handle.
- Add real guest testimonials when available.
- If desired, replace the lightweight Instagram gallery with a live Instagram provider/embed. The current implementation intentionally avoids a heavy third-party feed to preserve page speed.
- Update current offers in `index.html` when the promotions change.

## Performance

Images are pre-compressed WebP assets. Critical hero imagery is loaded eagerly; other imagery is lazy-loaded. The site uses vanilla HTML/CSS/JS with no framework or runtime dependencies.
