# 🍋 애스터 / 장서원 2025 PORTFOLIO
> when life gives you lemons, make lemonade  
> 어려운 일이 있더라도 긍정적인 마음으로 이겨내라는 의미를 담고 있습니다.


<p align="center">
  <!-- Version Control & Collaboration -->
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/> 
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/> 

  <!-- Frontend -->
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/> 
  <img src="https://img.shields.io/badge/React%20Native-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>  

  <!-- Backend -->
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/> 

  <!-- Database -->
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/> 

  <!-- Infra & OS -->
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/> 
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/> 
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> 

  <!-- AI & ML -->
  <img src="https://img.shields.io/badge/AI%20Fine--Tuning-FF6F00?style=for-the-badge&logo=openai&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"/> 
</p>
</br>

## 💎 Development Experience
- 2022 성신여대 소프트웨어 경진대회 은상 – `<flexy tale>`  
- 2024 멋쟁이 사자처럼 프론트엔드 12기  
- 2024 코드잇 부스트 백엔드 데모데이 3등  
- 2024 JavaSwing 게임 `<JAVACOOKIE>` 팀장  
- 2025 Draconist 소모임 운영 → [인스타](https://www.instagram.com/draconist_coding_yongsa/)  
- 2025 지도기반 나만의 걷는 길 공유 서비스 `<Geotdam>` 팀장  
- 2025 강아지 동영상 표정인식 서비스 `<PuppySense>` 팀장
- 2025 링크 저장 및 추천 서비스 `<LinkU>` 백엔드 파트장
</br>

## 🌟 대표 프로젝트
### 💻 Backend Projects
<details>
<summary>링큐 - 귀찮은 자료 저장과 관리를 한번에. 자료를 다시 보도록 추천해드립니다 (Spring Boot) </br> 
</summary>

- **귀찮은 폴더 정리를 AI가 알아서!**  
  기능) 사용자가 웹 링크만 입력하면, AI가 자동으로 폴더를 분류해줍니다. </br>
  구현) 도메인과 제목을 우선하고 크롤링한 본문을 보조 정보로 활용하도록 Open API 프롬프트를 설계했습니다.</br></br>
  어려웠던 점) </br>
  
- **잊고 있던 자료를 추천해줍니다!**  
  기능) 사용자의 현재 감정과 상황을 받아, 사용자가 저장했던 링크들을 추천해줍니다.</br>
  구현) </br></br>
  어려웠던 점) </br>

- **긴 글은 AI가 짧게 요약해줍니다!**</br>
  기능) AI가 사용자의 링크에 대한 요약을 제공합니다. </br>
  구현) 웹 크롤링을 통해 수집한 본문을 기반으로 사용자가 입력한 상황과 감정,기존에 분류했던 폴더명을 보조 정보로 활용합니다.</br>
  제목·요약·키워드를 포함한 JSON 형식으로만 반환하도록 프롬프트를 설계했고 이를 기반으로 사용자가 입력한 링크에 대한 요약을 제공합니다. </br></br>
  어려웠던 점) 크롤링 기술에 법적 논란이 있어서 이에 대한 고민을 오래했습니다. </br>
  팀 차원에서 창업 동아리 연계 상담과 교수님 법률 자문을 병행 진행했고, 개인적으로도 공부했습니다. </br>
  robots.txt를 준수하고 본문을 직접 저장하여 이용하지 않는 방식으로 코드를 수정하였습니다. 

- **다른 사람들과 링크 공유 기능**</br>
  기능)</br>
  구현)보기 권한을 부여 </br></br>
  어려웠던 점) </br>
  

