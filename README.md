# Introduction to Econometrics

* Here you can look at the slide for the 2025 [Econometrics](https://github.com/Frohly-Constance/Course_Econometrics) course by Constance Frohly. This course was created by Gustave Kennedi, Mylène Feuillade, Florian Oswald and Junnan He.


## Slides

| Lecture | HTML | PDF | Tasks |
|---------|:----:|:---:|-------|
| Lecture 1: Introduction | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_intro/Deck1_Intro.html) | [PDF](https://rawcdn.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_intro/Deck1.pdf) | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_intro/tasks/intro_tasks.html) |
| Lectures 2/3: Tidying, Visualising and Summarising Data | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_tidy/Deck2_Tidy.html) | [PDF](https://rawcdn.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_tidy/Deck2_Tidy.pdf) | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_tidy/tasks/Task2_Tidy.html)  |
| Lecture 4: Simple Linear Regression | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_slr/Deck3_slr.html) | [PDF](https://rawcdn.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_slr/Deck3_slr.pdf) | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_slr/tasks/Task3_slr.html)  |
| Lecture 5: Introduction to Causality | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_causality/Deck4_Causality.html) | [PDF](https://rawcdn.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_causality/Deck4_Causality.pdf) | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_causality/tasks/Task4_Causality.html) |
| Lecture 6: Multiple Linear Regression | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_mlr/Deck5_mlr.html) | [PDF](https://rawcdn.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_mlr/Deck5_mlr.pdf)  | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_mlr/tasks/Task5_mlr.html) |
| Lecture 7: Linear Regression Extensions | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_regext/Deck6_regext.html) | [PDF](https://rawcdn.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_regext/tasks/Task6_regext_Task1&2.html)  | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_regext/tasks/regext_tasks.html)  |
| Lecture 8: Sampling | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_sampling/Deck7_sampling.html) | [PDF](https://rawcdn.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_sampling/Deck7_sampling.pdf) | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_sampling/tasks/Task7_sampling.html)  |
| Lecture 9: Confidence Intervals and Hypothesis Testing | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_ci_hyptest/Deck8_ci_hyptest.html) | [PDF](https://rawcdn.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_ci_hyptest/Deck8_ci_hyptest.pdf) | [HTML]()  |
| Lecture 10: Regression Inference | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_reginference/Deck9_reg_inference.html) | [PDF](https://rawcdn.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_reginference/Deck9_reg_inference.pdf) | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter_reginference/tasks/Task9_reginference.html) |
| Lecture 11: Regression Discontinuity | [HTML](https://raw.githack.com/Frohly-Constance/Course_Econometrics/master/chapter-RDD/Deck10_RDD.html) | [PDF](https://rawcdn.githack.com/Frohly-Constance/Course_Econometrics/master/chapter-RDD/Deck10_RDD.pdf)  | [HTML]() |

The suggested reading list can be found [here](https://github.com/Frohly-Constance/Course_Econometrics/blob/master/syllabus.md).

## Additional Lectures by Florian Oswald, Gustave Kennedi and Pierre Villedieu

Bootstrapping: More details about bootstrapping. [HTML](https://raw.githack.com/ScPoEcon/ScPoEconometrics-Slides/master/chapter_bootstrap/boostrap.html)

Differences-in-differences:
[HTML](https://raw.githack.com/ScPoEcon/ScPoEconometrics-Slides/master/chapter_did/chapter_did.html) [PDF](https://rawcdn.githack.com/ScPoEcon/ScPoEconometrics-Slides/master/chapter_did/chapter_did.pdf)

## Legal

You can copy and adapt this material for your purposes, as long as you give appropriate credit and share the work yourself  under same terms. Of course you can use the slides to teach in your classrooms. *Appropriate Credit* means that somewhere in your slides there is link back to this repo, indicating that this is what you are building upon. Click on the icon for details.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

## How to build

* These are simply Rmarkdown slides.
* So, in Rstudio, just click *knit*.
* To print slides as PDF, do 
```decktape chapter1.html chapter1.pdf --chrome-arg=--disable-web-security```
using the awesome [decktape](https://github.com/astefanutti/decktape)
