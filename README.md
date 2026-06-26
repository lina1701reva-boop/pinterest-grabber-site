# PinGrab — landing page

Standalone one-file landing page for the Pinterest Grabber extension. Dark, Pinterest-style,
black background, red accent. No build step — it's a single `index.html`.

## View it
Double-click `index.html` (opens in your browser).

## Put it online (free)
- Easiest: go to **netlify.com/drop** (or **vercel.com**) and drag this whole folder in. You get a live URL instantly.
- Or upload to any hosting / your own domain.

## What to fill in before publishing (search the file for these)
- **`Add to Chrome` buttons** — replace `href="#"` / `href="#install"` with your Chrome Web Store URL.
- **Videos** — every dashed box is a placeholder. Each has a label saying *what to record*
  (main demo, getting started, whole board, selected pins, PDF, private boards, queue).
  Replace a box with a real `<video controls>` or a YouTube `<iframe>` when ready.
- **Pricing** — `$19` / `$0` and the "100 pins per board" limit are placeholders. Set your real plan.
- **Brand name** — it's "PinGrab" everywhere. Find/replace if you pick another name.
- **Contact** — `you@example.com` in the footer.
- **Privacy / Terms** — add real pages and point the footer links at them (required for the Chrome Web Store).
- Remove any "placeholder" notes once finalized.

## Notes
- The masonry pins in the hero are pure CSS (no Pinterest images) — no copyright risk.
- Footer already includes the "not affiliated with Pinterest" disclaimer.