- **사용자 맞춤 월간 큐레이션 및 AI 추천 외부 링크**  
  기능) 구독한 사용자는 내가 지난 한달동안 관심있던 링크에 대한 AI의 큐레이션을 제공받고, 비슷한 외부 링크를 추천받을 수 있습니다.</br>
  구현) LinkU가 기록한 사용자의 최근 URL을 기반으로 Gemini + Google Search가 외부링크 및 월별 가장 많이 열람한 링크를 추천해줍니다. </br></br>
  어려웠던 점) 큐레이션에서는 외부 링크 추천 기능이 제공되는 데 이것의 정확도가 높지 않았습니다. </br>
  이것에 대해 고민을 하던 무렵에, 5-Day AI Agents Intensive Course with Google 을 들었습니다.</br>
  수강 중 model과 tool 분리 개념을 접하였고, Perplexity 대비 OpenAI 정확도 문제를 Gemini+Google Search 조합으로 해결하며 실전 적용 성공했습니다.</br>

  - **총평/후기**   
    아직 진행하고 있는 프로젝트인데 여전히 구현할 부분이 많고, 항상 공부할 거리를 던져주어 매우 고맙게 생각하고 있습니다.</br>
    열정있는 기획자와 디자이너, 개발자들과 일하는 것은 항상 새롭고 즐거운 일입니다.</br>
</details>

<a href="https://github.com/LinkYou-2025/LinkU_backend" target="_blank">
  <img src="https://github.com/user-attachments/assets/7e92645c-c528-42fa-a393-73c301b2bf28" 
       width="1920" height="1400" alt="표지" />
</a>


<a href="https://github.com/LinkYou-2025/LinkU_backend" target="_blank" style="margin-left:20px;">
  <img src="https://img.shields.io/badge/링큐-UMC_8th_LINKU-CE93D8?style=for-the-badge&logo=github&logoColor=white" />
</a>
</br></br></br>
  
<details>
<summary>희소식 – 긍정뉴스 모음 (Spring Boot)
</summary>

- **맞춤형 긍정 뉴스 피드 & 스크랩**  
  기능) 사용자가 선택한 긍정 키워드 기반 뉴스 추천 및 평가하고 스크랩하는 기능을 제공합니다. </br>
  구현) 네이버 뉴스 api와 jsoup 웹크롤러를 사용하여 사용자가 가입시 입력한 키워드에 속하는 긍정 뉴스를 추천해줍니다. </br>
  사용자는 매일 제공받는 새로운 기사의 긍정도를 표시할 수 있고, 이것은 나의 감정 그래프에서 사용됩니다.</br></br>
  어려웠던 점) java에서 처음으로 크롤러를 사용해봤습니다. </br>
  처음에는 네이버 뉴스 api만으로 구현하려고 했지만 실제 뉴스 기사내용을 보여주어야 하는 기능이었기 때문에 jsoup을 같이 사용했습니다.</br>
  element.text()로 a태그 하위 링크까지 모두 긁어오는 문제를 element.ownText()로 해결하였고, Spring에서 메서드별 동작 차이 이해의 중요성을 깨닫게 되었습니다.
  

- **희소식 커뮤니티**  
  기능) 사용자가 직접 경험한 긍정적인 경험이나 뉴스를 공유할 수 있는 커뮤니티를 만들 수 있습니다. 이미지 업로드 및 댓글 및 좋아요를 통한 공감과 소통을 할 수 있습니다.</br>
  구현) Post와 Member의 다대다 관계 중간 매핑 테이블로 PostLike 테이블을 두었고 </br>findByUserIdAndPostId()로 좋아요 존재 여부 확인 후 존재시 삭제/없으면 PostLike 테이블을 생성하도록 했습니다. </br>  이를 통해다대다 관계 설계와 활용을 깊이 이해했습니다.

- **나의 감정 그래프**  
  기능) 사용자가 매일 추천되는 긍정적인 뉴스에 남긴 평가 기능을 기반으로, 일정 기간 동안의 감정 변화를 시각화한 그래프를 제공합니다. 주/월/6개월/전체 기간 비교 가능합니다.</br>
  구현) 사용자별 기간(주/월/6개월/전체) 완료 기록을 degree 합산해 그래프 배열로 변환하도록 했습니다. </br></br>
  어려웠던 점) 기간 별로 그려지는 그래프가 달라지게 기획되어 있어 다양한 기간 범위 계산(ChronoUnit, minusMonths)과 정확한 인덱싱 로직이 필요했습니다.</br>
  기획자,프론트 개발자와  여러번 의견을 나누며 로직을 확실히 정하여 해결했습니다. 협업능력을 향상시킬 수 있었습니다.

- **검색 기능** 
  기능) 긍정 피드와 희소식에서 키워드와 제목을 기반으로 검색이 가능합니다.
  
