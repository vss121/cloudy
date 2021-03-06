:pushpin:프로젝트명
------------
클라우디 : 문화 콘텐츠 리뷰 데이터 시각화 프로그램    
Cloudy : Cultural contents review data visualization program

:heavy_check_mark:개발 기간
-------------
2022년 5월 5일 ～ 2022년 6월 10일

:heavy_check_mark:개발 목적
-----------------
문화 컨텐츠에 대한 수요와 공급이 높아짐에 따라 많은 양의 리뷰를 시각화하여 한 눈에 알아보기 쉽게 하고 사용자가 문화 컨텐츠를 선택함에 있어 도움을 주고자 함.


:heavy_check_mark:작품의 주요 기능
----------------
1. 이용자가 검색할 키워드를 입력하고 분류를 설정한다.(영화, 드라마, 책 등)
2. 각종 리뷰 사이트에서 크롤링하여 데이터를 가져온다.
3. 리뷰 데이터에서 의미 있는 단어들의 빈도수를 체크 한다.
4. 긍정적인 단어와 부정적인 단어를 분류 분석한다.
5. 워드 클라우드를 생성한다.
6. 데이터베이스를 활용해서 검색 기록 확인 기능을 제공한다


:heavy_check_mark:시스템 구성도
------------
![이미지 이름](./img/project.png)


:heavy_check_mark:실행화면
-----------
:white_check_mark:홈 화면    
![이미지 이름](./img/main.png)    
:white_check_mark:검색 화면       
![이미지 이름](./img/search.png)    
:white_check_mark:검색 화면 - (예 : 겨울왕국 영화 검색 시)    
![이미지 이름](./img/cloud.png)    
:white_check_mark:기록 화면    
![이미지 이름](./img/history.png)    


:heavy_check_mark:실행방법
--------------
:large_blue_circle: crawling.py 파일을 모듈로 사용하여    
:large_blue_circle: main.py 파일을 실행    
:large_blue_diamond: fonts.json와 malgunbd.ttf 파일로 폰트 설정    
:large_orange_diamond: test.db 파일로 sqlite3 이용    
