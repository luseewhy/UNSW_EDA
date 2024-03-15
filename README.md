# UNSW_EDA
Intrusion Detection Systems
IDS are of two types: misuse-based IDS and the anomalybased IDS (Aydin, Zaim, & Ceylan, 2009). In misusebased IDS, the attack signatures of new connections in a network are compared with the existing attack signatures to determine whether the new connection is malicious or not. Misuse based IDS are useful only in detecting the known attacks. What is more, dangerous are the latest attacks or the "zeroday" attacks, which are never seen before (Boutaba, et al., 2018). Here, anomalybased intrusion detection systems come into the picture. The basic idea of anomalybased intrusion detection system is to check for the normal behavior of the network and report any deviation from the expected. Anomaly-based IDS can be implemented using various machine learning approaches.

# UNSW-NB15 > KDD
The UNSW-NB15 dataset (The UNSW-NB15 Dataset Description, 2018), an upgraded version of the KDD cup dataset. This dataset helps us analyze the features of a healthy network and a network under attack. UNSW-NB15 is a modern, more balanced dataset and is becoming the new benchmark dataset for building robust intrusion detection models(IDS). This dataset is class wise more balanced as compared to other datasets available for intrusion detection. The UNSW-NB15 dataset although less in size as compared to others, but even less redundant, is sufficient to train a model with high accuracy.

CLASSES IN UNSW-NB15: The UNSW-NB15 dataset contains ten classes, namely: Normal, Fuzzers, Analysis, Back- doors, DoS, Exploits, Generic, Reconnaissance, Shell Code, and Worms.

# EDA
Exploratory data analysis is the process in which we use data visualization techniques to analyze and find patterns in the data so to have a better understanding of the features. Through EDA we get insights of how the data is distributed, how one feature is correlated with the other and what anomalies are there in the dataset. Based on the insights, we make future decisions on what could be the optimum features to include in the dataset while training or what relevant features could be extracted for improving the accuracy of the model.

Dataset Used
Binary version of dataset is also available where 0 describes normal and 1 for attack. There are total 45 features in the dataset which helps in accurately classifying the targets. The size of training data is 175,341 samples whereas 82,332 is the size of the test data.

# RESULTS:
Random Forest Accuracy: 1.0000
SVM Accuracy: 0.6777
Logistic Regression Accuracy: 0.7465

# CONCLUSION:
Key Takeaways:
1.	IDS Strategies:
•	Grasped the strengths and weaknesses of misuse-based and anomaly-based IDS strategies.
•	Acknowledged the necessity of combining both approaches for comprehensive threat detection.
2.	Dataset Understanding:
•	Gained proficiency in navigating the UNSW-NB15 dataset for intrusion detection model training.
•	Acknowledged the dataset's balanced nature and suitability as a benchmark.
3.	Data Preprocessing Skills:
•	Acquired practical skills in data preprocessing, specifically in outlier removal using z-scores.
•	Recognized the impact of data quality on model performance.
4.	Visualization Insights:
•	Appreciated the role of visualization, such as correlation heatmaps, in understanding complex datasets.
•	Realized the importance of EDA for making informed decisions during model development.
Future Implications:
1.	Continued Learning:
•	Recognized the ever-evolving nature of cybersecurity threats and the need for continuous learning in the field of intrusion detection.
2.	Application in Real-World Scenarios:
•	Understand the practical application of learned concepts and skills in real-world scenarios.
•	Acknowledge the ongoing importance of staying updated on the latest advancements in IDS and dataset standards.