- **총평/후기**   
  기본이 되는 CRUD부터 좋아요,북마크 그리고 배포까지 Spring의 기초를 다질 수 있었던 프로젝트였습니다.</br>
  사실상 첫번째 spring 프로젝트였는 데, 처음부터 끝까지 친구들과 같이 공부하며 알아갈 수 있어서 즐거웠고, 이후 프로젝트를 진행하는 데 크게 도움이 되었습니다.</br>
  
</details>
<a href="https://www.instagram.com/reel/DOYuE8MiPfe/?utm_source=ig_web_button_share_sheet&igsh=MzRlODBiNWFlZA==" target="_blank">
  <img width="2988" height="1681" alt="표지" src="https://github.com/user-attachments/assets/2d47b675-22e9-49d8-a2eb-4f3c1a1d88db" />

</a>
<a href="https://github.com/Good-LuckyNews/BE" target="_blank" style="margin-left:20px;">
  <img src="https://img.shields.io/badge/희소식-DRACONIST-FFEB3B?style=for-the-badge&logo=github&logoColor=white" />
</a>
  </br>
    </br>
  </br>
<details>
<summary>FitLink – 맞춤형 운동 추천 & 주변 운동 기회 연결 (Spring Boot)</summary>

- **AI 기반 맞춤형 운동 추천 & 체력 분석** </br>
  기능) 사용자의 체력 진단 결과를 바탕으로 AI가 체력 수준을 분석하고, 개인에게 맞는 운동 루틴을 추천해 주는 웹 서비스입니다.  </br>
  구현) 국민체육진흥공단 위치기반 체력측정 및 운동처방 데이터를 Python으로 전처리했고 Weka에서 Weka에서 여러 분류기를 실험하여 LMT(Logistic Model Tree) 모델을 채택했습니다. </br>준비운동·본운동·정리운동 각각에 대해 별도 모델을 학습하고 Spring Boot 서버와 연동하여, 사용자의 성별·연령·체력 측정값을 입력하면 세 구간별 추천 운동을 반환하도록 구현했습니다. </br> </br>
  어려웠던 점) 공공데이터의 한글 인코딩 문제와 항목 불균형, 준비운동·정리운동 구간의 상대적으로 낮은 정확도가 문제였습니다. 클래스명을 영어로 치환하고, CoolDown 구간은 Top-3 추천 방식으로 보완하는 등 여러 실험을 통해 실용적인 정확도를 확보했습니다.


- **주변 공공체육시설 및 프로그램 탐색**  
  기능) 지도 기반 UI로 내 주변 공공체육시설과 운동 프로그램 정보를 한눈에 확인하고, 목적과 일정에 맞는 시설·프로그램을 쉽게 찾을 수 있습니다. </br>
  구현) 체육종합빅데이터센터 공공체육시설 프로그램 데이터를 수집한 뒤, 지자체마다 다른 포맷과 누락값을 처리하기 위해 정규화·정제 파이프라인을 구축하고, 좌표 변환 및 위경도 검증 과정을 거쳐 지도에 시각화했습니다. </br> Tmap 경로 API와 브라우저 위치 서비스를 연동해 현재 위치에서 선택한 시설까지 두 가지 최적 경로를 제시하도록 구현했습니다. </br> </br>​
  어려웠던 점) 시설명·주소·좌표가 불일치하거나 중복된 데이터가 많아, 자동 필터링 규칙과 수동 검증을 병행해야 했습니다. 프론트엔드와 함께 UX를 고려한 마커 색상, 요약 정보 구성, 필터 설계를 반복적으로 조정하며 사용자가 직관적으로 시설을 탐색할 수 있도록 개선했습니다.
  
