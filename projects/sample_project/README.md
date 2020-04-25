# Causal Models of a Particular Domain (Example Project)

## Authors 

[Robert Osazuwa Ness](https://www.linkedin.com/in/osazuwa/), [Author 2
](https://towardsdatascience.com), [Author 3](https://www.khoury.northeastern.edu)

## Abstract

People often use predictive models to recommend actions within a particular domain.  However, those predictions are biased by confounding.  Addressing this issue requires a causal model.  We built a causal generative model to analyze data in this domain.  We used public data to validate the testable implications of the structure of the model.  We then chose a parametric form of the model that performed well in posterior predictive checks.  We show the causal effects of the action on the outcome and provide a simple Web app that illustrates an application of the proposed method.

[See video abstract](https://www.youtube.com/watch?v=o3GfnEjTdIQ)

## How to explore this project

There is one jupyter notebook: **OOP-Scene-Generation** and two folders in this project: a **/pic** folder which includes the basic input images we have and a **/generatedPic** which includes all the final images generated.

* **OOP-Scene-Generation**: all project details are included in the jupyter notebook which can be used as a tutorial. The project can be run directly using the jupyter notebook with pre-installed packages mentioned below in **Reproducibility** part.

* **/pic** folder: the input entity and background images are in this folder and their name have to match what the values are in jupyter notebook. (They should match the values of gender, type and background in the alias.) The image type has to be .png or .jpg. If there are both .png and .jpg file with the same name, .png file will be used by default.

* **/generatedPic** folder: all the pictures generated from the code will be saved as .png file in this directory by default named with their descriptions. 

### Presentation

There are a **built-in user interface** in the project. Users can select the variables and values that they want to condition or intervent on. The user interface generation function (userInterface()) needs to be run once to get the variable_choices window. After it is generated, users can change the values of the selected variables and click on the corresponding button everytime they want to get a new picture. The variable selection window are shared by all the buttons, so please make sure that correct values are selected before the image generation.



Presentation means you have done your best to make it easy for future students to understand and learn from your work.  A bad presentation is having many badly named notebooks with lots of code, and little text explanation.  NEU students will be penalized for poor presentation.

Presentation also means clean code.  **Python code must adhere to [flake8](http://flake8.pycqa.org/en/latest/index.html#quickstart)**, even if the code is inside Jupyter notebooks.  R code should follow R conventions.  I suggest the [tidyverse style guide](https://style.tidyverse.org/).

**Avoid unneccesary code and output in notebooks**.  If loading a package in your R notebook causes a bunch of warnings and messages to be printed, turn message printing and warning printing off in that block of code.  Don't import libraries in your Jupyter notebook if you are not going to use them.  Don't have `!pip install ...` lines, just tell us what to install.  Don't have long-run on lines

### Reproducibility

**Reproducibility** means that someone can easily clone this repo and reproduce your work.  Ideally, you should have notebooks (R Notebook or Jupyter notebooks) that you can be run directly.

* Make it clear what libraries need to be installed.
* You can put data, figures, code, slides, and other files in their own directories.  If you do, explain them in your version of this README.md.
* If you want to get fancy, you can [wrap your analysis in an R package](https://www.r-bloggers.com/creating-an-analysis-as-a-package-and-vignette/), or a Python library, or use the [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/).  But this is purely a matter of personal preference. 

Other notes:
* Above, there is a link to a video abstract.  You **must** create a **short** video summary of your work.  No more than 5 minutes.
* Use links in the author's section to link you your own websites, Linkedin, online portfolios, etc.
