# 용어 정리
- 논문 읽으면서 등장하는 용어들 정리

## 용어

|용어|의미|
|------|---|
|[Affinity Propagation](https://datascienceschool.net/03%20machine%20learning/16.05%20Affinity%20Propagation.html)|모든 데이터가 특정한 기준에 따라 자신을 대표할 대표 데이터를 선택|
|Auto-encoder|입력-출력이 같도록 하는 구조, 입력값에 특별히 라벨이 있는 것이 아니라 입력값 그 자체가 정답|
|Batch Learning(Offline Learning)|점진적으로 학습해나가는 것이 아닌, 가용 데이터를 모두 사용해 훈련시키는 방식<br/>- Online Learning: 데이터를 순차적으로, 또는 미니 배치 단위로 시스템을 학습시키는 방식|
|Erd ős-Rényi model|가장 간단한 랜덤 그래프 모델 중 하나로 고정된 확률값에 의해 각 간선이 독립적으로 정해지는 모델|
|[Nucleus sampling](http://dsba.korea.ac.kr/seminar/?mod=document&uid=1345)|다음에 등장할 단어에 대한 확률을 계산한 다음, 그 확률을 내림차순으로 정렬한다. 이때 각 확률값의 합이 p 이상이 될 때 까지 단어들을 선택한 다음 샘플링|
|Permutation invariant(<-> Permutation equivariant)|입력 벡터요소 순서와 상관 없이 같은 출력 생성하는 모델(eg. MLP)|
|Piece-wise Constant Function|계단 함수|
|Posterior|사후 확률<br/>- 베이즈 정리로 근사 가능|
|Universal Approximation Theorem|신경망 네트워크를 이용해 어떤 함수도 근사시킬 수 있다는 이론|


## 참조
- https://3months.tistory.com/140#:~:text=Universal%20Approximation%20Theorem%EC%9D%B4%EB%9E%80%201,%EB%8A%94%20%EB%B9%84%EC%84%A0%ED%98%95%ED%95%A8%EC%88%98%EC%97%AC%EC%95%BC%ED%95%A9%EB%8B%88%EB%8B%A4

