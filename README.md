# Antivirus Project - Software Engineering
 
![image](https://github.com/CaptHarsh/Antivirus-Project---Software-Engineering/assets/117205669/ed4b0301-9df2-47fd-95ee-5a175dfa4e74)

![image](https://github.com/CaptHarsh/Antivirus-Project---Software-Engineering/assets/117205669/d29683b1-2e6a-4326-85b2-f07b886a300e)


# Antivirus using Machine Learning
Welcome to the Antivirus using Machine Learning project! This repository combines the power of machine learning with Python to create a specialized antivirus tool designed to analyze Portable Executable (PE) files, such as EXEs and DLLs. The primary goal of this antivirus is to determine whether a given file is malicious or benign. It achieves this through the utilization of five different machine learning models and a user-friendly graphical interface.

# Overview
Machine Learning Models
The antivirus employs five distinct machine learning models for its analysis:

    DecisionTree: Utilizes decision trees for classification.
    RandomForest: Based on random decision forests, combining multiple decision trees for improved accuracy.
    GradientBoosting: Enhances the performance of decision trees through boosting capabilities.
    AdaBoost: Focuses on improving the accuracy of weak classifiers.
    GNB (Gaussian Naive Bayes): A probabilistic model based on Bayes' theorem, often used for classification tasks.
    
# Feature Importance
During the analysis, 12 features are identified as crucial for the detection process. These features are ranked in terms of their importance in making accurate predictions:

    DllCharacteristics (0.139851)
    Characteristics (0.110925)
    Machine (0.098678)
    VersionInformationSize (0.073950)
    SizeOfOptionalHeader (0.052664)
    SectionsMaxEntropy (0.050645)
    Subsystem (0.048727)
    ResourcesMinEntropy (0.048205)
    ImageBase (0.046917)
    MajorSubsystemVersion (0.043630)
    ResourcesMaxEntropy (0.038683)
    MajorOperatingSystemVersion (0.035103)
    
# Model Training Results
The machine learning models are trained on the provided dataset, and their performance is evaluated. Here are the results:

    DecisionTree: Achieves an accuracy of 99.141615%.
    RandomForest: Achieves the highest accuracy at 99.427744%.
    GradientBoosting: Achieves an accuracy of 98.906193%.
    AdaBoost: Achieves an accuracy of 98.572981%.
    GNB (Gaussian Naive Bayes): Achieves an accuracy of 70.166606%.
    
The winning model among these is RandomForest, boasting an impressive success rate of 99.427744%.

# False Positive and False Negative Rates
The tool provides insight into its performance by reporting the false positive and false negative rates:
    
    False Positive Rate: 0.449079%
    False Negative Rate: 0.861964%
    
These rates indicate the tool's ability to correctly identify benign and malicious files, ensuring a robust and efficient antivirus solution capable of handling a variety of PE files and helping users protect their systems from potential threats.
Feel free to explore the repository, run the tool, and contribute to the ongoing development of this machine-learning-powered antivirus solution! Your feedback and contributions are highly appreciated. Stay secure!
