
# FABRICATING AN ENSEMBLE OF MACHINE LEARNING MODELS TO PREDICT FOREST COVER TYPES 

This project is submitted as a final submission for DSCI633 - Fundamentals of Data Science and Analytics by Swetha Srinivasan, Master's in Information Technology and Analytics, Rochester Institute Of Technology. 

The Dataset used is from sklearn datasets called forest covtypes. The Dataset corresponds to 30×30m patches of forest in the US with 54 features.

Class Labels - Spruce/Fir, Lodgepole Pine, Ponderosa Pine, Cottonwood/Willow, Aspen, Douglas-fir, Krummholz.

Classes - 7

Samples total - 581012

Dimensionality - 54

Features - int

The project is run by executing the codeblocks one-by-one. 

Model and Training : The dataset is split into 80% (training) and 20%(testing). Preprocessing techniques like PCA, SMOTE and Standard Scaler is applied since the data is very imbalanced. Models - Gradient Descent, Logistic Regression, Decision Tree, Random Forest Classifier, Ada Boost Classifier and Multi Layer Perception ( with Model Regularization ) is applied. The results and findings are analysed. 


[Link to the Dataset](https://colab.research.google.com/corgiredirector?site=https%3A%2F%2Fscikit-learn.org%2Fstable%2Fmodules%2Fgenerated%2Fsklearn.datasets.fetch_covtype.html%23sklearn.datasets.fetch_covtype)

[Link To Presentation](https://docs.google.com/presentation/d/1d5GWm8CWDzwqi_YJF5qYKKci6Mv8xKuL/edit?usp=sharing&ouid=117529234842628091881&rtpof=true&sd=true)

[Link To Project](https://colab.research.google.com/drive/18lN3Bz_kj66T0KFM_y0Tn0YABcYK4wfj?usp=sharing)







## Authors

- [@swetha2507](https://github.com/swetha2507)


## Acknowledgements

 - [Forest Cov Type Dataset](https://scikit-learn.org/0.18/datasets/covtype.html)
 - [SMOTE Documentation](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTE.html)
 - [PCA Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)
 - [Multi Layer Perception](https://scikit-learn.org/stable/modules/neural_networks_supervised.html)

