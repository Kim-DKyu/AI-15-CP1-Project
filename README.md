## 프로젝트명
이진 판단 인공신경망(순전파) 프로그래밍

## 프로젝트 개요
AI 모델에 대하여 순전파 연산 방식 이해 및 python을 활용한 0 또는 1로 이진 분류를 진행하는 인공신경망 구성을 통해 딥러닝 모델 활용 능력을 향상

## 프로젝트 진행
- tensorflow/sklearn을 사용하지 않고 python 및 numpy, pandas 등 내장함수만을 사용하여 진행
- Activation Function : sigmoid
- weight / bias : numpy를 통한 랜덤 값 할당
- mini_batch : 데이터를 한꺼번에 학습하지 않고 단위 별로 쪼개 인공지능 학습 진행
- accuracy :  F1 Score 를 구하는 것이 올바른 평가 방식이지만, 신경망의 최종 예측 결괏값과 실제 정답 데이터의 일치 여부를 비교하여 평균을 내는 방식으로 진행
- loss : cross_entropy_loss

## 폴더 구성 설명
- data
   - 이진 분류 인공신경망 구성에 사용된 데이터 파일
   - 출처 : https://drive.google.com/file/d/1SCO0ZGL_EDGWc9Le0JFDw9eww86xk1xJ/view?usp=share_link
   
- src
   - 프로젝트 진행 inpynb 파일
   
- technical report
   - 기술 보고서 pdf 파일
   - 내용 : 프로젝트 개요, 구성, 파이프라인 및 데이터, 함수 소개 등   
