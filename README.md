# CNT-5410-Analysis-of-Machine-Learning-Based-Malicious-URL-Detection-Methods
CNT 5410 Final Project

# Contributors 
1. Sankalp Talankar (UFID: 7322-1305)
2. Rajan Patel (UFID: 6144-9897)
3. Rahul Porwal (UFID: 4459-0947)

# Objective
Machine learning approaches have received more attention in recent years to improve the generality of malicious URL detectors. Most of the papers for these models use different datasets and metrics to evaluate their performance, making it difficult to compare the models. The purpose of this paper is to use a standardized dataset and metric to compare some of the latest machine learning algorithms for malicious URL detection. We are using the URL dataset provided by the University of New Brunswick consisting of around 610,000 URLs as a standard dataset to evaluate our models. Since it is much more damaging if a malicious URL is not detected as compared to a benign URL that is classified as malicious, it is more relevant to analyze how well the model can detect the malicious URLs. We decided to use AUPRC (Area under Precision- Recall curve) as the standard evaluation metric. Our analysis shows that deep learning models like URLNet perform better than traditional machine learning models because machine learning models use manually engineered features and they do not generalize well on data where such features are not present. So, while machine learning models are currently more popular, moving forward, deep learning models will be more prevalent.

# Code Description
A zip file of the dataset is present in the repository. 

There are 5 python notebooks present in the repository: 
1. Lexical_Analysis.ipynb - Analyzes the lexical features and runs on various ML models. 
2. Host_Features.ipynb - Analyzes the host features and runs on various ML models. 
3. Combined_ML_Models.ipynb - Analyzes all the features (lexical and host) and runs on various ML models. 
4. cnn-for-malicious-url.ipynb - Analyses the dataset using Convolutional Neural Net
5. malicious-url-detection-using-gru.ipynb - Analyses the dataset using Convolutional Neural Net

# Instructions:
1. Download all the files. 
2. Unzip the dataset in the same location as that of the notebook files. 
3. Makes sure the path mentioned in each notebook for the csv is appropriate. (check directory location at pandas.read_csv part of the code)
