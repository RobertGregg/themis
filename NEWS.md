# themis (development version)

# themis 0.2.0

## New steps

* `step_smotenc()` have been added to implement SMOTENC which can handle categorical as well as numerical values. Thanks to @RobertGregg (#82)

## Improvements and Other Changes

* export `nearmiss()` functions to users.
* Update examples to no longer use `iris` or `okc` data sets.
* All recipe steps now officially support empty selections to be more aligned with dplyr and other packages that use tidyselect (#55)

## Bug fixes

* `step_rose()` now correctly allows you to use characters variables. (#26)
* `step_tomek()` now ignore non-predictor variables when appropriate. (#51)
* Fix bug where wrong ordering of columns caused error in `smote()`. (#76)

# themis 0.1.4

* export `smote()`, `adasyn()`, and `bsmote()` functions to users.

# themis 0.1.3

* Steps that use nearest neighbors gives cleaner errors.

# themis 0.1.2

* tuneable steps now properly work with tune package.
* Steps now Retain original factor level ordering. (#22)
* Oversampling steps now ignore non-predictor variables when appropriate. (#20)

# themis 0.1.1

* `step_smote()` now work regardless of order of classes. Thanks to @sebastien-foulle for point it out #14.

# themis 0.1.0

* Added a `NEWS.md` file to track changes to the package.
