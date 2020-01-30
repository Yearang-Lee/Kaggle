# [EDA]

**1. Null data check**

**2. Target label 확인**

**3. 변수 확인**

  1) Pclass

  2) Sex 

  3) Pclass, Sex

  4) Age

  5) Pclass, Sex, Age

  6) Embarked

  7) Sibsp

  8) Parch

  9) Fare

**4. 통계 분석**

  1) 상관 관계

# [Data Preprocess / Feature Engineering]

**1. Fill Null**

  1) Age

- 방법1) Name 열 활용
- 방법2) null data 가 없는 데이터를 기반으로 새로운 머신러닝 알고리즘을 만들어 예측해서 채워 넣기

  2) Cabin

  3) Embarked

  4) Fare

**2. Outlier detection**

  1) Outlier detection

  2) Drop outliers

  3) 편향된 데이터 바로 잡기

**3. Make New Columns**

  1) Parch + SibSp = Family Size

  2) Name

**4. Continuous to Categorical**

  1) Age

- 방법1) loc 사용
- 방법2) apply 를 사용해 함수를 넣기
- 방법3)

  2) Fare

**5. String to Numerical**

  1) Sex

  2) Embarked

  3) Ticket



**6. One-hot encoding**

**7. Drop columns**



# [Single Model]

**1. Split dataset**

**2. Model**

# [Advanced Model],[Stacking]

**1. Cross Validation**

* Confusion Matrix

* Hyper-Parameters Tuning

  1) SVM

  2) Random Forests

**2. Ensembling**

  1) Voting Classifier

  2) Bagging

- Bagged KNN
- Bagged DecisionTree

  3) Boosting

- AdaBoost(Adaptive Boosting)
- Stochastic Gradient Boosting



**3. Hyperparameter tunning**

**4. Plot learning curves**

**5. Feature importance**

**6. Predict**

