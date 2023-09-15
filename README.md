# Toy_dcx_data_analytics
- 환자 페인 포인트 찾기 : 안과 환자
- 댓글 최소 1천건 이상(스크래핑 사이트 3개 이상)
- DB 컬럼 : 작성자, 작성일, 내용, 별점 , 병원명 중 존재하는 컬럼 가져오기
- 팀원 : 김상아 , 조효원 

### 📑스크래핑 사이트
| 사이트 | DB컬럼 | 뽑은거..! |방식 | 
| -- | -- | -- | --|
| [아이리뷰](https://xn--oy2b21f01h9lc.com/)  | 작성자, 내용,  병원명 | 스마일라식,라식,라섹,노안백내장,안내렌즈삽입술,망막,녹내장,안구건조증,기타 | 더보기 | 
| [구글_푸른세상안과](https://www.google.com/search?q=%ED%91%B8%EB%A5%B8%EC%84%B8%EC%83%81%EC%95%88%EA%B3%BC%EC%9D%B8%EC%B2%9C&sca_esv=564238075&biw=1283&bih=821&tbm=lcl&sxsrf=AB5stBgpa9UHUzKxElUOy8pcmUItR49ZsA%3A1694401294025&ei=DoP-ZNGUAcHb-QaI7oC4BQ&ved=0ahUKEwjR0_LZyKGBAxXBbd4KHQg3AFcQ4dUDCAk&uact=5&oq=%ED%91%B8%EB%A5%B8%EC%84%B8%EC%83%81%EC%95%88%EA%B3%BC%EC%9D%B8%EC%B2%9C&gs_lp=Eg1nd3Mtd2l6LWxvY2FsIhjtkbjrpbjshLjsg4HslYjqs7zsnbjsspwyAhAmMgIQJjICECZIpilQqwlY8iZwCHgAkAECmAFroAGWDaoBBDE3LjK4AQPIAQD4AQHCAgQQIxgnwgIFEAAYgATCAgoQABiABBgUGIcCwgIHEAAYigUYQ8ICBBAAGAPCAgsQABiABBixAxiDAcICBxAAGA0YgASIBgE&sclient=gws-wiz-local#rlfi=hd:;si:17075660981150999360,l,ChjtkbjrpbjshLjsg4HslYjqs7zsnbjsspxI1OflheeAgIAIWi8QABABEAIYABgBGAIYAyIb7ZG466W4IOyEuOyDgSDslYjqs7wg7J247LKcKgIIApIBD29waHRoYWxtb2xvZ2lzdKoBRBABMh8QASIbd-9OFehOaJTc2c2DULaHO3By6LkZqZLWtf1DMh8QAiIb7ZG466W4IOyEuOyDgSDslYjqs7wg7J247LKc;mv:[[37.44377917731903,126.70182128533088],[37.44341922268097,126.70136791466909]])  | 작성자, 작성일 , 내용, 별점 , 병원명 | 스마일라식라섹, 노안백내장, 드림렌즈 |스크롤 | 

## 👩 김상아
### 구글_푸른세상안과
- 구글_푸른세상안과_리뷰
s

## 👩🏻 조효원
### 아이리뷰 홈페이지 
- 작성자, 내용, 병원명 리뷰 가져와 리스트에 담기

  <img src="./images/병원리뷰.JPG" width="600" >

- csv로 저장하기 

     [eyereviews_list.csv](./datasets/eyereviews_list.csv)
  <img src="./images/csv.JPG" width="600">









