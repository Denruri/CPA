# CPA Landing Page

This is a lightweight HTML landing page for CPA offers — optimized for Netlify.

## 🚀 Quick Deploy

1. **Fork this repository** into your own GitHub account.
2. Go to [Netlify → New Site from Git](https://app.netlify.com/start).
3. Connect your GitHub account, pick this repo, and click **Deploy Site**.
4. (Optional) Change your site name in Netlify → Site Settings → Change site name.

## 🔧 Customizing

- Replace `DEFAULT_OFFER_URL` inside `index.html` with your own CPA link.
- Or pass it dynamically via query params:
  ```
  https://yoursite.netlify.app/?offer=https://your-offer.com&subid=123
  ```
- Add images inside `assets/` and update paths in `index.html` if needed.

## 🛠 Updating

- Push changes to `main` branch → Netlify redeploys automatically.
- Use GitHub Actions or any CI/CD pipeline to automate tracking or versioning.

---
Happy earning! 🚀
