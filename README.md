# Final-project
# Linear_regression of The predicting housing prices 
# Members of the group : Rohit V Satyendra, Serena Jacob, Vijaya Palaniappan

Packages Used for Project:
1. Pandas
2. Matplotlib
3. Seaborn 
4. SKLearn
5. Numpy

sources:
https://scikit-learn.org/stable/modules/model_evaluation.html

Algorithm Used:
1. linear_model
2. LinearRegression
3. train_test_split

Interesting Exploration:
This data set has a lot of interesting values added to it.
The datset contains 80 columns detailing the different characteristics of each house and 2919 rows with CVS extension. The data contains the following columns:
1. Id
2. MSSubClass
3. MSZoning
4. LotFrontage
5. LotArea
6. Street
7. Alley
8. LotShape
9. LandContour
10. Utilities
11. LotConfig
12. LandSlope
13. Neighborhood
14. Condition1
15. Condition2
16. BldgType
17. HouseStyle
18. OverallQual
19. OverallCond
20. YearBuilt
21. YearRemodAdd
22. RoofStyle
23. RoofMatl
24. Exterior1st
25. Exterior2nd
26. MasVnrType
27. MasVnrArea
28. ExterQual
29. ExterCond
30. FoundationBsmt
31. QualBsmtCond
32. BsmtExposure
33. BsmtFinType1
34. BsmtFinSF1
35. BsmtFinType2
36. BsmtFinSF2
37. BsmtUnfSF
38. TotalBsmtSF
39. Heating
40. HeatingQC
41. CentralAir
42. Electrical
43. 1stFlrSF
44. 2ndFlrSF
45. LowQualFinSF
46. GrLivArea
47. BsmtFullBath
48. BsmtHalfBath
49. FullBath
50. HalfBath
51. BedroomAbvGr
52. KitchenAbvGr
53. KitchenQual
54. TotRmsAbvGrd
55. Functional
56. Fireplaces
57. FireplaceQu
58. GarageType
59. GarageYrBlt
60. GarageFinish
61. GarageCars
62. GarageArea
63. GarageQual
64. GarageCond
65. PavedDrive
66. WoodDeckSF
67. OpenPorchSF
68. EnclosedPorch
69. 3SsnPorch
70. ScreenPorch
71. PoolArea
72. PoolQC
73. Fence
74. MiscFeature
75. MiscVal
76. MoSold
77. YrSold
78. SaleType
79. SaleCondition
80. SalePrice

A few of the data points are more important to consider when predicting the price of housing. 
By using the datas provided to us, we decided to do Exploratory Data Analysis, split the training and testing data, Model Evaluation and Predictions. 

Explanation of these attributes can be found: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt

To use the simple UI that is coded in the notebook, the input should be for
OverallQual: any number of desired overall quality on a 1-10 scale
GarageCars: any number of desired #car garages
GrLivArea: any number of desired square ft for above ground living area
Neighborhood: choose from neihborhood: 'CollgCr', 'Veenker', 'Crawfor', 'NoRidge', 'Mitchel', 'Somerst', 'NWAmes', 'OldTown', 'BrkSide', 'Sawyer', 'NridgHt', 'NAmes', 'SawyerW', 'IDOTRR', 'MeadowV', 'Edwards', 'Timber', 'Gilbert', 'StoneBr', 'ClearCr', 'NPkVill', 'Blmngtn', 'BrDale', 'SWISU', 'Blueste'
TotRmsAbvGrd: any number of rooms above ground
WoodDeckSF: any number of square ft for wooden deck
Fireplaces: any number of desired fireplaces
