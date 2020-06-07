![wip](https://img.shields.io/badge/-WIP-yellow) ![vale](https://img.shields.io/badge/Vale-&ge;v2.2.0-blue) ![license](https://img.shields.io/badge/License-MIT-green)

# The Writer for Vale

An attempt to implement [the Writer style guide](http://www.thewriter.com/what-we-think/style-guide/) as a set of rules for [Vale](https://errata-ai.gitbook.io/vale/).

> A work in progress.
> Tested and verified with Vale 2.2.0.

Copy **TheWriter** folder to your `StylesPath`, and include it in the Vale config file.

```ini
# Example Vale config file (`.vale.ini` or `_vale.ini`)

# Path to Vale styles relative to this config file
StylesPath = .

# Minimum alert level to show, and break the CI build
MinAlertLevel = suggestion

# Global settings (applied to every syntax)
[*]
BasedOnStyles = TheWriter
```
