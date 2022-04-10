# End to End Machine Learning - Diabetes Classifier
# Colab 에서 개발 및 실행 (하단 실행방법 참조)
# Github : https://github.com/MunJinSeo/E2E_ML_DiabetesClassifier
<br>

## References 1
- (1) xx의 "xxx"<br>
url

- (2) xxx님의 Github : xxx <br>
url

## 사용모델: xxx
- xxx <br>
url
- xxx <br>
xxx <br>
xxx<br>
참고 : xxx <br>

## Dataset (xxx)
- xxx<br>
xxx <br>
xxx_train.txt <br>
xxx_test.txt <br>

## 과제 파일
- xxx : xxx <br>

## References 2
- xxxx


## 실행 방법 / 유의사항
- Colab 에서 반드시 GPU로 실행 (Colab Pro 권장)
- 과제파일은 사전에 서버로 업로드
- 모델 학습을 위한 데이터셋은 사전에 서버로 업로드<br>
  단, 한국어는 자동 다운로드 처리가능, 영어는 수동 업로드
- 소스는 위에서부터 순차적으로 실행하면 됨
- CUDA(GPU) 메모리 오버되는경우 학습시 Batch size 줄여서 해볼것-- 다만, 너무 작으면 성능 떨어짐
- KoELECTRA base_v3으로 사용했으며 1epoch 당 약 60분
- 만약 정확도 확인하는 부문에서 CUDA(GPU) 메모리 오버가 나오면 ▷ 모델 별도 저장 ▷ 런타임 초기화 ▷ 모델 로딩 ▷ 학습은 건너뛰고 정확도 실행
- ELECTRA large 사용했으며 1epoch 당 약 30분


## 처리 순서 (한국어/영어 동일함)
- 필요 lib 설치
- NSMC / Friends 데이터셋 처리
- 필요 모듈 import
- 데이터셋 처리 (Dataset Calss / 전처리)
- 모델 생성 (Create Model)
- 학습(Learn) - train파일만 사용(test제외)
- 테스트 데이터셋 정확도 확인하기
- 모델 저장하기
- 과제용 데이터 예측 및 맵핑
- 결과 파일 저장




