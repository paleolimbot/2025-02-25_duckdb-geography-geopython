#  duckdb-geography: Global vector data in DuckDB

*duckdb-geography introduces a "geography" type optimized for global vector geometry to DuckDB powered by Google's S2Geometry library.*

DuckDB's spatial extension is an excellent wrapper around the planar spatial libraries that underpin the modern open source GIS stack. These libraries are well-suited to planar geometry; however, workarounds are required for global datasets that include polar regions and/or straddle the antimeridian. Google's S2Geometry library (http://s2geometry.io/) provides a robust mathematical basis for spherical operations on the sphere and its C++ implementation is well-suited to wrapping as a DuckDB extension. Using the basis for the spatial data science-focused s2 package for R (https://github.com/r-spatial/s2) and the Spherely package for Python (https://github.com/benbovy/spherely), this talk will showcase the process and result of porting a collection of vectorized geospatial geometry operations to DuckDB.

