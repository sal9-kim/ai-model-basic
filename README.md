# 🤖 AI Model Basic – Iris Classification

Iris 데이터를 활용해 머신러닝 분류 모델(Decision Tree)을 구현한 기초 AI 실습 프로젝트입니다.  
데이터 로딩, 전처리, 모델 학습, 예측, 평가까지 머신러닝의 기본 흐름을 이해하는 것을 목표로 합니다.

## 📌 프로젝트 개요

| 항목 | 내용 |
|------|------|
| 목적 | 머신러닝 기초 모델 학습 및 평가 경험 습득 |
| 알고리즘 | Decision Tree Classifier |
| 데이터 | sklearn Iris dataset |
| 환경 | Google Colab |
| 기술 스택 | Python, Scikit-learn, Pandas, Seaborn |

## 🧩 모델링 과정

### ✔ 1. 데이터 로딩  
- sklearn Iris dataset 사용  
- DataFrame 변환 후 기본 구조 확인  

### ✔ 2. EDA  
- 품종(target) 분포 확인  
- 상관관계 heatmap 시각화  

### ✔ 3. 전처리  
- Train/Test 분리 (8:2)  

### ✔ 4. 모델 학습  
- Decision Tree Classifier 사용  

### ✔ 5. 평가  
- Accuracy 계산  
- classification_report 출력  

## 📊 예시 코드

```python
model = DecisionTreeClassifier(random_state=42)
model.fit(X_train, y_train)

pred = model.predict(X_test)
print("Accuracy:", accuracy_score(y_test, pred))
```

## 📈 결과

* Accuracy: 보통 **0.9 ~ 1.0** 수준
* Multi-class 분류 모델에 대한 기본 이해 확보
* 학습/평가 전체 흐름 실습 완료

## 🚀 다음 단계

* Logistic Regression, SVM 등 다른 모델 적용
* Hyperparameter tuning 실습
* Mini-project-EDA → Model Basic → ML Pipeline 구축으로 확장 가능
