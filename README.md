# 🖌️ Star Folio

스테이폴리오 사이트를 모티브로 공간을 예약하는 플랫폼

## 1. 제작 기간 & 참여 인원

- 2022년 3월 14일 ~ 2022년 3월 25일

**Front-end**

- 박철진, 정건희, 유강호

**Back-end**

- 박건규, 김가람휘

## 2. 사용 기술

**Front-end**

- React.js(v17)
- react-router-dom(v6)
- styled-components
- JavaScript
- HTML5 / CSS
- Git

**Communication**

- GitHub
- Slack
- Trello

* ## 구현기능
  * 회원가입/로그인
    * 카카오 엑세스 토큰을 받아 유저를 확인하고 유저 정보를 암호화하여 db에 저장하고 jwt 토큰 발행
    * request.header에 담긴 토큰을 이용하여 로그인 여부 확인
  
  * 행성 List API
    * 선택한 은하계, 테마, 검색, 인원수, 최소가격, 최대가격에 따라 행성을 불러오는 필터링기능 구현  
![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/87808288/160289167-b0c9bbc4-8a12-45bd-b716-774a42f8fe53.gif)  
![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/87808288/160289229-0d57b38a-acad-413a-b83a-977fea62c3f8.gif)

    * 체크인, 체크아웃 날짜 선택 시 예약되어있지 않은 행성을 불러오는 필터링기능 구현
    * 페이지네이션, 최신순, 가격순 정렬기능 구현  
![ezgif com-gif-maker](https://user-images.githubusercontent.com/87808288/160289028-9e9bd143-e039-43cc-83ac-20a8b8df7cd0.gif)  
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/87808288/160289220-b3629bee-2f40-49bc-bfac-86e6e360c635.gif)  


  * 숙소 Detail API
    * 체크인, 체크아웃 날짜를 선택한 후 행성을 선택하여 숙소 디테일로 들어갈 경우 숙소정보를 불러올 수 있는 기능 구현
    * 날짜를 선택하지 않고 숙소 디테일로 들어갈 경우 숙소정보와 예약가능한 날짜들을 불러올 수 있는 기능 구현

  * 예약 API
    * 예약할 인원 수가 숙소의 기준인원보다 클 경우 요금이 추가되는 기능 구현
    * 예약하고 예약정보를 불러올 수 있으며 예약상태를 변경하고 예약을 삭제할 수 있는 기능 구현
  
  * 위시리스트 API
    * 유저가 행성을 선택하여 위시리스트에 추가할 수 있고 위시리스트를 불러올 수 있는 기능 구현

# API Document

[API Document](https://documenter.getpostman.com/view/19725087/UVsSMigh)

# 시연영상

[starfolio](https://www.youtube.com/watch?v=BfIAwz-oeyc)
