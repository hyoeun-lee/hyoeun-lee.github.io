# hyoeun-lee.github.io

Personal academic website of Hyoeun Lee, served by GitHub Pages at
<https://hyoeun-lee.github.io>.

Plain HTML and CSS, no build step. Edit a file, commit to `main`, and the site
updates within a minute or two.

| File            | Content                                      |
|-----------------|----------------------------------------------|
| `index.html`    | About, contact, research interests           |
| `research.html` | Publications, conference and invited talks   |
| `teaching.html` | Courses and student mentoring                |
| `cv.html`       | Education, appointments, fellowships         |
| `style.css`     | Shared styling for all pages                 |

## Common updates

- **Photo:** add `images/profile.jpg` (square, at least 400×400). It appears on
  the home page automatically.
- **CV PDF:** add `files/CV_HyoeunLee.pdf`, then uncomment the download link
  at the top of `cv.html`.
- **New paper or talk:** copy an existing `<li>...</li>` block in
  `research.html` and edit the text.
- **Preview locally:** run `python3 -m http.server` in this folder and open
  <http://localhost:8000>.
