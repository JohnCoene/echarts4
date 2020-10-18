## Test environments
* OS X R 4.0.3, devel (local + github actions)
* ubuntu 14.04 (on travis-ci) and 16.04 (on github-actions), R 4.0.3, ubuntu 18.04 (local) R 4.0.3
* win-builder (devel and release) - `devtools::check_win_*`
* `rhub::check_for_cran` `devtools::check_rhub`

## R CMD check results

0 errors | 0 warnings | 0 note

>   Found the following (possibly) invalid URLs:
>     URL: http://echarts4r-assets.john-coene.com/ (moved to
>https://echarts4r-assets.john-coene.com/)
>       From: NEWS.md
>       Status: 200
>       Message: OK

Fixed
