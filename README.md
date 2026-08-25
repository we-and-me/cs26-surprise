# The Door · Connectors Summit 2026 Day-3 Easter egg

One page, two acts, all in `index.html`:

- **Before December 11, 2026** — "The Door": countdown, a different daily
  message (31 in rotation), and it remembers repeat peekers.
- **December 11 onward** — "The Wisdom of the Room": draw-a-card insight
  cards in the Acts of Connection card style, browse-by-theme, and the
  CONNECTORS2026 coupon P.S.

## Preview while building

- Door state: `index.html?act=door`
- Reveal state: `index.html?act=reveal`

The date switch is automatic in production (`REVEAL_DATE` in index.html).

## The Day-2 data drop

The wisdom cards currently use `WISDOM` sample data in index.html.
Night of Day 2: give Claude the transcripts, chat logs, and Typeform
journaling exports; Claude distills them into the same format (quote,
who, session, theme), replaces `WISDOM`, and pushes. Theme chips and
card colors build themselves from that data.

## Publish

Push this folder to a clean public GitHub repo → enable GitHub Pages →
point `weand.me/do-not-scan-until-day-3` (GoDaddy redirect) or a
subdomain at it. Do not include anything else in the repo.
