# WIDS_Mentorship_Resources_2024


- Attaining position as mentor allowed/permitted granted opportunistic platform in broadening  and sharpening my communicational and linguistical in association with refining my technical skillset respectively.

               **** Notebook Title: Explanatory Data Analysis for Breast Cancer Dataset. ****
                                    [Tutorial_1_1_EDA_Breast_Cancer_DS.]


- The following particularly focus on developmental methodical steps for Intro. Data Science Fundamentals in accommodation with further manipulative and critical analysis steps respectively.

 
 		Structural formatted comprehensive Data Dictionary whereby illustrating the Covariate Analysis Background of the dataset coupled with the theoretical analysis of the diverse range of variables established [; 1) Patient and Metastatic Triple Breast Cancer information , 2) Patient Population and Density Representation, 3) Property Economics Value and Ownership ( income_household_median, income_household_six_figure, etc, ) , 3) Residential Labour and Education Status (education_college_or_above , labor_force_participation ) ,  Race and Ethnicity ( Hispanic,  race_white), Age Grouping Distribution(age_under_10)]


	Exploration of Breast Cancer Dataset via plethora of fundamental Data Science techniques/principles such as ( Data Ingestion, Data Pre-processing, Explanatory Data Analysis (EDA); Data Visualization ) in highlighting and conveying meaningful information.


	Overview of the Dataset(Train/Test), insightfully incorporated {: .shape, .info(), .dtypes; .unique(), .describe(), .head() , .isna(), duplicated(), etc}. Proceeded with explanatory analysis of missing values within our Dataset, highlight overall distribution NAN-value percentages accordingly.


	Conducted  EDA on the missing Values both on the Training/Testing Dataset incorporating dictionary;  key [k for k, v in dict(BreastCancer_Train_Data] function methodology showcasing different various NAN- value distributional percentage ( >=50% , <50%, <10%, <1%).


	The multi-beneficiary usage of plotly express library really distinguishes in-depth comprehensive graphical overview: {highlight data points, preparation of DataFrame before chart manifestation, overall background visualization and  template}


	Afterwards, proceeding in overview analysis of the exploration and Data visualisation underlying relationships factors in regards to patients’ Scio-economic status,  Characteristics Data Status, Environmental Condition. Some various distinctive types of graphs include: { pie-chart , barplot showcasing Relative Frequency Pat. Diagnosis Treatment, Kernel density plot of distribution of features numerical and categorical)

                 ****Notebook 2 (Intro to Machine Learning):****

		Utilise dataset expressed as such :  healthcare-dataset-stroke which extensively focus and explores the spectrum  various of machine learning models algorithms and its evaluation metrics accordingly.

		Performed the fundamental techniques incorporated : Data Ingestion, Data Pre-processing , EDA: Missing values incorporating col_names() : function created to get the columns names that has categorical and numerical data separately,[ proceed in graphical representation via Data Visualisation].

		Additionally, we inclusively check the following outliers (:def check_outliers(df, numerical_cols, low_threshold=0.1 , up_threshold=0.9): for all numerical features :{ id, age, avg_glucose_lev_).

		Primarily in regards Categorical features, perform accordingly to attributes of categories presented: apply label encoder (nunique values <2) or  One-hot encoder( > nunique categories)

	 Afterwards proceed in focusing on the target variable : stroke;  graphical its distribution of target variable, correlation with other feature columns via  groupby() + agg() technique function accordingly. Then we executed  correlation between the target and categorical variable accordingly.

		Exploit wide variety of classification models  list such as: Logistic Regression, K-Neighbours Classifiers, Decision Tree Classifiers, Random Forest Classifier, Support Vector Machine, Gradient Boosting Classifier, XGB Classifier, LGM Classifier. Then accessed by its evaluation metrics for each classifier measured its: scoring=["accuracy","f1","recall","precision"].
 
	 Technique) Sampling { SM = SMOTE() } whereby execute by fitting  (X_train_smote, y_train_smote) into our classifier models . Afterwards evaluating via confusion matrix {confusion_matrix(y_test, Clasf)} alongside its evaluation metrics 

  




