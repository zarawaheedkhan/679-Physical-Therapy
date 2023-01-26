# Dimenstionality-reduction-for-functional-data

For this project we worked with Kerry Costello, PhD, a postdoctoral scholar in the Movement
and Applied Imaging Lab at Sargent College, BU. As a part of her research work, she is working
on a project to predict MRI Osteoarthritis Knee Score (MOAKS) using gait and physical activity
measures. Identifying knees at risk of worsening osteoarthritis could help to identify individuals
in need of interventions. Specifically, demographic and clinical data, ground reaction force data
obtained through self-selected speed walking and physical activity data from 7 days of accelerometer
wear collected from patients with and without knee pain is being used for modeling. The ground
reaction force, along with the center of pressure and moments, was represented as functional data
with high dimensionality (p=100). The client had previously tried to extract features manually from
this data to use it as predictors in predictive modeling. However, she wanted to know if there are
other automatic ways of generating features. Our project was to explore Machine Learning based
dimensionality reduction techniques for the functional data (p=2990 and p=100). In the initial
stages of our project, we worked on Functional Principal Component Analysis and Multivariate
Functional Principal Component Analysis which gave us good results. We decided to use these as
our baseline models. In the second half of the project, we tried non-linear Neural Network based
models, first AutoEncoders and later Variational AutoEncoders.
