# GNS

The GNS news website: America's Number One Source for News.

The whole site is one self-contained file, `index.html`. Every article and photo is built into it, so it needs no server, build step or other files. Open it in a browser, or host it with GitHub Pages.

## Sections

U.S., Politics, Global Affairs, Elections, Business, Opinion, Editorial Pieces, Cartoons and GNS Weekly. Each article has its own page, and the search button looks through every story.

## Publishing with GitHub Pages

In this repository's **Settings → Pages**, set the source to the `main` branch and the root folder. The site will be live at `https://glennbourbon7-web.github.io/gns/`.

## GNS Weekly

Like Newsweek, GNS puts out a weekly magazine cover. The newest cover sits at the top of the front page, and every past issue is under **Weekly** (`#/weekly`).
To add an issue: put the cover image in `IMAGES`, add its cover story to `ARTICLES`, and add one line to the top of `ISSUES` with the date, the cover image key, the headline and the cover story's slug.
