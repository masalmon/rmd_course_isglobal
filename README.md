RMarkdown course ISGlobal
=========================

In this course (note: language to be decided based on the audience), we will learn how to use RMarkdown, a powerful reporting tool in R. Instead of copy-pasting tables, figures, number of patients into Word documents, you will be able to embed the corresponding code directly in your report.

We will prepare a scientific manuscript together, including citations. We will also discuss collaboration for manuscripts written in RMarkdown.

Producing a .docx/.pdf is only one of the many things you can do with RMarkdown. Based on the RMarkdown knowledge adquired in this course, you should be able to start exploring other RMarkdown outputs. We will have a look at `reveal.js` which is a framework for producing slides. 

All course material will live in this repository, and you're welcome to open issues.

# How much do I need to know about R?

You just need to know that R exists, how to load data into R, and for instance do a linear regression with R. Don't hesitate to contact me via maelle dot salmon at yahoo dot se if you're not too sure about whether you should come.  

We are not going to write any advanced code in the chunks, and starting to learn RMarkdown could be of the first steps of your R journey.

# What should I install before coming to the course?

You will need

* [R](https://cran.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/download/)

* the `rmarkdown` package (`install.packages("rmarkdown")`)

* the `broom` package (`install.packages("broom")`)

* the `revealjs` package (`install.packages("revealjs")`)

* the `citr` package (`install.packages("citr")`)

* A tex installation (for pdf output), see https://www.latex-project.org/get/

Don't hesitate to send me an email or come to my office (campus Mar, sala B) if you have any installation issue.

# What is in this repository?

* At some point I'll add the data/bibliography file.

* The slides although I doubt I'll make too many slides, we'll be too busy coding for looking at slides.

* The RMarkdown we'll prepare together (I'll live code).


# Further resources

* RStudio RMarkdown [website](http://rmarkdown.rstudio.com/)

* The link to the RStudio RMarkdown [cheatsheet in English](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf) and [in Spanish](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-spanish.pdf) I'll also have printed for you and give to you after the course

* This paper ["Good enough practices for scientific computing"](https://arxiv.org/pdf/1609.00037v2.pdf) is full of useful tips and won't make you feel bad for not doing everything _perfectly_. 

* This [Coursera course](https://es.coursera.org/learn/reproducible-research) about reproducible research is great.

* Collaboration and version control can be made easier by git and Github. You can have a look at [this tutorial](http://happygitwithr.com/) from Jenny Bryan and the chapter about git from [Hadley Wickham's R package book](http://r-pkgs.had.co.nz/git.html).

* There is a part about RMarkdown and a ton of useful stuff in [this book](http://r4ds.had.co.nz/) from Hadley Wickham and Garrett Grolemund.

# Other courses at ISGlobal

The material of the course from April 2016 about data wrangling in R with `dplyr` and `tidyr` lives [here](https://github.com/masalmon/domar_datos).