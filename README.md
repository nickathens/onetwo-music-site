# onetwo-music.com

The OneTwo Music website. A single page, hand built (`index.html` + `data.js` + `assets/`), served by GitHub Pages on the custom domain `onetwo-music.com`.

OneTwo Music is a bespoke film music production house in Athens.

## Structure

- `index.html`: the whole page (markup, styles, and script inlined).
- `data.js`: the six jobs on the opening grid (`OT_HOME`, with each tile's logo, its size and the award sticker), the work list with credits, the films and their scores, the team, contact details and the about copy.
- `assets/fonts/`: Geologica and Sofia Sans (latin and greek subsets, SIL Open Font License, see the OFL files).
- `assets/media/web/`: work stills and team portraits. `assets/media/hd/`: sharper stills taken from the Vimeo thumbnails (Superbet's and KENTIA's from YouTube's).
- `assets/reel/`: the showreel (`reel_web.mp4`) and its poster frame. It plays at the top of the Films section.
- `assets/films/`, `assets/scores/`: film posters and the score previews.
- `assets/brand/`: the logo files; `mark.svg` is the boxed mark used as the favicon.
- `assets/logos/`: the client logos and the Ciclope logo on the opening grid, each from the brand's own website (white versions; Superbet's is the white logo superbet.gr itself uses; the Olympos one, made white from its own shapes, is kept but no longer on the grid).

Work credits come from the descriptions on vimeo.com/onetwomusic. A job without a credit line there gets none on the site.

Two jobs are videos on the client's own YouTube channel, Superbet's film for Olympiacos BC and KENTIA Timeless: their entries in `data.js` say `"host": "youtube"`, and the video window plays them in YouTube's privacy-enhanced player (youtube-nocookie.com).

No build step. Editing `index.html` or `data.js` and pushing to `main` redeploys.
