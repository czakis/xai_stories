# XAI Stories. Case studies for eXplainable Artificial Intelligence

ebook: https://pbiecek.github.io/xai_stories/


Machine learning has a number of applications. Very often, however, machine learning predictive models are treated as black boxes which can be automatically trained without worrying about the domain in which they are used.

The development of XAI tools allows to x-ray these black boxes. In the following chapters, we show example applications of different XAI techniques to real-world problems.

## How this book came about

This book is the result of a student projects for [Interpretable Machine Learning](https://github.com/pbiecek/InterpretableMachineLearning2020) course at the University of Warsaw and the Warsaw University of Technology. Each team has prepared one case study for selected XAI technique.

This project is inspired by a fantastic book [Limitations of Interpretable Machine Learning Methods](https://compstat-lmu.github.io/iml_methods_limitations/) done at the Department of Statistics, LMU Munich.
We used the LIML project as the cornerstone for this repository.

## How to build the book

Step 1: Clone or download the repository https://github.com/pbiecek/xai_stories.

Step 2: Install dependencies

```
devtools::install_dev_deps()
```

Step 3: Render the book (R commands)

```{r}
bookdown::render_book('./', 'bookdown::gitbook')
```

