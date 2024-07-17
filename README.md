# BigCare2024

![Building the site](https://github.com/seandavi/2024-r-intro-bigcare/actions/workflows/build_site.yaml/badge.svg)

This repository contains the code for the website for the [BigCare 2024](https://bigcare.uci.edu/) course.

- <https://seandavi.github.io/2024-r-intro-bigcare/>

To install the required packages, run the following code:

```{r}
install.packages('BiocManager')
BiocManager::install('remotes')
BiocManager::install('seandavi/2024-r-intro-bigcare')
```


## local development

To build the website locally, run the following code:

```
quarto render
```

To build the website and serve it locally, run the following code:

```
quarto preview
```

To publish the website to GitHub pages, run the following code:

```
quarto publish
```