# data-science-fundamentals
Code and data for the course Data Science Fundamentals: A Bayesian Perspective

## How to Use these Materials

All the files are jupyter notebooks, created within Google's [Colab environment](https://colab.research.google.com/).
I highly recommend viewing and manipulating these files in that environment, and having your students manipulate copies 
of those files in colab as well. Colab is not only user friendly, its also a standard environment for doing data analysis 
and machine learning in inudstry.

Files are broken up into Units. Within each unit there is an Answer Key (AK) and Student Facing Notes (SF). AKs 
are written to be viewed by educators and students alike.

SFs have tasks and blanks spots for student answers. Educators are meant to guide students to an answer when doing a task,
and are intended to collaborate as much as possible on the tasks in SFs. Its very possible students will be unable to 
reach a resonable or compplete answer; teacher's are to then fill in the blanks, with the help of the AK.

There two other files: Exercises, and Projects.

Excercises are either meant to :

- walk students through mechanical or conceptual basics that did not fit within the flow of the main lesson notes
- Reeforce complex or important skills.

Projects are open ended activities where students apply the preivous Unit's knowledge onto a data set of the student's 
choosing.

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
- it gives us intuition for how and deep neural neural networks (the large, complicated AI models that make the news) work.

I'll expand on that last point: the bayesain framework shows the connection between all of statistical inference, learning, 
and decision theory.

So what's the catch?

I, and many other bayesians, don't think there is a catch.

But some people might say there are two "catches" with bayesian statistics:
- we need to admit that all predictions requie assumptions.
- we end up with some gnarly integrals.

The first one isn't actaully a problem, its just an exercise in humility.

The second one, about the integrals, is more interesting. It used to be a problem before computers and certain algorithms
(Markov Chain Monte Carlo mostly) were invented and refined. With librairies like pymc or similar, we can consistently wiggle
our way past the integral computations. There's a lot fo depth here, but the point is we have tools that are just as reliable 
as those tables of z scores you'll find on the AP stats exam.

Oh here's a benefit I forgot to mention: its cleaner to derive bayesian statistics from the probablity axioms than other
frameworks. I'd say its more natural.

## Textbook(s) Used
Martin Osvaldo A, Bayesian Analysis with Python. Packt Publishing. 2024. ISBN 978-1-80512-716-1

I used the third additon, and will reference it as BAP3. Buy it, support the author.

I cannot recommend this textbook enough. This course closely follows this textbook in scope, content, pace, and presentation.
The main difference is that my course breaks BAP3's first two units into 3 units, and my course adds an intro to python unit.
Later chapters are even more closely aligned.

### License

Data Science Fundamentals © 2024 by David Arredondo is licensed under CC BY-NC-SA 4.0 
