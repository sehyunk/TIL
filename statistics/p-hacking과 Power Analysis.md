# 1. p-hacking

- 유의미한 결과를 만들기 위해 p-value를 조작하는 것을 p-hacking이라 한다.
- 실험 결과를 정확하게 평가하기 위해 유의하도록 하자

## Multiple Testing Problem(다중 검정 문제)

- 95%의 신뢰구간에선 5%의 1종오류를 포함하고 있음
- 여러번 테스트를 걸쳐 5%의 1종오류를 찾아 결과에 활용하는 것은 p-hacking
- 이런 방식의 검정을 지양해야하고 다중검정문제를 보완할 수 있는 FDR이라는 방법도 있음

## 애매한 p-hacking

- p-value가 애매하게 유의미하지 않게 나왔을 경우(ex: 0.06)
    - 추가적으로 몇개의 샘플을 더해서 유의미한 결과를 만들 수 있으나 이건 p-hacking
    - 실험전에 미리 적절한 표본의 크기를 결정해놓고 실험에 임해야 함
- p-value가 크다면 둘 중 하나의 경우
    - 샘플 수가 적거나
    - 샘플은 충분하지만 두 그룹간의 차이가 없거나
- 올바른 샘플 사이즈를 알기 위해선 Power analysis(검정력 분석)를  해야함

# 2. Power Analysis(검정력 분석)

- 이미 진행한 실험을 바탕으로 적정 샘플 수를 계산하여 실험에 적절한 샘플의 수를 구하는 분석
- 검정력은 2가지 영향을 받음
    - 식별하길 원하는 두 분포 사이가 얼마나 벌어져있는가
    - 각 그룹에서 몇개씩 측정값을 얻을 것인가
- 적은 차이를 구분하기 위해서는 충분한 샘플사이즈가 필요함
    - 샘플사이즈가 클 수록 모집단의 평균을 잘 대변하기 때문
- 일반적으로 사용하는 검정력은 0.8, 유의수준은 0.05
    - 80%의 확률로 올바르게 귀무가설을 기각

### 참고영상

[https://www.youtube.com/watch?v=HDCOUXE3HMM](https://www.youtube.com/watch?v=HDCOUXE3HMM)

[Power Analysis, Clearly Explained!!!](https://www.youtube.com/watch?v=VX_M3tIyiYk)

[Introduction to power in significance tests | AP Statistics | Khan Academy](https://www.youtube.com/watch?v=6_Cuz0QqRWc)
