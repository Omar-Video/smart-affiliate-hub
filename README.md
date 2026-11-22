# Smart Affiliate Hub — GitHub Pages

A static, responsive editorial website built with semantic HTML, CSS, and vanilla JavaScript. No build step, paid hosting, framework, or API key is required.

## Included
- Responsive homepage and three starter editorial articles
- Light/dark theme with saved preference
- Language selector with currently authored full homepage UI translations for English, Arabic, and French; other selector languages are present as planned language options, not complete translations yet
- RTL layout direction for Arabic and Urdu
- Client-side article-card search
- About, Contact, Privacy, and Affiliate Disclosure starter pages
- Canonical URLs, Open Graph basics, robots.txt, sitemap.xml, and `.nojekyll`
- Defensive JavaScript: shared script also works on secondary pages where homepage-only controls are absent

## Publish on GitHub Pages
1. Extract this ZIP.
2. Open `Omar-Video/smart-affiliate-hub` on GitHub.
3. Upload the **contents** of this folder to the repository root (not the ZIP itself). Keep the `assets` and `articles` folders.
4. Open **Settings → Pages**.
5. Choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
6. Wait for the Pages deployment. Expected URL: https://omar-video.github.io/smart-affiliate-hub/

## Required owner setup before public launch
- Replace the placeholder contact email in `contact.html` with a monitored address.
- Review `privacy.html` against the actual analytics, cookies, mailing list, and affiliate services you decide to use. It is a starter policy, not legal advice.
- Add your real affiliate links only after approval. Put a clear disclosure near each affiliate recommendation and verify each destination.
- Connect a real mailing-list provider before advertising newsletter signup. The current form is intentionally a demo and does not transmit/store addresses.
- Add original, fact-checked articles and genuine product testing. The three included articles are starter editorial content, not product reviews.
- Verify the deployed sitemap in Google Search Console and request indexing. A sitemap helps discovery but does not guarantee indexing or rankings.

## Language and SEO note
A language dropdown alone does not create 20 indexable translated websites. Only English, Arabic, and French homepage interface translations are authored in this version. The other 17 languages are selectable placeholders, and article/legal pages remain English. For proper multilingual SEO, create reviewed translated page versions under language paths (for example `/ar/` and `/fr/`) and add reciprocal `hreflang` tags plus language-specific canonical URLs. Do not claim that the site is fully translated until that work is complete.

## Local validation
This project uses plain static files. Validate links after deployment and test the site in current desktop and mobile browsers.
