UI
==

웹사이트에 자주 쓰이는 UI 모음

##참고 

* IE9.js - https://code.google.com/p/ie7-js/
* html5.js - https://code.google.com/p/html5shiv/
* respond.js - https://github.com/scottjehl/Respond
* Normalize.css v3 - http://necolas.github.io/normalize.css/ ie8+ 지원
* Normalize.css v1 - https://github.com/necolas/normalize.css/tree/v1 ie6+ 지원
* Reset.css - http://meyerweb.com/eric/tools/css/reset/
* CDN - http://cdnjs.com/

##네이밍
###기본규칙
* 영문,숫자,언더스코어(_)만 사용할 수 있다.
* 단어와 숫자를 조합할 때는 언더스코어를 생략한다.
* 언더스코어를 이용해 3단계를 초과하여 조합할 수 없다. ex) section_lst_type
####클래스 네이밍 확장
* 종속 확장 클래스 : 기본형 클래스에 종속되어 여백,색깔,행간 등의 몇 가지 속성을 부여하고자 할 때 사용하는 클래스
* 독립 확장 클래스 : 기본형 클래스의 변형이 타입으로 분류할 만큼 클 경우 사용하는 클래스
```
 .mykin_lst // 기본
 .mykin_lst_v1,.mykin_lst_v2 // 종속 확장 클래스 
 .mykin_lst2,.mykin_lst3 // 독립 확장 클래스
 #wrap #header #container #content #footer // 레이아웃 예약어
 #pop_wrap #pop_header #pop_container // 팝업 레이아웃
```

###이미지 네이밍 규칙
* 형태+의미+상태 
```
 tab1_recomm_on // 형태_의미_상태
 btn_srch
 icon_num_black1
```

###파일 및 폴더 네이밍 규칙
* 메뉴이름+의미+상태 
```
 mykin_nboard_view.html // 메뉴이름_의미_상태
```
