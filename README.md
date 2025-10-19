# Introduction
This research examines whether beginners in Python can create machine learning (ML) models from scratch without using pre-built modules. To fully understand how ML modules are made, exploring the algorithms and calculations underlying them is essential. Harnessing the programming skills gained from York University's graduate-level Python course "Computer Programming for Experimental Psychology (PSYC6273)", alongside insights from a Python programming books and free resources like YouTube, Kaggle, and GitHub, this study aims to not only deepen our understanding of Python but also build a strong foundation in research and data analysis for our social science studies and research designs. Through hands-on projects, I will explore and develop machine learning models such as k-Nearest Neighbors (k-NN), Linear Regression, and Logistic Regression, Decesion Trees, Random Forests, and Support Vector Machines (SVMs), translating theoretical concepts into practical, real-world applications. 

The first three machine learning models (k-NN, Linear Regression, and Logistic Regression) used a subset of the PISA 2018 dataset, originally compiled by the OECD, to assess the academic performance of 15-year-old students worldwide. For this project, a preprocessed version provided by Puah (2021) was used, and a random sample of 300 observations was selected to reduce computational demands. The dataset includes variables related to students’ scientific literacy, socioeconomic background, educational resources, and language spoken at home. Twelve key variables were chosen using a Variable Importance function from a random forest model, and their names were simplified for clarity. This dataset served as the foundation for building and testing machine learning models in a psychological research context.

## k-Nearest Neighbours (k-NN)
The model was designed to predict the language spoken at home (English vs. Non-English) based on the parents' wealth. This classification task aimed to explore sociolinguistic patterns using a simple distance-based algorithm.

## Linear Regression
The model aimed to predict students’ science literacy scores using home ownership as the independent variable. This regression task examined whether socioeconomic indicators could explain academic performance.

## Logistic Regression
The model was used to predict the probability that a student speaks a language other than English at home, using family wealth as the predictor. This binary classification task explored the relationship between economic status and language use.

Three additional machine learning models—a Decision Tree, Random Forests, and a Support Vector Machine—were developed using data from the National Financial Capability Study (NFCS), curated by the FINRA Investor Education Foundation. As of 2025, the NFCS is in its sixth edition and surveys over 25,000 adults across all 50 states and the District of Columbia. It offers a detailed snapshot of financial capability in the U.S., encompassing variables on financial knowledge, behaviours, experiences, and attitudes. The dataset covers areas such as financial stress, saving habits, retirement planning, credit card use, debt patterns, and financial literacy, as well as demographic factors like age, income, education, and household structure. This comprehensive scope makes it an ideal resource for examining psychological and behavioural aspects of financial decision-making, which this study uses to train machine learning models from the ground up.

## The Decision Tree 
This model was designed to find out whether financial knowledge, education, and security predict a greater willingness to take investment risks. 

## The Random Forest 
This model examined whether complex patterns of credit card usage—such as late fees, minimum payments, and cash advances—can predict financial vulnerability. 

## The Support Vector Machine (SVM) 
This model investigated whether demographic and behavioural traits, including age, fintech usage, and self-rated financial knowledge, systematically distinguish cryptocurrency investors from non-investors. Each model was implemented from scratch using core Python to emphasize algorithmic transparency and educational value.

By meticulously dissecting each step and coding block, I provide practical guidance for individuals with minimal Python experience (near zero) to comprehend and apply these machine-learning models in psychological studies. I inspire fellow psychological researchers to embrace advanced statistical tools, including machine learning and large language models, to push the boundaries of our field. This study serves as a candid journal, documenting the victories and challenges of my learning journey and offering my insights and encouragement to those venturing into these transformative psychological methods.
