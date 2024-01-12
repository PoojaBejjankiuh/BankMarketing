# Bank Marketing Data Analysis
# Data Set Link
https://archive.ics.uci.edu/dataset/316/condition+based+maintenance+of+naval+propulsion+plants 
# Phase 1
1) Selecting a dataset: Select a dataset from uci data repository or an API based tabular dataset
(example: Twitter developer tools , time series stock data etc) (creativity will be appreciated). It must
have at least 10000 rows and 10 columns (dataset selection will be done based on first come first
serve) (will share a google sheet of groupwise dataset links with everyone to access it, make sure the
dataset isn’t already taken). Explain why you selected this dataset, what is the target variable you
want to predict (is it regression or classification based problem).
2) Files to submit:
a) “Group_1_Raw_Data.csv/excel” – actual Data excel/csv file. (If file is too large share the link)
b) “Group_1_Data_Cleaning.ipynb/ colab file link clearly mentioning Group_1_Data_Cleaning” -
Clean the data using preprocessing techniques, perform EDA and share your insights.
c) “Group_1_Data_Cleaning.pdf” - print the ipynb and save as pdf.
d) “Group_1_Clean_Data.npz” - save the clean data as a npz file. (use np.savez(file, df.to_numpy()) command)
e) “Group_1_Clean_Data.sql” – save the new data in SQL workbench and run 1 query, create 1
function and 1 view on the workbench)

# Phase 2
1) Use the same dataset from the Semester Project Part 1 and perform classification or regression based
on your dataset. Keep some test data to report the performances of your selected models on only
train data. Perform visualization of your model performances using apt metrics and charts (ex: MSE
bar plots of all the models to identify best models). Please use markdowns to the best use to make
code easy to understand, comment important parts, insights, brief descriptions of the steps involved.
Use 4 modeling techniques:  ́
 Linear regression/classification
 KNN
 Random Forest
 SVM with linear kernel and SVM with nonlinear kernel
 Another one that you can choose. Deep Learning is not allowed.
2) Selecting Perform Variable Selection. Choose one of the following techniques and explain why you
selected that one.
 Lasso: https://en.wikipedia.org/wiki/Lasso_(statistics))
 KNN
 Correlation
3) Perform model structure selection to select the hyperparameters of your models after step 2 feature
selection(Using grid search or Random search or any other method). Perform visualization of your
model performances using apt metrics and charts (ex: MSE bar plots models before and after
optimizing hyperparameters).
4) Use the best model from step 1 and step 3 and perform another variable selection using a Bi-
directional elimination as a wrapper method.
https://www.analyticsvidhya.com/blog/2020/10/a-comprehensive-guide-to-feature-selection-using-
wrapper-methods-in-python/
5) After feature selection step 2 also build (Based on the models compatibility with the data i.e
classification or regression problem) (also write a 3 lines on what you understand about these models
you are free to use online resources but please cite them):
 XGBoost
 Extreme Machine Learning Model
 A basic deep learning model with two layers
 An Ensemble model containing the top 3 models overall.
6) Perform visualization of your model performances, insights etc using apt metrics and charts (ex: MSE
bar plots of all the models to identify best models).
