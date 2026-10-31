LIMA FC WEBSITE
===============
Upload everything in this folder (all the .html files + assets/) to your web
host (Netlify, Vercel, cPanel, GitHub Pages, etc.).

Pages
  index.html       Homepage (every section in one scroll)
  club.html        The club
  news.html        Club news
  tournament.html  End-of-year tournament: results, table, fixtures
  gallery.html     Gallery
  leadership.html  Club leadership
  join.html        Join Lima FC
  dues.html        Pay your dues
  policy.html      Lima policy

Updating content
  All pages share the same content block. Search for "SITE CONTENT" in
  index.html, edit it, then copy the same edit into the other .html files
  (or ask Claude to rebuild the site for you).

Before going live
  1. Replace YOUR-DOMAIN in the og:image / twitter:image tags with your domain
     (for example https://limafc.live).
  2. Add your Paystack or Flutterwave payment-page link to payments.onlineUrl.