- **체력 리포트 & 홈트레이닝 영상 연동**   </br>
  근력·지구력·유연성 등 항목별 점수와 개선이 필요한 영역을 그래프 형태로 제공하고, 국민체력 100 동영상 오픈 API와 연동하여, 부족한 체력 요소별로 최적의 운동 영상을 자동 매칭·추천합니다.  </br>
  구현) 국민체력 100 등급 기준의 불연속 구간을 선형 보간법으로 100점 만점 연속 지표로 환산하고, 레이더 차트와 연령대 평균 비교 막대그래프를 통해 사용자의 상대적 위치를 보여주도록 설계했습니다.   </br>점수가 평균 미만인 요소에 대해서는 국민체력 100 동영상 오픈 API를 호출해, 요소별로 적합한 홈트레이닝 영상을 추천하도록 연동했습니다. </br> </br>​
  어려웠던 점) 등급제 지표를 그대로 사용하면 사용자 입장에서 세밀한 차이를 느끼기 어려워, 여러 보간 방식과 시각화 방식을 기획자와 함께 비교·검토해야 했습니다. 또한 민첩성·순발력처럼 API에 영상이 없는 항목은 “적합한 영상이 준비되지 않았다”는 안내 문구를 추가해 사용자 혼란을 줄였습니다.
  
- **로그인, 온보딩 및 사용자 경험 설계**   </br>
  일반 회원가입과 카카오·구글 소셜 로그인을 지원하며, Spring Security와 JWT 기반 인증으로 확장성과 보안을 확보했습니다.   </br>
  구현) 첫 접속 시 서비스 핵심 가치를 소개하는 스플래시·온보딩 화면을 제공하고, 이후 일반 회원가입(이메일·비밀번호·프로필·위치 동의)과 카카오·구글 소셜 로그인을 지원하도록 설계했습니다.  </br>
  백엔드는 Spring Security와 JWT 기반 인증 구조를 사용해 토큰으로 권한을 검증하고, 멀티 소셜 로그인 시에도 하나의 계정으로 통합 인식되도록 구현했습니다. </br> </br>​
  어려웠던 점) 구글은 OIDC 표준이라 스프링 기본 구현 + 단순 매핑이면 됐는데, 카카오 소셜로그인의 경우, 기본 OAuth흐름은 같지만 응답 JSON이 달라서 직접 꺼내 써야 했습니다.</br>
  직접 카카오 소셜로그인 문서를 찾아보며 해결했습니다.
​
</details>

<a href="https://www.instagram.com/reel/DScyT4JjMyC/?utm_source=ig_web_button_share_sheet&igsh=MzRlODBiNWFlZA==" target="_blank">
<img width="1920" height="1080" alt="FitLink" src="https://github.com/user-attachments/assets/6a0ef39e-2cc2-45fb-943f-04473398b5b8" />

  
</a>
<a href="https://github.com/FitLink-project/FitLink-BE" target="_blank" style="margin-left:20px;">
  <img src="https://img.shields.io/badge/FitLink-DRACONIST-3C7DFF?style=for-the-badge&logo=github&logoColor=white" />

</a>
<a href="https://github.com/FitLink-project/FitLink-AI" target="_blank" style="margin-left:20px;">
  <img src="https://img.shields.io/badge/FitLinkAI-DRACONIST-4CAF50?style=for-the-badge&logo=github&logoColor=white" />
</a>
</br></br></br>



</br></br>


### 💻 frontend Projects
<details>
<summary>걷담</summary>


- **GCP 배포 및 CI/CD 구축**   </br>​
  기능) GitHub Actions와 GCP를 연동해 코드 변경 시 자동 테스트·배포가 가능하도록 하며, Nginx + Let's Encrypt로 HTTPS 백엔드를 안정적으로 운영했습니다. </br>
  구현) GitHub Actions 워크플로우로 CI/CD 파이프라인을 구축하였고, Nginx 설정으로 HTTPS 적용 및 DNS를 연결했습니다. </br> </br>
  어려웠던 점) Node.js와 Nginx 프록시, 두 곳에서 CORS 헤더 설정을 했기 때문에 CORS에러가 발생했습니다.</br>
  브라우저 네트워크 텝에서 access-control-allow-credentials 이중 헤더 문제라는 것을 알아내었고 Nginx 에서 기존 헤더를 무시하고 새로 설정하도록 하여 해결했씁니다.</br>
  ​
