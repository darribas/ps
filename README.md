# `PS` - Population Science in R

- [Francisco Rowe](http://www.franciscorowe.com/)
- [Fran Darlington-Pollock]()

Book site: https://fcorowe.github.io/ps/

This is a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown). 

Please see the page "[Get Started](https://bookdown.org/yihui/bookdown/get-started.html)".

Build website
> bookdown::render_book('index.Rmd', 'bookdown::gitbook')

Build pdf
> bookdown::render_book('index.Rmd', 'bookdown::pdf_book')

Build ebook
> bookdown::render_book("index.Rmd", "bookdown::epub_book")

For Tufte static:
> bookdown::render_book("index.Rmd", "bookdown::tufte_html_book")

Compile pdf
> bookdown::render_book('index.Rmd', bookdown::pdf_book(keep_tex = TRUE))

More detailed instructions are available here https://bookdown.org/yihui/bookdown/build-the-book.html.

