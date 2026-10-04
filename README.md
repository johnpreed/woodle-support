# Woodle Support

The support and privacy site for **Woodle**, a word ladder puzzle game for iOS —
change one letter at a time to reach the target word.

- Privacy Policy: https://johnpreed.github.io/woodle-support/privacy.html
- Support & FAQ: https://johnpreed.github.io/woodle-support/support.html

## AdMob app-ads.txt

The canonical file is https://johnpreed.github.io/app-ads.txt. It is maintained
in the root of the separate
[johnpreed/johnpreed.github.io repository](https://github.com/johnpreed/johnpreed.github.io),
with GitHub Pages publishing from `main` and `/`.

This repository also publishes an identical copy from `app-ads.txt` at
https://johnpreed.github.io/woodle-support/app-ads.txt. Keep both files in sync
when updating authorized sellers.

```text
google.com, pub-9864706200027545, DIRECT, f08c47fec0942fa0
```

AdMob discovers the developer website from the App Store's **Marketing URL**
field, displayed as the **Developer Website** link, not the Privacy Policy URL.
Set the Marketing URL to https://johnpreed.github.io/woodle-support/ in App Store
Connect and confirm it appears in the published listing. Google notes that this
field can be edited when launching an app or releasing a new iOS version.
The existing privacy and support URLs can stay unchanged.

AdMob ignores the URL's path and looks for `/app-ads.txt` at the hostname root.
This repository is a GitHub Pages project site under `/woodle-support/`, so its
copy is supplementary and does not replace the canonical root file required
for discovery. No game-source change is needed to publish these files.

After the file and developer website link are public, open AdMob's **Apps >
View all apps > app-ads.txt**, expand the app, and select **Check for updates**
if available. Allow at least 24 hours for the verification status to update;
recent App Store listing changes can take longer.

References: [Google's app-ads.txt setup guide](https://support.google.com/admob/answer/9363762)
and [GitHub Pages site types](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages).

## Contact

- Email: **woodle.support@gmail.com**
- Or open an issue in this repository.
