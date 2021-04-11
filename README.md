# CSE523-Machine-Learning-MeTooQuartet

One of the most sensitive and major concerns across globe-Women Safety. The early identification of the crucial issue of sexual harassment is vital for mitigating the risk. This can certainly be worked upon using Machine Learning techniques. The model aims to use classification algorithms based on abusing categories with the prediction of most prevailing locations. This data can be helpful for the government for taking necessary actions, safeguarding the nation and also alert females from such unavoidable incidents.

The dataset we are using is basically from the Safecity.


Firstly, the dataset was acquired from the Safecity. After acquiring the dataset, the dataset was preprocessed, Exploratory Data Analysis was performed and statistical and
graphical representations were carried out.

Our main aim was to classify the category of the assault from the discription of the incident. 

Most of the important data was in text form, hence it was necessary to implement TF-IDFvectorizer and CountVectorizer so that the data can be used for feature extraction. Initially, the following classification algorithms i.e.LogisticRegression, RandomForestClassifier, LinearSVC, and MultinomialNB were implemented.

We also tried to use PCA for dimensionality reduction and tried to implement above algorithms.

Then, we used GridSearchCV for Hyper-Parameter Tuning.

After this we have used RepeatedStratifiedKFold to maximize the use of the available data for training and then testing a model with the GridSearchCV.

The code for this and snapshots of the results are in their respective folders.
