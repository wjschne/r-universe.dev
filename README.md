# W. Joel Schneider's R Package Universe

https://wjschne.r-universe.dev/ui#builds

To install packages from this universe, use

```r
# Enable this universe
options(repos = c(
    wjschne = 'https://wjschne.r-universe.dev',
    CRAN = 'https://cloud.r-project.org'))

# Install some packages
install.packages('wjschne')
```

