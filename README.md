# catsplainr

### What is catsplainr?

**catsplainr** makes a cat translate S3 objects into text using standard templates in a simple and convenient way.

For help with the **catsplainr** R-package, there is a vignette available in the /vignettes folder.

# Installation

The package can be installed with

    devtools::install_github("hilaryparker/catsplainr")

After installation, the package can be loaded into R.

    library(catsplainr)

# Using catsplainr

The main function in the **catsplainr** package is `catsplain()`.

```
prop.test(x = 500, n = 1008) %>%
    catsplain()
```

# Bug reports
Report bugs as issues on the [GitHub repository](https://github.com/hilaryparker/catsplainr)

# Contributors

* [Hilary Parker](https://github.com/hilaryparker)
* [David Robinson](https://github.com/dgrtwo)
* [Stephanie Hicks](https://github.com/stephaniehicks)
* [Roger Peng](https://github.com/rdpeng)
