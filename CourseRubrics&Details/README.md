## Suggestions on grading

I created a scheme that:
- focues on how students explain and justify their decisions
- rewards creativity in written, oral, and visual presentation.

### Grade Break Down

Overall:
- 50% for class participation
- 20% for exercises
- 30% for projects

#### Class Participation

Students can earn participation credit by:
- asking the instructor a relevant question.
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

The next day, I select a random sample of students to present. I average those students' presentation performances,
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

## Break Down of the Units:

- Unit 1: Crash Course in Python. I only cover enough python to give students the ability to use numpy arrays and pandas dataframes, and read a for loop.
  - Approx. length: 3 hours of class time for the notes and 1 hour for the exercises. Not project this unit. 4 total hours; much shorter if this isn't your first coding class.

- Unit 2: Intro to Probability. I blend probability and statsitcs together in a single example. This unit assumes no previous exposure to probability/statistics.
  - we also conlude by buidling a model with pymc, although students are not expected to understand that model yet.
  - Approx. length: 6 hours for the notes. 2.5 hours for exercises, and 3.5 hours for the project. 12 total hours

- Unit 3: Playing with Probability Distributions. Through several examples, we explore different types of probability/randomness, what priors and likelihoods are, and how to check our models
  -  More comentary/examples with pymc woven in.
  -  Approx. length: 2 hours for notes, 3 hours for exercises, and 6 hours for the project. 11 total hours
 
-  Unit 4: Hierarchical Models. An introduction to hyper priors, and how we can use them to make a model with partially dependent groups.
  - Guess at length: 4 hours for the notes, 3 hours for exercises, and 3.5 hours for the project. 10.5 total hours

- Unit 5: Linear Models (1 predictor). How to use one set of data to predict another, and all the perils therein. We cover a lot of single variable generlized linear model concepts.
  - Guess at length: 6 hours notes, 4 hours for exercies, and 5 hours for the project. 15 total hours.

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

- [Not ready] Unit 13: Other Modern Machine Learning Methods. I've to cover a modern implementation of k-means called UMAP here, but we'll see if there's time.
  - Guess at length: ? total hours 

Units 9 is optional. It contains useful techniques and concepts, but I probably wouldn't want to devote a whole project to it. 
Unit 10 would really just be a class period or two covering the basic concepts of MCMC and related ideas. Also no project.
