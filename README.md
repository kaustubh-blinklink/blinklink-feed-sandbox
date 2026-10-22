# Blinklink Feed Sandbox

A test page for the v5 feeds embed (web-embed), hosted on GitHub Pages:
https://kaustubh-blinklink.github.io/blinklink-feed-sandbox/

- `index.html` — the **Third Wave** (social, dev) feed "Feed sandbox", slot `feed-sandbox`, drawn twice: the
  console's one-line inline tag and its UI trigger. The page URL is on Third Wave's whitelist (added by Create Feed
  in console-v5 dev), so the feed serves here; any other path on this site is an unknown page and lands in the
  whitelist as a pending request.
- `legacy.html` — the original POC against the old stack (web-sdk carousel, stream `STREAM0001`, placement
  `PLACEMENT0001`).
