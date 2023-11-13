# DATA 6505 Final Project
## Fall 2023
__This is the final project document.__

## Overview
Students work in 2/3-person teams to define and complete a moderately-sized analytical project in Python. Detailed instructions are provided regarding selecting and framing a suitable analysis. Grading criteria will reflect demonstrated achievement of the objectives and compliance with the requirements.

## Objectives
* Apply Python skills to a student-selected analytical project of moderate (but nontrivial) scope and complexity.
* Demonstrate mastery of Python, Numpy, Pandas, Matplolib, and Jupyter.
* Work in teams, with professional-quality tools and standards.

## Guidance
* The core work required for a passing project is to build descriptive analytics that demonstrates mastery of Numpy, Pandas and Matplotlib in public repository created via Google Classroom.
* Students are strongly encouraged to go above and beyond and create interesting datasets to then do analytics on, that demonstrate the interaction between a builder mentality, business intuition, and software excellence.
* Above and beyond examples could involve other engineering steps, but with focus on making sure you focus on the analytics.
  * Building a python clone of a game like Angry Birds or Flappy Bird, training a model to solve flappy birds while tracking data on model performance, and building analytics/reporting on the models learning process
  * Scraping data from websites and doing analytics on what you collected
  * Parsing a massive, messy, opensource dataset such as YouTube-8M, etc, extracting features from it, and doing analytics on that
  * Make your analytics interactive
  * Set up your interactive with testing to help you collaborate with your team as if you were an industry team
* The focus will always be on the conclusion of building a business analytics report, but if you have time to choose a meaty problem to solve in a business-appropriate way that ends in that report with software documentation for how and why it was built the way it was, that could prove much more value to your resume and career than stand-alone analytics (But that depends on the analytics, some people make very successful careers out of complex dashboarding).

## Project Requirements
* **All work must be your own.** It is your responsibility to demonstrate the unique contributions made by your work. You are also expected to thoroughly understand and be able to explain any work done by your teammates.
* **Academic honesty policies and scholarship norms apply.** All relevant previous work and data sources must be properly cited.
* **The analysis must be fully reproducible, even and especially with new data.** This is to be professional work, subject to prevalent standards. Suggestion: create a separate module to load/clean/integrate your data. That will allow us to test and reuse your work in other projects.
* **Descriptive analytics (as in BUAN 6500) are sufficient.** However, there is no need to constrain your work. If you can apply forecasting or decision modeling, then feel free to do so.
* **The analysis should stand on its own.** All work will be posted a *public* repository created via GitHub Classroom. You will be asked to present your work on the final day of class, but the analysis itself should be readily accessible and understandable from your final notebooks.
* **Project size and scope should be sufficient to demonstrate mastery of Numpy, Pandas, and Matplotlib.** At a minimum the datasets used should have at least 10K records with a dozen or more fields. Further, there should be some opportunity for you to filter/reduce/analyze the data using Numpy/Pandas. If the work could just as easily be performed by an undergraduate in Excel, then keep looking for another project.
* **All data used must be posted in your GitHub repository.** If you are borrowing data from Kaggle, then please cite the original source in your `summary.ipynb` notebook. It should be possible for anyone to reproduce your work, including collecting the data from original sources.
* **Document your work.** At a minimum, each analytical step (code cell) should be documented with markdown cells above and below stating your intention (_above_) and interpretation (_below_). Your notebooks should tell a story about the data. 

<!--**One should be able to read the rendered notebook in GitHub (without running your code or your presentation) and know exactly what you did, why you did it, and why we should care about the results.**-->

## Instructions  

