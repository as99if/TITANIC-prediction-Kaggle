# TITANIC-prediction-Kaggle
Kaggle competition for ML : TITANIC prediction

 Collecting data
- Data analysis
	- finding missing values
	- visualization accorrding to different features
	- selection of catagorical features
		- Pclass
		- sex
		- SibSp
		- Parch
		- Embarked
		- Cabin
	- Feature Engineering
		- Age - filling missing values with median of Title from 'Name'
		- mapping 'age' from nominal to numeric
		- mapping 'sex' into numerical value 
		- embarked - filling missing 
		plotting 'Pclass' and 'embarked'
		- fare - fill missing values by according to 'Pclass'
		- mapping 'fare' from nominal to numeric
		- cabin - filling missing values by plotting 'Pclass' and 'cabin' into numeric
		- generate feature 'FamilySize' from 'SibSp' and 'Parch'
		- deleting features - 'ticket', 'SibSp', 'Parch'
	- Modelling
		- using kNN
		- SVM
		- RandomForest
		- NB
		- k-fold
	maximum accuracy from SV<

	- Testing with SVM

	Score .78947, leaderboard position 3345
