# Bilbao News

Dark installable PWA for a daily Bilbao/Bizkaia digest in Russian.

The site is deployed by GitHub Actions to GitHub Pages. The workflow rebuilds the digest every day from public RSS feeds and Open-Meteo, so the repository does not need a new manual release for each daily update.

Expected Pages URL:
https://aerotsunami.github.io/bilbao-news/

## How updates work

- `push` to `main` deploys immediately.
- `schedule` runs every day at 05:30 UTC, which is 07:30 in Bilbao during summer time and 06:30 during winter time.
- News cards are short self-contained Russian summaries with a source link.
- Weather and rain are shown separately.
- Events and attention items are separated from general news.

If GitHub asks for Pages source, choose **GitHub Actions** in repository settings.
