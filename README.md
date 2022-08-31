# GiftClassification

## the solution consists of data exploration/cleaning and some test/train scores for classification models with AUC included
### !!!to test solution from the scratch train and test csv files should be put in the same folder as a .ipynb Jupyter notebook  
Firstly, I've loaded the model, dropped everything empty (or almost empty), did some exploratory analysis, including histograms, correlation matricies, simple statistics, etc. I removed any missing values either by replacing the empty space with column's median or putting 0 for binary features.  

Secondly, I've created the training set itself by including the best features and creating binary features for categorical ones.   

Thirdly, I've trained few models: DecissionTreeCLassifier, RandomForrest, MultiLayerPerceptron and SupportVectorMachine. Almost all of them showed 0.90-0.1 score for test/train and 0.5 scores for everything except tree alrgorithms. 0.5 score indicates that algorightm is unable to generalize the features of each class.  

