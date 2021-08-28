### 3장 사이킷런을 타고 떠나는 머신 러닝 분류 모델 투어


    다항 로지스틱 회귀(multinomial logistic regression) = 소프트맥스 회귀(softmax regression)

    오즈(odds): 특정 이벤트가 발생할 확률
    
    오즈비(odds ratio): P/(1-P), 이 때 P는 양성 샘플일 확률
    
    양성 샘플: 예측하려는 대상
    
    로짓(logit) 함수: logit(P) = log(P/(1-P)), 0과 1 사이의 입력 값을 받아 실수 범위 값으로 변환
   
    로지스틱 시그모이드 함수(logistic sigmoid function): logit 함수의 역함수, 간단히 시그모이드 함수(sigmoid function)라고도 함
   
    편향(bias): 예측이 정확한 값에서 얼마나 떨어져 있는지
    
    분산(variance): 특정 샘플에 대한 예측의 일관성(또는 변동성)을 측정
    
    규제(regularization): 데이터에서 잡음을 제거하여 과대적합을 방지할 수 있는 매우 유용한 방법
    
    서포트 벡터 머신(Support Vector Machine, SVM): 마진을 최대화하는 모델 
    
    서포트 벡터(support vector): 초평면에 가장 가까운 훈련 샘플
    
    마진(margin): 클래스를 구분하는 초평면(결정 경계)과 이 초평면에 가장 가까운 훈련 샘플 사이의 거리
    
    모수 모델(parametric model): 새로운 데이터 포인트를 분류할 수 있는 함수를 학습하기 위해 훈련 데이터셋에서 모델 파라미터를 추정한다. 훈련이 끝나면 원본 훈련 데이터셋이 더 이상 필요하지 않다.
    
    비모수 모델(nonparametric model): 고정된 개수의 파라미터로 설명될 수 없다. 훈련 데이터가 늘어나면 파라미터 개수도 늘어난다.
    
    인스턴스 기반 모델: 훈련 데이터셋을 메모리에 저장하는 것이 특징이다.
    
