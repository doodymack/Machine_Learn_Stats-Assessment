
# H Dip in Data Analytics 2021-2022
# Machine Learning & Statistics
## Winter Semester Assessment
***
<br>
by Paul Mc Grath


Add in detasils here about the repository

## Setup

How to Install Jupyter (paste from below)


## Running the Notebooks


How to Run (paste from below)


## What to expect (explore)

Paste in from below and edit


## Referencesjupyter note

add in references demonstrating online learning such as: <br>

- link to statisitical functions
- wikipedia for general stats







# Fundamentals of Data Analytics 2021-2022
## Winter Semester Assessment- Paul Mc Grath
***
<br>

This repository contains jupyter notebooks and other relevant files used to demonstrate my work on:
- ``Machine Learning``
- ``Statistics``
<br>

 for my module: 
 Fundamentals in Data Analytics

---
---

# Install

Steps to install
---
<br>

The work is based on **Python 3** code and executed via a **Jupyter Notebook** <br>
Jupyter allows the creation of a Notebook that contains summary text and image files while also allowing the running of of Python code. <br><br>
The key files to run in the repository are:  **Pyplot.ipynb** and **XXXXX**. <br>
To execute the work you should have **Python 3**  and  **Jupyter** notebooks installed. <br><br>


### How to install the necessary packages:
While Jupyter runs code in many programming languages, Python is a requirement (Python 3.3 or greater, or Python 2.7) for installing the Jupyter Notebook. It is recommended to use the Anaconda distribution to install **Python** and **Jupyter**. <br>
Anaconda conveniently installs Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science.

***Note the packages and dependencies are in my 'requirements.txt' file*** <br> <br>

### Installation instructions:

- [Download Anaconda](https://www.anaconda.com/products/individual) <br>
 Its recommended to download Anaconda’s latest Python 3 version (currently Python 3.5).
- Install the version of Anaconda which you downloaded, following the instructions on the download page.
This should also have installed Jupyter Notebook. <br>
---
<br>

## Running the notebook in Github:

Note: 
- The notebook is created to automatically run all code if executed within the GitHub 
- should the code not run, close the file and re-open <br><br>

---

## Running the notebook on your local PC environment:

After installing **Python** and **Jupyter** packages via **Anaconda**:


How to run the ipynb files:

- The key file is ipynb file.
- Once this is opened Jupyter starts off in web browser but is running on your machine
- Once opened click on the 'kernel' dropdown button on the taskbar at the top of the screen
- click on 'restart kernel and run all cells'
- Thus recreates the text and re-runs the code in each program cells from the beginning
- read the notebook from top to bottom
- read the text above each program cell for background as to the purpose of the python code 
- within each code are additional commments on the specific code  as non-executable commented out brief explanation  i.e. ***#asterisk followed by green text***

#### In summary once the required code is downloaded:
1. Download the required packages
2. open the ipynb file: 
3. restart the notebook
4. read the notebook from top to bottom

Troubleshooting:
- The code has been checked to ensure it runs end to end
- However if you get a warning then restart the kernel again as per above <br>

---
---



## Explore 


Have a look at the **three?** notebooks in this repository in Jupyter

Some interesting aspects:
The Notebook `plots.ipynb` has three different plot types as examples. You can edit the parameters of the plots to see different effects.
e.g.
- in the 'beginning with matplotlib' the  x and y values can be changed to determin their impact Change the parameters and rerun the cell code (from run dropdown menu)
- For the visualizations of the iris dataset using matplotlib histograms the # of bins can be changed  from 10 to e.g. 20 i.e.: <br>

**xxxxx**

to determine the impact the parameter in  representation of the data.

In the plot2x2 pairwise sns plot the attributes to be plotted can be changed i.e. currenty: 'petal width' vs 'petal length'  to other attributes i.e.: sepal_width/sepal_length/petal_width/petal_length.  Thus individual correlation plots can be generated for all plots.

---

The Notebook `CAO_points.ipynb` describes the method to pull the CAO points dat from the CAO website for three years (2019-2021) for comparison purposes.

- The 2021 points required use of a regular expression to 'scrape' th required data from the html.
- It was noted that some course did not list points. However there is no guarantee that these courses do have points for latter years.  Thus a simpler regular expression that included these was chosen.
-The 2020 data was in excel format which made it easier to upload to a PANDAS dataframe
- The 2019 data was in pdf format.  A more manual method was suitable here.  The pdf was converted to an editable word format before being readied for csv (comma separated) creation.
- Notepad++ was used for this purpose. Care was takne not to delete any points data.
- To create a master dataframe the 2021 course list was used.  Data from each year was concatenated together using PANDAS functionality- while removing duplicates.
- The final dataframe was checked for completeness.
- After concatenating it was noted the course points data was read as 'object. This was converted to 'float' using PANDAS functionality prior to plotting/analysis.
- The analysis chosen was the histogram/kernel density estimate functionality.

#### Mean
The mean points are comparable between 2019 and 2020 (0.35% drop between 2019 and 2020)
There is a marked rise in the mean CAO points from 2020 2021 (16% from 2020)
The mean rise is to be qualified that the number of courses per year are not constant
#### Combined Histogram
The combined plot clearly shows a gradual shift over the period analysed (2019-2021) from course points centred on 250-300 points to a broader span for 2021 with indications of bimodal distribution.

#### histplots/distplots/kde:
The combined histplot-kde clearly shows the course points shift from 2019 to 2021.
This may identify the apparent points 'inflation' seen in 2021 CAO courses for specific courses.

The above techniques establish if there is an overall trend across the years. <br> 
However the data analysis does not measure the change (increase/decrease) in specific course points.<br> This is difficult as courses offered in one year are not necessarily offered in subsequent years.<br> 

#### Future work
An analysis of overall course inflation by measuring the course inflation per course and summing these per year could be an interesting analysis.<br> Of interest is does this collate with the 'course code blind' analysis using histogram/kernel density estimates.<br> 


### Conclusion:

The project allowed me to improve my working knowledge of the python PANDAS and Matplotlib  functionality to extract multiannual data from online data of different format. <br>  The project allows me put forward ways to scrape and engineer online data into a dataframe. <br>  Therafter the functionality of matplotlib can be used to analyse the multiannual data for trends.<br> 
I learned that there are many ways to capture data and transform it to trendable data using the functionality of PANDAS. <br> 
Regular expressions are fundamental in allowing scraping/capturing of data from online ansd 'messy' data.<br> 
However the power of PANDAS does not avoid the need from time to time for the data analyst to manually inspect the raw data and clean it ready to be uploaded as a csv file. <br> 



## Contact: 

[doodymack@gmail.com](mailto:doodymack@gmail.com)


# Numpy_Random_Assessment

An investigation into the Numpy package for assessment as part of  Programming for Data Analysis Assessment.

Author: Paul Mc Grath

Tools use: Numpy/Jupyter lab/

Objective:

Using a Jupyter lab notebook to explain the use of the NumPy package including details of at least 5 5 of the distributions provided f or in the NumPy package.  The following are covered:

1. Explain the overall 
2. Describe
3. Explain 

references:
https://www.tensorflow.org/guide
https://www.tensorflow.org/resources/learn-ml?gclid=Cj0KCQiAsoycBhC6ARIsAPPbeLsFBtcANYp7SyiaiNTmQpVvJUL3ie1M3o_RvAcENzzBD-GEXHa0kBYaAlSEEALw_wcB
https://towardsdatascience.com/all-the-numpy-you-need-to-supercharge-your-deep-learning-code-e7a22fe4ede2