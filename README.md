# Harjah (هرجة) — Website

Landing page and privacy policy for the **Harjah** Android app, a dictionary of authentic Omani words and proverbs.

- **Site:** https://harjah.al-mawali.com
- **Privacy policy:** https://harjah.al-mawali.com/privacy.html
- **Google Play:** https://play.google.com/store/apps/details?id=com.harjah.app
- **Developer:** Habib AlMawali (حبيب المعولي) — https://habib.al-mawali.com — habib.almawali@gmail.com

## App details

| | |
|---|---|
| App name | هرجة (Harjah) |
| Language | Arabic (RTL) |
| Application ID | `com.harjah.app` |
| minSdk / targetSdk | 26 (Android 8.0) / 36 |
| Version | 1.2 (versionCode 3) |

## Structure

```
harjah/
├── index.html      # Landing page: features, screenshots, app details, changelog, download
├── privacy.html    # Privacy policy (Arabic + English summary) for Google Play Console
├── 404.html        # Custom "page not found" page (used automatically by GitHub Pages)
├── CNAME           # Custom domain for GitHub Pages: harjah.al-mawali.com
├── .nojekyll       # Tells GitHub Pages to serve files as-is (no Jekyll build)
├── robots.txt
├── sitemap.xml
├── README.md
└── assets/
    ├── icon.png      # App icon (512×512)
    ├── favicon.png   # Favicon (64×64)
    ├── s1.jpg        # Screenshot: all words
    ├── s2.jpg        # Screenshot: favorites
    └── s3.jpg        # Screenshot: settings
```

All pages are static HTML with inline CSS and no JavaScript or build step. The only external request is Google Fonts (Cairo, Tajawal).