# Classification-models-on-titanic-dataset

# Objective:

 the Aim is to provide a comprehensive overview of supervised learning and apply
 various algorithms to assess their comparative accuracy.
 
 # STEPS THAT SHOULD BE FOLLOWED:
 
# 1.Import data:

   Download the titatnic dataset from the kaggle
   
   There are 11 variables using which we have to predict whether a person will survive the  accident or not.
   
 # 2.Data preprocessing and cleaning
 
  We will remove columns from both data frames if they are deemed unimportant or contain more than 80% null values.
  Once we have removed unnecessary columns, we will handle null values. If a column contains less than 80% null values, we will replace them with either the category     with the highest count (for categorical columns) or the mean value of the column (for numerical columns). If a column has between 60-80% null values and is 
  considered    important, we can create a new category to replace the null values.
  For the numerical columns, we will generate a box plot to identify any outliers and replace them with appropriate values. Finally, we will apply all the     
  afore mentioned approaches to the   data set.
  
# 3.Splitting Data into Training and Test Set
  We need to specify our dependent and independent variables. In this case, our dependent variable will be "Survived" because we aim to predict whether a person will   
  survive or not. The remaining variables will be considered independent.
  
# 4.Applying all the Classification algorithms
  All of the Machine Learning models are stored in the scikit-learn (sklearn) package. We will  use this package to apply all of the models mentioned above to the 
  processed Titanic dataset and compare their accuracy scores. To start, we need to import all of the algorithms.

# Conclusion

  a.Random Forests have provided the most accurate predictions.
  
  b.It is worth noting that we have not yet implemented any model improvements to enhance the accuracy.



 
