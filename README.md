# data-science-fundamentals
Code, data, and content for the course Data Science Fundamentals: A Bayesian Perspective

## Goal

Form an intuitive understanding of the modern machine learning/AI wave, and learn some practical model building skills along the way.

By the end of the course, students will be able to:

- understand that all models are wrong, but that some models are useful.

- explain why all models require assumptions/context.

- Create and interpret bayesian and causal models.

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

- Notes. There are two per unit: an Answer Key (AK) and Student Facing Notes (SF). SFs have tasks for students. AKs have answers to the tasks (surprise)
and are written to be viewed by educators and students alike.   

- ExercisesSF. Excercises also have tasks. I have AKs for the most of the Exercises, but I have chosen to leave them unpublished.

- Project. Projects are open ended activities where students apply a Unit's content onto a data set of the student's choosing.

See the folder 'CourseRubrics&Details' for a more thorough break down of the units and my personal grading scheme.

## What's this whole Bayesian Thing?

Instead of explaining what bayesian statistics is, I'll just say why its good:

- *all* assumptions about the scope of a problem can--theoretically--be included in a bayesian causal model.
- all parts of a bayesian causal model have a precise (often intuitive) mathematical meaning.
- it gives us intuition for how and why deep neural neural networks (the large, complicated AI models that make the news) work.

I'll emphasize that last point: the bayesain persepctive connects all the various parts of statistics and machine learning.

Here are some reason's why people have found the bayesian persepective uncomfortable:
- we need to admit that all predictions requie assumptions.
- we end up with some gnarly integrals.

The first point is an exercise in humility--which can be difficult, but rewarding.

The second one, about the integrals, is interesting. 
It used to be a problem before computers and certain algorithms--Markov Chain Monte Carlo variants, mostly--were invented and refined. 
Now, with librairies like pymc or similar, we can consistently wiggle our way past the integral computations. 
There's a lot of depth here, but the point is that we have tools that are just as reliable as those tables of normal z scores you'll find on the AP stats exam.

## Textbook(s) Used
The textbook below serves as the backbone of the course

[Bayesian Analysis with Python](https://bap.com.ar/): A pratical guide to probablistic modeling, citation below:

Martin Osvaldo A, Bayesian Analysis with Python. Packt Publishing. 2024. ISBN 978-1-80512-716-1

Buy it, support the author. I used the third additon, and will reference it as BAP3.  [Github link to code for the book](https://github.com/aloctavodia/BAP3).

This course closely follows this textbook in scope, content, pace, and presentation.
The main differences: my course breaks BAP3's first 2 units into 3 units, my course adds an intro to python unit, changes the order and scope of later units, and leaves out content 
(the left out content is mostly stuff to do with binary and discrete decision making, such as bayes factor, bayesian p values, ROPE, etc.).

There's a second textbook I recommend, which serves as the soul of the course:

[Statistical Rethinking](https://xcelab.net/rm/): A Bayesian Course with Examples in R and Stan, by Richard McElreath.

It moves even slower the BAP3, and gracefully melds practical programming advice, sound mathematical reasoning, and sober scientific ideals together, all with a dash of humor.
Buy it, read it, [watch his lectures on youtube](https://www.youtube.com/watch?v=FdnMWdICdRs&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus).

### Other Useful Texts

[Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/), the Third Edition, is a classic Bayesian statistical text. 
Its one of the best places to find mathematical explanations for the things we do in this course 

It assumes much more knowledge than either of the previous textbooks I mentioned, though.

My final recommendation is Kevin Murphy's [Probabilistic Machine Learning](https://probml.github.io/pml-book/) textbooks: An Introduction, and Advanced Topics.
It is an attempt to summarize the collective human knowledge of Machine Learning techniques as of late 2023.

# License

Data Science Fundamentals © 2024 by David Arredondo is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 

The following is not the full legal text of the license, but a summary of it:

You are free to:

- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:

- Attribution — You must give appropriate credit , provide a link to the license, and indicate if changes were made . You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

- NonCommercial — You may not use the material for commercial purposes .

- ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Notices:

You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable exception or limitation .

No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as publicity, privacy, or moral rights may limit how you use the material.
