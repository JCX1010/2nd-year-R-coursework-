# 2nd-year-R-coursework-

The aim of this coursework is to  investigate associations between the birthweight of children and various potential explanatory variables. The training data is used to explain findings and develop models. Then we use the testing data to make birthweight predictions comparing two different linear models.

A non-technical summary of the findings and conclusions for reporting back to medical professionals provided at the end.

## The data
Data are available regarding the birthweight of 327 children, together with various other measurements. 
The data (referred to as the training data) are contained in the file BirthTrain.txt. 
The variables are:
- `age`  Age of mother.
- `gest` gest Gestation period.
- `sex`  Sex of child.
- `smokes` Whether the mother smoked during pregnancy, with levels ’No’, ’Light’ and ’Heavy’.
- `weight` Pre-pregnancy weight of mother.
- `rate` Rate of growth of child in the first trimester. 
- `bwt` Birthweight of child.
  
The variables ’smokes’ and ’sex’ should be treated as factors, the rest as numerical variables. Additionally, the file BirthTest.txt contains the same measurements for a further 100 individ- uals. This is to be used for testing the predictive ability of models, and should not be used in any model development. This is referred to as the test data.
