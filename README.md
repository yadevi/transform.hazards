# transform.hazards

```R``` package for transforming cumulative hazard estimates to obtain a range of parameters in survival analysis<sup>[1](#transforming)</sup>.

## Getting Started


### Installing

Make sure to have the ``devtools`` package installed. Then run

```
devtools::install_github("palryalen/transform.hazards", build_vignettes=TRUE).
```
You can also download the source from this page and build the package manually.

<font color="red">NB! With devtools 2.0.0, devtools::install_github("repository", build_vignettes = TRUE) no longer builds the vignettes. In that case, use the following command:</font>

```
devtools::install_github("palryalen/transform.hazards", build_opts = c("--no-resave-data", "--no-manual")).
```

### Vignette
A detailed vignette with worked examples on how to utilize the package can be found using the command ``` browseVignettes("transform.hazards") ```

NB! The vignette doesn't compile properly for some R versions (e.g 3.2.3). I am currently looking into the issue.
## Examples

```
browseVignettes("transform.hazards")

library(transform.hazards)

example(pluginEstimate)
```

## Versioning

We use [SemVer](http://semver.org/) for versioning.

## Authors

* **Pål Ryalen**

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) licence. You are therefore [free to](https://creativecommons.org/licenses/by-nc/4.0/)

* Share — copy and redistribute the material in any medium or format.

* Adapt — remix, transform, and build upon the material.


## References




<a name="transforming">1</a>: Pål Ryalen, Mats Stensrud, Kjetil Røysland, [*Transforming cumulative hazard estimates*](https://arxiv.org/abs/1710.07422v3)

<!---
<a name="additive_consistent">2</a>: Pål Ryalen, Mats Stensrud, Kjetil Røysland, [*The additive hazard estimator is consistent for continuous time marginal structural models*](https://arxiv.org/abs/1802.01946)
-->

