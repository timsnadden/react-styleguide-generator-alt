# 2.0.5 (2015-11-24)

  * Fix major bug as a result of renaming the package from fork

# 2.0.0 (2015-11-24)

  * First alt version, forked from `react-styleguide-generator`
  * Removed `browserify` and replaced with `webpack` + hot module replacement
  * Complete overhaul of the core `rsg.js` lib to support `webpack`
  * `react-docgen` generation and asset distribution moved to custom webpack plugins
  * Fixed a bug where using input text boxes and typing into them will shift focus to the search box
