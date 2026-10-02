# onetwo-music.com

The OneTwo Music website. A single page, hand built (`index.html` + `data.js` + `assets/`), served by GitHub Pages on the custom domain `onetwo-music.com`.

OneTwo Music is a bespoke film music production house in Athens.

## Structure

- `index.html`: the whole page (markup, styles, and script inlined).
- `data.js`: the work list with credits, the films and their scores, the team, contact details and the about copy.
- `assets/fonts/`: Geologica and Sofia Sans (latin and greek subsets, SIL Open Font License, see the OFL files).
- `assets/media/web/`: work stills and team portraits. `assets/media/hd/`: sharper stills taken from the Vimeo thumbnails.
- `assets/reel/`: the showreel the opening plays (`reel_web.mp4`) and its poster frame.
- `assets/films/`, `assets/scores/`: film posters and the score previews.
- `assets/brand/`: the logo files; `mark.svg` is the boxed mark used as the favicon.

Work credits come from the descriptions on vimeo.com/onetwomusic. A job without a credit line there gets none on the site.

No build step. Editing `index.html` or `data.js` and pushing to `main` redeploys.
