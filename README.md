# 2023_RYANBUCKS_v1.0
스타벅스를 모방한 <라이언벅스> 컨셉으로 만들어진 웹 페이지입니다.<br>
일반적인 프랜차이즈 커피전문점 사이트와 차별화하기 위해 장바구니&주문 기능을 추가했습니다.

<br>

### 📅 개발 기간
2023/10/10 ~ 2023/11/03

### 🛠️ 개발 환경
+ `JDK 11`
+ **IDE**: eclipse (2020-09)
+ **DB**: Oracle Database 11g Express Edition
+ **WAS**: Apache Tomcat 9.0.80

### 🧑‍🤝‍🧑 팀원 소개
+ 팀장 이승현: LOGIN, My Ryanbucks-개인정보 관리
+ 팀원 김태안: EVENT, NOTICE, My Ryanbucks-주문 내역
+ 팀원 박수연: MENU, My Ryanbucks-리뷰 관리, 장바구니, 주문 | DB 설계, 샘플 데이터 생성
+ 팀원 윤찬혁: INFO | 샘플 데이터 생성, 통합 테스트
+ 팀원 정다소: 메인, 헤더&푸터, 장바구니
+ 팀원 정영은: COFFEE, MENU, My Ryanbucks-리뷰 관리

<br>

## 📌 주요 기능
+ 비회원 서비스
  + INFO
    + 사이트맵
  + COFFEE
    + 커피 이야기
    + 에스프레소 음료
  + MENU
    + 음료
    + 푸드
  + EVENT
    + 이벤트
  + NOTICE
    + 공지사항
+ 회원 서비스
  + LOGIN
    + 로그인
    + 아이디/비밀번호 찾기
    + 회원가입
  + My Ryanbucks
    + 개인정보 관리
      + 개인정보 확인 및 수정
      + 비밀번호 변경
      + 회원 탈퇴
    + 주문내역
    + 리뷰 관리
  + 장바구니
  + 주문

<br>

## 💾 ERD
![ERD+20231106](https://github.com/sypark8393/2023_RYANBUCKS_v1.0/assets/161054595/bc0f2a1e-4a4f-4af1-9daa-98ac925b0b97)

<br>

## 📁 디렉터리 구조
+ RYANBUCKS_v1.0
  + WebContent
    + WEB-INF
    + cart
    + coffee
    + common
      + css
      + img
    + event
    + info
    + login
    + menu
    + my_ryanbucks
    + non_co_img
      + coffee
      + event
      + main
      + menu
      + review
      + sub_title
    + notice
    + review
  + src
    + address
    + cart
    + category
    + common
    + event
    + event_img
    + member
    + menu
    + menu_img
    + menu_option
    + notice
    + order_detail
    + order_total
    + review
    + review_board
    + utils

<br>

## 🎞️ 시연 영상
+ 비회원 서비스
  + [2023_RYANBUCKS_v1.0 │ [비회원 서비스] 시연 영상](https://youtu.be/d3pC6y6j6_c)
+ 회원 서비스
  + [2023_RYANBUCKS_v1.0 │ [회원 서비스] 시연 영상1](https://youtu.be/hoD2TtR9V4A)
  + [2023_RYANBUCKS_v1.0 │ [회원 서비스] 시연 영상2](https://youtu.be/YsJhfwPk3ZY)
  + [2023_RYANBUCKS_v1.0 │ [회원 서비스] 시연 영상3](https://youtu.be/8-PkNt1BhTo)
  + [2023_RYANBUCKS_v1.0 │ [회원 서비스] 시연 영상4](https://youtu.be/joCCo77utbU)
