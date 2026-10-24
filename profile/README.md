# wxylib

Rust crates that take the modular ideas inside GDAL (grids, georeferencing,
chunked reads, warping, virtual datasets), give each one its own small home,
and build on existing crates (async-tiff, zarrs, Icechunk, rwarp) rather
than replacing them. Every result is checked against GDAL, with a decision to match it or diverge (and/or contribute back).

**Early and pre-release:** nothing is published yet and APIs will change.

![The R0 to R6 raster-vector spectrum: one data model from a bare array to a table of features](https://raw.githubusercontent.com/wxylib/docs/main/img/spectrum.svg)

**Documentation: https://wxylib.org/docs/**, the one place for
everything below:

- [Start here](https://wxylib.org/docs/start.html): run `wxy` from a
  container or build it.
- [Capability map](https://wxylib.org/docs/capabilities.html): what
  works, what is planned.
- [How-tos](https://wxylib.org/docs/vignettes/README.html) and
  [explainers](https://wxylib.org/docs/explainers/index.html).
- [Live demos](https://wxylib.org/docs/demos.html): warping COGs in
  the browser.
- [Gaps and contributing](https://wxylib.org/docs/contribute.html).

Repositories: [design](https://github.com/wxylib/design),
[core](https://github.com/wxylib/core),
[fixtures](https://github.com/wxylib/fixtures),
[docs](https://github.com/wxylib/docs),
[py](https://github.com/wxylib/py), [r](https://github.com/wxylib/r),
[web](https://github.com/wxylib/web),
[images](https://github.com/wxylib/images).
