# How to use

* project runs on `renv` (ensures reproducibility, R packages often have breaking changes)
* to create a new article, execute `R> distill::create_article("articles/<name-of-article>.Rmd")`
* to render the site, execute `R> rmarkdown::render_site("articles")` -> site can be served from the `docs` directory
