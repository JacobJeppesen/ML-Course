# Introduction to Linear Regression and Gradient Descent
NOTE: This code has been forked from: https://github.com/michaelhaar/Intro-to-Linear-Regression-and-Gradient-Descent

This project contains the code for [this](https://youtu.be/uwwWVAgJBcM) video on Youtube by Siraj Raval and is aimed to teach the concept of "Gradient Descent". We are using a small dataset of student test scores and the amount of hours they studied. Intuitively, there must be a relationship right? The more you study, the better your test scores should be. We're going to use [linear regression](https://onlinecourses.science.psu.edu/stat501/node/250) to prove this relationship.

The target is to predict the students test score, when given the amount they studied.

<p align="center">
  <img src="Linear_regression_files/Linear_regression_3_0.png">
</p>

## View this project

I've generated a [preview file](PREVIEW.md), which allows us to view the jupyter notebook without any further installation steps.

(Hint: I've done this by running `jupyter nbconvert --to markdown Linear_regression.ipynb`)

## Usage

1. Clone this repository
2. Install the dependencies
3. Open the `Linear_regression.ipynb` file from the browsers jupyter tap.

## Dependencies

We'll need Python 2 or 3 with the following dependencies:

* numpy ... (for matrix multiplications)
* matplotlib ... (for creating visualizations)
* jupyter ... (for starting the jupyter notebook)

I've used [conda](https://conda.io/docs/index.html) to create an virtual environment and to install the dependencies.
```
# create a virtual environment with required dependencies
conda create --name tutorial-env numpy matplotlib jupyter

# activate the environment
source activate tutorial-env  # for macOS and Linux Users

# run the jupyter notebook server
jupyter notebook

# ... edit the notebook in your browser

# When done, shut down jupyter notebook and deactivate the virtual environment
source deactivate tutorial-env  # for macOS and Linux User

```

Of course you can also use [pip](https://pip.pypa.io/en/stable/) to install any dependencies.

## Credits

Credits for this code go to [mattnedrich](https://github.com/mattnedrich) and [Siraj Raval](https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A). I've merely created a summary for myself.
