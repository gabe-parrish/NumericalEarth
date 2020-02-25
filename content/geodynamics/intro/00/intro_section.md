# Introduction

## Golden Rules of Numerical Modeling

Gerya gives these simple rules (below in quotes), which I found very encouraging. When
I first learned numerical modeling, I didn't really know what a computer model even 
consisted of and was pretty overwhelmed, even though I had a decent math background. The 
golden rules calmed my nerves quite a bit.

1. "Numerical modeling is simple and based on simple mathematics". Derivatives and Linear 
Algebra, that is.

2. "When numerical modelling looks complicated see Rule 1."

3. "Numerical modeling consists of solving partial differential equations (PDEs)". 
...and not that many of them: Conservation of mass, momentum and heat.

4. "Read books on numerical methods several times."

5. "Repeat transformations of equations involved in numerical modeling." That is, 
practice the math involved in solving the PDEs.

6. "Visualization is important!"

7. "Ask!" Get help from someone. I recommend online. As I work through examples
 and if I find any good resources I will point you towards them.

## Why use Python?

Practically speaking, Matlab, the original coding language for this textbook, costs money,
and Python does not. Some folks say that there is a steeper learning curve to Python, but 
I don't know if I agree. With Python there are a few things we'll have to learn: 1. How to read
data from a comma-separated values (CSV) file. 2. How to do mathematical operations. 3. How to 
use the Numpy package to work with arrays (which works a lot like Matlab), 4. and how to visualize 
our results with the Matplotlib package.

Just so all the names don't overwhelm: Python packages we will use are Numpy and Matplotlib. They are built on top of 
Python to add
functionality. To use them we will 'import' them to our scipts and apply them to our problems. To be a good python
 programmer you need to practice, and to practice you need motivation. There's no better motivation than having problems
 to solve that require Python. And you'll come to realize, once you've ingested lots of Python, that all that matters 
 are loops, logic and data structures. Most importantly, don't allow yourself to be intimidated. Baby steps and normal 
 human brains will get you there.
 
 We will use Python Jupyter notebooks to do the exercises because you can write text and execute code all in one place. 
 It's really nice.
 
  There are all manner of resources out there for learning (I like "Learn Python the 
 hard way". Google it!), but you learn so much more if you have a "mission" to accomplish. Just try the examples in Python on your 
 own before looking at mine (with the exception of this first exercise). It's for your own good.
 
 ## Diving into the exercise
 
 These are the same two exercises given in the textbook (which you should get), but adapted for Python. All of Gerya's 
 Matlab scripts are online, so if you want to see those you can. 
 
 Google how to set up a Jupyter Python Notebook. I would google "How to set up Jupyter NB with Conda". 
 That should get you going.
 
 Practice: 
 
 ###Part I
 
 (To be done in a Jupyter notebook.)
 
 1. Defining variables, numpy vectors and matrixes.
 2. Learn the mathematical functions + - * ** / ^ exp, log etc.
 3. opening, reading, writing data to and from text or csv files.
 4. How to plot data in 2D or 3D with Matplotlib.
 5. programing for loops and while loops
 6. condition statements for loops: if, and , or, else, elif, ==, >=, <=, != on and on.
 
 P.S. Numpy arrays have specific logic for arrays that can be a bit different, so I'll show that when I need to but
  it's worth a google.
  
###Part II

Write a script to visualize the sin() and cos() functions in 2d and 3d with Matplotlib. Do this in a Jupyter Notebook.


