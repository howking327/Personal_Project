# Car Classification with Keras CNN :car:

Python-Jupyter Notebook으로 DeepLearning을 이용한 자동차 모델 분류 프로젝트입니다.  
(2020/01/10 ~ -수정진행중- )

### ▶ Concept
사진을 찍어 상품을 검색하거나 동식물의 품종을 검색하는 등의 서비스를 차량 이미지 검색에 적용하기 위한 DeepLearning 프로젝트 입니다.

### ▶ Tool
- **Language** : Python  
- **Tool** : Jupyter Notebook

## Data Set
- **출처** : AI Hub
- **구성** : 국내 브랜드 별 대표 차종에 대한 낮/밤 , 수평각도/수직각도, 실내/실외의 구분으로 다중 촬영된 Image 파일입니다.

## CNN
![car_cnn](https://user-images.githubusercontent.com/57980363/78028820-93336c00-739a-11ea-9c33-de888c8071fe.png)

## Improvements
  
- **Data set pumping 후 model 생성 시 memory error 해결**  
74개의 category 당 각 3000장으로 구성되어 model 생성 시 memory error 발생하여 server를 이용하거나 memory 증대가 있을 예정입니다.
   
- **전체 이미지가 아닌 차급 별 학습 후 emsemble과정 시도**  
기존 상위 문제를 해결하는 방안으로도 고려 중인 것으로 전체 차종을 한 번에 model에 담는 것이 아니라 suv, sedan, van 등 차급 별로 나누어 진행하는 것을 고려중입니다.

- **검색 서비스 구현으로 확대**  
model분류 결과에 따른 중고차 가격 검색 서비스 구현으로 확대할 계획입니다.

