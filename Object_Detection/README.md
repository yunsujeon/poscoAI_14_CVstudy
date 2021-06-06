# Object Detection

### 5/26 study

1. R-CNN

2. SPPNet

3. Fast R-CNN

4. Faster R-CNN
- [논문 링크](https://arxiv.org/abs/1506.01497)
- [study PPT링크](https://docs.google.com/presentation/d/13PpVQUB_BIWYVsJKqW-ZgRYIEsQdBoZ_Ggm1263yXsM/edit?usp=sharing)
- 논문 이외 References
   - http://incredible.ai/deep-learning/2018/03/17/Faster-R-CNN/?
   - https://ganghee-lee.tistory.com/37
   - https://datascience.stackexchange.com/questions/80878/why-does-faster-r-cnn-use-sgd-optimizer-instead-of-adam	-Faster RCNN에서 Adam 대신 SGD 쓰는이유
   - https://nittaku.tistory.com/273
- 요약 : 
   - Region Proposal Network 를 제안함
   - Bounding Box를 만드는 부분에서 성능향상을 요함
   - 이전까지의 Selective Search 방식이 아닌 RPN(Network 형식)을 채택
   - 결과적으로 실시간 객체인식의 성과를 달성함