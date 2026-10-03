# Makeshift web deployment

This repository contains generated GitHub Pages output only. Application source,
builds, tests and the manual **Release web mode** workflow live in
[osuushi/makeshift](https://github.com/osuushi/makeshift).

The release workflow publishes tested files to `gh-pages` using a dedicated deploy
key. Pages serves that branch from `/`. Do not add a second site-building workflow
here. The first app deployment follows the first web release from the main repository.
