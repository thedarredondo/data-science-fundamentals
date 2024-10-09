# data-science-fundamentals
Code, data, and content for the course Data Science Fundamentals: A Bayesian Perspective

## Goal

Form an inuitive understanding of the modern AI/machine learning wave, and learn some practical model building skills along the way.
I'd love to hear feedback on how to better achieve this goal.

By the end of the course, students will be able to:

- understand that all models are wrong, but that some models are useful.

- explain why all models require assumptions/context.

- explain the concepts of under/over fitting , and which parts of a model influnces under/over fitting.

Additionally, students will gain an understanding of why neural networks perform so well, by exploring the concepts of priors, likelihoods, and Gaussian Processes

I am an amateur at bayesian techniques, and this is my first time writing a new course/curriculum.
Please let me know if you have any suggestions.

## Prerequisites 
Hardware:

  - 1 to 1 student to computer ratio

  - If using Colab, which I recommend, then consistent internet access is a must.

Content Knowledge:

  - Algebra II

This course assumes students have decent graphical inuition, and assumes that students find it obvious that graphs can summarize functions/algorithms. 

No prior coding/progamming experience necessary.

## Structure of the Lesson Materials

All the files are jupyter notebooks, created within Google's [Colab environment](https://colab.research.google.com/).
Colab is user friendly, and its a standard environment for doing data analysis 
and machine learning.

The course is broken up into units. Within each unit there are 4 files.

- Two of those are Notes: an Answer Key (AK) and Student Facing Notes (SF). AKs are written to be viewed by educators and students alike. SFs have tasks and blank spots for student answers.  

- Another file is ExercisesSF. Excercises also have tasks and blank spots. I have AKs for the most of the Exercises, but I have chosen not to publish them on github.

- The last type of file is a Project. Projects are open ended activities where students apply a Unit's content onto a data set of the student's choosing.

See 'How to Use the Lesson Materials' for more details.

### Break Down of the Units:

- Unit 1: Crash Course in Python. I only cover enough python to give students the ability to use numpy arrays and pandas dataframes, and read a for loop.
  - Approx. length: 3 hours of class time for the notes and 1 hour for the exercises. Not project this unit. 4 total hours; much shorter if this isn't your first coding class.

- Unit 2: Intro to Probability. I blend probability and statsitcs together in a single example. This unit assumes 0 previous exposure to probability/statistics.
  - we also conlude by buidling a model with pymc, although students are not expected to understand that model yet.
  - Approx. length: 6 hours for the notes. 2.5 hours for exercises, and 3.5 hours for the project. 12 total hours

- Unit 3: Playing with Probability Distributions. Through several examples, we explore different types of probability/randomness, what priors and likelihoods are, and how to check our models
  -  More comentary/examples with pymc woven in.
  -  Approx. length: 2 hours for notes, 3 hours for exercises, and 6 hours for the project. 11 total hours
 
-  Unit 4: Hierarchical Models. An introduction to hyper priors, and how we can use them to make a model with partially dependent groups.
  - Guess at length: 4 hours for the notes, 3 hours for exercises, and 3.5 hours for the project. 10.5 total hours

- Unit 5: Linear Models (1 predictor). How to use one set of data to predict another, and all the perils therein. We cover a lot of single variable generlized linear model concepts.
  - Guess at length: 6 hours notes, 3 hours for exercies, and 5 hours for the project. 14 total hours.

- Unit 6: Linear Models (multiple predictors). Linear models, except more than 1 predictor. Under/Overfitting, model/variable selection, and visualizing high dimensional models.
  - Guess at length: 3.5 hours class time, 1.5 hours for exercises, and 5 hours for the project. 10 total hours

- [Sorta Ready] Unit 7: Fitting Curves. Polynomial regression, b splines, and Gaussian Processes. Also: how all those relate on a continuum, and discussion on where Neural Networks lie on that continuum.
  - Guess at length: 3 hours class time, 1 hour for exercises, and 4 hours for the project. 8 total hours

- [Not ready] Unit 8: Bayesian Additive Regression Trees (BART). A bayesianification of random forests. I'll cover probabilistic decison trees and pure random forests as well.
  - Guess at length: 8 hours total

- [Not ready, possibly will drop form course] Unit 9: Miscellaneous Methods with PyMC. Mixture models, Zero Inflated models, Out of Sample data.
  - Guess at length: 3 hours total, 1 hour exercises

- [Not ready, possibly will drop from course] Unit 10: An Intro to Markov Chain Monte Carlo. Walk through a Metropolis-Hastings example, More Advanted model Diagonstics.
  - Guess at length: 1.5 total hours

- [Not ready] Unit 11: The Multi-Layer Perceptron. Introduces MLPs as a speedy approximation of a guassian process.

- [Not ready] Unit 12: Priors and neural networks. Introduces dropout, CNN, and transformers as priors.

- [Not ready] Unit 13: Other Modern Machine Learning Methods. This might be multiple units. We will introduce Neural Networks here.
  - Guess at length: ? total hours 

Units 9 is optional. It contains useful techniques and concepts, but I probably wouldn't want to devote a whole project to it. 
Unit 10 would really just be a class period or two covering the basic concepts of MCMC and related ideas. Also no project.


## How to Use the Lesson Materials

