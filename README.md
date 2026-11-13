# assertive.base

A lightweight core of the assertive package: predicates and assertions for run-time testing in other packages.

Compatibility updates by Renova.

Version 0.0.9.9001 turns Rd cross-references to the uninstalled packages `assertive.properties` and `assertive.types` into plain text, reformats the `NEWS` file into R's NEWS format, and removes the stale optional `Date` field. No R function was changed.

## Install

```r
install.packages("assertive.base", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/assertive.base@renova-0.0.9.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

assertive.base is by Richard Cotton (maintainer), with translations by Sunkyu Choi, Ivanka Skakun, Gergely Daróczi, Anton Antonov, Hisham Ben Hamidane, Anja Billing, Aditya Bhagwat, Rasmus Bååth, Mine Cetinkaya-Rundel and Aspasia Chatziefthymiou; the original project is at <https://bitbucket.org/richierocks/assertive.base>. License: GPL (>= 3); see [COPYING](COPYING).
