# Feature-Engineering-Predicting-CNP-Central-Neuropathic-Pain-

Case Study is about predicting Central Neuropathic Pain (CNP), where approximately 50% of people are suffering with Spinal Cord Injury (SCI) have Central Neuropathic Pain (CNP) and there is currently no treatment, only prevention. Also, preventative medications have strong side effects. Predicting whether a patient is likely to develop pain is useful for selective treatment.
● Manual assessment is time-consuming, error-prone and somewhat subjective.
● There is some evidence that brain Electroencephalogram (EEG) data has characteristic
markers.
● We have a (small) dataset with EEG from SCI patients, of which some later developed CNP.
● The data is extremely high-dimensional, so it is very hard for a classifier to tell them apart.
Can feature engineering help to predict - better than random guessing - who later
develops CNP?
We have used Principal Component Analysis (PCA), Chi2 and Recursive feature elimination (RFE) method as feature engineering for dimensionality reduction. The main idea is to find the objective measure such as Cross-validation accuracy, sensitivity and specificity where dataset is given with 180 rows (18 subjects x 10 repetitions) x 432 columns (9 features x 48 electrodes).
Import Required Libraries, numpy, pandas, matplotlib, sklearn.
