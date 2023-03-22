# The Writer for Vale

![WIP][ii01] ![Vale][ii02] ![License][ii03]

An attempt to implement [the Writer style guide][li01] as a set of rules for [Vale][li02].
For the style coverage, see [Scope][li03].

> A work in progress.
> Tested and verified with Vale 2.24.0.

Copy **TheWriter** and **Vocab** folders to your `StylesPath`, and include them in the Vale configuration file.

```ini
; Vale configuration file (`.vale.ini`)

StylesPath = path/to/style

Vocab = TheWriterNames

MinAlertLevel = suggestion

[*]
BasedOnStyles = Vale, TheWriter
```

[li01]: https://www.thewriter.com/tools/style-guide
[li02]: https://vale.sh/
[li03]: Scope.md

[ii01]: https://img.shields.io/badge/-WIP-yellow
[ii02]: https://img.shields.io/badge/Vale-2.24.0-blue
[ii03]: https://img.shields.io/badge/License-MIT-green
