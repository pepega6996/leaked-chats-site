# Leaked Chats — official series website

Static, responsive 10-book catalog for **Leaked Chats** by Vijay Anand.

## Files
- `index.html` — complete one-page site, with two rows of five covers on desktop.
- `assets/leaked-chats-world-war-ii-official.jpg` — original, unmodified JPEG provided by the author, as submitted to Amazon.
- `books.json` — editable metadata for the ten series books.

All unpublished covers and teaser chat lines are promotional concepts, **not authenticated historical quotations**. The published WWII cover is the supplied final design.

## Publish with GitHub Pages

1. Open **Settings → Pages** for this repository.
2. Under **Build and deployment**, set **Source: Deploy from a branch**.
3. Select **main**, **/(root)**, then **Save**.
4. When GitHub has deployed, the default Pages URL is `https://pepega6996.github.io/leaked-chats-site/`.
5. Under the same Pages settings, add the exact custom domain (expected `leakedchats.com`, confirm before saving).
6. In Namecheap (PremiumDNS), add four A records for `@`, pointing to:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
7. Add a CNAME record: host `www`, target `pepega6996.github.io`.
8. Remove conflicting default web records for `@` or `www` (don't remove mail records). Use GitHub's **Enforce HTTPS** once offered.

GitHub Pages instructions: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Amazon purchase link

When the exact live listing URL is known, edit `const AMAZON_URL = "";` at the bottom of `index.html`, putting the URL between the quotation marks. The World War II cover and Amazon button will then open the listing.

## Editable titles
The ninth title is currently a **working title: The Scientific Revolution**. Its promotional preview and description are provisional.
