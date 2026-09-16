# Junteng Liu — Academic Homepage

Personal academic website based on [Academic Pages](https://github.com/academicpages/academicpages.github.io). The upstream MIT license is retained in `LICENSE`.

## Content

- About, academic background, research experience, and research areas
- Six publications with author lists, years, and venues
- CV and scholarship
- Email, GitHub, Google Scholar, and X contact links

The hosting repository belongs to `onrueamt1593-pixel`; the academic GitHub profile saved in memory is `Vicent0205`. These are intentionally distinct.

## Editing

- `_config.yml`: identity, sidebar, social links, hosting URL, and base path
- `_data/navigation.yml`: navigation
- `_pages/`: About, Research, Publications, CV, Contact, and Sitemap
- `_data/publications.yml`: publication list used by the publications page and CV
- `_includes/personal-*.md`: shared education, experience, and research-area content
- `_data/cv.json`: structured CV; keep in sync with page content
- `images/junteng-monogram.svg`: initials graphic (not a portrait)

Template sample posts, publications, teaching, talks, portfolio, example pages, and sample downloadable files are excluded from the generated site. Their source is retained for reference.

## Information requiring confirmation

Content is populated from saved memory, not a fresh external verification.

- The outdated 'first-year' description has been omitted. The saved Ph.D. dates are 2024–present.
- The MINIMAX internship started February 2025 and was last recorded as ongoing. Its end date is unconfirmed and is labeled accordingly.
- Publication venues reflect memory: two arXiv preprints in 2025, EMNLP and ICML papers in 2024, and two NeurIPS papers in 2023.
- Exact paper URLs, DOI/arXiv IDs, code repository URLs, and publication month/day values are not stored; none were invented.
- No programming languages, software frameworks, languages spoken, or proficiency levels were recorded. The site lists documented research areas rather than unverified technical skills; the JSON CV's skills array remains empty.
- No portrait, phone number, street address, or downloadable personal CV was recorded.

## Preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000/LJT-Homepage/`. Restart Jekyll after editing `_config.yml`.

## GitHub Pages

Configuration targets `https://onrueamt1593-pixel.github.io/LJT-Homepage/` using:

```yaml
url: "https://onrueamt1593-pixel.github.io"
baseurl: "/LJT-Homepage"
```

To publish with GitHub's branch-based Jekyll build, go to **Settings → Pages**, choose **Deploy from a branch**, and select **master / (root)**. Saving content does not itself confirm that Pages is enabled or that deployment succeeded.
