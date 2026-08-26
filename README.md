# 🫙 The Swear Jar

Paste in a movie script, a set of lyrics, or your own foul-mouthed rant, and The Swear Jar tallies the profanity and tells you what you owe.

Every cuss word is sorted into a tier — minor, medium, or severe — and priced accordingly. Watch the jar fill with coins as the total climbs.

**[Try it live →](#)** *(update once GitHub Pages is enabled)*

## How it works

1. Paste text into the box — a script, lyrics, whatever you've got
2. The app scans it against a tiered profanity list
3. Each match adds to your running total, tallied per word
4. The jar visually fills with coins as the total grows

## Rate card

| Tier | Examples | Rate |
|------|----------|------|
| Minor | crap, damn, dang, heck, hell | $0.10 |
| Medium | ass, bastard, bitch, dick, piss, prick, tits | $0.25 |
| Severe | cocksucker, cunt, fuck, motherfucker, shit | $0.50 |

All seven of George Carlin's "dirty words" are covered across the tiers.

A flat-rate mode is also available if you'd rather charge a single price per cuss, regardless of severity.

## Design notes

- Single-file, client-side only — `index.html` contains all HTML, CSS, and JS
- No text is stored, transmitted, or logged anywhere; everything happens in your browser tab
- No scripts or lyrics are bundled with or fetched by the app — you supply your own text, which keeps things copyright-clean
- Built with a mason-jar / vintage-label aesthetic: `Special Elite` for the stamped display type, `Work Sans` for body copy, `JetBrains Mono` for labels and data

## Roadmap

- File upload support for `.txt` and `.pdf`, parsed entirely client-side (PDF.js for PDFs), with file size caps
- Inline highlighting of matched words within the pasted text itself

## License

MIT — see [LICENSE](LICENSE).

Built by [starheartstudio](https://github.com/starheartstudio). The Swear Jar is a novelty calculator for entertainment purposes.
