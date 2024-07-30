# 네이버 쇼핑 리뷰 감성 분류기

이 프로젝트는 네이버 쇼핑 리뷰 데이터를 사용하여 감성 분류를 수행하는 딥러닝 모델을 구현합니다. GRU(Gated Recurrent Unit) 네트워크를 사용하여 리뷰의 감성을 긍정 또는 부정으로 분류합니다.

## 주요 기능

1. 네이버 쇼핑 리뷰 데이터 전처리
2. GRU 기반의 텍스트 분류 모델 구현
3. 모델 학습 및 평가

## 사용된 기술

- Python
- PyTorch
- Transformers (Hugging Face)
- pandas
- scikit-learn

## 데이터셋

네이버 쇼핑 리뷰 데이터셋을 사용합니다. 이 데이터셋은 리뷰 텍스트와 평점으로 구성되어 있습니다.

## 모델 구조

- 임베딩 레이어
- 양방향 GRU 레이어
- 완전연결 레이어

## 설치 방법

필요한 라이브러리를 설치합니다:
pip install torch torchvision torchaudio transformers pandas scikit-learn
Copy
## 사용 방법

1. 데이터 다운로드 및 전처리
2. 데이터셋 및 데이터로더 생성
3. 모델 초기화
4. 모델 학습
5. 모델 평가

## 주요 구성 요소

1. `NaverShoppingDataset`: 커스텀 데이터셋 클래스
2. `GRUClassifier`: GRU 기반 분류 모델
3. `train_epoch`: 학습 함수
4. `eval_model`: 평가 함수

## 성능

테스트 세트에서의 정확도와 손실을 출력합니다.
