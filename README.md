# HAPPY HOUSE

# Spring Boot, Vue.js 실습 프로젝트

#### Project Member : [Hyeonin Choi](https://github.com/HyeonIn), [Insoo Kim](https://github.com/iknowkis)

#### Project execution period : 2022.11.16~24

### Description

- HAPPY HOUSE는 아파트 매물 검색 웹 어플리케이션으로, 집을 구하는 사람들에게 매물 정보와 주변 상권 등 다양한 정보를 제공하는 어플리케이션이다.

### Tech

- BackEnd
  - Spring Boot
  - Tomcat
  - MySQL
  - MyBatis
  - 카카오 API
  - 네이버 검색 API
- FrontEnd
  - Vue.js
  - HTML/CSS
  - Vuetify
  - JavaScript(ES6)

### DataBase ERD

<img src="/db_erd.png">

### Detail

#### 회원 관리

- 로그인
  - 비밀번호 찾기 기능
    - 사용자가 등록한 이메일로 비밀번호 전송
- 회원 가입
  - 단계별 회원 가입
    - 아이디 중복 검사
    - 비밀번호 확인
    - 이메일 본인 인증
- 회원 정보 확인
  - 회원 정보 : 아이디, 비밀번호, 이메일, 프로필 이미지
- 정보 수정
  - 비밀 번호, 프로필 이미지 수정 가능
- 관심 아파트 등록

#### 아파트 매물 관리

- 매물 검색
  - 지역 선택 후 마커 표시
- 상권 검색
  - 특정 업종(학교, 카페, 스타벅스, 편의점) 커스텀 마커 적용 및 개별 관리
  - 동네 임의 키워드 장소 표시
- 표시 필터 옵션
  - 거래 정보 지도 표시 토글
  - 매물 금액 범위 제한 검색
  - 실시간 교통 상황 표시
- 아파트 매물 상세 정보
  - 직관적 ui 상세 정보 표현
  - 로드 뷰
  - 조회 수 표시 및 증가
  - 관심 매물 등록

#### 부가 기능

- 네이버 뉴스
  - 분야별 최신 뉴스 제공
- 인기 매물 확인
  - 높은 조회수를 가진 아파트 매물 리스트 제공
- 게시판
  - 공지사항 게시판 제공
    - 관리자만 공지사항 등록 가능
  - QnA 게시판 제공
    - 질문은 일반 회원만 가능
    - 답변은 관리자만 등록 가능

## [시연 영상](https://youtu.be/GX3VZfi_wPU)
