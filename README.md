# Modelling with `tidymodels`

## Summary

This repository provides materials for a session that is part of the [I2DS Tools for Data Science workshop](https://github.com/intro-to-data-science-24-workshop) run at the [Hertie School, Berlin](https://www.hertie-school.org/en/) in October 2024. The student-run workshop is part of the course [Introduction to Data Science](https://github.com/intro-to-data-science-24) taught by Simon Munzert at the Hertie School, Berlin, in Fall 2024.

### Session contents

This session will introduce you to the powerful `tidymodels` framework in `R`, which streamlines the modeling process in data science.

We'll begin by exploring `recipes`, a package that simplifies the pre-processing and feature-engineering of data.

Next, we will dive into `rsample`, which provides robust tools for data splitting and offers several distinct sampling strategies (we will discuss v-fold cross-validation, bootstrapping and rolling forecasting origin methods).

Moving on to modeling, we'll introduce `parsnip`, which standardizes the interface for creating and tuning models across different algorithms.

Finally, we will focus on `yardstick`, which provides a suite of functions for evaluating model performance.

### Main learning objectives

The goals of this session are to (1) equip you with conceptual knowledge about the `tidymodels` package and its usage in the whole regression modeling workflow, (2) show you the key sub-packages like `rsample`, `recipes`, `parsnip` and `yardstick`, and (3) provide you with practice material as well as some further readings.


## Tutorial

The session is accompanied by a tutorial, which can be accessed [here](https://github.com/intro-to-data-science-24-workshop/12-tidymodels-tetteroo-hagemann-berdiyeva/blob/main/practice/12-tidymodels-lab.html).

> [!IMPORTANT]  
> If you are planning on attending the live-session of the workshop, please make sure to have the practice material ready before the session. As you will need our `.RData` file, cloning this repository is the easiest way to do so. In the best case, you will also make sure to install the `tidymodels` package before the beginning of the session.


## Instructors

- Franka Tetteroo ([GitHub](https://github.com/FMTetteroo))
- Linus Hagemann ([GitHub](https://github.com/linusha))
- Sofiya Berdiyeva ([GitHub](https://github.com/sophiyaberdiyeva))


## Further resources

- Website of the [`tidymodels`](https://www.tidymodels.org/) package, including documentation, examples and guides
    - `tidymodels` consists of many more packages than we could cover in this session!
- [Tidy Modelling with R](https://www.tmwr.org/)
- [Get started with tidymodels and classification of penguin data by Julia Silge](https://www.youtube.com/watch?v=z57i2GVcdww)
- [tidymodels: Adventures in Rewriting a Modeling Pipeline - posit::conf(2023)](https://www.youtube.com/watch?v=R7XNqcCZnLg)
- [A Gentle Introduction to tidymodels](https://rviews.rstudio.com/2019/06/19/a-gentle-intro-to-tidymodels/)
- [Tidymodels Ecosystem Tutorial](https://rpubs.com/chenx/tidymodels_tutorial)
- [Holistic Tidymodels Tutorial](https://www.stepbystepdatascience.com/ml-with-tidymodels)


## License

Our code and practice materials are made available under the [MIT license](http://opensource.org/licenses/mit-license.php). 

## Statement of contributions

**Franka Tetteroo** prepared a brief overview of the whole `tidymodels` package and introduced the `rsample` package along with different sampling techniques.

**Linus Hagemann** prepared the `recipes` and `parsnip` packages' introduction. He also edited the recording and provided strong support with git-repository maintenance.

**Sofiya Berdiyeva** prepared the description of the `yardstick` package.

All of the authors have also prepared the lab materials, including code example and exercises, respective to their sub-theme from the presentation.
