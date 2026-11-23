# cataScience in your browser

[Open the cat café classroom in English](https://shanlong-who.github.io/cata/?lang=en) or [open it in Simplified Chinese](https://shanlong-who.github.io/cata/?lang=zh). The [original Lao workshop link](https://shanlong-who.github.io/cata/classic/) opens the same classroom. Bookmarks with a language preference keep it.

Load the two cat tables, check the source measurements, record a correction and join the tables by ID. The charts follow the current analysis values. Compare group counts and percentages or inspect individual weights alongside group means. Add a finding and a limitation to download a one-page HTML report.

The app runs R in the browser. Uploaded data stay on the device. The first visit downloads the runtime and R packages. You can switch between English and Chinese in the classroom without losing your work. The optional kNN exercise uses the local R app with the VIM package.

[English guide](https://shanlong-who.github.io/cataScience/) · [中文指南](https://shanlong-who.github.io/cataScience/zh/) · [R package source](https://github.com/shanlong-who/cataScience)

## Updating the deployment

Run the **Build the Shinylive classroom** workflow in the source repository. Its `cataScience-shinylive` artifact contains the site built by `pkgdown/build-shinylive.R`. Check the source commit in `build-info.json`, the shared classroom, language switching and the legacy link before publishing.

The package's MIT licence and image attribution apply to the app sources. Shinylive, webR and bundled R packages retain their respective licences.

Maintainer: Shanlong Ding, dings@who.int
