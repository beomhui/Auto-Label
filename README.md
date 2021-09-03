### Auto Labeling System

> **Collaborator : 이범희, 김남훈, 김민규**

1. Auto Labeling의 전체적인 Architecture 분석
2. 입력된 이미지에 대한 분류와 객체 탐지를 위한 예측 모델 개발
3. 입력된 이미지에 대한 모델의 Confidence를 측정하여 Confidence가 낮은 일부 데이터는 사용자에게 Labeling 작업을 진행하도록 요청
4. 사용자가 Labeling한 데이터를 저장하여 모델의 업데이트에 활용(3~4: 준지도학습, Active Learning)
5. 출력된 결과를 수정할 수 있는 
