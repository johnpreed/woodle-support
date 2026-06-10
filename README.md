# Woodle Support Site

This public repository hosts the static support and privacy policy site for
**Woodle**, a word ladder puzzle game for iOS. It exists so the app can provide
the two URLs App Store Connect requires.

It contains **no game source code** — only a small static website
(`index.html`, `privacy.html`, `support.html`, `styles.css`). No build tooling,
no JavaScript, no analytics, no third-party dependencies.

## Enable GitHub Pages

1. Go to the repo on GitHub → **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Set **Branch** to `main` and **Folder** to `/ (root)`.
4. Click **Save**. Wait a minute for the first deploy.

## Expected URLs

- Privacy Policy: <https://johnpreed.github.io/woodle-support/privacy.html>
- Support: <https://johnpreed.github.io/woodle-support/support.html>
- Home: <https://johnpreed.github.io/woodle-support/>

## Add the URLs to App Store Connect

In App Store Connect for the Woodle app version:

- **Privacy Policy URL** → `https://johnpreed.github.io/woodle-support/privacy.html`
- **Support URL** → `https://johnpreed.github.io/woodle-support/support.html`

## Before submitting to Apple — TODO

- [ ] Replace **`support@example.com`** with a real support email in
      `privacy.html` and `support.html`.
- [ ] Confirm the **effective date** in `privacy.html` is correct.
- [ ] Verify both Pages URLs load before entering them in App Store Connect.

## Keep the policy accurate

If a future version of the Woodle app adds **analytics, ads, accounts, cloud
sync (iCloud/CloudKit), Game Center, a backend/network service, or crash
reporting**, update `privacy.html` to disclose it **before** submitting that
app update. As of this site's creation, the app is local-only with no tracking.
