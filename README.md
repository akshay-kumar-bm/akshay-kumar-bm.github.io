# akshay-kumar-bm.github.io

Archived GitHub Pages site. My portfolio has moved to [akshaykumarbm.tech](https://www.akshaykumarbm.tech).

## What it is now
`index.html` and `404.html` are tiny redirect pages: a zero-delay `meta refresh` plus `rel="canonical"` and `noindex` to consolidate search authority on the new domain (GitHub Pages cannot issue a real 301). The pages carry inline styling in the site's paper/ink/emerald palette and a short fallback link.

## History
The previous static portfolio (HTML, CSS, vanilla JS with project images, skills icons and certificate images) is preserved in the repository's git history only; the working tree no longer contains it.

## Structure
```
index.html   # redirect + fallback content
404.html     # same redirect for unknown paths
README.md
```

## Limitations
Redirect only; nothing to run or build.
