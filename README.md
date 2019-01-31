# Overview
Everything below is free and ready to follow. The curriculum below provides an introduction to machine learning and deep learning for a 5 ECTS points Master's level course. 

If you want a good introduction to neural networks to get an overview, go watch 3Blue1Browns (Grant Sanderson) neural networks introduction [here](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)

# Curriculum
| Tables    | Are                                       | Resources         |
| ----------|-------------------------------------------|-------------------|
| Week 1    | Linear regression and classification      | Machine Learning by Andrew NG, lecture 1.1 to 2.9 <br> [Exercise 1](Exercises/Exercise1.ipynb)   |
| Week 2    | Linear regression and classification with multiple variables    |     |
| Week 3    | Logistic regression and classification|     |
| Week 4    | Winter break      |     |
| Week 5    | Decision trees and nearest neighbour models      |     |
| Week 6    | Support Vector Machines      |     |
| Week 7    | Neural networks      |     |
| Week 8    | Convolutional Neural Networks      |     |
| Week 9    | Convolutional Neural Networks      |     |
| Week 10   | Practical use of ML algorithms      | [Paper](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)    |
| Week 11   | Project       |     |
| Week 12   | Project      |     |
| Week 13   | Project      |     |
| Week 14   | Project      |     |

# Full online courses
## Machine learning 
[Coursera's (Stanford's) Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning)

All lectures [here](https://www.youtube.com/playlist?list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN)

Exercises in Python [here](https://github.com/dibgerge/ml-coursera-python-assignments)
Exercises in Python [here](https://github.com/dibgerge/ml-coursera-python-assignments)

or for a more theoretical approach

[Stanford's Statistical Learning by Trevor Hastie and Rob Tibshirani](https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/)

Good textbook for the course: [Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/download.html)

Python exercises [here](https://github.com/JWarmenhoven/ISLR-python)

## Deep learning 
[Stanford's cs231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)

All lectures available [here](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv).

Get exercises from their own webpage [here](http://cs231n.github.io/)

Good textbook on the subject can be downloaded [here](https://www.deeplearningbook.org/)

# Other valuable resources
## Python tutorials
My advise is to go through the following tutorial: 
[Similar to our setup](https://stackabuse.com/python-tutorial-for-absolute-beginners/#installationandsetup)

For the rest of this course, get examples for Python code from [here](https://jakevdp.github.io/PythonDataScienceHandbook/)

If you would rather have lectures, go [here](https://www.youtube.com/watch?v=YYXdXT2l-Gg&list=PL-osiE80TeTskrapNbzXhwoFUiLCjGgY7)

### Full course
[Larger course with lectures and a book (exercises are in the book)](https://www.py4e.com/)

Watch lectures [here](https://www.py4e.com/lessons)

Download book [here](http://do1.dr-chuck.com/pythonlearn/EN_us/pythonlearn.pdf)

### If you are interested in improving your general programming skills (not just Python), I very much advise you to take
[Harvard's cs50: Introduction to Computer Science](https://www.edx.org/course/cs50s-introduction-computer-science-harvardx-cs50x)

All lectures available [here](https://www.youtube.com/results?search_query=cs50+harvard).

Get help at the subreddit [here](https://www.reddit.com/r/cs50/). 

Following this course, dig into object oriented programming, and you should be good.

## YouTube channels
[Python tutorials by Corey Schafer](https://www.youtube.com/user/schafer5)

[Math recap by 3Blue1Brown (Grant Sanderson)](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw), especially see his [Essence of linear algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) and [Essence of calculus](https://www.youtube.com/watch?v=WUvTyaaNkzM&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) videos.

## Textbooks
[Mathematics for Machine Learning](https://mml-book.com/)

[Deep Learning Book](https://www.deeplearningbook.org/)

[Python for Data Science](https://jakevdp.github.io/PythonDataScienceHandbook/)

[Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/download.html)

### For PhD students:
During my PhD we were allowed to follow one of the courses and do a project based on it for our own research to obtain 5 ECTS points as part of the required

# Installing our Python environment
1) Install Anaconda with Python 3.7. The installer can be downloaded here:  https://www.anaconda.com/download​ . It will at some point ask if you want to 'Add Anaconda to my PATH environment variable'. The answer to this question is 'no', you do not want to do this.

2) Launch a Jupyter Notebook in Anaconda (use the Anaconda Navigator if you use Windows/Mac or create and run it from a new conda environment if you use Linux).

3) Write and run the following code: print("Hello, World!")

4) Assuming that the computer is having a good day, you should see the words "Hello, World!" being printed. If this is not the case, or you never even made it to step 4, then do not worry. Take a deep breath and a sip of your coffee. Search for solutions online and try one more time. 

Using Anaconda should be seen as a suggestion for newcomers in the field. If you already have another solution running, such as using Docker containers, you are welcome to continue in this way. 