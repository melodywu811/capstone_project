# Capstone Project: MOOC User Logs and Course Reviews 

## Check-in 2 (March 24, 2021)  
In this project check-in, I provide updates on the preliminary problem statement and describe the datasets identified for the project. 

### Background  
#### What are MOOCs? 
Massive Open Online Courses (MOOCs) are paid/free online courses available for anyone to enroll (note: some programs and MOOCs might enroll students based on a selective admission, but this is not common). MOOCs provide an affordable and flexible way to learn new skills, advance career and deliver quality educational experiences at scale. 

Source: https://www.mooc.org/ 

### Problem Statement
Although MOOCs can provide convenience and flexibility to learner, it has a significant drawback. In an article in Science, Dr. Justin Reich and Dr. José A. Ruipérez-Valiente from Massachusetts Institute of Technology (MIT) highlight that "among all MOOC participants, only 3.13 percent completed their courses in 2017-18". 

In this project, I hope to investigate the dropout issue of MOOCs and to identify improvement areas by analyzing two data sources: 1) a MOOCs dataset with user logs and complection status from the [XuetangX (the "XuetangX dataset")](https://www.xuetangx.com/global) (China's first and largest MOOC platform) and 2) reviews scraped from [Coursera (the "Coursera reviews")](https://www.coursera.org/) (the largest MOOC platform in the U.S.). I plan to use these two datasets for different sub-analysis and use these findings to answer a series questions.

1. by conducting EDA on the XuetangX dataset, I hope to uncover some latent characterists of students who completed a course and students who dropped out using unsurpervised ML methods. 
2. I plan to use different binary classification models to predict dropout, using the XuetangX dataset, and evaluate their performance.  
3. by conducting NLP EDA on the Coursera dataset (on selected courses), I hope to understand what are some of the most discussed factors MOOC learners in data science/data analytics and identify areas of improvements. 
4. I plan to conduct sentiment analysis compare the sentiments of the reviews from begineer, intermediate, and advanced courses to see whether learners' sentiment changes in different levels of courses. For instance, students might feel more "negative" in advanced courses.
5. With understanding that many people choose MOOC courses based on their ratings and reviews, I hope to investigate whether the ratings are consistent with review texts by investigating the correlation between the two (or predicting ratings with review characteristics, including generated sentiments).


Ideally, I wish I can analyze the same sets of data (XuetangX user activities with XuetangX reviews or Coursera user aactivities and Coursera reviews), but I was not able to obtain the consistent pairs. XuetangX is the only public available MOOC user data with detailed logs, but its reviews are mostly in Chinese. Coursera has the largest users body and the most most reviews, but its user activities are not available for public use. Therefore, I will stick with analyzing user dropouts with one set of data and analyzing options, trends, and sentiments from another set. 

