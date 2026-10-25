# Stefan's AABA Fake Book

A swing-dance fake book for the piano chair of a small band, in seven parts: piano, trumpet (B♭), alto sax (E♭), tenor sax (B♭), guitar, bass and drums. Thirty-two standards, alphabetical, with lead-sheet changes in the band's keys, how-to-play notes per chair, key notes for solos, a recording to listen to for each tune, and the whole thing as one PDF.

- **Site:** `index.html` (GitHub Pages serves it at the repo's Pages URL)
- **PDF:** [Stefans-AABA-Fake-Book.pdf](Stefans-AABA-Fake-Book.pdf), 495 pages, all seven parts

The site is a single self-contained HTML file: the charts are rendered from the tune data inside it, horn parts are transposed on the fly, and each tune's YouTube clip loads only when you press play.

## Updating

Edit `index.html` (the tune data is the `TUNES` array; recordings are the `YT` map), commit, push: Pages redeploys in about a minute. Regenerate the PDF from the page with a print-to-PDF at A4 if the content changes.
