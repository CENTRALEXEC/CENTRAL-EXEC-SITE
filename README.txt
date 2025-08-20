V42 Portable Site — Upload Anywhere
------------------------------------
Files:
- index.html (main landing page)
- booking.html (EasyTaxi iframe embed — no local success page)
- assets/css/site.css (styles), assets/js/site.js (small helpers)
- assets/img/ (placeholders for Executive, Minibus, Luxury, Hero)

How to deploy on GitHub Pages:
1) Create repo → Settings → Pages → Source: Deploy from a branch → Branch: main (/root).
2) Upload the contents of this folder (index.html, booking.html, assets/).
3) When live, add your custom domain in Settings → Pages and update DNS.
4) Optional: uncomment the canonical link in <head> after the domain is final.

Swap images: replace files in assets/img/ with your real photos (same filenames) or update <img src> paths accordingly.
