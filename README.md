# Customer churn prediction with SageMaker XGBoost

본 리포지토리의 코드는 SageMaker 기본기능의 이해를 목적으로 작성되었으며, 아래 총 3개의 주피터 노트북으로 구성되어 있습니다.

- [1.xgboost_customer_churn.ipynb](1.xgboost_customer_churn.ipynb) - SageMaker XGBoost 알고리즘을 이용한 고객 이탈 예측
- [2.xgboost_customer_churn-HPO.ipynb](2.xgboost_customer_churn-HPO.ipynb) - SageMaker HPO기능을 이용하여 1번에서 생성한 모델을 개선
- [3.xgboost_customer_churn-abtest.ipynb](3.xgboost_customer_churn-abtest.ipynb) - SageMaker 엔드포인트의 production variant 기능을 이용한 A/B 테스트

다음 SageMaker 공식 리포지토리의 더 많은 예제를 함께 참고하십시오.
- https://github.com/aws/amazon-sagemaker-examples

본 코드는 해당 예제 중 일부를 한글로 번역한 것입니다.





