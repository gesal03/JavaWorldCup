<img width="240" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/2ad2ec5d-82ae-4f6b-aafd-635483368afa"># JavaWorldCup
⚽️ '22 객체지향언어2(Java) Mini Project - JavaWorldCup

## 설명
2022 카타르 월드컵에서의 대한민국의 투혼을 이어 받아, 월드컵에 직접 참여하고 싶은가? <br>
그렇다면 **2022 Java World Cu**p에 참가하라!<br>
사용자는 떨어지는 단어를 타이핑하여 점수(단어 점수)를 얻어 5에 도달하면 슈팅 찬스에 도달한다. <br>
이때, 스페이스바를 연타하여 설정된 수치(100)에 도달하면 골을 넣을 수 있다. <br>
제한 시간 90분동안 상대보다 더 많은 골을 기록하여 월드컵에서 우승하라!<br>

## 시스템 구조
### 전체 프로그램 구조
<img width="494" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/eb8806eb-59f6-4f77-8aed-4d47de19145d">

### 게임 프로그램 구조
<img width="493" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/4a39e2d1-5297-4986-9643-5306dc8e5ba6">

## 관련 이미지
### 시작 화면

#### 메인 화면
메인 화면에서 게임 시작, 난이도 조절, 단어 추가, 랭킹, 배경음악(On/Off)가 가능하다.<br>
<img width="361" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/9e3a1132-aab8-4514-b5ab-f67dfdc3bb02">

#### 난이도 조절
난이도 설정 버튼을 클릭하게 되면 난이도를 선택할 수 있는 창이 뜬다. Easy, Normal, Hard 중 하나를 선택할 수 있다.<br>
<img width="359" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/8069ada8-34db-476d-9577-80a434e1d703">

#### 단어 추가
단어 추가 버튼을 클릭하게 된다면 단어를 입력할 수 있는 창이 뜬다. 이 창에서 단어를 추가할 수 있다.<br>
<img width="238" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/3b22df0d-f9cd-4fd4-8f71-f601631d89ec">
<img width="237" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/9314ebe8-518f-4ef3-9c5b-e47db4c29bfb">


#### 랭킹
랭킹 추가 버튼을 클릭하게 된다면 누적 랭킹을 볼 수 있다. 난이도(Easy,Normal,Hard) 별로 우승자 중 골 수가 높은 Top 5가 출력된다.<br>
<img width="298" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/4364d925-95ef-43ba-af73-f339a8ce0da8">
<img width="238" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/9aecb10d-c953-47e9-a31b-e627947b47ef">
<img width="240" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/293697b8-119f-4b14-9d8a-75894d5b32fa">

### 게임 진행 화면
#### 8강전
메인 화면에서 게임 스타트를 누르면 8강전 게임 화면으로 전환된다. 8강전임을 알리는 프레임이 출력된다.<br>
<img width="345" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/8f0a9d32-3646-4d0f-9b13-e244ea2c560b"><br>

Start 버튼: 중단되었던 게임(half-time, pause 버튼 클릭 시)을 재개할 수 있다.<br>
Pasue 버튼: 게임을 일시 중지 할 수있다.<br>
Exit 버튼: 게임에서 나가 메인화면으로 돌아갈 수 있다.<br>
Mute 버튼: 배경음악을 중단할 수 있다.<br>
Audio 버튼: 배경음악을 재생할 수 있다.<br>
단어 점수: 단어를 입력하여 1점씩 얻을 수 있다. 5점을 모으면 슈팅 찬스로 전환된다.<br>
내 골 수: 슈팅 찬스를 통해 골을 넣을 수 있다.<br>
상대 골 수: 난이도, Stage에 따라 일정한 확률로 증가한다.<br>
<img width="489" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/5e3ac420-12a4-4906-a955-5ef0b8f8cda8"><br>

점수가 증가할 때마다 손흥민 선수가 골대를 향해 움직이고 있다.<br>
<img width="439" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/4aef94dc-cc94-47cc-ae27-c0829acb7dcb">

스페이스 바를 연타하여 슛 게이지를 채울 수 있다. 슛 게이지가 끝에 도달하면 Goal이라는 메세지와 함께 나의 골 수가 1 증가한다.<br>
<img width="450" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/8b9b8f8d-0527-4f6a-9172-759ac33735cc">
<img width="454" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/b4f2b3ee-0207-401e-a127-ccf333b47e0d">

위와 같은 방법으로 게임을 진행하며 골을 넣어, 90분이 되었을 때, 내 골 수가 상대 골 수보다 많으면 경기에서 승리하게 된다.<br>
매 Stage 승리하게 되면 본 화면으로 전환된다.<br>
<img width="428" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/bb09d050-1b2f-4527-a2c4-b347052c6c44">

#### 4강전
4강전은 배경 이미지와 배경음악이 변경된다. 또한, 슛 게이지 차는 속도가 낮아지고, 상대 골 넣을 확률이 증가한다.<br>
<img width="421" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/afef118d-23d1-4f1f-9678-aad6a6ffe002">
<img width="465" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/55e2dfd4-f54b-4fdf-b95b-7840802bda26">

#### 결승
결승전 또한 배경음악과 배경이미지가 변경되고, 슛 게이지 차는 속도 하강, 상대 골 넣을 확률이 증가된다.<br>
<img width="431" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/c88809de-1403-4a9c-a235-7c21be734fc7">
<img width="454" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/b5d2df73-b941-4430-bc1a-12a9d491ee6f">

경기에서 승리하게 되면 이름을 입력하여 랭킹에 기록할 수 있다. 랭킹 기록 기준은 한 게임 동안 넣은 골 수이다.<br>
<img width="393" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/7881def9-eb5d-4fe5-864c-4466db56bcb8">

#### 패배 시
게임이 종료되었을 때, 상대 골 수 보다 내 골 수가 적으면 2번째 화면으로 전환된다. 그 후 랭킹 프레임으로 전환된다.<br>
<img width="438" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/97b2577c-a135-4a42-aaf3-f119a98582d7">
<img width="436" alt="image" src="https://github.com/gesal03/JavaWorldCup/assets/77336664/dff381e2-3456-4f3b-8ee7-fcb059eb355e">

### 느낀점
미니 프로젝트를 진행하면서 프레임 전환부터, 게임 전반적인 스레드 관리 등 다양한 어려움에 직면했지만, 책을 꼼꼼히 읽고, 프로그램 설계를 통해 해결할 수 있었다. <br>
이번 프로젝트를 통해 응용프로그램 개발에 큰 흥미를 느끼게 되었고, 방 중 Java를 통한 프로젝트를 해보고 싶은 생각이 들었다. 또한 Java에 대한 깊이 있는 공부가 필요함을 느꼈다.


