# World Talk Radio

Tune into real, live news and talk radio streams from public broadcasters around the world, grouped by region. Runs entirely in your browser.

**Live:** <https://world-talk-radio.slippylabs.com/>

## What it does

- Live news and talk streams from public broadcasters worldwide.
- BBC, NPR, RFI, Deutschlandfunk, ORF, ABC, RNZ, NPO and more.
- Grouped by region, with a persistent now-playing panel.

## Run it locally

A static site. No build step, no package manager, no dependencies:

```
git clone git@github.com:slippylabs/world-talk-radio.slippylabs.com.git
cd world-talk-radio.slippylabs.com
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Notes

The player is client-side, but **the streams are not mine** — they are the public broadcast feeds of the stations listed, played directly from their own servers. Nothing is proxied, cached or rehosted here. A station that goes down, geoblocks, or changes its stream URL will stop working until the URL is updated.

---

Part of [Slippy Labs](https://slippylabs.com). Every tool is indexed at
[projects.slippylabs.com](https://projects.slippylabs.com).
