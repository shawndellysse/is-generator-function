1.0.4 / 2015-03-03
=================
  * Add support for concise generator methods (#2) This is a patch change since concise methods are not in any actual released engines yet.
  * Test on latest `io.js`
  * Update `semver`

1.0.3 / 2015-01-31
=================
  * Speed up travis-ci tests
  * Run tests against a faked @@toStringTag
  * Bail out early when typeof is not "function"

1.0.2 / 2015-01-20
=================
  * Update `jscs`, `tape`
  * Fix tests in newer v8 (and io.js) where Object#toString.call of a generator is GeneratorFunction, not Function

1.0.1 / 2014-12-14
=================
  * Update `jscs`, `tape`
  * Tweaks to README
  * Use `make-generator-function` in tests

1.0.0 / 2014-08-09
=================
  * Initial release.
