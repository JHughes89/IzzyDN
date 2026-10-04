# Date Night — simple GitHub Pages app

No accounts. No database. No Supabase.

## What it does
Pick a date, time, dress code, food and restaurant. Then:
- **Email the plan** opens a ready-filled email to `JHughes89.yt@gmail.com`
- **Text the plan** opens a ready-filled SMS to `07488711426`

The person still taps **Send** in Mail/Messages. A static GitHub Pages site cannot silently send email or SMS without a third-party backend/service.

## Put it on GitHub Pages
1. Create a new GitHub repository, for example `date-night`.
2. Upload these files to the repository root:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon.svg`
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.
6. GitHub will publish a URL like `https://YOURNAME.github.io/date-night/`.

## Add to iPhone home screen
1. Open the GitHub Pages URL in Safari.
2. Tap **Share**.
3. Tap **Add to Home Screen**.
4. Tap **Add**.

## If you want messages to send automatically
That requires a service such as EmailJS/Formspree for email, or Twilio for SMS. Do not put private API secrets directly in GitHub Pages code.
