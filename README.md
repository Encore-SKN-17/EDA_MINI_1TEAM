
<!-- 팀명과 부제목: 중앙 정렬, 크기 순서대로 -->
<div align="center">
    </h1><h2>🌸 산하엽(Skeleton Flower) 🌸</h2>

</div>

<!-- 주제: 왼쪽 정렬, 두 번째 크기 -->
<div align="center">
  <h2>대중문화(영화,음악)의 러닝타임 상관 관계</h2>
</div>

<!-- 팀 소개: 왼쪽 정렬 -->
<div align="left">
  

  <h3>✅ 팀 명</h3>
  <p><strong>SKN17-1st-1Team : 🌸 산하엽(Skeleton Flower) 🌸</strong></p>

  <h3>🧑‍💻 팀 멤버</h3>
  <!-- 팀 멤버 정보는 여기에 추가하세요 -->
</div>


| 이름    | 사진                                  |
|:-------:|:-------------------------------------:|
| [양정민](https://github.com/Yangmin3)|
| [김주서](https://github.com/kimjuseo71) |
| [홍문봉](https://github.com/Glowcloudy) |
| [한 훈](https://github.com/Hoonieboogie) |

---
## 대중문화(영화,음악)의 러닝타임 상관 관계
### 🗓️ (Mini)프로젝트 기간
✔️ 2025.07.18 ~ 2025.07.24
### 📖 프로젝트 소개

- 대중문화(**영화**,**음악**)의 러닝타임에 따른 변화를 그래프로 표현.

### 📌 프로젝트 필요성 (배경)

1. 영화의 러닝타임이 길어질수록 영화광고(PPL)가 증가하고, 이는 영화 수익에 긍정적인 영향을 미칩니다.
이로써 120분 이상의 영화는 더 높은 수익 가능성을 가지지만 동시에 수익 편차도 커져 리스크가 증가합니다.
상영 시간은 영화의 수익성과 직접적인 상관관계를 가지며, 120분 내외가 수익 안정성 측면에서 최적인 것으로 나타났습니다.

- 출처 : **1.** "Analysis of Business Factors Influencing Film Revenue"
   Advances in Economics Management and Political Sciences 166 **(February 2025)**


2. UCLA 연구에 따르면, 2020년 기준 Spotify에서 발매된 곡의 평균 길이는 약 3분 17초로, 1930년보다 오히려 2초 길어졌지만,
  1990년대부터는 전체적으로 노래 길이가 줄어드는 추세입니다. 이는 주의 집중 시간이 점점 짧아지고,
  스트리밍 사용자가 트랙을 자주 건너뛰면서 짧은 곡이 알고리즘에 의해 더 추천되기 때문이라는 분석이 제기됩니다.

- 출처 : **2.** "The Shorter the Song, the Sweeter the Stream?"  DataRes at UCLA **(Jan 7, 2022)**

  
3. TikTok은 음악을 처음 접하는 창구로서 중요한 역할을 하며, 짧은 콘텐츠를 통해 곡의 인기를 확산시킵니다.
 이는 Spotify 등 유료 플랫폼으로의 유입과 수익화로 이어지며, 음악이 ‘짧고 쉽게 소비되는 형태’로 진화하는 흐름을 촉진하고 있습니다.
- 출처 : **3.** "The Impact of Social Media on Music Demand: Evidence from a Quasi-Natural Experiment" **(May 2024)** 


<h1> Result <h1>
</div>

### 🎯 프로젝트 목표
  
- 대중문화 중 영화 와 음악의 러닝타임 상관 관계
- 시간이 지날수록 영화의 시간은 증가하고 음악의 시간은 감소함
- 그로 인한 상관 관계를 그래프로 표현

### 기술 스택
- <img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=Python&logoColor=white">
- <img src="https://img.shields.io/badge/pandas-150458?style=plastic&logo=pandas&logoColor=white">
- <img src="https://img.shields.io/badge/git-F05032?style=plastic&logo=git&logoColor=white">
- <img src="https://img.shields.io/badge/github-181717?style=plastic&logo=github&logoColor=white">
- <img src="https://img.shields.io/badge/numpy-013243?style=plastic&logo=numpy&logoColor=white">
- <img src="https://img.shields.io/badge/matplotlib-11557c?style=plastic&logo=matplotlib&logoColor=white">




### 데이터 출처

- [음악](https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-19212020-600k-tracks)    <img src="https://img.shields.io/badge/Spotify-1DB954?style=plastic&logo=spotify&logoColor=white">


- [영화](https://www.kaggle.com/datasets/raedaddala/imdb-movies-from-1960-to-2023?utm_source=perplexity) <img src="https://img.shields.io/badge/Netflix-E50914?style=plastic&logo=netflix&logoColor=white">


### WBS
| 단계 | 설명 | 일정 |
| --- | --- | --- |
| 🧩 **1. 데이터 수집 및 전처리** | - 차량 등록 수, 인구, 면적 등 공공 데이터 수집<br>- 지역별 차량 밀집도 계산 (등록 수 / 면적) | 7/10 |
| 🗂️ **2. ERD 설계 및 DB 구축** | - 관계형 데이터베이스 설계 (ERD)<br>- 차량 등록, 지역, 인구, 밀집도 등 테이블 생성 | 7/10 ~ 7/11 |
| 🤖 **3. 웹 크롤링 (FAQ 수집)** | - Selenium 활용하여 현대, 기아 FAQ 수집<br>- 질문·답변 구조화 후 DB에 저장 | 7/10 |
| 💻 **4. 웹사이트 구현** | - 차트/지도 기반 시각화 (차량 밀집도 등)<br>- 필터 기능 (지역, 차종, 연료 등)<br>- 사용자 맞춤형 코멘트 제공 | 7/11 |
| 📄 **5. 문서화 및 발표 자료 준비** | - README, ERD, WBS 정리<br>- 시연 및 발표 자료 구성 | 7/11 |


### 요구 사항 명세서

| 기능        | 설명                                                               |
| --------- | ---------------------------------------------------------------- |
|  |                             |
|   |                                |
|    |                                 |
|     |                           |
|  |  |
|      |                       |



### ERD


### 수행결과 및 시연페이지



### 회고록

- 양정민 : 
  
- 김주서 :
- 
- 홍문봉 :
- 
- 한 훈 : 
