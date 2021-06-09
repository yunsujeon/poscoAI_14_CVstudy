# Image Classification

### 5/12 study
1. AlexNet
- [논문 링크](https://www.nvidia.cn/content/tesla/pdf/machine-learning/imagenet-classification-with-deep-convolutional-nn.pdf)

2. VGGNet
- [논문 링크](https://arxiv.org/abs/1409.1556)

3. ResNet
- [논문 링크](https://arxiv.org/abs/1512.03385)
- [study 문서링크](https://docs.google.com/document/d/10jnnSvAlrxamERIJon_d7IWWydkc5jFHkZlQbFVAIWA/edit?usp=sharing)

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

### 5/19 study
5. MobileNet
- [논문링크](https://arxiv.org/pdf/1704.04861.pdf)

6. DenseNet
- [논문링크](https://arxiv.org/pdf/1608.06993.pdf)
- [study 문서링크](https://docs.google.com/document/d/1VPHR-tEUKZNWe3PAysoI28Y9rHKMZbPrShI2cGAVbPc/edit?usp=sharing)
- 논문 이외 References
   - https://blog.airlab.re.kr/2019/07/densenet
   - https://csm-kr.tistory.com/10
   - https://deep-learning-study.tistory.com/528
   - https://ysbsb.github.io/cnn/2020/02/12/DenseNet.html
   - https://velog.io/@kangtae/%EB%85%BC%EB%AC%B8%EB%A6%AC%EB%B7%B0-Densely-Connected-Convolutional-NetworksDenseNet
   - https://jayhey.github.io/deep%20learning/2017/10/13/DenseNet_1/
   - https://chloe-ki.tistory.com/entry/densenet-densely-connected-convolutional-networks
   - https://wikidocs.net/121707
   - https://warm-uk.tistory.com/46


7. SeNet
- [논문링크](https://arxiv.org/pdf/1709.01507.pdf)
- [study PPT링크](https://docs.google.com/presentation/d/18RblST2lA_6EuKZqCC82yoHAgLc-ZI-1fqXAFn0fqKg/edit?usp=sharing)
- 요약 : 
   - 짜내고(Squeeze) 활성화시키는(Excitation) 망
   - SE block을 통해 Squeeze 와 Excitation을 수행한다.
      - Squeeze : Feature map을 Squeeze를 통해 C개 차원의 1x1 사이즈 Map으로 변환해준다.
      - Extraction : 두 개의 FC 층을 더해 각 채널의 상대적 중요도를 알아가는 것
   - SE block은 기존 CNN 모델과 결합해서 사용이 가능
      - 성능 향상 but 파라미터 수 많이 늘지 않는 장점

8. EfficientNet
- [논문링크](https://arxiv.org/pdf/1905.11946.pdf)
