# brianpitre.github.io

An index of every public GitHub Pages site on this account, at
**https://brianpitre.github.io** — one link, with instant filtering.

## Heads up before sharing that link

The page is served with `noindex, nofollow` **on purpose**. Several of the sites
it links to are themselves `noindex` because they carry personal details — crew
phone numbers and emails, a home address, flight numbers. Those sites are still
publicly reachable by URL; `noindex` only keeps them out of search results. An
index that gathers all of them in one place is exactly the thing not to post
publicly. Keep the robots meta.

## Editing

`index.html` here is **generated** — do not edit it directly.

The source lives in `Desktop/AI/GitHub Pages Index/index.html` (authored for the
Claude Artifact publisher, which supplies its own doctype/head/body). To update:

```
cd "Desktop/AI/GitHub Pages Index"
python3 build_site.py                  # writes site/index.html
cp site/index.html <clone>/index.html
git commit -am "..." && git push
```
