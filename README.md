# iacoley.github.io
It's my website

iancoley.org

## Building

Source lives in `src/` on the [`redesign/eleventy-mockup`](https://github.com/iacoley/iacoley.github.io/tree/redesign/eleventy-mockup)
branch, built with [Eleventy](https://www.11ty.dev/). `main` holds the
built static output that GitHub Pages actually serves (legacy branch-based
Pages, no build step on GitHub's side).

To ship an edit:

```
git checkout redesign/eleventy-mockup
# edit files under src/
npx eleventy          # writes ./_site
# copy _site/ contents over to a checkout of main, commit, push
```
