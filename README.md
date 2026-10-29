# Inkwell Sources

Data-only website definitions for the personal Inkwell novel reader. This repository contains no app code, novel text, account credentials, or saved libraries.

## Install on your phone

In Inkwell, open Browse → Sources → Add repository link and enter:

`https://github.com/Tran-Steven/Inkwell-Sources`

Build 5 follows this feed for its bundled sources automatically. Newly published sources still require selecting them in the repository preview. Source updates preserve saved books, chapter identities, downloads, collections, and reading progress.

Direct feed: [inkwell-repository.json](https://raw.githubusercontent.com/Tran-Steven/Inkwell-Sources/main/inkwell-repository.json).

## If a website breaks

Use Settings → Updates & repair → Check for source updates. If a fix is unavailable, prepare a source report and attach it to a new issue here. Review the report before posting; avoid sharing your library backup, account details, cookies, or chapter text. Reports are not uploaded automatically.

A maintainer must repair and test the definition, increase its version, and commit the new manifest. The phone can then download the fix without a new IPA. Rollback is available in Inkwell if a definition update causes trouble. Website changes requiring a new parser or login capability still need an app update.

## Supported definitions

The manifest currently includes LightNovel.to, NovelFire, DasuiTL, Skythewood Translations, JadeScrolls, Webnovel, and a retired LightNovelWorld entry. Each website can change or restrict access. Locked/paid previews are never treated as complete chapters.

Extension files contain configuration, not executable scripts. Schema 4 (including JadeScrolls title-plus-genre search) requires Inkwell build 4 or newer. Increase each changed source's version; keep existing IDs and canonical chapter URLs stable. Native app tests and the in-app Test source action remain necessary in addition to this repository's basic JSON checks.
