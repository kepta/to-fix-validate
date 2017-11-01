[![Build Status](https://travis-ci.org/mapbox/to-fix-validate.svg?branch=master)](https://travis-ci.org/mapbox/to-fix-validate)

  Vist [to-fix-schema/docs](https://github.com/mapbox/to-fix-internal/blob/master/DOCS.md) about the to-fix schema.
# to-fix-validate

Exposes a function to validate FeatureCollections sent to the to-fix backend, enforcing the `properties` schema.

Currently exposes a single function called `validateFeatureCollection` that returns `false` if no errors, else an Array of strings with error messages.
