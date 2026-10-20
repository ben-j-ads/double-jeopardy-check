# Double Jeopardy Check

Is your brand's loyalty normal for its size? Paste penetration and purchases per buyer for the brands in your category and see whether yours sits above, below or on the line that size predicts.

Open `index.html` in any browser. No build step and no dependencies.

- **Input:** one row per brand, `name, penetration %, purchases per buyer`, from the same panel and period. The pre-filled rows are made up, to show the format. At least 5 brands.
- **Verdict:** `normal for its size`, `more loyal than its size` or `less loyal than its size`.
- **Method:** a straight line through the other brands, with a prediction interval at your penetration (ordinary least squares, Student's t critical values interpolated from a table). Every brand in the table is judged against the others.
- **Shows:** expected and actual purchases per buyer, the gap, the normal range, a scatter with the interval, and a per-brand table.
- **Share:** a paper-ground PNG card, and the URL hash carries your data.

Double jeopardy is an empirical regularity (Ehrenberg and colleagues). A handful of brands gives a loose line and most brands will look normal, which is the honest answer. Niche brands can differ for real reasons.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
