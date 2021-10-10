# NIH Internship

Anuva Banwasi <br />
Software Engineering Fellow, National Institutes of Health (NIH) <br />
Coding it Forward Fellow <br />
06/2021 - 08/2021 <br />


This repository includes sample code from my internship. The Classifier.ipynb is a Python notebook that includes my code
for a supervised ML model that classifies an application grant based on its abstract text and determines the likelihood
that the grant is data science related. The classifier correctly identified 192/195 data science-related grants in 2020.


Project Goal: To improve the process for classifying and analyzing data science-related application grants at the NIH.
 
1. Built data loading module in Python that automatically scrapes and extracts new project application grant data as it is published on the public NIH RePORTER website. 

2. Implemented, trained, and tested machine learning model in Python using natural language processing techniques that classifies application grants and determines the likelihood that a project is data science-related based on its abstract text. 

- Cleaned and vectorized text with term frequency-inverse document frequency (TD-IDF). 
- Trained and tested supervised ML models such as support vector machines, stochastic gradient descent, and ensemble models with scikit-learn in Python. 
- Analyzed results with confusion matrix on multiple datasets and Receiver Operating Curve (ROC). The classifier correctly identified 192/195 data science grants in 2020 and had area under ROC over 0.90. 

3. Developed and deployed real-time, interactive web application using Python and Streamlit that provides an open-source, easy-to-use platform to visualize, analyze, and curate the NIAID data science portfolio.

Both the classifier and web application continue to be used by the Office of Data Science and Emerging Technologies at the NIH to help perform portfolio analysis on project grants. 
