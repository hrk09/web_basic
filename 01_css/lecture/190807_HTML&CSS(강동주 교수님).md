# HTML & CSS

- 잘 꾸며진 네이버 사이트도 WEB developer로 style 을 제거해서 보면 웹 초기 버전과 다를 것이 없다.
- 포트폴리오: 영화 추천 서비스 웹 제작 => 음성인식 기반(빅스비, 구글 어시스턴트 etc) 영화 추천 서비스

![캡처](C:\Users\student\Desktop\캡처.PNG)



★★ **box model/ 단위(em, px 등) 중요함(시험에 나올 수 있음)/ display 속성** ★★

- h1은 block 속성을 갖고 있다. 

  - 따라서 화면크기 전체를 차지하고 있음
  - h1의 박스 크기를 줄인다고 하더라도, h1 이외에는 해당 줄에 들어올 수 없음
  - block 요소와 inline 요소가 있는데 inline 요소가 더 적어서 이걸 외우고 나머지는 block요소라고 외우는게 효율적

- block

- inline

  - block level과 달리 중간에 무언가를 넣고 싶을 때,(중간 링크 삽입 등)

  ```html
  <a href='#'>이건 인라인 태그야</a> 바로 뒤에 요소가 올 수 있어.
  관련 사항을 확인하고 싶다면 <a href='#'>이곳</a>으로 가주세요
   
  ```

  - 글자를 꾸며주는 친구들(strong)은 보통 inline

- none 과 visability hidden의 차이

  - none은 공간도 없고, visability hidden은 공간은 남아있다.