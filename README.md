# Predicting Workers Cyber-Resilience Through Mental Health Risk Modeling in Tech Industries

## Abstract
This research investigates the impact of mental health issues such as anxiety, depression, and fatigue on employees' productivity, decision-making, and job performance. It explores how these factors can increase the risk of errors, overlooking critical details, and engaging in risky behaviors, thereby weakening cybersecurity measures. The study aims to provide insights into the connections between mental health and cybersecurity, and offer suggestions for creating a healthier and more secure workplace.

## Objectives
- Identify employees most at risk for mental health issues based on demographics, workplace environment, and policy factors, using algorithms like logistic regression, random forest classifiers, and nearest neighbors.
- Quantify the potential impacts of poor mental health on employee productivity, resignation rates, and obesity/chronic disease risks.
- Link symptoms like fatigue, trouble concentrating, and irritability to increased cybersecurity risks, including vulnerable online behaviors, accidental data exposures, and overlooking security protocols.
- Motivate tech companies to prioritize mental well-being by quantifying the risks associated with poor mental health.

## Implementation
- Data preparation: Cleaning the dataset, removing unwanted columns, and handling null values.
- Feature engineering: Creating a new target attribute 'cybersecurity_risk' based on the combination of 'treatment' and 'work_interfere' attributes.
- Data visualization: Exploring the dataset using various plots and visualizations.
- Encoding categorical data: Performing label encoding on categorical variables.
- Splitting the dataset: Dividing the dataset into 80% training and 20% testing sets.
- Testing: Implementing and evaluating various classification algorithms, including logistic regression, random forest classifier, support vector machines, and k-nearest neighbors.

## Experimental Results
Among the tested classification models, the random forest classifier achieved the best accuracy, followed by logistic regression.

## Future Work
- Explore human-AI collaboration in addressing mental health and cybersecurity challenges.
- Address ethical considerations related to data privacy, consent, and algorithmic bias.
- Foster partnerships between academia, industry, and government agencies to co-create solutions and share best practices.
- Empower employees to take ownership of their mental health and cybersecurity through training, resources, and support networks.

## Conclusion
The project aimed to analyze the intersection of mental health and cybersecurity within the tech industry workforce. Through comprehensive data analysis and machine learning modeling, patterns were identified, cybersecurity risks were predicted, and insights were provided to support employee well-being and data security measures. The random forest classifier and logistic regression models showed promising results in predicting cybersecurity risks based on mental health factors.
