# Taejun Yoon's personal website

A minimal, responsive academic homepage at <https://ytj0604.github.io/>.
The current site uses plain HTML and CSS, a dark palette, and the visitor's
system font. It requires no JavaScript, third-party requests, or build tools.

## Preview locally

From the repository root:

```sh
python3 -m http.server 4000 --bind 127.0.0.1
```

Open <http://localhost:4000>. Use the browser's Print command for the light,
print-friendly layout. The previous `/print` and `/print.html` routes redirect
to the homepage.

## Editing

- `index.html`: biography, contact links, publications, education, experience,
  teaching, and languages. Publication details come from the site owner;
  add a paper/DOI link when its public URL is available.
- `assets/css/site.css`: layout, colors, responsive breakpoints, and print styles.
- `assets/images/profile.png`: the owner's existing portrait, unchanged.
- `assets/favicon.svg`: original vector monogram.

The `.nojekyll` file tells GitHub Pages to serve the static files directly.
Publish through the repository's existing GitHub Pages branch configuration.
No dependency installation or bundler is needed.

## Design and attribution

The renewed HTML, CSS, and monogram were written specifically for this site.
Sangoh Lee's and Sungho Park's homepages informed the broad dark academic-page
direction; none of their code, text, images, fonts, or other assets were copied.
Fonts are resolved locally (`-apple-system`, `BlinkMacSystemFont`, `Segoe UI`,
`Helvetica Neue`, Arial, sans-serif); no Apple font files are redistributed.

The repository historically used the Orbit template by Xiaoying Riley at
[3rd Wave Media](https://themes.3rdwavemedia.com/), adapted to Jekyll by
[webjeda / sharu725](https://github.com/sharu725/online-cv).
Legacy `_layouts`, `_includes`, `_sass`, `_data`, Ruby configuration, and
vendor assets remain for provenance. They are not used by the renewed homepage.
Their original attribution and embedded license notices remain intact.
The new design does not load the old theme, analytics, Bootstrap, jQuery,
Font Awesome, or externally hosted fonts.
