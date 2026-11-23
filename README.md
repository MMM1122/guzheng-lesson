# 筝探 · ZhengTan
https://mmm1122.github.io/guzheng-lesson/

Bilingual (中文 / English) website for guzheng lessons near UBC, with a playable 21-string guzheng in the browser.

- Keep `index.html`, `styles.css` and `favicon.svg` together. Open `index.html` directly, or publish it with GitHub Pages (Settings → Pages → Deploy from branch `main`, folder `/ (root)`).
- Add `#en` or `#zh` to the link to open a specific language.

## Design and interaction

- Rice-paper palette, celadon ink, cinnabar seals and a softly layered mountain backdrop.
- A canvas-drawn, playable 21-string guzheng with wood grain, orchid panels, raised bridges and string animation. On small screens, swipe horizontally to explore the instrument and vertically across the strings to play.
- Chinese / English copy, remembered language preference, keyboard-accessible demonstrations and a collapsible numbered score.
- The booking form prepares an email or a message to copy. It does not submit a booking automatically.
- No build step or JavaScript dependencies. Pushes to `main` publish through the existing GitHub Pages workflow.

## Credits

Guzheng note samples come from [Musician: Extended](https://github.com/LenweSaralonde/MusicianExtended) by LenweSaralonde, licensed under GPL-3.0. The samples were trimmed and converted to MP3 and are embedded in `index.html`.
