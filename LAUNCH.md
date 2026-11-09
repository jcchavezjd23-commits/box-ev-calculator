# Box EV Calculator — $0 Launch Plan

A free tool site for trading-card players. Every step below costs nothing.

## How it makes money
| Stream | Sign-up (free) | Rough payout |
|---|---|---|
| Affiliate "Check box price" button | TCGplayer affiliate (via Impact), eBay Partner Network, or Amazon Associates | ~1–5% of each purchase people make after clicking |
| Tips | Ko-fi or Buy Me a Coffee | 100% of tips (Ko-fi takes 0% on one-off tips) |
| Ads (later) | Google AdSense — usually needs some traffic + a few content pages | Per view/click |

## Step 1 — Put it online (5 minutes)
**Easiest:** go to https://app.netlify.com/drop and drag the folder containing `index.html` onto the page. You get a free `something.netlify.app` URL.

**Alternative:** create a free GitHub account → new public repo → upload `index.html` → Settings → Pages → deploy from `main`. URL: `yourname.github.io/repo`.

## Step 2 — Turn on the money
Open `index.html`, find the `CONFIG` block near the bottom, and paste your links:
```js
tipUrl:       "https://ko-fi.com/yourname",
affiliateUrl: "https://your-affiliate-link",
```
Re-upload. The buttons and the affiliate disclosure appear automatically.

## Step 3 — Get traffic (this is the real work)
1. **Post set-specific results.** When a new set releases, fill in its pull rates and prices, click **Copy share link**, and post "Is the new ___ box worth it? I ran the numbers" to the game's subreddit, Discord servers, and Facebook groups. The share link opens your site with the numbers pre-filled.
2. **Short videos.** Screen-record the calculator on TikTok / YouTube Shorts: "This box costs $120, here's what it's actually worth." Link in bio.
3. **One page per set** (later): copy `index.html` to `new-set-name.html` with that set's data as the `EXAMPLE`. Each page can rank on Google for "[set name] booster box worth it".

## Rules to stay safe
- Keep the affiliate disclosure visible (the page does this for you once a link is set).
- Read each subreddit's self-promotion rules; lead with useful numbers, not the link.
- Don't claim guaranteed profit — the page already says "estimates only".

## Realistic expectations
Expect $0 for the first weeks. Income tracks traffic: a few thousand visits a month around set releases can bring in tens of dollars from affiliates and tips; more pages and regular posting grow it from there.
