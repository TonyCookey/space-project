# Kepler Space Project

A basic NodeJS CSV Parser utilizing the NASA Exoplanet Archive Data to find out habitable planets. Utilizing the following

- `csv-parse` package
- `fs` package
- using ReadStream method from the `fs` package to read the csv data row by row
- method to find habitable planets using `koi_disposition`, `koi_insol` and the `koi_prad` parameters to ensure it is a habitable planet


Link to the NASA Exoplanet Archive:  https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=cumulative
