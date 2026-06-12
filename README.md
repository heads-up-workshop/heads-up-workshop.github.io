# AHIMR'26 — Workshop Website

Website for **The 1st International Workshop on AI-Mediated Heads-Up Interaction in Wearable Mixed Reality (AHIMR'26)**, co-located with IEEE ISMAR 2026 in Bari, Italy, on October 5, 2026.

## Deploying with GitHub Pages

1. Create a new GitHub repository (e.g. `ahimr26` or `ahimr26.github.io`).
2. Upload the contents of this folder — `index.html` and the `images/` directory — to the repository root.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then **Save**.
5. After a minute or two, the site will be live at `https://<username>.github.io/<repo>/`.

No build step is required — this is a single static `index.html` with vendored Google Fonts loaded from a CDN.

## Files

- `index.html` — the complete single-page site (HTML, CSS, and JS inline).
- `images/` — organizer headshots (square, web-optimized JPEGs).

## Editing

- **Dates** live in the `#dates` panel inside `index.html`. The hero countdown reads the deadline from the `deadline` variable in the `<script>` block at the bottom — update both if the submission deadline changes.
- **Organizers** are the `.org` cards in the `#organizers` section. Each references an image in `images/`.
- **Program** rows are `.slot` elements in the `#program` section.

## Contact

shengdong.zhao@cityu.edu.hk
