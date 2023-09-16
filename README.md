# Report on Heart Disease Prediction (DSCI100-Project)

In Canada, heart disease is the second leading cause of death (Prevention & Wellness Centre). Heart disease is defined as any condition that causes a negative impact on the structure or function of the heart. Several risk factors such as high cholesterol levels, high blood pressure, unhealthy diet, stress, age, sex and many more can increase the likelihood of developing a heart disease. (Heart and Stroke Foundation of Canada)

The question that we want to answer in this project is:

Could we use thalach (maximum heart rate) and age for heart disease diagnosis?

The dataset we will use is on https://archive.ics.uci.edu/ml/datasets/Heart+Disease . In this directory, there are 4 databases concerning heart disease diagnosis. Data was collected from 4 different medical institutions in Cleveland, Hungary, California and Switzerland.

In our project we will only focus on the data from Cleveland (specifically, processed.cleveland.data). The dataset we use has 14 different attributes, but we will only use age and thalach (maximum heart rate achieved) (bpm, beats per minute) as our predictors and num as our predictive variable which refers to the presence of heart disease within a patient. 0 (no diagnosis) to 1 (diagnosed). We will rename last column from num to diagnosis_heart_disease to make our classification variable easier to distinguish. That is why our predictive variable will be referred to as diagnosis_heart_disease.

We will use age and thalach as our predictor variables to predict the presence of heart disease.

Descriptions for the other 11 attributes can be found here: https://archive.ics.uci.edu/ml/datasets/Heart+Disease                                                                                            
