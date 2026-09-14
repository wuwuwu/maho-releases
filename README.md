# Maho releases

This repository exists to be fetched by a program. It holds the update feed for
[Maho](https://github.com/wuwuwu/maho), a macOS manga reader, and the archives that feed points at.

- **[`appcast.xml`](appcast.xml)** — the Sparkle feed. Every installed copy of Maho reads it from
  `https://wuwuwu.github.io/maho-releases/appcast.xml`, which is this file served by GitHub Pages.
- **[Releases](../../releases)** — a single `archives` tag holding every version's `.zip`, the
  `.dmg` a person installs from the first time, and the deltas between adjacent versions. One tag
  rather than one per version because the feed carries a single download prefix for every enclosure
  in it, so the prefix has to be a constant.
- **`Maho-<version>.md`** — the release notes for each version, which the feed links to and the
  update window shows before anybody agrees to install anything. `.nojekyll` is here so that Pages
  serves those files as they were written instead of building a site out of them.

Maho itself is not developed here and issues filed here will not be seen. The app is at
[wuwuwu/maho](https://github.com/wuwuwu/maho).
