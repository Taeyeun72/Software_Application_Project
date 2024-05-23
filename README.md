# 가정 내 위급상황 음성 인식 모델 개발
- 소프트웨어응용 프로젝트
  - Whisper 모델에 MLP Head를 붙여 19가지의 위급/비위급상황을 분류하는 모델 개발
  - Whisper Encoder, Decoder, CNN Model을 Ensemble하여 19가지 상황 분류는 97.40%로, 위급/비위급 상황 이진분류는 99.93%의 정확도를 보여주었다.
- 기간: 2023.09.01. ~ 2023.12.10.

- 00, 01, 02, 03, 12: AIHub 데이터 전처리
- 11: CNN Model 결과 출력
- 13: Whisper Model 학습
- 16: LRP를 통한 CNN Model의 결과 분석
- 17: CNN Model 학습
- 18: 프로젝트 결과 시각화
