## 1. Analysis
### Problem definition
The chosen topic for the final hand-in is criminal profiling. Based on the crime and victim given, the program is supposed to predict the profile of serial killer.

### Business Objective
The objective of this project is to assist law enforcement agencies in identifying potential future criminals and assessing an individual's likelihood of engaging in criminal behavior based on tendencies observed in historical data. By leveraging data-driven insights, the goal is to enhance the efficiency and accuracy of criminal investigations, particularly in profiling serial offenders. This approach aims to improve the predictive analysis of behavioral patterns, aid in the identification of potential suspects, and help prioritize investigative resources.

The key benefits include:

* Resource Optimization
* Increased Case Resolution Rates
* Public Safety Improvement
* Standardization of Profiling Practices

### Framing the problem
This is a supervised machine learning problem as the goal is to build a model that classifies criminal profiles (e.g., age, zodiac sign, gender) based on labeled historical data about known serial offenders and their crimes. This data includes attributes such as behaviors, occupations, and victim profiles.

Supervised learning is well-suited for this task since the dataset contains input-output pairs, allowing the model to learn from historical patterns. The variables used for modeling will primarily be categorical and discrete, aligning with the nature of the data

### How is performance going to be measured?
Performance will be calculated based on the model's ability to predict the most accurate profile of the assailant.
Performance should be measured using the following:
* Classification Accuracy (if building a classifier): How well does the model correctly predict characteristics or behaviors?
* Precision and Recall (or F1-score): Especially important in minimizing false positives (e.g., wrongly profiling innocent individuals) and false negatives (missing critical leads).
* Time-to-Insight: A metric that evaluates how quickly actionable insights are generated.

