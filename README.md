# NaverWebtoon_Recommendation_System_CBF
네이버 웹툰 추천 시스템

네이버 웹툰에 있는 콘텐츠들을 콘텐츠 기반 필터링(CBF)를 통해 추천 시스템을 만드려고 한다.

먼저 네이버 웹툰에 있는 웹툰 정보를 크롤링하기 위한 코드를 짜고 있다. (2020.08.07)

네이버 웹툰 홈페이지에서 웹툰 제목, 작가, 평점 데이터들을 가져올 수 있는 코드 구현을 완료했다. (2020.08.11)

지난번 TMDB 예제 실습을 해보고나서 떠올린 접근 방법은, 장르별 평점 기준 상위 10개 웹툰들을 샘플로 뽑아 각각의 웹툰 마다의 키워드를 5개~10개 정도 산출하여 

CBF 기반으로 구현하는 방법이었다.

문제는 이러한 분석을 넘어서 그림체 분석이나 스토리분석 등과 같은 분석을 통해 비슷한 서비스를 운영하고 있는 이미 있다는 점이었다.
관련 사이트 : https://www.picktoon.com/home

개인프로젝트로서 주제를 틀어야할지, 아니면 생각했던대로 구현해보아야할지 고민중이다. (2020.08.11)
