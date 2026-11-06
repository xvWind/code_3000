# code_3000
Collection of Assignments for CSE 3000: Contemporary Issues in Computer Science and Engineering

_Note_: Odd-numbered assignments are in HuskyCT, while even-numbered assignments are found in this repo and can be submitted to Gradescope via a Github connection.

## Outline of Assignments

### Module 02: Bot Predictor
Your goal is to build a machine learning model using given data and a Python template. You'll make changes to the GradientBoostingClassifer in mod02_build_bot_predictor.py and then test your changes in mod02_test_bot_predictor.ipynb. Can you minimize the misclassification rate on the test set?

### Module 04: Model Bias
You are given a model that was built to predict a mystery variable using zip code, income, and education level. The variable "group" represents a demographic that is prohibited and was NOT used in the model. Your goal is to use the SHAP package to review this model for bias.

### Module 06: Data De-Anonymization
Your goal is to connect anonymized data back to its source data and check the match rate. To complete this activity, write functions in the "deanonymize" script to (1) link the records in the two datasets and (2) calculate the rate at which you are successful doing so. 

### Module 08: Sustainability in Computing
You will be given a toy dataset and have the opportunity to explore the potential effects of choosing sustainable energy sources to perform computations. You'll code the energy calculation in "sustainability calculations" script, and then you can review the results of various decisions in the "check calculations" notebook. 

# Ethics Statement
Reading Chapter 5 of Ethical Machines made me realize that most AI ethics statements fail because they are too vague to actually guide how software gets built. Listing broad concepts like fairness or transparency does not really help developers make day-to-day decisions when writing code or working with data. My view on ethics in software engineering is pretty practical: rather than focusing on abstract values, it is much more useful to look at the specific risks of a project, where the training data comes from, and how the end product might negatively impact users. Moving forward, I think ethical considerations should just be defined as clear, testable rules alongside standard technical requirements so teams know exactly what boundaries they need to follow before deploying a system.