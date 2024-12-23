## 1. Analysis
### Problem definition
The chosen topic for the final hand-in is criminal profiling. Based on the crime and victim given, the program is supposed to predict the profile of serial killer. This project will utilize the motive method called Holmes typology to classify killers. ­Acc­ording to Holmes typology, serial killers can be act-focused (who kill quickly), or process-focused (who kill slowly).  For act-focused killers, killing is simply about the act itself. 
Within this group, there are two different types: the visionary and the missionary.
The visionary murders because he hears voices or has visions that direct him to do so(not present in our database). The missionary murders because he believes that he is meant to get rid of a particular group of people.
Process-focused serial killers get enjoyment from torture and the slow death of their victims. 
These include three different types of hedonists -- lust, thrill and gain -- and power-seeking killers.

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

###Video

Find Video presentation of solution/results here: [Machine Learning Presentation](https://www.youtube.com/watch?v=hH_-rkpCaDY)
