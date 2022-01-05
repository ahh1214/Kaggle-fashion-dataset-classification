# Kaggle-fashion-dataset-classification

fashion dataset link :
https://www.kaggle.com/paramaggarwal/fashion-product-images-small

패션 데이터셋을 이용한 multi-class 분류모델
 - 널리 알려진 ResNet을 사용하여 데이터를 분류해본 후, 모델을 더 개선할 수 있는 방법을 찾아 **기존 ResNet보다 약 1.48%** 향상된 정확도를 얻을 수 있었습니다.
 - 단순한 배경의 데이터 셋 뿐만 아니라, 배경이 존재하는 데이터셋에 대해서도 비교실험을 진행하였습니다. : Noise_image_applied_model(Proposed_model or Base_model).py


### 1. dataset download
### 2. data_preprocessing 실행
### 3. Proposed_model(96.54%) / Base_model(95.06%) 실행
    * dataset(pre_data) 형태
    *  |train
    *    |Accessories
    *    |Apparel
    *    |Footwear
    *    |Personal Care
    *    |Sporting Goods
    *  |test
    *    |Accessories
    *    |Apparel
    *    |Footwear
    *    |Personal Care
    *    |Sporting Goods
### 4. (선택) Noise_image_applied_model(Proposed_model) / Noise_image_applied_model(Base_model) 실행
