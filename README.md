[![Udacity logo](https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png)](https://www.udacity.com/)

### [Udacity Data Analyst Degree](https://www.udacity.com/course/data-analyst-nanodegree--nd002)

#### Project II: Investigate a Dataset

### Table of Contents 
- [Installation](#installation) 
- [Project Motivation](#motivation) 
- [Project Overview](#project_overview) 
    - [Choose Your Data Set](#step1) 
    - [Get Organized](#step2) 
    - [Analyze Your Data](#step3) 
    - [Share Your Findings](#step4) 
- [Submission](#submit) 
- [Results](#results) 
- [Licensing, Authors, and Acknowledgements](#licensing) 

## Installation 
Working in a Jupyter Notebook on your PC the installing the following packages (libraries) is required is a must. These packages may be installed using conda or pip. They include: 
- Pandas 
- Matplotlib 
- Seaborn 

## Project Motivation <a name="motivation"></a>
This is an Udacity Nanodegree project.With an interest in public health, I chose this dataset because it offers me a first hand experience of handing a data which I believed to be a real-world scenario in examining public health related issues. I was interested to see:  
- How responsive to appointments accross aga groups 
- How much did SMS influence patients showing up for appointments 

## Project Overview <a name="project_overview"></a>
You will perform your own data analysis for the final assignment and produce a file to share that details your conclusions. You need to begin by looking at your dataset and considering what inquiries it may be able to address. Then, you should utilize pandas and NumPy to respond to the queries that most interest you, and then produce a report outlining your findings. In order to accomplish this assignment, you are not obliged to employ inferential statistics or machine learning, but you should make it apparent in your communications that your results are preliminary. Since there isn't a single proper solution, this project is indefinitely open-ended. 

### Choose Your Data Set <a name="step1"></a>
- Choose Your Data Set Click this [link](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a\_data-set-options/data-set-options.pdf) (available in a Google doc [here](https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy\_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub?embedded=True)) to open a document with links and information about data sets that you can investigate for this project. You **must** choose one of these datasets to complete the project. 

### Get Organized <a name="step2"></a>
- Get Organized Eventually you’ll want to submit your project (and share it with friends, family, and employers). Get organized before you begin. We recommend creating a single folder that will eventually contain:

*   The **report** communicating your findings
*   Any **Python code** you wrote as part of your analysis
*   The **data set** you used (which you will not need to submit)

You may wish to use a Jupyter notebook, in which case you can submit both the code you wrote and the report of your findings in the same document. Otherwise, you will need to submit your report and code separately. If you would like a **notebook template** to help organize your investigation, you can click [here](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/April/5ac7a08a_investigate-a-dataset-template.ipynb/investigate-a-dataset-template.ipynb.zip). Or there may be a page in the project here called Project Workspace: Complete and Submit Project, where you can do all your work and submit the project. 

### Analyze Your Data <a name="step3"></a>
- Analyze Your Data Brainstorm some questions you could answer using the data set you chose, then start answering those questions. You can find some questions in the [data set options](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a\_data-set-options/data-set-options.pdf) to help you get started. Try and suggest questions that promote looking at relationships between multiple variables. You should aim to analyze at least one dependent variable and three independent variables in your investigation. Make sure you use NumPy and pandas where they are appropriate! 

### Share Your Findings <a name="step4"></a>
- Share Your Findings Once you have finished analyzing the data, create a report that shares the findings you found most interesting. If you use a Jupyter notebook, share your findings alongside the code you used to perform the analysis. Make sure that your report text is contained in Markdown cells to clearly distinguish your comments and findings from your code work. You should also feel free to use other tools and software to craft your final report, but make sure that you can submit your report as an HTML or PDF file so that it can be opened easily. 

## Submission <a name="submit"></a>
What to include in your submission

*   A PDF or HTML file containing your analysis. This file should include:

*   A note specifying which dataset you analyzed
*   A statement of the question(s) you posed
*   A description of what you did to investigate those questions
*   Documentation of any data wrangling you did
*   Summary statistics and plots communicating your final results

*   Code you used to perform your analysis. If you used a Jupyter notebook, you can submit your .ipynb. Otherwise, you should submit the code separately in .py file(s).
*   A list of Web sites, books, forums, blog posts, github repositories, etc. that you referred to or used in creating your submission (add N/A if you did not use any such resources).

## Results 
- I categorized the ages of patients into `pediatric_ group`, `young_group`, `middle_age_group`, and `elderly_group` 
- Of the 35422 patients that did receive text messages, 25698 patients did not show up for their appointments and 9784 patients did show up for their appointments. Receiving text messages did not influence patients to show up for their appointments. - A great number of patients elderly age group did showed up to appointments. 

## Licensing, Authors, Acknowledgements <a name="licensing"></a>
Must give credit to Kaggle for the data. You can find the Licensing for the data and other descriptive information at the Udacity Webpage.