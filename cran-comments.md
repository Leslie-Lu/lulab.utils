## lulab.utils 1.0.2

This release restores `Table1()` and updates it for the current `table1`
rendering API, avoiding the deprecated `render.strat.default()` function.

It also stabilizes tests with network or interactive side effects and updates
the package metadata, documentation, and dependency lockfile.

## Test environments

- Local Windows 11, R 4.6.0

## R CMD check results

- `R CMD check --as-cran --no-manual lulab.utils_1.0.2.tar.gz`: OK
- Full `R CMD check --as-cran lulab.utils_1.0.2.tar.gz` passed all checks up
  to `checking PDF version of manual`, then exceeded the local 10-minute
  command timeout.
