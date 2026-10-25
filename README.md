# fremontbridge.com

Forwards fremontbridge.com to [seattle-bridges.com](https://seattle-bridges.com),
where the site now lives (source: the `fremont-bridge` repo). It keeps the
path, so `fremontbridge.com/ballard/` lands on `seattle-bridges.com/ballard/`.

Served by GitHub Pages straight from `main`, with no build. `404.html` is the
same page as `index.html`, so every old address forwards too. The link-preview
tags keep already-shared fremontbridge.com links showing the Fremont card.

Namecheap's own URL redirect can't do HTTPS, which is why this repo exists.

`img/og*.jpg` are copies of the link-preview images, so cards for links shared
before the move still find their picture at the old address.
