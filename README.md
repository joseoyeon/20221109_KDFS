# 외형적 특징을 활용한 문서 작성 집단 분류 방법

## 실험 대상 기관 

* 고용노동부(A) : [https://www.moel.go.kr/news/enews/report/enewsList.do?pageIndex=1](https://www.moel.go.kr/news/enews/report/enewsList.do?pageIndex=1)
* 국립생태원(B) : [https://www.nie.re.kr/nie/bbs/BMSR00029/list.do?menuNo=200097&pageIndex=1](https://www.nie.re.kr/nie/bbs/BMSR00029/list.do?menuNo=200097&pageIndex=1)
* 금융위원회(C) : [https://fsc.go.kr/no010101?curPage=1](https://fsc.go.kr/no010101?curPage=1)
* 기획재정부(D) : [https:\\www.moef.go.kr/nw/nes/nesdta.do?searchBbsId1=MOSFBBS_000000000028&menuNo=4010100&pageIndex=1](https:\\www.moef.go.kr/nw/nes/nesdta.do?searchBbsId1=MOSFBBS_000000000028&menuNo=4010100&pageIndex=1)
* 산업통상자원부(E) : [https://www.motie.go.kr/motie/ne/presse/press2/bbs/bbsList.do?bbs_cd_n=81](https://www.motie.go.kr/motie/ne/presse/press2/bbs/bbsList.do?bbs_cd_n=81) 
* 외교부(F) : [https://www.mofa.go.kr/www/brd/m_4080/list.do?page=1](https://www.mofa.go.kr/www/brd/m_4080/list.do?page=1)
* 행정안전부(G) : [https://www.mois.go.kr/frt/bbs/type010/commonSelectBoardList.do?bbsId=BBSMSTR_000000000008&pageIndex=1](https://www.mois.go.kr/frt/bbs/type010/commonSelectBoardList.do?bbsId=BBSMSTR_000000000008&pageIndex=1)

## 성능 

### 선별된 55개의 특징으로 학습된 각 알고리즘별 분류 성능 지표

--
  | 정확도(Accuracy) | 정밀도(Precision) | 재현율(Recall) | F1-Score
  | 평균(%) | 표준편차(%) | 평균(%) | 표준편차(%) | 평균(%) | 표준편차(%) | 평균(%) | 표준편차(%)
SVM | 27.4898 | 00.8317 | 22.9225 | 01.6635 | 26.9726 | 00.8706 | 19.8921 | 01.0549
DecisionTree | 87.5102 | 01.7191 | 87.7607 | 01.6485 | 87.5061 | 01.7269 | 87.5405 | 01.7210
RandomForest | 95.2653 | 00.8649 | 95.3903 | 00.8264 | 95.2704 | 00.8729 | 95.2891 | 00.8634
ExtraTrees | 95.0612 | 01.1058 | 95.1549 | 01.0731 | 95.0618 | 01.1161 | 95.0716 | 01.1110
--

![image](https://user-images.githubusercontent.com/46625602/199924398-4cc731c9-cdf8-4fb3-93bf-78586b83b02e.png)
![image](https://user-images.githubusercontent.com/46625602/199923856-474b5625-34bd-4369-9ae9-01712ab5946d.png)
