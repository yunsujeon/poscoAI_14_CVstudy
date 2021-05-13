# Image Classification

### 5/12 study
1. AlexNet
- [논문 링크](https://www.nvidia.cn/content/tesla/pdf/machine-learning/imagenet-classification-with-deep-convolutional-nn.pdf)

2. VGGNet
- [논문 링크](https://arxiv.org/abs/1409.1556)

3. ResNet
- [논문 링크](https://arxiv.org/abs/1512.03385)

4. Inception V1 ~ V3
  - [논문 링크](https://arxiv.org/abs/1512.00567)
  - [study PPT링크](https://docs.google.com/presentation/d/197SMZgEppGqs4sU3dC4gjvAoTdzxLs1eYOAYVLXEba4/edit?usp=sharing)
  - 논문 이외 References
    - https://deep-learning-study.tistory.com/517
    - https://www.stand-firm-peter.me/2020/09/06/inception_v2_v3/?
    - https://ikkison.tistory.com/86
    - https://norman3.github.io/papers/docs/google_inception.html
  - 요약 : 
    - Inception 구조는 parameter수를 감소시키기 때문에 계산에 효율적
    - Factorizing Convolutions
      - Factorization into smaller convolutions (5x5 -> 3x3)
      - Asymmetric Convolutions (3x3 -> 3x1 or 1x3)
    - Utility of Auxiliary Classifiers (보조분류기 활용 -> 정규화 효과)
    - Effieicnt Grid Size Reduction (그리드 크기 축소)
    - Model Regularization via Label Smoothing (1,0,0,0 -> 0.925,0.025,0.025,0.025)
    - 위 기술들을 모두 사용, 최적점을 찾아 적용 한 것이 Inception V3
    - 위 기술들을 조금씩 사용, 하나씩 사용 한것은 Inception V2 모델들

