# Overview
This repository is a collection of open material to learn machine learning. The curriculum below is designed to match a 5 ECTS points course for Master's level students. It is a combination of lectures and exercises from two courses, namely [_Machine Learning_ by Andrew Ng](https://www.coursera.org/learn/machine-learning) and [_CS231N: Convolutional Neural Networks for Visual Recognition_ from Stanford University](http://cs231n.stanford.edu/). All exercises are to be solved by downloading them to your local computer and solve them using Jupyter Notebook. The curriculum is designed to cover important aspects of the possiblities when applying machine learning, with plenty of opportunities for students to expand their understanding by following each of the online courses in their full extent. For the interested, additional resources are available for a recommended full course on [_Statistical Learning_ by Trevor Hastie and Rob Tibshirani](https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/). 

If you would like a brief introduction to machine learning, watch 3Blue1Brown's (Grant Sanderson's) [introduction to neural networks](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi).

The [ML_in_research](ML_in_research/) folder contains references for novel research within the natural sciences employing deep learning.

# Curriculum
|           | Content                                   | Resources         |
| ----------|-------------------------------------------|-------------------|
| Week 1    | Introduction and installation of Python environment   | See [installation guidelines](#installing-the-python-environment) below.                  |
| Week 2    | Linear regression                                     | Video lectures: [Machine Learning by Andrew Ng](https://www.youtube.com/playlist?list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN), lecture 1.1 to 2.8 (optional: lecture  4.1 to 4.9 for linear regression with multiplie variables). <br>  Exercises: [Exercise 1](CourseMaterial/MachineLearning/Exercises) <br>  Lecture slides: [Lecture 1](CourseMaterial/MachineLearning/LectureSlides/Lecture1.pdf) and [Lecture 2](CourseMaterial/MachineLearning/LectureSlides/Lecture2.pdf) (optional: [Lecture 4](CourseMaterial/MachineLearning/LectureSlides/Lecture4.pdf)) <br>  Lecture notes: [Notes 1](CourseMaterial/MachineLearning/LectureNotes/MachineLearning-01.ipynb) and [Notes 2](CourseMaterial/MachineLearning/LectureNotes/MachineLearning-02.ipynb)|
| Week 3    | Winter break                                          |     |
| Week 4    | Logistic regression and regularization                | Video lectures: [Machine Learning by Andrew Ng](https://www.youtube.com/playlist?list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN), lecture 6.1 to 7.4. <br>  Exercises: [Exercise 2](CourseMaterial/MachineLearning/Exercises) <br>  Lecture slides: [Lecture 6](CourseMaterial/MachineLearning/LectureSlides/Lecture6.pdf) and [Lecture 7](CourseMaterial/MachineLearning/LectureSlides/Lecture7.pdf) <br>  Lecture notes: [Notes 3](CourseMaterial/MachineLearning/LectureNotes/MachineLearning-03.ipynb) <br> Optional: [Video](https://www.youtube.com/watch?v=ErfnhcEV1O8) on the binary cross-entropy loss function by Aurélien Géron |
| Week 5    | Neural networks                                       | Video lectures: [Machine Learning by Andrew Ng](https://www.youtube.com/playlist?list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN), lecture 8.1 to 9.8. <br>  Exercises: [Exercise 4](CourseMaterial/MachineLearning/Exercises) <br>  Lecture slides: [Lecture 8](CourseMaterial/MachineLearning/LectureSlides/Lecture8.pdf) and [Lecture 9](CourseMaterial/MachineLearning/LectureSlides/Lecture9.pdf) <br>  Lecture notes: [Notes 4](CourseMaterial/MachineLearning/LectureNotes/MachineLearning-04.ipynb) and [Notes 5](CourseMaterial/MachineLearning/LectureNotes/MachineLearning-05.ipynb)    |
| Week 6    | Support Vector Machines                               | Video lectures: [Machine Learning by Andrew Ng](https://www.youtube.com/playlist?list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN), lecture 10.1 to 10.7 and 12.1 to 12.6. <br>  Exercises: [Exercise 6](CourseMaterial/MachineLearning/Exercises) <br>  Lecture slides: [Lecture 10](CourseMaterial/MachineLearning/LectureSlides/Lecture10.pdf) and [Lecture 12](CourseMaterial/MachineLearning/LectureSlides/Lecture12.pdf)       |
| Week 7    | Case study using scikit learn                         | Video lectures: [Machine Learning by Andrew Ng](https://www.youtube.com/playlist?list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN), lecture 11.1 to 11.5. <br>Read: [A Few Useful Things to Know about Machine Learning](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) <br>  Exercises: [scikit-learn exercise](CourseMaterial/MachineLearning/Exercises)   |
| Week 8    | Convolutional Neural Networks                         | Video lectures: CS231n from Stanford University 2017, [lecture 5](https://www.youtube.com/watch?v=bNb2fEVKeEo&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv&index=5) <br>  Exercises: [CNN Exercise 1](CourseMaterial/DeepLearning)    |
| Week 8    | Convolutional Neural Networks                         | Video lectures: CS231n from Stanford University 2017, [lecture 9 (until 28:20)](https://www.youtube.com/watch?v=DAOcjicFr1Y&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv&index=9) <br> Optional lectures: CS231n from Stanford University 2017, [lecture 12](https://www.youtube.com/watch?v=6wcs6szJWMY&index=12&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv) <br> Exercises: [CNN Exercise 2](CourseMaterial/DeepLearning)   |
| Week 10    | Recurrent Neural Networks                            | Video lectures: CS231n from Stanford University 2017, [lecture 10](https://www.youtube.com/watch?v=6niqTuYFZLQ&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv&index=10)  <br>  Exercises: [RNN Exercise](CourseMaterial/DeepLearning)     |
| Week 11   | Project (or deep learning in research)                |     |
| Week 12   | Easter break                                          |     |
| Week 13   | Project                                               |     |
| Week 14   | Project                                               |     |
| Week 15   | Project                                               |     |

# Online course material
### Machine learning 
* Original course webpage: [_Machine Learning_ by Andrew Ng](https://www.coursera.org/learn/machine-learning).

* All lectures are available [here](https://www.youtube.com/playlist?list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN).

* Course material is available [here](CourseMaterial/MachineLearning/). All exercises can be downloaded as a zip file [here](CourseMaterial/MachineLearning/Exercises/AllExercisesForDownload.zip) (right click -> save as). The exercises are modified versions of those implemented by [Gerges Dib](https://github.com/dibgerge/ml-coursera-python-assignments).

* Textbook for the course (with Python examples): [_Python for Data Science_ by Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/).

### Deep learning 
* Original course webpage: [_CS231N: Convolutional Neural Networks for Visual Recognition_ from Stanford University](http://cs231n.stanford.edu/)

* All lectures from 2016 available [here](https://www.youtube.com/playlist?list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC) and all lectures from 2017 available [here](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv).

* Get exercises from the course webpage [here](http://cs231n.github.io/)

* Textbook for the course: [_Deep Learning Book_ by Ian Goodfellow, Yoshua Bengio, and Aaron Courville](https://www.deeplearningbook.org/)

* If you are interested, hundreds of students' final projects from the course are available [here](http://cs231n.stanford.edu/2017/reports.html).

### Statistical Learning (not included in curriculum above)
* Original course webpage: [_Statistical Learning_ by Trevor Hastie and Rob Tibshirani](https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/)

* Python exercises are available [here](https://github.com/JWarmenhoven/ISLR-python) (made by Jordi Warmenhoven).

* Textbook for the course: [_Elements of Statistical Learning_ by Trevor Hastie, Rob Tibshirani, and Jerome Friedman](https://web.stanford.edu/~hastie/ElemStatLearn/download.html).

# Valuable resources
### Free textbooks
* [_Mathematics for Machine Learning_ by Marc Peter Deisenroth, A Aldo Faisal, and Cheng Soon](https://mml-book.com/)

* [_Python for Data Science_ by Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/)

* [_Elements of Statistical Learning_ by Trevor Hastie, Rob Tibshirani, and Jerome Friedman](https://web.stanford.edu/~hastie/ElemStatLearn/download.html)

* [_Deep Learning Book_ by Ian Goodfellow, Yoshua Bengio, and Aaron Courville](https://www.deeplearningbook.org/)

* [_Pattern Recognition and Machine Learning_ by Christopher Bishop](https://www.microsoft.com/en-us/research/people/cmbishop/prml-book/) (Python implementations of algorithms available [here](https://github.com/ctgk/PRML))

### YouTube channels
* For learning Python: [Python tutorials by Corey Schafer](https://www.youtube.com/user/schafer5)

* Mathematics recap: [Math videos by 3Blue1Brown (Grant Sanderson)](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw). Especially notice his [_Essence of linear algebra_](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) and [_Essence of calculus_](https://www.youtube.com/watch?v=WUvTyaaNkzM&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) playlists.

* Short presentations of deep learning research: [_Two Minute Papers_ by Károly Zsolnai-Fehér](https://www.youtube.com/user/keeroyz)

### Programming resources
* A brief introduction to Jupyter Notebook can be found [here](https://medium.com/codingthesmartway-com-blog/getting-started-with-jupyter-notebook-for-python-4e7082bd5d46).

* A brief introduction to the Python programming language can be found [here](https://stackabuse.com/python-tutorial-for-absolute-beginners/#installationandsetup).

* I advise newcomers to see code examples during the course from [_Python for Data Science_ by Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/).

* A YouTube channel containing many valuable Python lessons can be found at [Python tutorials by Corey Schafer](https://www.youtube.com/user/schafer5/playlists).

* For a full course on Python, go [here](https://www.py4e.com/). Lectures are available [here](https://www.py4e.com/lessons) and a book with exercises is available [here](http://do1.dr-chuck.com/pythonlearn/EN_us/pythonlearn.pdf).

* If you are interested in improving your general programming skills (not just Python), I very much advise you to take
[_CS50: Introduction to Computer Science_ from Harvard](https://www.edx.org/course/cs50s-introduction-computer-science-harvardx-cs50x). All lectures are available [here](https://www.youtube.com/watch?v=5azaK2cBKGw&list=PLhQjrBD2T382eX9-tF75Wa4lmlC7sxNDH).

### More free online courses
* The Coursera Machine Learning course we use in the curriculum above is a slimmed down version of CS229 from Stanford University, which presents the same subjects as the Coursera version, but from a more mathematically rigorous point of view. Full curriculum and exercises are available at [CS229 at Stanford University](http://cs229.stanford.edu/syllabus-autumn2018.html) with [lectures on YouTube](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU).

* Many free online courses on machine learning has been collected in [this list](https://github.com/luspr/awesome-ml-courses), including ones on more advanced topics.


# Installing the Python environment
1) Install Anaconda with Python 3.7. The installer can be downloaded here:  https://www.anaconda.com/download​ . It will at some point ask if you want to 'Add Anaconda to my PATH environment variable'. The answer to this question is 'no', you do not want to do this.

2) Launch a Jupyter Notebook in Anaconda (use the Anaconda Navigator if you use Windows/Mac or create and run it from a new conda environment if you use Linux).

3) Write and run the following code: print("Hello, World!")

4) Assuming that the computer is having a good day, you should see the words "Hello, World!" being printed. If this is not the case, or you never even made it to step 4, then do not worry. Take a deep breath and a sip of your coffee. Search for solutions online and try one more time. 

Using Anaconda should be seen as a suggestion for newcomers in the field. If you already have another solution running, such as using Docker containers, you are welcome to continue in this way. 

# Acknowledgments
The material in this repository has been collected from a variety of sources. Thanks to the authors of the online courses for making their valuable teachings accesible for free. Furthermore, thanks to all authors of the open textbooks, YouTube channels, exercises, and lecture notes.

Machine learning exercises were forked from [Gerges Dib](https://github.com/dibgerge/ml-coursera-python-assignments) and lecture notes and slides were forked from [Remy Marquis](https://github.com/rmarquis/coursera-machinelearning).