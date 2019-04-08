# 디스코드 랑이 봇 #
이 봇은 개인적으로 만들어질 목적이었으나 외국~~노동~~문화 동아리 디스코드 서버에서 만들게 되면서 대규모 프로젝트로 바뀌어 버린 봇입니다.
## Requirements ##

1.**Python 3.6**

2.**discord.py**

3.**beautifulsoup4.py** 

4.**youtube_dl.py**

5.**ffmpeg** 

6.**chromedriver**

7.**lxml**

## 랑이봇 사용법 ##

1. 위 requirement 에 있는 것들을 다운 받기
 - 2, 3, 4, 7번 은 pip 를 통해 다운 가능
 - 5번은 환경 변수 설정 해야 사용 가능 방법은 [여기](http://blog.naver.com/PostView.nhn?blogId=chandong83&logNo=221165275268&parentCategoryNo=&categoryNo=112&viewDate=&isShowPopularPosts=false&from=postView)
 - 6번은 함께 올려 놓았음으로 설치된 위치만 알아두시면 됩니다.(search.py 파일에 있는 크롬드라이버 위치를 당신 컴퓨터 기준에 맞게 바꾸시면 됩니다.)
 - 1번은 3.6 이하 버전을 사용을 권장 합니다.(3.7이상 버전 discord.py 사용 )

2. 봇 토큰 설정
 - 먼저 디스코드 봇을 만들기 만드는 방법은 [여기](https://blog.naver.com/wpdus2694?Redirect=Log&logNo=221192640522) 
 - 만든 후 봇 토큰을 복사해 Project_RangYi_Bot.py 파일 맨 아래 Bot_Token 부분을 당신의 봇 토큰으로 변경
 - 그다음 Project_RangYi_Bot.py를 실행 해서 
 
 Logged in as
 
 (당신의 봇 이름)
 
 (봇 id)
 
  이렇게 출력됬을시 성공

 - 디스코드 봇을 만드는 방법에 나온 서버에 봇 추가하는 방법대로 원하는 서버에 봇을 추가하면 됨(단 당신이 관리자 권한을 가지고 있는 서버만 )

## 참고 ##
Project_RangYi_Bot.py 실행을 중지 했을시 봇도 함께 꺼짐 봇을 24시간 운영하고 싶으시다면 라즈베리 파이 같은 호스팅 방법을 찾으시면 됩니다.

노래 재생기능에 약간의 오류(재생중에 재생 명령어를 쓰면 봇이 죽음)가 존재하므로 이 점 유의하시고 사용해 주시길 바랍니다.(언젠가 업데이트 )

## 기능 ##
(언젠가 제대로 업뎃함, 사진 추가 )

**1. 급식 크롤링**

명문 고등학교 광주 소프트웨어 마이스터고(통칭: GSM)의 급식을 불러옵니다(매월 마지막날 급식을 부르면 고장난다는 사실~~ 언젠가 고침)

**2. 아침운동 기능**

명문 고등학교 GSM에서 실시하는 기숙사 아침운동이 다음날 할지 안할지를 알려줌(~~정확도는 기대마라~~)

**3. 노래 틀기**

그대로 음성방에서 노래트는 기능임 ~~아야나나 프레드포트 같은 성능은 기대마라~~

**4. 유튜브 검색**

유튜브에서 영상을 검색해 띄움

**5. 사진 검색**

구글에서 사진 검색해서 올림 ~~5252 이 기능은 성인단어 검열이 안된다구!!~~

**6. 숨겨진 기능**

랑이 연애 시뮬레이터 제작 예정

**7. 발표 순서 정하기**

사람 이름만 넣어주면 발표순서를 정해서 올려줌 (현재는 이 봇이 사용되는 외문동 기준)

**8. 댓글 삭제**

말그대로 디코 대화를 삭제해줌

**9. 고소 관련 기능**

디코 대화중 말싸움이 생겼을시 관리자와 싸움이 발생한 2사람이 관리자와 2사람 제외 

볼 수 없는 방에서 조용히 해결하고 나오는 기능
