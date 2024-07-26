# data-science-fundamentals
Code and data for the course Data Science Fundamentals: A Bayesian Perspective

## Goal

The goal of this course is to help people form a partical and inuitive understanding of mathematics behind the modern AI/machine learning wave.
The focus is not on calculus and linear algebra aspects machine learning/AI, but on the mathematical underpinnings of using a computer to model the real world.
I'd love to hear feedback on how to better achieve this goal.

By the end of the course, students will be able to:

- understand that all models are wrong, but that some models are useful.

- explain why all models require assumptions/context.

- explain the concepts of under/over fitting , and which parts of a model influnces under/over fitting.

If you're familiar with either bayesian statisticals or statistical learning, or using this course to teach yourself, then here's a more concrete teaser: 

- by the end of the course, you will be able to apply the bayesian additive regression tree 
(BART) model to real world data, explain how BART models connect to neural networks (NN), and explain why BART models perform as well or
better than NNs on small to medium size data sets.

This is my first time writing a course/curriculum, and I was surprised to learn that course writing is an exercise in what NOT to include. Please let me know if you have any suggestions.

## Prerequisites 
Hardware:

  - 1 to 1 student to computer ratio

  - If using Colab, which I recommend, then consistent internet access is a must.

Content Knowledge:

  - Algebra II

  - The Alg. II prereq. could be relaxed if the material was modified to almost entirely ignore mathematical formula. This course assumes students have decent graphical inuition, and assumes that students find it obvious that graphs can summarize algorithms and functions. 

No prior coding/progamming experience necessary.

## Structure of the Lesson Materials

All the files are jupyter notebooks, created within Google's [Colab environment](https://colab.research.google.com/).
I recommend viewing and manipulating these files in that environment, and having your students manipulate copies 
of those files in colab as well. Colab is user friendly, and its a standard environment for doing data analysis 
and machine learning.

The course is broken up into Units. Within each unit there are 4 files, two of which are Answer Key Notes (AK) and Student Facing Notes (SF). AKs 
are written to be viewed by educators and students alike.

SFs have tasks and blanks spots for student answers. Educators are meant to guide students to an answer when doing a task,
and students are intended to collaborate as much as possible on the tasks in SFs. Its possible students will be unable to 
reach a resonable or complete answer on their own; teacher's are to then step in with a lecture, with the help of the AK. 
See 'How to Use the Lesson Materials' for more details.

There two other files in a Unit: Exercises, and Projects.

Excercises are either meant to:

- walk students through mechanical or conceptual basics that did not fit within the flow of the main lesson notes
- Reinforce complex or important skills.

I have AKs for the most of the Exercises, but I have chosen not to publish them on github. I know this makes it harder to use them in your own practice, 
but I think its important to have activites where there's no immediate authority to run to.

Projects are open ended activities where students apply a Unit's content onto a data set of the student's 
choosing.
- Students are encouraged to copy code from the AK and Exercises for their project, modifying as needed.
- All projects have a proposal component, so that the educator can review a student's proposed data set, and guide them towards a workable model.

### Break Down of the Units:

- Unit 1: Crash Course in Python. I only cover enough python to give students the ability to use numpy arrays and pandas dataframes, and read a for loop.
  - Guess at length: 3 hours of class time for the notes and 1.5 hour for the exercises. Not project this unit. 4.5 total hours

- Unit 2: Intro to Probability. I blend probability and statsitcs together in a single example. This unit assumes 0 previous exposure to probability/statistics.
  - we also conlude by buidling a model with pymc, although students are not expected to understand that model yet.
  - Guess at length: 7 hours for the notes. 2.5 hours for exercises, and 4 hours for the project. 13.5 total hours

- Unit 3: Playing with Probability Distributions. Through several examples, we explore different types of probability/randomness, what priors and likelihoods are, and how to check our models
  -  More comentary/examples with pymc woven in.
  -  Guess at length: 5 hours for notes, 2.5 hours for exercises, and 4.5 hours for the project. 12 total hours
 
-  Unit 4: Hierarchical Models. An introduction to hyper priors, and how we can use them to make a model with partially dependent groups.
  - Guess at length: 5 hours for the notes, 3 hours for exercises, and 4.5 hours for the project. 12.5 total hours

