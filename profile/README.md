# wxylib

Rust crates that take the modular ideas inside GDAL (grids, georeferencing,
chunked reads, warping, virtual datasets), give each one its own small home,
and build on existing crates (async-tiff, zarrs, Icechunk, rwarp) rather
than replacing them. Every result is checked against GDAL, and must match
it exactly.

**Early and pre-release:** nothing is published yet and APIs will change.

![The R0 to R6 raster-vector spectrum: one data model from a bare array to a table of features](https://raw.githubusercontent.com/wxylib/docs/main/img/spectrum.svg)

- **Start here:** [intro page](https://github.com/wxylib/docs#readme):
  what works, what the tests check, how to get involved.
- **Try it on real data:** [a month of OISST as virtual Zarr](https://github.com/wxylib/docs/blob/main/oisst-virtual.md).
- [design](https://github.com/wxylib/design): design documents and roadmap.
- [core](https://github.com/wxylib/core): the Cargo workspace and the `wxy`
  command.
- [fixtures](https://github.com/wxylib/fixtures): test files and GDAL oracle
  outputs.
- [py](https://github.com/wxylib/py) and [r](https://github.com/wxylib/r):
  early Python and R bindings.