These lessons were built with the "guide on the side" model in mind, as opposed to the "sage on the stage."
The materials are self contained and suitable for self study. The intrsuctor's role is more that of a consultant.
I suggest doing the NotesSF, reading NotesAK, doing ExercisesSf, and doing the unit's project. I suggest only grading the exercises and project.

Presentations for the projects have gone well, and they have been great oppurtunites to reinfornce key concepts or warn about missteps.


## Suggestions on grading

The main purpose of this course is to get students to think about modeling decisions. I encourage you to create a grading 
plan that
- focues on how students explain and justify their decisions
- rewards creativity in written, oral, and visual presentation.

My personal grading scheme:

### Grade Break Down

Overall:
- 50% for class participation
- 20% for exercises
- 30% for projects

#### Class Participation

Students can earn participation credit by:
- asking the instructor (me) a relevant question.
- asking a classmate a relevant question.
- explaining a relevant concept to a classmate or to classmates.
- arguing about data science
- completing tasks from the notes or exercises
- working on a project

#### Exercises

As long as all sources are cited, anything goes for exercises. On exercises, my notes do not need to be cited. Exercises are mostly for students to evaluate their own understanding.

~66% of this grade is completion (given reasonable answers).

~33% is accuracy

#### Projects

Students are not allowed to look at another student's project, until the project deadline has passed. Failure to comply will result in a 0.
That said, any hand written or verbal communication about a project is allowed. On projects, my notes do not need to be cited.

Grade breakdown:

- 10% for getting a proposal approved

- 10% for a working model--i.e. the code runs, and produces a relevant model.

- 10% for helpful comments embedded in the code, and for having clean, readable code.

- 10% for thoughtful prior, likelihood, and model selection, with written justification.

- 10% for writing up the "story" of the model building process--what was tried, what failed, what eventually worked, etc.
Note that a working model is not necessary to earn full credit here.

- 20% for linking the data, the reality of the context in question, and the model together, with an appropriate conclusion.
Its possible to get the majority of the credit here without a fully working model.

- 20% for including relevant visualizations, and explaining those visualizations.

- 10% for an oral presentation that covers all the above

Once the dealine for a project has passed, I give students one day to collaborate as much as they like in preperation for oral presentations.
This also gives me time to grade.

The next day, I select a random sample of students to present. I'll average those students' presentation performances,
and apply that average as everyone's presentation grade.

#### Late policy/Absence Policy

- Projects:
  - First late project penatly: max grade of a 90; 0 for the presentation grade.
  - Second: max grade is a 70, and I will deprioritize grading it.
  - Third or more: max grade is a 60, and I will deprioritize grading it.
- Class participation:
  - Absent students are exempt from that week's participation grade.
- Exercises:
  - Late exercises will be given a grade of 40. 

## What's this whole Bayesian Thing?

Instead of explaining what bayesian statistics is, I'll just say why its good:

- it allows for precise *and* interpretable controlling of overfitting
- *all* assumptions about the scope of a problem can--theoretically--be included in a bayesian model.
- it gives us intuition for how and why deep neural neural networks (the large, complicated AI models that make the news) work.

I'll emphasize that last point: the bayesain persepctive connects all the various parts of statistics and machine learning.

Here are some reason's why people have found the bayesian persepective uncomfortable:
- we need to admit that all predictions requie assumptions.
- we end up with some gnarly integrals.

The first point an exercise in humility--which can be difficult, but rewarding.

The second one, about the integrals, is interesting. 
It used to be a problem before computers and certain algorithms--Markov Chain Monte Carlo variants, mostly--were invented and refined. 
Now, with librairies like pymc or similar, we can consistently wiggle our way past the integral computations. 
There's a lot of depth here, but the point is that we have tools that are just as reliable as those tables of z scores you'll find on the AP stats exam.

## Textbook(s) Used
This testbook serves as teh backbone of the course

[Bayesian Analysis with Python](https://bap.com.ar/): A pratical guide to probablistic modeling, citation below:

Martin Osvaldo A, Bayesian Analysis with Python. Packt Publishing. 2024. ISBN 978-1-80512-716-1

Buy it, support the author. I used the third additon, and will reference it as BAP3.  [Github link to code for the book](https://github.com/aloctavodia/BAP3).

This course closely follows this textbook in scope, content, pace, and presentation.
The main differences: my course breaks BAP3's first two units into 3 units, my course adds an intro to python unit, changes the order and scope of later units, and leaves out content 
(the left out content is mostly stuff to do with binary and discrete decision making, such as bayes factor, bayesian p values, ROPE, etc.).

There's a second textbook I recommend, which serves as the soul of the course:

[Statistical Rethinking](https://xcelab.net/rm/): A Bayesian Course with Examples in R and Stan, by Richard McElreath.

It moves even slower the BAP3, and gracefully melds practical programming advice, sound mathematical reasoning, and sober scientific ideals together, all with a dash of humor.
Buy it, read it, **watch his lectures on youtube**.

### Other Useful Texts

[Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/), the Third Edition, is a classic Bayesian statistical text. 
Its one of the best places to find mathematical explanations for the things we do in this course 

It assumes much more knowledge than either of the previous textbooks I mentioned, though.

My final recommendation is Kevin Murphy's [Probabilistic Machine Learning](https://probml.github.io/pml-book/) textbooks: An Introduction, and Advanced Topics.
They contain summaries of the collective human knowledge of Machine Learning techniques as of late 2023.

# License

Data Science Fundamentals © 2024 by David Arredondo is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 
