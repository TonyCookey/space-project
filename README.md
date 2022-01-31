# Kepler Space Project

A basic NodeJS CSV Parser utilizing the Kepler Space Research Data to find out habitable planets. Utilizing the

- `csv-parse` package
- `fs` package
- using ReadStream method from the `fs` package to read the csv data row by row
- method to find habitable planets using `koi_disposition`, `koi_insol` and the `koi_prad` parameters to ensure it is a habitable planet
