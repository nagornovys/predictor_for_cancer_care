# predictor_for_cancer_care

Title: 
---
Analysis of the ICGC data using of machine learning methods based on novel isolation kernel and targeting of the accurate prediction of personal cancer treatment

Authors and contributor list:
---
_**Iurii Nagornov**_ (Maintainer, Author)
The National Institute of Advanced Industrial Science and Technology, Japan

_**Asmaa Elzawahry**_ (Author)
University of Oslo, Norway

ABSTRACT
---
Genomic ICGC data has huge dimensionality, and a subset corresponding to a particular type of cancer has a low size to have enough evidence for an efficient prediction in personal treatment. Personalized medicine is a challenge for the ICGC project, but it requires much more information, and nobody knows when it will have been accumulated enough. Machine learning (ML) based on isolation kernel (iKernel) has attractive advantages like strong sustainability to the high dimensionality of data and accurate prediction for sparse data. It is important to denote that this ML method is outstanding from neural network approaches and others. This project aims to improve the prediction efficiency for personal immunotherapy treatment using ML based on iKernel and its approaches. The project will use ICGC Controlled Data for lung and breast cancers as the most common cancers which have more data in comparison with other types. We are going to use data on the efficiency of immunotherapy for these cases to train ML analysis and construct the predictor. 80% of dataset will be used for training and 20% for measuring method accuracy, and repetition of the training procedure with a shuffle of data will be applied for evaluation of stability.

Aims
---
The project is trying to achieve a significant improvement in the cancer immunotherapy by improving diagnostic accuracy, treatment planning, and predicting outcomes of care.
New approach of ML method based on iKernel will be applied to predict immunotherapy responses based on immune signatures and personal features of the patient medical data (for example, features of the histological analysis). The used ML will have been employed to improve the accuracy of predicting patient response to immune checkpoint inhibitors by analyzing clinical results and transcriptome data of cancer tissues. Another application area of the iKernel ML method will have enabled the simultaneous prediction of the tumor immune and stromal microenvironment, which can help improve the prediction of the benefit of adjuvant chemotherapy and response to anti-PD-1 immunotherapy in cancer patients.

Use of Data and Methodology 
---
In our upcoming research, we plan to employ advanced machine learning methods, including the isolation kernel and its modifications. This encompasses metasampling techniques based on the maxima-weighted iKernel, as well as the utilization of other kernel methods like Gaussian and Laplacian kernels. 

For comparative analysis, we will also integrate well-established techniques such as biomarker identification (feature selection and principal component analysis), classification models (support vector machines, random forests, decision trees, and regression models), deep learning models.

The predictive models will rely on computational methodologies that consider a wide range of factors and comparison will be realized using consistencies between the predictor's output and a patient responses to immune checkpoint inhibitors. The input data for these models will be derived from personalized clinical results and transcriptome data sourced from cancer tissues. This integration of diverse data sources aims to enhance the robustness and accuracy of our predictive models, contributing to a more nuanced understanding of individualized responses to immunotherapy.

