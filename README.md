# House Price Prediction Project

**Introduction:**

Predicting house prices accurately is crucial for real estate market participants, including buyers, sellers, and investors. Machine learning provides powerful tools to analyze historical housing data and forecast prices based on various features. This project aims to develop a machine learning model that predicts house prices using relevant attributes such as location, size, amenities, and market trends.

**Problem Statement:**

The objective of this project is to build a machine learning model capable of predicting house prices based on a set of features available for each property. Using a dataset containing attributes such as location, number of bedrooms, square footage, year built, and other relevant factors, the model will learn to accurately estimate the market value of houses.

**Dataset:**

The dataset used for this project has 1,460 Records and has the following variables:

•	Id: A unique identifier for each house sale record.

•	MSSubClass: The type of dwelling involved in the sale.

•	MSZoning: The general zoning classification of the property.

•	LotFrontage: Linear feet of street connected to the property.

•	LotArea: Lot size in square feet.

•	Street: Type of road access to the property.

•	Alley: Type of alley access to the property.

•	LotShape: General shape of property lot.

•	LandContour: Flatness of the property.

•	Utilities: Type of utilities available.

•	LotConfig: Lot configuration.

•	LandSlope: Slope of property.

•	Neighborhood: Physical locations within Ames city limits.

•	Condition1, Condition2: Proximity to various conditions.

•	BldgType: Type of dwelling.

•	HouseStyle: Style of dwelling.

•	OverallQual, OverallCond: Rates the overall material and finish of the house, and the overall condition.

•	YearBuilt: Original construction date.

•	YearRemodAdd: Remodel date.

•	RoofStyle, RoofMatl: Type of roof and roofing material.

•	Exterior1st, Exterior2nd: Exterior covering on house.

•	MasVnrType, MasVnrArea: Masonry veneer type and area in square feet.

•	ExterQual, ExterCond: Evaluates the quality of the material on the exterior and the present condition.

•	Foundation: Type of foundation.

•	BsmtQual, BsmtCond: Evaluates the height of the basement and the general condition.

•	BsmtExposure: Refers to walkout or garden level walls.

•	BsmtFinType1, BsmtFinSF1, BsmtFinType2, BsmtFinSF2: Rating of basement finished area and type, and second finished area if present.

•	BsmtUnfSF: Unfinished square feet of basement area.

•	TotalBsmtSF: Total square feet of basement area.

•	Heating, HeatingQC: Type of heating and heating quality and condition.

•	CentralAir: Central air conditioning (Y/N).
•	Electrical: Electrical system.

•	1stFlrSF, 2ndFlrSF, LowQualFinSF, GrLivArea: First and second floor square feet, low quality finished area square feet, and above grade living area square feet.

•	BsmtFullBath, BsmtHalfBath, FullBath, HalfBath: Basement full bathrooms, basement half bathrooms, full bathrooms above grade, and half baths above grade.

•	BedroomAbvGr, KitchenAbvGr, KitchenQual, TotRmsAbvGrd: Bedrooms above grade, kitchens above grade, kitchen quality, and total rooms above grade.

•	Functional: Home functionality rating.

•	Fireplaces, FireplaceQu: Number of fireplaces and fireplace quality.

•	GarageType, GarageYrBlt, GarageFinish, GarageCars, GarageArea, GarageQual, GarageCond: Garage location, year garage was built, finish quality, number of cars it can hold, garage area in square feet, and garage quality and condition.

•	PavedDrive: Paved driveway.

•	WoodDeckSF, OpenPorchSF, EnclosedPorch, 3SsnPorch, ScreenPorch: Wood deck area, open porch area, enclosed porch area, three season porch area, and screen porch area in square feet.

•	PoolArea, PoolQC: Pool area in square feet and pool quality.

•	Fence: Fence quality.

•	MiscFeature, MiscVal: Miscellaneous feature not covered in other categories and value of miscellaneous feature.

•	MoSold, YrSold: Month and year of sale.

•	SaleType: Type of sale.

•	SaleCondition: Condition of sale.

•	SalePrice: Sale price in dollars (target variable).

**Project Description:**

• Conducted Exploratory Data Analysis (EDA) to analyze insights and patterns

• Performed Data Pre-processing and Feature Engineering in order to prepare data for modelling.

• Developed Machine Learning Models such as Linear Regression with Ridge (L2) Regularization, Random Forest, and AdaBoost to predict house prices.

• Implemented cross-validation methods and hyperparameter tuning to optimize model accuracy.

• Employed stacked ensemble models to significantly boost predictive capabilities.

• Conducted Homoscedasticity and Normal Distribution Check

• Analyzed feature importance across models, revealing key predictors for enhanced accuracy.

• Employed Root Mean Squared Logarithmic Error (RMSLE) as the evaluation metric.

**Observation:**

•	CentralAir and OverallQual are the most important features for Linear Regression with L2 Regularization

•	YearBUilt and OverallQual are the most important features for Random Forest Model

•	GrLivArea and OverallQual are the most important features for AdaBoost Model

•	Achieved an Root Mean Squared Logarithmic Error (RMSLE) of 0.07 for the stacked model.

**Skills:** Cross Validation · Advanced Model Assessment · AdaBoost · Model Stacking · Feature Importance Analysis · Data Pre-Processing · Feature Engineering · Linear Regression · Random Forest · Hyper-Parameter Tuning · Machine Learning · Exploratory Data Analysis
