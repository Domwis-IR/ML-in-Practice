# ML-in-Practice
2021-1학기 배성호 교수님의 실전기계학습 수업

## 1. 중간 프로젝트: Data Augmentation
Base 모델: ResNet34
데이터: CIFAR100

1. 최신 DA 논문 2개를 읽고 구현 </br>
    - RandomShadow : https://arxiv.org/abs/2101.05361
    - Inaugment : https://arxiv.org/abs/2104.03843

2. 새로운 DA 아이디어를 구현하여 최신 모델과 성능 비교 </br>
    - RCRS : RandomColorRandomShadow
    - ACRS : AverageColorRandomShadow
    - RRI : RandomRotateInaugment

## 2. 기말 Competition : Face Regression
데이터: FaceAge  
목표: 모델 parameter 수가 2M 미만의 모델을 주어진 Face 이미지 데이터셋만을 이용해 Training해 RMSE를 낮추기

1. Hyper Parameter 조정하기
2. 모델 변경하기
