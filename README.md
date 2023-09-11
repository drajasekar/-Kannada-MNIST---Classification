# Kannada-MNIST-Classification

## Description
The "Kannada MNIST Classification" project addresses a fascinating machine-learning challenge that involves recognizing handwritten digits in the Kannada script. Unlike traditional Hindu numerals, the Kannada script represents the numerals used predominantly by the people of Karnataka in southwestern India, where the Kannada language is spoken by approximately 45 million native speakers.
![download](https://github.com/drajasekar/-Kannada-MNIST---Classification/assets/44079369/841feb55-ee84-4f16-8cda-ad4399d770e9)


Problem Statement:

The primary goal of this project is to create a robust classification system for Kannada digits. The dataset used for this task is known as the "Kannada MNIST" dataset, which is a recently-released dataset designed specifically for the Kannada language. This dataset consists of handwritten Kannada digits, and it presents a 10-class classification problem, where each class corresponds to a different digit.

Key Components:

Kannada Script: Kannada is a rich and intricate script used for writing the Kannada language. It holds cultural significance in the region and is distinct from the familiar Hindu-Arabic script used for English numerals.

Dataset: The dataset required for this project can be obtained from Kaggle at the following link: Kannada MNIST Dataset. It includes a substantial number of handwritten Kannada digits for both training and testing purposes.

Dataset Curation: The dataset's curation and details have been meticulously documented in the research paper titled "Kannada-MNIST: A new handwritten digits dataset for the Kannada language" by Vinay Uday Prabhu. You can find this paper here: Research Paper.

Project Goals:

The primary objectives of this project:

Utilize machine learning techniques to accurately classify handwritten Kannada digits into their respective categories.
Apply dimensionality reduction through PCA (Principal Component Analysis) to simplify the feature space.
Experiment with various classification models, including Decision Trees, Random Forest, Naive Bayes, K-NN Classifier, and SVM.
Evaluate the performance of each model using metrics such as precision, recall, F1-score, confusion matrices, and ROC-AUC curves.

Classification Model test Result for 10 component size :

SVM
F1 Score:  0.8866826079564731

KNeighborsClassifier
F1 Score:  0.8781246801433077

LogisticRegression
F1 Score:  0.805346718278235

DecisionTreeClassifier
F1 Score:  0.8034572508382888

RandomForestClassifier
F1 Score:  0.8747518117030051

Naive Bayes Mode
F1 Score:  0.7710828842695301

RoC - AUC curve:
![img1](https://github.com/drajasekar/-Kannada-MNIST---Classification/assets/44079369/49e26b4c-6213-413e-a0c0-a64e73151fa3)



Classification Model test Result for 15 component size :

KNeighborsClassifier
F1 Score:  0.9088698616752358

SVM
F1 Score:  0.9144279375940038

LogisticRegression
F1 Score:  0.8319884050551556

DecisionTreeClassifier
F1 Score:  0.8087277078582826

RandomForestClassifier
F1 Score:  0.8915821501693953

Naive Bayes Mode
F1 Score:  0.7813117107240918

RoC - AUC curve:

![img2](https://github.com/drajasekar/-Kannada-MNIST---Classification/assets/44079369/4600c6fa-fa88-4328-8492-e01ee0e2fadf)



Classification Model test Result for 20 component size :


SVM
F1 Score:  0.9308308853317468

LogisticRegression
F1 Score:  0.8501780419253402

DecisionTreeClassifier
F1 Score:  0.8049057059967286

RandomForestClassifier
F1 Score:  0.8992025309723746

Naive Bayes Mode
F1 Score:  0.7958024556103679

RoC - AUC curve:

![download (2)](https://github.com/drajasekar/-Kannada-MNIST---Classification/assets/44079369/487cd59f-3e52-40da-b8b2-c79853883d9f)

Classification Model test Result for 25 component size :


SVM
F1 Score:  0.9359155693048505

LogisticRegression
F1 Score:  0.8604267002739955


DecisionTreeClassifier
F1 Score:  0.8033021947537583

RandomForestClassifier
F1 Score:  0.9043064241285714

Naive Bayes Mode
F1 Score:  0.8037561814444575

RoC - AUC curve:

![download (4)](https://github.com/drajasekar/-Kannada-MNIST---Classification/assets/44079369/e025c15d-b6ac-47a0-a6dd-41b1ac453807)

classification Model test Result for 30 component size :


SVM
F1 Score:  0.9387095341144158

LogisticRegression
F1 Score:  0.8659274304753551

DecisionTreeClassifier
F1 Score:  0.8079475164562043

RandomForestClassifier
F1 Score:  0.9079634701891233

Naive Bayes Mode
F1 Score:  0.8119420681850823

RoC - AUC curve:

![download (5)](https://github.com/drajasekar/-Kannada-MNIST---Classification/assets/44079369/92338d38-b6b1-4f82-b0a4-10031290047b)

