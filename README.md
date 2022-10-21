# STARBOX
--

### JUSTCODE 6기 2nd Project STARBOX팀의 Megabox 클론코딩 프로젝트입니다.
- 국내 대표 영화 티켓팅 사이트 '[메가박스](https://www.megabox.co.kr/)'을 모티브로 한 프로젝트입니다.
- 사이트 선정 이유
  -  처음 프로젝트를 e-commerce로 하였기에, 새로운 형태와 분야의 사이트를 찾던 중 기본 CRUD는 물론 이외 다양한 기능을 구현해 볼 수 있을 것 같아서 선정했습니다.

![영화 메인](https://user-images.githubusercontent.com/88419431/193578658-46ee5ce7-9cd6-42a1-aaae-13051aa3df86.PNG)


  
## 1. 개발 기간 및 인원

- __개발 기간__  : 2022.09.19 ~ 2022.09.30

- __프론트엔드__ :  박유빈, 이동호, 김정연, 양미옥

- __백엔드__ : 김민우, 오인환

- __[프론트엔드 GitHub](https://github.com/wecode-bootcamp-korea/justcode-6-2nd-team2-front)__ 

- __[백엔드 GitHub](https://github.com/wecode-bootcamp-korea/justcode-6-2nd-team2-back)__


## 2. 
 
## 2. 데이터 모델링

:paperclip:  [dbdiogram 링크](https://dbdiagram.io/d/6327c6e10911f91ba5db0917)   

![DB](https://user-images.githubusercontent.com/88419431/193578720-4b6a58e6-042d-4adc-aa50-f21e3beac4f9.PNG)

  
 
## 3. 적용 기술 및 구현 기능

### 3-1. 적용 기술(수정 필요)
+ Front-end : javascript, React.js, react-dom, react-router-dom, sass, styled-componets, react-icons, axios, qs, lazy-sizes,ContextAPI,webpack(컴파일러는  babel)
+ Common : RESTful API, PostMan, LiveServer
+ Community Tools : Slack, Zoom, Notion, Zepp, Trello
+ Version Control Tool : Git(flow는 github flow방식을 따름)


### 3-2. 프론트엔드 구현 기능

>프론트엔드  
  
- 이동호  
  - [예매페이지] 빠른예매 화면 UI 및 레이아웃
  - [예매페이지] 날짜, 시간별 슬라이드 추가
  - [예매페이지] 더보기 달력 추가 및 에러 헨들링 모달 기능
  - [예매페이지] 좌석선택 화면 전체 UI
  - [예매페이지] 인원별 좌선 선택 기능
  - [예매페이지] 결제화면 전체 UI
  - [예매페이지] 결제API 연동
  - [상영시간표] 전체 UI 및 레이아웃
  - [상영시간표] 더보기 달력 추가
  - [상영시간표] 날짜별 슬라이드
  - [상영시간표] 네비게이션 영화, 극장별 Tab

- 김정연
  - [상세페이지] 전체 레이아웃
  - [상세페이지] 누적관객수 tooltip
  - [상세페이지] 기대평 등록 삭제 레이아웃
  - [상세페이지] 무비포스트 레이아웃
  - [상세페이지] 예고편 레이아웃
  - [상세페이지] 스틸컷 레이아웃
  - [상세페이지] 기대평 map
  - [상세페이지] 예매버튼 링크
  - [상세페이지] 좋아요 api

- 박유빈
  - [메인페이지] 박스오피스 레이아웃
  - [메인페이지] 박스오피스 리스트 map
  - [메인페이지] 영화 검색 기능
  - [메인페이지] 페이지 이동 기능
  - [영화리스트] 전체 레이아웃
  - [영화리스트] 영화 카테고리 페이지 이동 기능
  - [영화리스트] 영화 리스트 카운트 기능
  - [영화리스트] 영화 리스트 map
  - [영화리스트] 영화 더보기 페이지네이션 기능
  - [영화리스트] 영화 포스트 이벤트
  - [영화리스트] 영화 검색 기능
  - [영화리스트] 영화 필터 기능

- 양미옥
  - [헤더] 전체 레이아웃
  - [헤더] use의 이동경로에 따른 ui 구현
  - [헤더] 서브메뉴 탭기능
  - [로그인] 전체 레이아웃
  - [로그인] 휴대폰 인증 기능
  - [로그인] 약관동의 레이아웃
  - [로그인] 약관동의 필터 기능
  - [마이페이지] 네비게이션 레이아웃
  
>백엔드

- 김민우  
  - ERD 모델링
  - 영화 리스트조회 API
  - 영화 상세페이지 조회 API 
  - 상영스케쥴 조회 API
  - 좌석선택 API
  - 티켓생성 API
  - 영화 좋아요 추가/삭제 API  

- 오인환
  - ERD 모델링
  - 회원가입 / 로그인 API 
  - 토큰 인증/인가 API   
  - 휴대폰 인증 API
  - 댓글 추가/삭제 Api
  - 마이페이지 API

  
## 4. 

  
## 5. API Docs

:paperclip: [전체 API](https://documenter.getpostman.com/view/22703204/2s7ZE4NQnp#de716034-8667-44c7-9662-0eadb80d143e)  


## Reference

- 이 프로젝트는 [메가박스](https://www.megabox.co.kr/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.

