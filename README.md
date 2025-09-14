# Tutorials for MATH 4432 Statistical Machine Learning

## Course information

MATH 4432 Statistical Machine Learning

Instructor: Prof. YANG Can

Teaching assistants: CHEN Yuheng (ychenlp@connect.ust.hk), LIU Yuyao (yliuow@connect.ust.hk)

This course is open to senior undergraduates in applied mathematics, statistics, and engineering who are interested in learning from data. It covers hot topics in statistical learning, also known as machine learning, featured with various applications.

## Tutorial files

* T02

For Python:

The source files are `.ipynb` files. And the corresponding `.html` files are provided. 

For R:

The source files of the slides are `.Rmd` files in the `R version` folders for R. If you are interested in how to create slides through R Markdown, you can have a look at them.

To get a full view of the slides, I recommend you open the `.html` files (e.g., [BiasVar.html](https://github.com/YangLabHKUST/MATH-4432-Statistical-Machine-Learning/blob/main/T02_Bias%20Variance%20Tradeoff/T02_R%20version/BiasVar.html)) with your browser after downloading the entire repository. Typically this works best in Chrome.

I also provide the PDF version via John Paul Helveston and Garrick Aden-Buie's R package [renderthis](https://github.com/jhelvy/renderthis).

```r
renderthis::to_pdf(from = "filename.Rmd", complex_slides = TRUE, partial_slides = FALSE)
```

**However, the “complex” slides containing panelsets or other HTML widgets / advanced features might not render well as a PDF.**

## Reference

* [An Introduction to Statistical Learning: With Applications in R/Python](https://www.statlearning.com/). Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani.

## Acknowledgments

* The tutorial notes are modified and supplemented based on the materials from our "elder academic brothers" (师兄们), Prof. CAI Mingxuan, CityU and WANG Zhiwei.
* Slides created via Yihui Xie's R package [xaringan](https://github.com/yihui/xaringan).
* Theme customized via Garrick Aden-Buie's R package [xaringanthemer](https://github.com/gadenbuie/xaringanthemer).
* Tabbed panels created via Garrick Aden-Buie's R package [xaringanExtra](https://github.com/gadenbuie/xaringanExtra/).
