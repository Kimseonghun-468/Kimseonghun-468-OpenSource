# OpenSource
- 운동 사진 촬영 
<img src="https://user-images.githubusercontent.com/54933779/117271024-c47f4500-ae94-11eb-9c51-0e4feb5c7013.JPG" width="50%"  heigh="50%">

운동 사진을 통해 관절 포인트 좌표를 추출할 준비를 합니다. (PointExtraction.ipynb)
- 관절 포인트 추출

<img src="https://user-images.githubusercontent.com/54933779/117271036-c77a3580-ae94-11eb-9e24-0165e21a0e7c.JPG" width="50%"  heigh="50%">

관절 포인트 좌표를 통해 모델을 학습합니다. (Model.ipynb)
1. 전처리 단계에서 관절 포인트 좌표를 좌표간의 각도로 변환합니다.
2. DNN 모델 구현 및 테스트 후, Sklearn의 RandomForest, MLP, GradientBoost, SVM, Bagging Classifier과 성능 비교

- 모델을 통해 결과 출력

<img src="https://user-images.githubusercontent.com/54933779/117271040-c812cc00-ae94-11eb-8ac8-5ecff010d26d.JPG" width="50%"  heigh="50%">

