Network-based Intrusion Detection Systems are very popular in today’s networking environments and they’re known to be a security tool which defends attacks from internally, externally and detects unauthorized access into the network. Concepts of NIDS managing firewall activates to guard the whole network infrastructure from unauthorized access via IP address and port numbers. NIDS is usually implemented outside the firewall monitoring the whole external traffic incoming by detecting and identifying the anomaly activates. However, if the network is multi-layered and complex NIDS are required to maintain and update due to the changing network system, and only a single IDS could only encompass the sensitive or confidential data of any network. Resulting in complications to process and manage the vast amount of traffic for the reason that there is only a single- entry point of a network output. At this point the NIDS requires more computational resources and power which could lead to having devasting affect in exhausting the NIDS. Leading to the overwhelmed NIDS becoming the bottleneck in a network. Delaying the outgoing and incoming packets due to inspections or even dropping the packets. Detection mechanisms will fail to identify any intrusion due to the dropped packet becoming incomplete packet matching. Safeguarding the confidentiality of any network for example, an organization network structure from an attack and make sure the privacy of all users, network administrator is protected. There are large varieties of machine learning algorithms have been widely used to detect the Anomaly Detection NIDS e.g. Support Vector Machine (SVM) Machine Learning (ML). There has been a subsequent development of Network Intrusion Detection System as classifiers to distinguish any anomaly from normal traffic. Recent researches findings concluded that some NIDS systems has a feature selection ability to make a subset of applicable attributes from the dataset to enhance the result of classifications. These attribute selection aids in abandoning the prospect of wrong training.Throughout the course of this research study, a machine learning intrusion detection models were developed utilising the random forest, Naïve Bayes, K nearest neighbours and decision trees algorithms. The recursive feature importance measure was applied to obtain the most important features for selection to the machine learning algorithms. Thereafter, the models were optimized with different techniques such as Random Search, Grid Search and TPOT to achieve a higher detection overall accuracy and examine how every parameter affects the models. It was observed that the TPOT automated genetic algorithm has generated the best optimised pipeline with the highest average score for all the models. The lowest accuracy result for binary classification was from the Naïve Bayes algorithm (91.23%), followed by Decision Tree (98.86%) and KNN (99.00%). The highest result was from the Random Forest achieving 99.44% for binary classification.
mitigate it.
The project was implemented in a virtual environment. The following tools were utilized to compelete the project:
- NSL-KDD,
- Virtual NIDS Lab and Open-Source IDS tools
- Fedora machine, Linux.
- Kali Linux VM Snort, Suricata.
- Jupyter Notebook (Anaconda).
- Python 3.
- Scikit-Learn
