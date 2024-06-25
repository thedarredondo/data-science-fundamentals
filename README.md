# data-science-fundamentals
Code and data for the course Data Science Fundamentals: A Bayesian Perspective

## Goal

The goal of this course is to get as many people as possible doing bayesian statistical analysis as soon as possible.
Any inclusions and exclusions in content were made with this goal in mind.
I'd love to hear feedback on how to better achieve the goal of getting the most people doing bayesian statistics.

By the end of the course, students will:

- understand that all models are wrong, but that some models are useful.

- understand the connection between between model architectures, from a single variable parameter estimate, through various forms of linear regression, and to Guassian proccesses and Random Forests.

- be able to explain why all models require assumptions.

- be able to use contextual knowledge and assumptions to their advantage in the contruction of statistical models, through the use of likelihoods and priors

- be able to explain the concepts of under and over fitting (AKA the bias/variance tradeoff), and how prior and likelihood selection influnces under and over fitting.

If you're familiar with either bayesian statisticals or statistical learning, or using this course to teach yourself, then here's a more concrete teaser: 

- by the end of the course, you will be able to apply the bayesian additive regression tree 
(BART) model to real world data, explain how BART models connect to neural networks (NN), and explain why BART models perform as well or
better than NNs on small to medium size data sets.

There's a lot of learning on the way to these goal, and I've ienvitably left things out. Let me know if you have any suggestions.

## Prerequisites 
Hardware:

1 to 1 student to computer ratio

Content Knowledge:

Algebra II

The Alg. II prereq. could be relaxed if the material in Units 1, 2, and 3 was modified to almost entirely ignore mathematical formula. This course assumes students have decent graphical inuition, and assumes that students find it obvious that graphs can summarize algorithms and functions. 

No prior coding/progamming experience necessary [*at least, once I finish Unit 1*]

## Structure of the Lesson Materials

All the files are jupyter notebooks, created within Google's [Colab environment](https://colab.research.google.com/).
I recommend viewing and manipulating these files in that environment, and having your students manipulate copies 
of those files in colab as well. Colab is user friendly, its a standard environment for doing data analysis 
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

## How to Use the Lesson Materials

These lessons were built with the "guide on the side" model in mind, as opposed to the "sage on the stage."

This is both more and less work for the educator.

The more:

- Educators need to be ready to respond to questions they don't know the answer to.
The exploratory nature of the content means that students will venture into territory outside the scope of a given unit,
or even outside the scope of the course. I think this is a plus. Although I've taken some steps to mitigate this and encourage focus on the relevant tasks at hand,
its important for any statistician to practice curiosity, creativity, and humility. I try to model this by letting students know when I don't know,
and then follow up that humility with curisoity: either a conjecture, or an impromtu class disscussion.

- Grading projects is hard.
Statistics is hard. I'm probably not qualified to teach a bayesian statistics course, let alone design one.
But in making and teaching this course, I'm becoming the type of person who is. And my students, even if they don't get the best course or the best instruction,
are getting exposed to cutting edge tools and statisical methods that might otherwise be totally inaccesible to them.
I have some tips on how to make grading easier for th educator and more encouraging for students below. Feel free to share your tips with me as well.

The less:

- Students can more or less teach themselves.
With the guide on the side model, I can wander around and see if students are completeing their tasks, asking any questions that come up.
If many students are confused or completely off track from the answer key, I can call their attention and delvier a short mini lecture as needed.
I don't have to hold the whole class' attention with song and dance for the entire class period--I just have to encourage them to be on task.
- Monitoring student progess on projects is easy.
When students are working their hardest, I'm working the least. All I have to do as in educator is look at google drive or github (however your handle document submission) and look for recent changes. This is especially easy with github, if you go that route. Project work is intended to take at least half of class time. This gives me time to have one on one converstations, small group discussions, or franctially prepare for tomorrow's lesson at my desk :D

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
