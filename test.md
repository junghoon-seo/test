# 인공신경망 세미나 자료 순서

1. 퍼셉트론: 생물학적 뇌를 본따 하나의 뉴런을 인공적인 모형으로 만든 모델
    + 퍼셉트론
        + 뉴런 : 각각의 돌기로 부터 신호를 받아 어떤 분계점에 도달하면 신호를 전달
        + 퍼셉트론 : 각각의 입력값에 가중치를 곱하여 합한 값을 활성함수에 입력하여 그 결과를 출력
        + 퍼셉트론 : 선형 변환의 합에 대한 비선형 변환
    + 활성함수
        + 다음 단계로 얼마만큼의 정보를 전달할 지 결정
        + 스텝펑션, 시그모이드, 하이퍼볼릭탄젠트,렐루...
    + 퍼셉트론의 목표
        + 입력값과 타겟값 사이의 관계를 잘 맞출 수 있는 가중치를 찾는 것
        + 관계가 잘 맞는지 어떻게 알 수 있나?
        + 손실함수(로스펑션) : 관측치 1개의 모델 예측치와 실제값이 얼마나 가까운가
            + 회귀 : MSE 를 사용(산술차의 제곱)
            + 분류 : 크로스엔트로피(범주 속할 확률이 높게 나타나는가)
        + 비용함수(코스트펑션) : 전체 데이터에 대한 오차, 손실함수의 평균값
    + 학습방법 : 경사하강법
        + 관련 수식
        + SGD
        + BGD(Batch
        + Mini Batch...
        + 학습률 러닝레잇
        + 다양한 경사하강법 알고리즘,, RMSP/ADAM
    + aaa
    + 

  
3. 다층 퍼셉트론
