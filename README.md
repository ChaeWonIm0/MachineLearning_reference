# MachineLearning_reference
Techinical reference and theories for Machine Learning and some Deep Learning model

since 2023_06_27 for Study
Tool : Jupyter notebook (anaconda), colab(for GPU)
reference : 1) Hands-on machine learning
2) https://github.com/rickiepark/handson-ml2/tree/master/datasets/
library : sklearn, keras, tensorflow
<br>
<hr>

##### (230629) 용량 문제로 pkl파일 제외
##### (230630) 학습셋이나 검증셋 인덱싱이 필요할 시 .iloc나 .loc 붙여서 이용 필요
<hr>

### 제롱이 추천하는 머신러닝 체크리스트

1. 문제를 정의하고 큰 그림을 그립니다.
- 가정을 세우고, 목표에 맞는지 검증합니다.
- 반드시 가정을 세웁니다.

#### "비즈니스의 목적은 무엇인가요"
<br>

2. 데이터를 수집하고 변환합니다.
- 데이터 자체는 바꾸지 않습니다.
- 가능하면 자동으로 받아들일 수 있게하고, 검증셋을 미리 들여다보지 않습니다.
- 크기와 type 확인 필수


3. 데이터를 탐색합니다.
- 각 feature의 특징을 탐구합니다.
- 각각의 상관관계가 있는지 조사하고, 있다면 무엇이 가능한지 조사합니다.
- 필요에 따라 수집단계로 돌아갑니다.


4. 데이터를 준비합니다.
- 원본 데이터셋은 최대한 유지합니다.<br>
 4.1. 데이터를 전처리<br>
 4.2. 불필요한 피쳐 제거<br>
 4.3. 분해하거나, 피쳐를 새로 만들수 있습니다.<br>
 4.4. 스케일을 정규화<br>

5. 유망한 모델을 선택합니다.
- 지도학습, 비지도학습, 준지도학습 등 다양합니다.
- 에러가 나타나면 분석합니다.
- 다시 feature engineering을 시작할 수 있습니다.


6. 모델 전반을 튜닝합니다.
- 다양한 방법을 연구합니다 ; cross validation, grid search 등
- ensemble을 고려하고 점수를 확인합니다.


7. 지금까지의 과정을 문서화합니다.
- 시각화하거나 발표 자료로 만듭니다.
- 문제점도 포함하고, 제약도 넣습니다.
- 주제의식을 포함합니다.

8. 시스템을 런칭합니다.
- 유지보수와 모니터링을 고려합니다.
- 정기적으로 다시 모델을 트레이닝 합니다.