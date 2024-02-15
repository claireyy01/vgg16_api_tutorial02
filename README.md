# 학습한 모델을 플러터에서 확인 및 배포하기
## 개요
앞서 진행한 DLthon 팀 프로젝트의 Jellyfish Classificaion Best Model을 플러터에서 확인하고 배포하는 퀘스트입니다.

## 퀘스트 내용
<img width="780" alt="image" src="https://github.com/claireyy01/vgg16_api_tutorial02/assets/145723730/3a621292-e803-4f5c-b7d0-d3051cc3297a">
<img width="787" alt="image" src="https://github.com/claireyy01/vgg16_api_tutorial02/assets/145723730/8fe7d688-8665-45b7-9033-1243bc650c62">

## 파일 가이드
- console_output.mov : 2개의 버튼을 눌렀을 때 debug console에 해당 내용이 출력되는지 확인용 영상입니다.
- jellyfish02.jpg : 모델 성능 확인에 사용한 샘플 이미지
- jellyfish_best_model.h5 : DLthon에서 만든 Best Model 파일
- jellyfish_prediction_model.py
    - 추론용 파이썬 모델
    - jellyfish_best_model.h5 로 모델을 불러들이고, 샘플 이미지를 추론하여 예측값을 반환합니다.
- main.dart.js : 플러터 구현 파일
- server_fastapi_jellyfish.py
    - fastapi 서버 파이썬
    - 추론용 파이썬 모델을 사용해 추론 결과를 반환하는 fastapi 서버를 작동합니다.

## 회고
### KEEP
- 해결하지 못한 부분들을 완성하기 위해 끝까지 포기하지 않았으며, 동료들과의 정보 공유로 함께 완성하였다.

### PROBLEM
- Github pages로 배포된 웹을 여는 단계에서 계속 오류가 발생하였으며, 깃헙 자체의 이슈로 인한 것이라 오류 해결에 상당 부분 시간이 소요되었다.
- W&B를 활용한 모델 실험에서 Best Model을 불러오는 방법을 찾지 못했다.
- 전반적으로 시간이 부족하여 위의 문제들을 찾아서 해결하는 데에 어려움을 겪었다.
  
### TRY
- 앱 구현부터 배포까지 반복 연습을 하여 익혀야겠다.
