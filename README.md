# MACS 30150 - Perspectives on Computational Modeling in Economics (Winter 2019)

|  | [Dr. Richard Evans](https://sites.google.com/site/rickecon/) | Zunda (Winston) Xu |
|--------------|----------------------------|--------------------------|
| Email | rwevans@uchicago.edu | zunda@uchicago.edu |
| Office | 208 McGiffert House |     |
| Office Hours | T 10:30am-12:30pm | Fr 10:30am-11:30am |
| GitHub | [rickecon](https://github.com/rickecon) | [zundaxu](https://github.com/zundaxu) |

* **Meeting day/time**: MW 11:30am-1:20pm, Saieh Hall, Room 247
* **Lab session**: W 4:30 - 5:20pm, Saieh Hall, Room 247
* Office hours also available by appointment

## Main text
* James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). [*An Introduction to Statistical Learning*](http://link.springer.com.proxy.uchicago.edu/book/10.1007%2F978-1-4614-7138-7). New York: Springer.


## Course description

This course is an economics-focused survey of modern computational modeling methods that are valuable to empirical, computational, and numerical research. The course begins with some basics of numerical derivatives and integrals. We then spend two days on dynamic programming, which is a very general and flexible way to pose a dynamic problem and which has powerful iterative global solution techniques. We then transition into a week-and-a-half of structural estimation methods. These methods generalize many of the specific estimation techniques that come after. Finally, we spend the last half of the course with a survey of some of the most common statistical learning/machine learning methods.

## Grades

You will have 8 problem sets throughout the term. I will drop everybody's lowest problem set score. For this reason, problem sets will only account for 80 percent of your grade.

| Assignment       | Quantity | Points | Total Points | Percent |
|------------------|----------|--------|--------------|---------|
| Problem Sets     | 8        | 10     | 70           | 77.8%     |
| Midterm exam     | 1        | 20     | 20           | 22.2%     |
| **Total Points** | --       | --     | 90           | 100%    |

Late problem sets will be penalized 2 points for every hour they are late. For example, if an assignment is due on Monday at 11:30am, the following points will be deducted based on the time stamp of the last commit.

| Example PR last commit | points deducted |
| ---------------------- | --------------- |
| 11:31am to 12:30pm     | -2 points       |
| 12:31pm to 1:30pm      | -4 points       |
| 1:31pm to 2:30pm       | -6 points       |
| 2:31pm to 3:30pm       | -8 points       |
| 3:30pm and beyond      | -10 points (no credit) |

## Assignment submission procedure

This folder on your fork of the class repository `github.com/YourGitHubHandle/persp-model-econ_W19/ProblemSets/` is where you will submit your problem sets and project assignments. You will just commit and push your assignments to the appropriate folder. For example, your files for PS1 should be committed to the PS1 folder on your fork of the class repository.

`/persp-model-econ_W19/ProblemSets/PS1/YourFile.pdf`

I will use a shell script to clone all class members' repositories at the time the assignments are due.

## Disability services

If you need any special accommodations, please provide us with a copy of your Accommodation Determination Letter (provided to you by the Student Disability Services office) as soon as possible so that you may discuss with me how your accommodations may be implemented in this course.

## Course schedule

| Date | Day | Topic | Readings | Assignment |
|------------|-------|---------------------------------------------------------|--------------|------------------------------|
| Jan.  7 | M | Model/theory building, data generating processes | [V1997](http://people.ischool.berkeley.edu/~hal/Papers/how.pdf), [Slides](https://github.com/UC-MACSS/persp-model-econ_W19/blob/master/Slides/PerspModel_Intro.pdf) | [PS1](https://github.com/UC-MACSS/persp-model-econ_W19/blob/master/ProblemSets/PS1/PS1.pdf) |
| Jan.  9 | W | Numerical derivatives | [Notes](https://github.com/UC-MACSS/persp-model-econ_W19/blob/master/Notes/ACME_NumDiff.pdf) | [PS2](https://github.com/UC-MACSS/persp-model-econ_W19/blob/master/ProblemSets/PS2/PS2.pdf) |
| Jan. 14 | M | Numerical integration | [Notebk](https://github.com/UC-MACSS/persp-model-econ_W19/blob/master/Notebooks/NumIntegr/NumIntegr.ipynb) |  |
| Jan. 16 | W | Dynamic programming   | [Notes](https://github.com/UC-MACSS/persp-model-econ_W19/blob/master/Notes/DynProg_Evans.pdf) | [PS3](https://github.com/UC-MACSS/persp-model-econ_W19/blob/master/ProblemSets/PS3/PS3.pdf) |
| Jan. 21 | M | **No class (Martin Luther King, Jr. Day)** |  |  |
| Jan. 23 | W | Dynamic programming   | |     |
| Jan. 28 | M | Maximum likelihood estimation (MLE) | [Notebk](https://github.com/UC-MACSS/persp-model-econ_W19/blob/master/Notebooks/MLE/MLest.ipynb) | [PS4](https://github.com/UC-MACSS/persp-model-econ_W19/blob/master/ProblemSets/PS4/PS4.pdf) |
| Jan. 30 | W | Generalized method of moments (GMM) | | PS5 |
| Feb.  4 | M | Generalized method of moments (GMM) | | |
| **Feb. 6** | **W** | **Evans Midterm** |  |  |
| Feb. 11 | M | Statistical learning and linear regression | JWHT Ch. 2, 3, Notes | PS6 |
| Feb. 13 | W | Classification and logistic regression | JWHT Chs. 2, 4 |    |
| Feb. 18 | M | Classification and logistic regression | Notes |  |
| Feb. 25 | M | Resampling methods (cross-validation and bootstrapping) | JWHT Ch. 5, Notes |  |
| Feb. 27 | W | Tree-based methods | JWHT Ch. 8, Notes | PS7 |
| Mar.  4 | M | Tree-based methods | JWHT Ch. 8 |  |
| Mar.  6 | W | Support vector machines | JWHT Ch. 9, Notes |  |
| Mar. 11 | M | Neural networks | HTF Ch. 11, G Ch. 10 | PS8 |
| Mar. 13 | W | Neural networks  | Notes |  |

## References and Readings ##

All readings are required unless otherwise noted. Adjustments can be made throughout the quarter; be sure to check this repository frequently to make sure you know all the assigned readings.

* [A2019] Athey, Susan, ``The Impact of Machine Learning on Econometrics and Economics,'' keynote presentation, American Economics Association/American Finance Association joint luncheon at the Allied Social Sciences 2019 Annual Meeting, Atlanta, Georgia (January 5, 2019). [[Slides](https://github.com/UC-MACSS/persp-model-econ_W19/blob/master/Slides/Athey2019_AEAAFAv2.pptx)]
* [A2018] Athey, Susan, ``[The Impact of Machine Learning on Economics](https://www.nber.org/chapters/c14009.pdf),'' forthcoming in *The Economics of Artificial Intelligence: An Agenda*, eds. Ajay K. Agarwal, Joshua Gans, and Avi Goldfarb, National Bureau of Economic Research (forthcoming).
* [G2017] Géron, Aurélien, *Hands-On Machine Learning with Scikit-Learn & TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems*, O'Reilly (2017).
* [HTF2009] Hastie, Trevor, Robert Tibshirani, and Jerome Friedman, [*The Elements of Statistical Learning: Data Mining, Inference, and Prediction*](https://web.stanford.edu/~hastie/Papers/ESLII.pdf), 2nd Edition, Springer (2009).
* [JWHT2013] James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). [*An Introduction to Statistical Learning*](http://link.springer.com.proxy.uchicago.edu/book/10.1007%2F978-1-4614-7138-7). New York: Springer.
* [V2016] VanderPlas, Jake. (2016). [*Python Data Science Handbook*](http://proquestcombo.safaribooksonline.com.proxy.uchicago.edu/book/programming/python/9781491912126). O'Reilly Media, Inc.
* [V1997] Varian, Hal R., "[How to Build an Economic Model in Your Spare Time](http://people.ischool.berkeley.edu/~hal/Papers/how.pdf)," in *Passion and Craft: Economists at Work*, eds. Michael Szenberg, University of Michigan Press, 1997.
