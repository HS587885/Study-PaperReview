# MLFLOW
- 데이터브릭스에서 만듬
- 데이터브릭스 hosted version

## MLflow란 무엇인가?

MLflow는 A Machine Learning Lifecycle Platform이라는 컨셉을 가지고 있습니다. 
![캡처](https://user-images.githubusercontent.com/48133382/196066735-69463fd5-39a4-45a5-8a8c-1efa3de7616a.PNG)

MLflow는 머신러닝(Machine learning) 모델의 실험을 tracking하고 model을 공유 및 deploy 할 수 있도록 지원하는 라이브러리 입니다. 
즉, 머신러닝 학습과 관련된 전반적인 lifecycle을 지원해주는 라이브러리 라고 볼 수 있습니다.



# MLflow 주요 기능 및 특징

## mlflow는 아래와 같은 주요 기능들이 있습니다. 

- MLflow Tracking
머신러닝 모델( Machine Learning model)을 학습시킬 때 생기는 각종 파라미터, 그리고 머신러닝 모델 training이 끝난 후 metric의 결과 등을 logging하고 그 기록 결과를 web ui로도 확인할 수 있습니다.

- MLflow Projects
Anaconda나 (Anaconda 없이도 사용 가능) docker 등을 사용해서 만들어 둔 모델을 reproducible 하고 실행할 수 있도록 코드 패키지 형식으로 지원해줍니다. 이러한 형식으로 만들어진 환경을 재사용할 수 있습니다.

- MLflow Models
동일한 모델을 Docker, Apache Spark, AWS 등에서 쉽게 배치할 수 있도록 지원
MLflow Model Registry
MLflow 모델의 전체 라이브사이클을 공동으로 관리하기 위한 centralized model store, set of API, UI


# Installing MLflow
You install MLflow by running:

PythonR
## Install MLflow
pip install mlflow

## Install MLflow with the experimental MLflow Pipelines component
pip install mlflow[pipelines]  # for pip
conda install -c conda-forge mlflow-pipelines  # for conda

## Install MLflow with extra ML libraries and 3rd-party tools
pip install mlflow[extras]

## Install a lightweight version of MLflow
pip install mlflow-skinny



