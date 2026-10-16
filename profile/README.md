# wxylib

Rust crates that take the modular ideas inside GDAL (grids, georeferencing,
chunked reads, warping, virtual datasets), give each one its own small home,
and build on existing crates (async-tiff, zarrs, Icechunk, rwarp) rather
than replacing them.

**Early and pre-release:** nothing is on crates.io yet and APIs will change.
Today it reads GeoTIFF/COG, Zarr and Icechunk virtual references byte for
byte as GDAL does, and `wxy warp` warps them to GeoZarr.

![wxy warp: plan, then fetch, then warp](https://raw.githubusercontent.com/wxylib/docs/main/img/pipeline.svg)

- **Start here:** [intro page](https://github.com/wxylib/docs#readme): what
  works, what the tests check, how to get involved.
- [design](https://github.com/wxylib/design): design documents and roadmap.
- [core](https://github.com/wxylib/core): the Cargo workspace.
- [fixtures](https://github.com/wxylib/fixtures): test files and GDAL oracle
  outputs.
  
