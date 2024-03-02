<h1>싸강두천 - 천재들의 싸움은 외나무다리에서 피어난다</h1>
![7F0AEFB8-A632-45F3-9FF6-B967CF1BC7C5__1_](/uploads/85814ea35423c581cb6b22353b4a6e0b/7F0AEFB8-A632-45F3-9FF6-B967CF1BC7C5__1_.gif)

<hr>

<h2>목차</h2>
1. [개요](#개요) <br>
2. [개발환경](#개발환경) <br>
3. [서비스 화면 및 기능](#서비스-화면-및-기능) <br>
4. [팀원 소개](#팀원-소개) <br>

<hr>

<h2>개요</h2>
경쟁 모드, 솔로 모드의 재밌는 시스템을 활용하여 학습 습관, 의지를 기르는 SNS 서비스

<h2>개발환경</h2>
Management Tool <br>
JIRA, GitLab, MatterMost, Notion, FIGMA
IDE <br>
VSCode, Intellij
infra <br>
AMAZON AWS, AMAZON S3, NGINX, DOCKER, UBUNTU
Frontend <br>
HTML, CSS, JAVASCRIPT, Vue.js
Backend <br>
JAVA, SpringBoot, Spring Security, Spring JPA, JWT, SWAGGER, MySQL

<h2>서비스 화면 및 기능</h2>
<h3>로그인</h3>
![로그인](/uploads/ea15ae4421157a005f04f1f9f3c86f52/로그인.gif) <br>
[상세 기능] <br>
- 아이디와 비밀번호를 입력 후 로그인 버튼을 누르면 로그인 완료 <br>
<h3>피드 게시판</h3>
![피드게시판](/uploads/68f72e9776622a7830bde87ec72e44a0/피드게시판.gif) <br>
[상세 기능] <br>
경쟁을 진행한 사람의 인증 사진이 올라가는 피드 게시판 <br>
- 해당 사람의 프로필, 닉네임, 인증 이미지, 대표 뱃지, 좋아요, 조회수 확인 가능 <br>
- 아래로 스크롤을 내리며 피드 확인 가능
<h3>피드 게시판 신고</h3>
![피드신고기능](/uploads/080c22a94acd6d30b5e34490ba42003a/피드신고기능.gif) <br>
[상세 기능] <br>
거짓 인증을 한 사람을 신고할 수 있는 기능 <br>
- 신고 사유 입력 가능
<h3>솔로 모드</h3>
![솔로모드기능](/uploads/85c4ea079e9cd6898c46106675535af0/솔로모드기능.gif) <br>
[상세 기능] <br>
혼자 사진을 올리며 일기처럼 기록하는 기능 <br>
- 하루에 한 번 솔로모드 진행 가능 <br>
- 해당 카테고리 버튼을 누르면 해당 솔로 모드를 진행하는 지 확인 <br>
- 솔로 모드가 생성되며 사진 인증 창으로 넘어감
<h3>메인페이지 솔로 모드 인증</h3>
![메인페이지솔로모드인증](/uploads/5e412b87beadb32714792d87568e7239/메인페이지솔로모드인증.gif) <br>
[상세 기능] <br>
- 사진 버튼을 누르고 인증 할 사진을 올리면 해당 카테고리는 완료
<h3>경쟁 및 솔로모드</h3>
![경쟁및솔로루트](/uploads/8a39dad1c59070c67a9e640d8f2b7133/경쟁및솔로루트.gif) <br>
[상세 기능] <br>
- 해당 카테고리를 진행했으면 더 이상 진행할 수 없음 <br>
- 솔로 모드 버튼을 누르면 솔로 모드 페이지로 이동 <br>
- 경쟁 모드 버튼을 누르면 경쟁 모드 페이지로 이동
<h3>알림창</h3>
![메인알림창](/uploads/9e547241eba1e8767d0b9bebea3323fd/메인알림창.gif) <br>
[상세 기능] <br>
경쟁 결과와 도전장 등 다양한 알림을 받을 수 있는 기능 <br>
- 경쟁 시작 알림 (미션 확인으로 진행도 확인 가능) <br>
- 경쟁 종료 알림 (결과 확인으로 경쟁 결과 확인 가능)
<h3>도전장함</h3>
![도전장함](/uploads/325553d437b5eb4bda2607472b2659ed/도전장함.gif) <br>
[상세 기능] <br>
받은 도전장을 확인할 수 있는 기능 <br>
- 해당 도전장을 수락하면 경쟁 시작하고 도전장이 사라짐 <br>
- 도전장 만료 시간 확인 가능
<h3>마이페이지</h3>
![마이페지수정도전장함쌀로우기능](/uploads/ab25cef2afddf515072bf452d9f03392/마이페지수정도전장함쌀로우기능.gif) <br>
[상세 기능] <br>
- 마이페이지에서 도전장함 버튼을 누르면 도전장함 확인 가능 <br>
- 마이페이지에서 쌀로우 가능
<h3>마이페이지 수정</h3>
![마이페이지수정](/uploads/bf01cdf3e54137ff9c4d33dadab826b3/마이페이지수정.gif) <br>
[상세 기능] <br>
마이페이지로 유저 정보 수정 가능 <br>
- 닉네임, 대표뱃지, 전화번호, 프로필 이미지 수정 가능
<h3>마이페이지 쌀로우</h3>
![마이페이지쌀로우기능](/uploads/fa093fefd3f7d5ebb2d75077142569ae/마이페이지쌀로우기능.gif) <br>
[상세 기능] <br>
- 쌀로워, 쌀로잉 버튼을 누르면 유저와 쌀로워, 쌀로잉 중인 현황 확인 가능 <br>
- 각각 유저의 프로필 페이지 이동 기능 및 쌀로우, 언쌀로우 기능
<h3>전적</h3>
![전적](/uploads/8366154e2ad7c9f5237b837374e0bbbf/전적.gif) <br>
[상세 기능] <br>
지난 경쟁 전적, 경쟁 카테고리별 승률 확인 가능 <br>
- 해당 전적 버튼을 누르면 경쟁 결과 상세 조회 가능
<h3>마이페이지</h3>
![마이페이지나머지기능](/uploads/d7e8311974077cbc8aff7eb5809fac89/마이페이지나머지기능.gif) <br>
[상세 기능] <br>
- 솔로 전적 <br>
- 뱃지 <br>
- 승률 <br>
- 도전 현황 <br>

<h2>팀원 소개</h2>

![image](/uploads/f658dea0fa5833f2ed2e31d1db05643c/image.png) | ![image](/uploads/0a09f8ffc401ea132e090c2b446be411/image.png) | ![image](/uploads/2baf8180ec158463bdb661f5099369bf/image.png) | ![image](/uploads/5eb7c7a249286c2afd421ccf50986624/image.png) |![image](/uploads/c7dc3ab730e1d99eaccd750e1e557aea/image.png) | ![image](/uploads/f13d774098ff8d15aaf9971f06e17a1a/image.png)|
 :---------:|:----------:|:---------:|:---------:|:----------:|:----------:
 유수안 | 홍지은 | 김태범 | 박현춘 | 오화석 | 전우리 |
 팀장/BE | 부팀장/FE | 팀원/FE | 팀원/BE | 팀원/FE | 팀원/BE |