- **실시간 위치 기반 마킹 표시 및 시각화**   </br>​​
  기능) 사용자 실시간 위치를 WebSocket으로 받아 주변 벤치·가로등·CCTV를 OSM/국토교통 API로 조회해 지도에 마킹하며, 거리 기준 정렬과 태그 제한으로 직관적 탐색을 지원합니다. </br>
  구현) Socket.io로 실시간 위치 수신, OSM API(3km 가로등/1km 벤치)와 CCTV API 연동 후 좌표 정제·필터링. 초록 버튼 클릭 시 소켓 연결 시작해 위치 표시 및 주소 정보 제공. </br> </br>
  어려웠던 점) API 응답 형식 불일치와 범위 제한 로직 설계가 복잡해 자동 필터링 규칙을 반복 조정했습니다. 프론트 UX(마커 색상·요약 정보)와 연동하며 실시간 데이터 처리의 안정성을 높였습니다.</br>
  ​
- **장소 북마크 생성**   </br>​
기능) 사용자가 장소에 북마크 토글(생성/삭제)을 할 수 있으며, 마이페이지에서 북마크 목록 페이징 조회 가능합니다. </br>
구현) 중복 북마크 방지를 위해 이미 존재하는 북마크 여부를 먼저 확인하는 로직을 작성했습니다. </br> </br>
어려웠던 점) 프론트에서 전달하는 Tmap의 placeId와 백엔드 places 테이블의 기본키 placeId가 이름 충돌을 일으켜 Path Variable에서 undefined 오류가 발생했습니다.</br>
places 테이블에 Tmap 전용 tmapPlaceId 컬럼을 신설하고, Tmap ID로 장소가 없으면 새로 생성·매핑하는 동적 처리 로직을 구현했습니다.</br>
​
</details>
<a href="https://github.com/geotdam/geotdam-server" target="_blank">
  <img src="https://img.shields.io/badge/걷담-BE-4CAF50?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://github.com/geotdam/geotdam-frontend" target="_blank">
  <img src="https://img.shields.io/badge/걷담-FE-81C784?style=for-the-badge&logo=github&logoColor=white" />
</a>
</br></br></br>
<details>
<summary> pairmate (React Native)</summary>
<a href="https://github.com/PairMate/frontPairMate" target="_blank">
  <img src="https://img.shields.io/badge/PairMate-frontend-1976D2?style=for-the-badge&logo=github&logoColor=white" />
</a>
- ****
</details>
</br></br></br>
<details>
<summary>당장가자 – 여행 공유 앱 (React Native)</summary>

</details>


### 💻 AI Projects
### 4. PuppySense – 강아지 동영상 표정인식
- 주: 성신여자대학교
- TensorFlow, BlazeFace 활용, 동영상 프레임 추출 및 얼굴 인식



### Other Projects

### 6. 냉부해 
- 주: NEORDINARY Hackathon

<details>
<summary> Geotdam – 지도 기반 걷기 공유 서비스 </summary>
- 주: 성신여자대학교
- 사용자 맞춤 경로 기록 및 지도 시각화
</details>

### 7. FlexyTale
- 주: 성신여자대학교

### 9. 멋쟁이 사자처럼 플젝
- 주: 멋쟁이 사자처럼 12기
</br></br>


### 💻 ETC Projects

### 8. JAVACOOKIE
- 주: 성신여자대학교



## 🏆 Awards & Activities
- 2024 WISET 글로벌 멘토링 올해의 멘티상  
- 2024 성신글로벌프렌즈 튜터링 프로그램  
- 2024 잠실 청소년 센터 번역단 멘토  


## 📄 Certificates
- TOEIC 900, TOEFL 76
- **성신여자대학교 컴퓨터공학과**, 4학년 재학
- UMC 8기 spring boot 수료
- 멋쟁이 사자처럼 12기 frontend 수료
- 코드잇 부스트 백엔드 1기 수료


<p align="right">
  <a href="https://www.linkedin.com/in/seowonroaring02/" target="_blank">
<img width="50" height="50" alt="png-clipart-blue-and-white-in-logo-social-media-computer-icons-linkedin-linkedin-social-icon-miscellaneous-blue-thumbnail" src="https://github.com/user-attachments/assets/680cee8a-1793-46df-beec-c6b9edd466aa" />

  </a>
  <a href="https://turtle0204.tistory.com/" target="_blank">
    <img width="50" height="50" alt="티스토리(TISTORY)_로고_아이콘" src="https://github.com/user-attachments/assets/f70f621d-cb39-420b-9e65-64fbf7535146" />

  </a>
</p>
