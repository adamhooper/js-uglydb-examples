Examples
========

This directory contains a few examples, to see what kind of space savings we can achieve using [UglyDB JSON format](https://github.com/adamhooper/js-uglydb).

Regenerate it using `grunt rebuild-examples` from the parent directory.

Each example consists of several files:

* A source description (`filename.SOURCE`)
* A plain JSON file, pretty-printed. (`filename.json`)
* A minified JSON file (whitespace removed). (`filename.min.json`)
* A CSV file, with all non-String, non-Number values derived by calling `JSON.stringify()` on them. (`filename.csv`)
* An UglyDB file. (`filename.uglydb.json`)
* All four files, gzipped with `-9` (best compression) (`filename.json.gz`, `filename.min.json.gz`, `filename.csv.gz`, `filename.uglydb.json.gz`)

This should give you some idea of what UglyDB can achieve.
