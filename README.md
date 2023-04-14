# CE880_Case_Study

With the influx of technology into every field, most businesses now have an online sector of performance. For the businesses dealing with physical objects, delivery is a major source of joy and problems, both. Tracking deliveries is a hassle, and slower deliveries can sway customers away from a brand. Even worse than slow deliveries are deliveries not arriving on time. A promised delivery date is provided based on multiple factors and when they don’t fall in place, a business suffers heavily as customers severely dislike this.
For such businesses, understanding if a product will arrive on time or not is a boon. Using AI for problem solving is its biggest use and here, we aim to solve this problem using AI and Machine Learning classifiers. We explore various classifiers, finally defining the best based on various factors. To do this we have a data set of deliveries with a marker to define if they reached on time or not and we aim to predict on time deliveries and maximise accuracy of our predictor.

To run this code, kindly save the provided dataset with the same name and the jupyter file in the same location and run each cell in order.
Some libraries may need to be installed and pip can be used for all.

Within the jupyter file provided, we import required modules and dataset to begin with.
We then convert continuous data to categorical fields, check correlations and drop correlated columns.

We then move to create classification models using 5-Fold cross validation.

The models created are KNN, SVM, Stochiastic Gradient Descent Classifier, Linear Regression, Decision Tree, Random Forest and Naive Bayes.
