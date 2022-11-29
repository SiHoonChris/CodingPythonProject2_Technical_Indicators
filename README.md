# CodingPythonProject2 - Technical Indicators (22.08.28 ~ 22.10.10)

<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"><br>

(사진)  

### 목차  
개발 동기 - 설계 - 후기 - 개선 사항 - 참고

## 개발 동기
주식 자동 매매  

## 설계
(사진)  
일목균형표, 볼린저밴드, 단순이동평균선, ATR

## 후기
꽤나 공들였던 기억이 난다.  
보조지표 개념에 대한 설명이 정확하지 못하여 정확한 구현이 어려웠다. 가령 26일 선행하는 보조지표를 만든다 하면, 당일을 포함하여 26일을 계산해야 하는지, 아니면 26일을 제외하고 계산해야 하는지 등 , 사소하지만 결과에 큰 영향을 미치는 것들. 그 수식에 적용하여 자료를 계산한 뒤, MTS 차트 보조지표와 비교하는 방식으로 결과 확인.   
수 많은 경우의 수에 대해 모두 코드를 작성하는 것이 어려웠다. 항상 예외 상황들이 등장해서 애먹었다. column을 구현하는데 힘들었다. 겹치는 경우, 시작은 같은데 끝이 여러개인 경우, 그 반대인 경우 등등. 서로 다른 색깔이 겹치는 경우 등
Anaconda , Jupyter Notebook 사용해봤다.  

## 개선 사항
매번 investing.com에서 csv파일 다운로드해서 xlsx파일로 변환하기 솔직히 귀찮다.
그 과정까지도 자동화시키면 좋을 것 같다.  
(일전에 investing.com에서 자료를 긁어오는 프로그램을 만든 적이 있으나, 이후 웹페이지 구조가 달라지는 바람에 적용안됨)

## 참고
- xx-xx-2022부, 별도 관리
- 현재 Repository에서의 기록  
레포 개설  
깃허브 업로드  
- 이전 Repository : ~
- 내의 Commit 기록들  
(xx-xx-2022) 주소1  
(xx-xx-2022) 주소1  