# Maho releases

This repository exists to be fetched by a program. It holds the update feed for
[Maho](https://github.com/wuwuwu/maho), a macOS manga reader, and the archives that feed points at.

- **[`appcast.xml`](appcast.xml)** — the Sparkle feed. Every installed copy of Maho reads it from
  `https://wuwuwu.github.io/maho-releases/appcast.xml`, which is this file served by GitHub Pages.
- **[Releases](../../releases)** — one per version, holding the `.zip` the updater downloads, the
  `.dmg` a person installs from the first time, and a source tarball.

The source tarball is not ceremony. Maho links vendored code from
[Suwayomi-Server](https://github.com/Suwayomi/Suwayomi-Server) under the MPL-2.0, and MPL asks that
the source of those files be available to whoever receives a binary built from them. A tarball beside
each release is that, until the main repository is public.

Maho itself is not developed here and issues filed here will not be seen. The app is at
[wuwuwu/maho](https://github.com/wuwuwu/maho).