1. **Watch and learn.** Study the following tutorial, which sets the bar for what constitutes A-level work in this course:  
[Reproducible Data Analysis in Jupyter](https://jakevdp.github.io/blog/2017/03/03/reproducible-data-analysis-in-jupyter)  
The tutorial is in 10 parts, with some of the more advanced work in the second half. At a minimum, your project should use the practices demonstrated in videos 1-5. To get the best grade, however, try something more advanced like the practices shown in videos 6-10.  
2. **Survey the best examples you can find.** One very convenient place to look is [Kaggle](https://kaggle.com), which has submissions from numerous data analytics competitions. Here a few particularly engaging Kaggle submissions to study:
  * [asindico//from-exploration-to-prediction](https://www.kaggle.com/asindico/from-exploration-to-prediction)
  * [anokas/exploratory-data-analysis-4 2017](https://www.kaggle.com/anokas/exploratory-data-analysis-4)
  * [sudalairajkumar/simple-exploration-notebook-5](https://www.kaggle.com/sudalairajkumar/simple-exploration-notebook-5)
  * [pmarcelino/comprehensive-data-exploration-with-python](https://www.kaggle.com/pmarcelino/comprehensive-data-exploration-with-python)
  
  <!--* [This](https://github.com/fairfield-university-ba505-fall2018/final-project-filip-s-angels) is an example of last year's student project in this course. You should use that as the reference for an excellent project. __NOTE__ that two of the three students in this group got hired because of this project.-->

   While some are more "finished" than others, you'll find that each tells a story with data. Try to learn to do that.  

3. **Find a suitable data source.** It must meet the requirements above. Collecting your own data (from an API, crawling/scraping, etc.) is encouraged though not required. If you are using a dataset discovered through Kaggle, then be sure to cite it and state how the analysis you are doing is different. Whatever you do, don't just replicate someone else's analysis. That will result in an immediate F for the course and (very likely) expulsion from the program. 
4. **Develop a few analytical questions that you'd like to answer based on the data.** The questions should be stated in the preamble to your notebook. The analysis should also demonstrate your abilities. Read the requirements again to makes sure your analysis will comply.
5. **Do some analysis**. This is likely to be a learn-as-you-go process. Suggestion: each team member should keep a scratch notebook file for trying things out. Then transfer your work to the finished notebook just before completion. However, only submit one notebook (with __clear instructions__ of the source data) as the final presentation.. 
6. **Try something more advanced.** Once you have a basic framework for your analysis, extend it with something more advanced. Perhaps you could try an advanced plot or maybe another data source or maybe replicated sampling to demonstrate reproducibility/lack of bias.
7. **Write a `summary.ipynb` notebook inside your folder outlining your project.** This file should be **markdown** cellls only, with links to your actual code notebooks. Instead of using slides, you will start and end your final presentation with this file, so use it to link to all your files and provide (meta) information about your project: motivations, data sources, challenges, lessons learned, etc. Suggestion: write this stuff early and update it as you go along.
8. **Clean up your final notebooks and the folder.** The final notebook is your presentation (i.e., there will be no slides) so make sure it is readable on a TV monitor from across the room. It is also your report, so make sure every objective, decision, interpretation, and conclusion you make is throughly explained and professional-looking. (Yes, styling and organization matters. We're professionals, right?) Make sure you don't have any unfinished or extraneous artifacts left over from your explorations. (Again, we're professionals, not undergrads.)

## Timeline/Workplan
* **Oct, 25:** Review assignment, form teams, and begin planning out the work. Do not create any shared folder yet. 
* **Nov, 15:** Follow instructions in class to set up your teams and shared folders. Also prepare a short (5-minute verbal) __proposal__ for your project that covers i) data source; ii) research questions; iii) anticipated challenges; and iv) what results you expect to present on the final day of class.
* **Nov., 22 and 29, Dec 6.:** Use the class time to meet with your team and ask questions when needed. (Note: You are expected to show up for class. We have other classwork to do yet.)
* **Dec., 13:** Preview of your results. This is like a dress rehearsal to address any remaining problems before your final presentations. 
* **Dec., 20:** Present your finished work. Walk us through your project, including your source/motivations, finished notebook, modules/testing, and lessons learned. There will be no slides for this. Just use your work. See the instructions for the `summary.ipynb` file above. 

