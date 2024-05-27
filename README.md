### 최종과제 계획_애니메이션 데이터 분석

![Disney](https://github.com/s2irene/Skku_class/assets/88326175/3d7ced5a-cf73-44c2-af72-52f27f301bbd)

###### 1. 연구 분야

* **분야:** 국내 애니메이션 시장
* **연구 목적:** 
    * 이용자 특성, 제작 현황, 시장 규모 및 성장세, 트렌드 분석
    * 국내 애니메이션 산업의 현황과 미래 전망은 어떠한가
    * 애니메이션 산업의 성장 가능성 및 발전 방향 도출
    * 긍정적인 리뷰와 부정적인 리뷰는 어떤 요소에 집중하는지 파악

###### 2. 데이터 확보 방법

* **데이터 출처:**
    * 공공데이터포털, 방송통신위원회(누리집), 제공 된 자료
    * 리뷰, 네이버, IMDB 등에서 리뷰를 수집 (텍스트 분석을 통해 긍정적인 의견과 부정적인 의견을 분류)
    * 애니메이션 제작사, 유통업체, 플랫폼 데이터 (필요 시 - 라프텔)
    * 소셜 미디어: 트위터, 유튜브 등에서 드라마 관련 해시태그와 키워드를 추적(시청자들의 반응과 의견을 분석)
    * Kaggle
    * The Movie Database (TMDB) API: TMDB는 영화, TV 프로그램, 배우 및 기타 엔터테인먼트 관련 정보를 제공하는 무료 오픈 API입니다. 넷플릭스에 없는 영화와 TV 프로그램 데이터를 포함하여 다양한 콘텐츠 정보를 제공합니다. TMDB API를 사용하여 넷플릭스와 유사한 웹사이트 또는 앱을 만들 수 있습니다.
    * JustWatch API: JustWatch는 다양한 스트리밍 서비스에서 사용 가능한 영화와 TV 프로그램을 검색할 수 있도록 도와주는 API입니다. Netflix, Hulu, Amazon Prime Video 등 다양한 스트리밍 서비스를 지원합니다. 사용자가 자신의 지역에서 어떤 콘텐츠를 스트리밍할 수 있는지 확인하는 데 도움이 되는 넷플릭스 클론 웹사이트 또는 앱을 만들 수 있습니다.
    * Trakt.tv API: Trakt.tv는 사용자가 자신의 시청 목록을 관리하고, 평점을 매기고, 다른 사용자와 추천을 공유할 수 있도록 도와주는 API입니다. 넷플릭스뿐만 아니라 다양한 스트리밍 서비스를 지원합니다. 사용자가 자신의 시청 습관을 추적하고 다른 사용자와 콘텐츠를 추천하는 넷플릭스 클론 웹사이트 또는 앱을 만들 수 있습니다.

* **활용할 데이터 확장자:**
    * MS Excel

###### 3. 분석 방법

![Graph](https://github.com/s2irene/Skku_class/assets/88326175/c6853f72-c56f-4960-92ce-f5e9a0f5104e)

* **통계 분석:**
    * 시청률, 평점, 리뷰 개수 등을 분석하여 인기 애니메이션을 선정
    * 연령, 성별, 지역별 드라마 선호도를 비교 분석

* **텍스트 분석:**
    * 리뷰의 긍정/부정 감정을 분석하여 시청자들의 반응을 파악
    * 리뷰에 자주 등장하는 키워드를 분석하여 애니메이션의 주요 특징을 파악

* **머신러닝:**
    * 과거 시청 데이터와 리뷰를 기반으로 새로운 애니메이션의 인기를 예측
    * 시청자에게 개인화된 애니메이션 추천 시스템 개발
      
* **분석 도구:**
    * Python (Pandas) - 데이터 분석 라이브러리
    * Tableau - 데이터를 탐색 및 관리

###### 4. 분석 내용

* **애니메이션 이용자 특성 분석:**
    * 지역별, 성별별, 연령별 애니메이션 이용 현황 비교
    * 성별, 연령대별 선호 장르 및 작품 분석
    * 자녀 여부에 따른 애니메이션 시청 패턴 분석
      
* **애니메이션 제작 현황 분석:**
    * 국내 제작 애니메이션 편수 및 분량 추이 분석
    * 장르별, 제작사별 제작 현황 비교 분석
    * 제작 비용 및 수익 분석 (데이터 확보 가능 시)
      
* **애니메이션 시장 규모 및 성장세 분석:**
    * 국내 애니메이션 시장 규모 및 성장률 추이 분석
    * 해외 시장 진출 현황 및 전망 분석
    * 매체별 시장 점유율 분석 (온라인, 오프라인)
      
* **애니메이션 트렌드 분석:**
    * 인기 있는 애니메이션 작품 및 장르 분석
    * 최근 애니메이션 시장 트렌드 분석 (예: IP 활용, VR/AR 활용)
    * 미래 애니메이션 시장 전망 분석


###### 5. 추가적 사항

* 애니메이션 산업의 사회적, 문화적 영향 분석 가능
* 특정 장르나 작품에 대한 심층 분석 가능
* 해외 애니메이션 시장과의 비교 분석 가능
* Git hub에 최종적 업로드 (깃허브 페이지에 최종 과제 결과를 공개하고, 다른 사람들과 소통
    * 연구 목적 및 질문
    * 사용된 데이터 및 분석 방법
    * 분석 결과 및 해석
    * 결론 및 시사점
* 페이지는 명확하고 간결하게 작성, 시각 자료를 활용하여 이해하기 쉽게 구성.)


###### 6. 기대 효과

* 국내 애니메이션 산업에 대한 이해를 높임
* 데이터 분석 및 시각화 기술을 활용
* 시청자들의 선호도를 파악하여 더 많은 시청자를 확보할 수 있는 전략을 수립할 수 있음
* 시청자들은 자신의 취향에 맞는 애니메이션을 쉽게 찾을 수 있음
* 애니메이션제작자들은 시청자들의 반응을 이해하고 더 나은 애니메이션 제작할 수 있음

###### 7. 프레젠테이션

* 최종 과제 결과를 프레젠테이션을 통해 발표할 수 있습니다.
* 프레젠테이션에는 다음과 같은 내용을 포함해야 합니다.
    * 연구 개요
    * 분석 방법
    * 주요 결과
    * 결론 및 시사점


* TMDB API 문서: [https://developer.themoviedb.org/docs/getting-started](https://developer.themoviedb.org/docs/getting-started)
* JustWatch API 문서: [https://apis.justwatch.com/docs/api/](https://apis.justwatch.com/docs/api/)
* Trakt.tv API 문서: [https://trakt.docs.apiary.io/](https://trakt.docs.apiary.io/)
* 넷플릭스 클론 코딩 GitHub 레포지토리: [https://github.com/g0garden/React_Netflix_Clone](https://github.com/g0garden/React_Netflix_Clone)
* 넷플릭스 클론 API 연동 방법: [https://m.youtube.com/watch?v=FoD33gwhu00](https://m.youtube.com/watch?v=FoD33gwhu00)


