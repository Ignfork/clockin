# Clock In ($CLOCKIN)

A single-file website. Upload `index.html` to GitHub Pages, Netlify, Vercel or any host, and it works as-is.

## Edit before launch
At the top of the `<script>` in index.html:

```js
var CONFIG = { xUrl:'https://x.com/ClockInLive', xHandle:'@ClockInLive' };
```

## Features
- Night-Shift-style dark page with a pixel wordmark and a hero hall of glowing retro screens around a punch clock on a pedestal (its clock hands show the real time)
- Working punch clock: Clock in / Break / Back in / Clock out, with a CRT timer, 8-hour progress bar and punch sounds. It keeps running if the tab is closed
- Printable time card: every finished shift prints a 1400×820 card with name, date, shift, every punch as an ink stamp and total hours; download it or share it on X
- This week chart and time-card history (stored only in the visitor's browser)
- Four shifts (Dawn amber, Day blue, Swing magenta, Graveyard green) that recolor the whole site; it auto-picks the visitor's local shift and they can switch
- World clock band: live times in 6 cities, each colored by the shift they're on
- Setup steps, FAQ accordion, read-only wallet connect (address prints on time cards)
- No CA on the site: "launch posted on X"
