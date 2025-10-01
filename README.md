[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/nxSHaD6X)

실험1 3310 이인해

2025.08.27. (수)

0: Precision 0.59 / Recall 0.74
2: Precision 0.44 / Recall 0.67
1: Precision 0.14 / Recall 0.0006

**문제**
- 지원 요구도 1에 있는 데이터를 거의 분류 못 함.

**추정 원인**
- 클래스 불균형은 심하지 않다(0: 46.3% / 1 : 26.9% / 2 : 26.8%)
- 평가 지표는 MultiClass(다중교차엔트로피)인데 큰 문제는 안 될 것 같다
- 모델도 크게 문제는 없는 것 같은데...


2025.10.01. (수)

모델: 랜덤포레스트
Train Accuracy: 0.6775095195657458
Validation Accuracy: 0.487200259235256


예전에 한 것:
- 중요도에 따라 일부 라벨만 가지고 학습해보기
- 얼리스탑핑 해보기

선생님 조언: 데이터 증강 시도해보기
