# Augmentation

### 6/9 study

1. Keras - ImageGenerator - Augmentation

2. Albumentation 라이브러리 (Blur, GridDistortion 등의 방법)
- [ppt링크](./image augmentation.pdf)
- 논문 이외 References
   - 

3. TTA

4. CutMix, Mixup
- [CutMix 논문 링크](https://arxiv.org/abs/1905.04899)
- [Mixup 논문 링크](https://arxiv.org/abs/1710.09412)
- [study PPT 링크](https://docs.google.com/presentation/d/13PpVQUB_BIWYVsJKqW-ZgRYIEsQdBoZ_Ggm1263yXsM/edit?usp=sharing)
- 논문 이외 References
   - https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=laonple&logNo=221758496781
   - https://everyday-image-processing.tistory.com/145
   - https://jjerry-k.github.io/blog/cutmix/?
   - https://blog.airlab.re.kr/2019/11/mixup
   - https://myunghaklee.github.io/blog/paper/2020-01-01-Manifold-Mixup-Better-Representations-by-Interpolating-Hidden-states_simple/?
- 요약 : 
   - CutMix는 모델이 객체를 식별할 수 있는 어떠한 부분에 집중하기보다 전체적 구역을 보고 학습해서 Localization 성능을 향상시키는 데 목적이 있다.
      - 두 개의 Sample을 조합해서 새로운 Sample 을 만든다.
         - 연속적으로 어떤 부분의 이미지를 Drop 시키고 그 공간에 다른 이미지를 채워넣는다.
   - Mixup은 훈련 데이터의 쌍 x,y 근방에서 가상의 feature-target 쌍을 찾을 확률을 측정하는 근방분포를 정의해서 데이터를 재모델링하는 것이다.
      - 과적합이 덜 발생할 수 있다. -> Regularization 의 역할
      - ERM -> VRM
