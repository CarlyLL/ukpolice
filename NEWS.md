# ukpolice 0.0.0.9100 (2016-11-14)

## NEW FEATURES

* Add `ukp_crime_poly()`, which is like `ukp_crime()`, but takes multiple pairs of long/lat to extract crime that falls within a polygon, instead of within a one mile radius of a particular point
* Added unexported function `ukp_crime_unlist` which flattens the crime data.

# ukpolice 0.0.0.9002 (2016-11-05)

## NEW FEATURES

* Created `ukp_crime()`, which accesses the crimes that occur within one mile of a given latitude and longitude, and from a specific month
* Created function `ukp_last_update()`, to search for the last update in the crime data.
* Added pkgdown website for the package documentation

# ukpolice 0.0.0.9001 (2016-10-26)

## MINOR IMPROVEMENTS
* Changed all functions to have prefix `ukp_`, so `get_neighbourhoods` changed to `ukp_neighbourhood()`, and `ukpolice_api()` changed to `ukp_api()`, as suggested by @sckott in [issue #6](https://github.com/njtierney/ukpolice/issues/6).
* Added function `ukp_neighbourhood_force()`, to find associated neighbourhood forcename and neighbourhood ID.
* Added `...` option in `ukp_api()`, to facilitate debugging, as suggested by @sckott in [issue #7](https://github.com/njtierney/ukpolice/issues/7)

# ukpolice 0.0.0.9000 (2016-10-25)

## NEW FEATURES
* Added a `NEWS.md` file to track changes to the package.
* Added the `get_neighbourhoods` function.

<!--NEW FEATURES, MINOR IMPROVEMENTS, BUG FIXES, DEPRECATED AND DEFUNCT -- >
