# Tutorials for MATH 4432 Statistical Machine Learning

## Course information

MATH 4432 Statistical Machine Learning

Instructor: Prof. YANG Can

Teaching assistants: HUANG Xinrui (xhuangcn@connect.ust.hk), CHEN Yuheng (ychenlp@connect.ust.hk)

This course is open to senior undergraduates in applied mathematics, statistics, and engineering who are interested in learning from data. It covers hot topics in statistical learning, also known as machine learning, featured with various applications.

## Tutorial files

* T01
  
The source files of the slides are `.Rmd` files. If you are interested in how to create slides through R Markdown, you can have a look at them.

To get a full view of the slides, I recommend you open the `.html` files (e.g., [introduction to jupyterlab.html](https://github.com/YangLabHKUST/MATH-4432-Statistical-Machine-Learning/blob/main/T01%20introduction/introduction%20to%20jupyterlab.html)) with your browser after downloading the entire repository. Typically this works best in Chrome.

I also provide the PDF version via John Paul Helveston and Garrick Aden-Buie's R package [renderthis](https://github.com/jhelvy/renderthis).

```r
renderthis::to_pdf(from = "filename.Rmd", complex_slides = TRUE, partial_slides = FALSE)
```

**However, the “complex” slides containing panelsets or other HTML widgets / advanced features might not render well as a PDF.**

## Reference

* [An Introduction to Statistical Learning: With Applications in R/Python](https://www.statlearning.com/). Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani.

## Acknowledgments

* The tutorial notes are modified and supplemented based on the materials from our "elder academic brother" (大师兄), Prof. CAI Mingxuan, CityU.
* Slides created via Yihui Xie's R package [xaringan](https://github.com/yihui/xaringan).
* Theme customized via Garrick Aden-Buie's R package [xaringanthemer](https://github.com/gadenbuie/xaringanthemer).
* Tabbed panels created via Garrick Aden-Buie's R package [xaringanExtra](https://github.com/gadenbuie/xaringanExtra/).
