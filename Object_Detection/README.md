# Object Detection

## 5/26 study

**1. R-CNN**
- [발표자료](https://drive.google.com/file/d/1A-BRY4Rw3fWX5nZxtQXz0Pzi11Tj4TIG/view?usp=sharing)
- [논문 링크](https://arxiv.org/abs/1311.2524)
- [참고자료1](https://jaehyeongan.github.io/2019/10/10/R-CNN/)
- [참고자료2](https://ganghee-lee.tistory.com/35)

**2. SPPNet**
- [논문 링크](https://arxiv.org/abs/1406.4729)
- [study pdf링크](https://drive.google.com/file/d/1SDbFpJMEJeqFp5KFroLMUAqtVsBLzOaL/view?usp=sharing)
- 논문 이외 References
   - https://blog.naver.com/PostView.nhn?blogId=jaeyoon_95&logNo=221785990158&categoryNo=0&parentCategoryNo=0&viewDate=&currentPage=1&postListTopCurrentPage=1&from=postView
   - https://man-about-town.tistory.com/52

**3. Fast R-CNN**
- [논문 링크](https://arxiv.org/abs/1506.01497) 
- [Fast R-CNN.pdf 첨부파일 참고]
- 논문 이외 References
   -https://ganghee-lee.tistory.com/36
- 요약 : 
   - ROI 추가로 CNN연산 횟수 감소
   - 한번의 학습으로 classification, lacalization 학습 가능
   
**4. Faster R-CNN**
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

## 6/16 study

**5. YOLOv1**
- [발표자료](https://drive.google.com/file/d/12QplEJiigX8BRuW-j-MEmcAKQpgGiETe/view?usp=sharing)
- [논문 링크](https://arxiv.org/abs/1506.02640)
- [참고링크1](https://bkshin.tistory.com/entry/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-YOLOYou-Only-Look-Once)
- [참고링크2](https://velog.io/@dkdk6638/YOLOv1-You-Only-Look-Once-Unified-Real-Time-Object-Detection)

**6. SSD**
- [논문 링크](https://arxiv.org/abs/1512.02325)

**7. YOLOv2**
- [논문 링크](https://arxiv.org/abs/1612.08242)

**8. YOLOv3**
- [논문 링크](https://arxiv.org/abs/1804.02767)
