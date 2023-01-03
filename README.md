# autosd-content-resolver

A private fork of the AutoSD content-resolver views.

## About

This project exists to simply run content-resolve manually ahead of the
scheduled nightly job so the upcoming dependency tree for AutosD can be
inspected.

A GitHub action workflow is attached to this repository that launches a Fedora
container, executes [content-resolver][0] and outputs the resulting pages.

The config files are scraped directly from the original
[content-resolver-input][1] repository.

[0]: https://github.com/minimization/content-resolver
[1]: https://github.com/minimization/content-resolver-input/tree/main/configs
