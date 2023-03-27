# movie-review-analysis
영화 감상평 분석 프로젝트

## 자신의 인생 영화를 1개 선정하고, Daum 영화에서 해당 영화의 리뷰를 이용하여 워드클라우드 그리기 & 분류기 학습 시키기

### 개발환경

![OS](https://img.shields.io/badge/OS-macOS%20Monterey-lightgrey)
![Language](https://img.shields.io/badge/Language-Python-%234B8BBE)
![Platform](https://img.shields.io/badge/Platform-Jupyter-%23EB7425)
![Library](https://img.shields.io/badge/Library-Matplotlib-%23306998)
![Library](https://img.shields.io/badge/Library-pandas-%23150554)

### 인생영화로 `하울의 움직이는 성`을 선택한 이유

### 개인적인 이유
언제 들어도 질리지 않는 멋진 배경음악도 좋고,  
영화 곳곳에 숨겨진 복선을 찾는 재미도 쏠쏠하며,  
무엇보다도 **하울이 잘생겼기 때문이다.**

### 기술적인 이유
`하울의 움직이는 성` 의 Daum 영화 평점은 2022년 12월 9일 기준 총 903명이 평가했다.  
댓글 없이 평점만 등록한 건을 제외하면 평가 건수가 더 적을 것으로 예상한다.  
그럼에도 불구하고, `naive-bayes 분류기`가 긍정/부정을 잘 학습할 수 있을지 호기심이 생겨 해당 영화를 선택하였다.

</br>

## 영화 리뷰 데이터를 이용하여 나만의 새로운 결과물 만들어보기


### 개발환경

![OS](https://img.shields.io/badge/OS-macOS%20Monterey-lightgrey)
![Language](https://img.shields.io/badge/Language-Python-%234B8BBE)
![Platform](https://img.shields.io/badge/Platform-Jupyter-%23EB7425)
![Library](https://img.shields.io/badge/Library-Matplotlib-%23306998)

### 해당 결과물을 만든 이유

### 개인적인 이유
지정 과제에서 만든 워드클라우드가 너무 투박하다고 생각한다.  
인생 영화로 선택한 `하울의 움직이는 성`의 명장면을 활용하여 워드클라우드를 만들면   
텍스트 마이닝과 더불어 시각적으로도 의미있는 결과물을 만들 수 있기 때문에  
**영화의 한 장면을 영화 리뷰 워드클라우드로 표현**하고자 한다.


### 기술적인 이유
리뷰 데이터를 이용하여 워드 클라우드를 도출하는 지정과제를 수행할 때,  
청록색 계열의 색이 랜덤하게 나왔다.  
파라미터를 추가해 다른 테마의 색으로도 변경 가능하지만,  
여전히 색상 선택에 제한이 있다.  
따라서 지정 과제의 결과물에서 더 나아가, **워드클라우드를 좀더 예쁘게 출력**하고자 한다.