- Unit 5: Linear Models (1 predictor). How to use one set of data to predict another, and all the perils therein. We cover a lot of single variable generlized linear model concepts.
  - Guess at length: 7 hours notes, 3 hours for exercies, and 5 hours for the project. 15 total hours.

- Unit 6: Linear Models (multiple predictors). Linear models, except more than 1 predictor. Under/Overfitting, model/variable selection, and visualizing high dimensional models.
  - Guess at length: 4.5 hours class time, 1.5 hours for exercises, and 5 hours for the project. 11 total hours

- Unit 7: Fitting Curves. Polynomial regression, b splines, and Gaussian Processes. Also, how all those relate on a continuum, and discussion on where Neural Networks lie on that continuum.
  - Guess at length: 4 hours class time, 1.5 hour for exercises, and 3.5 hours for the project. 9 total hours

- [Not ready] Unit 8: Bayesian Additive Regression Trees (BART).
  - Guess at length: 9 hours total

- [Not ready] Unit 9: Miscellaneous Methods with PyMC. Mixture models, Zero Inflated models, Out of Sample data.
  - Guess at length: 7 hours total

- [Not ready] Unit 10: An Intro to Markov Chain Monte Carlo. Walk through a Metropolis-Hastings example, More Advanted model Diagonstics.
  - Guess at length: 7 total hours

- [Not ready] Unit 11: Other Modern Machine Learning Methods. This is an excuse for students to explore ideas from outside the course.
  - Guess at length: 7 total hours 

## How to Use the Lesson Materials

These lessons were built with the "guide on the side" model in mind, as opposed to the "sage on the stage."

Students are intended to work in groups through the student facing notes, running code and completing tasks as they go along.
If they get stuck, they can either ask the educator for assitance, or consult the answer key.
I may force everyone to stop and listen to me lecture--or  maybe I won't. Small group and one-on-one conversations may be enough.

When students are ready, they can tackle the exrcises for that unit, in order to check that they understood the key concepts.
Once the exercises are complete, students can move on to selectiong a data set, getting their project approved, then building their model.
After their model is complete to their statisfication, they will procede to write up their thought processes and conclusions in the juypter notebook their code lives in.
Finally, they will prepare to orally prosent their model, their findings, and their journey.


## Suggestions on grading

The main purpose of this course is to get students to think about modeling decisions. I encourage you to create a grading 
plan that focuses on how students explain and justify there decisions, and rewards creativity, oral, and visual presentation.

My personal grading scheme:

[*I swear I'll do this eventually*]

## What's this whole Bayesian Thing?

Instead of explaining what bayesian statistics is, I'll explain why more and more people in industry and academia are
taking a Bayesian perspective:

- it allows for precise *and* interpretable controlling of overfitting
- *all* assumptions about the scope of a problem can--theoretically--be included in a bayesian model.
- it gives us intuition for how and why deep neural neural networks (the large, complicated AI models that make the news) work.

I'll expand on that last point: the bayesain framework shows the connection between all statistical inference, learning, 
and decision theory.

So what's the catch?

I, and many other bayesians, don't think there is a catch.

But as an educational exercise, I'll pretend there are two "catches" with bayesian statistics:
- we need to admit that all predictions requie assumptions.
- we end up with some gnarly integrals.

The first one isn't actually a problem, its just an exercise in humility.

The second one, about the integrals, is more interesting. It used to be a problem before computers and certain algorithms
(Markov Chain Monte Carlo variants, mostly) were invented and refined. Now, with librairies like pymc or similar, we can consistently wiggle
our way past the integral computations. There's a lot of depth here, but the point is that we have tools that are just as reliable 
as those tables of z scores you'll find on the AP stats exam.

## Textbook(s) Used
Martin Osvaldo A, Bayesian Analysis with Python. Packt Publishing. 2024. ISBN 978-1-80512-716-1

I used the third additon, and will reference it as BAP3. Buy it, support the author.

I cannot recommend this textbook enough. This course closely follows this textbook in scope, content, pace, and presentation.
The main difference is that my course breaks BAP3's first two units into 3 units, and my course adds an intro to python unit.
Later chapters are even more closely aligned.

There's a second textbook I recommend:



### License

Data Science Fundamentals © 2024 by David Arredondo is licensed under CC BY-NC-SA 4.0 
