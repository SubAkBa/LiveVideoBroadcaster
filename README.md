# LiveVideoBroadcaster
Native Android app that can broadcast and play live video via RTMP - It is developed by [Ant Media](http://antmedia.io) (feat. SubAkBa)

## 3단계를 통해 라이브 스트리밍 앱을 쉽게 개발할 수 있다.

### Step 1: Media Server 다운
- URL : https://github.com/ant-media/ant-media-server
- 위 URL에서 Media Server Repository를 clone한 후에 start.sh 파일을 실행한다.
```
./start.sh
```

### Step 2: 모바일 기기에서 Live Streaming 하기
- 원본 URL : https://github.com/ant-media/LiveVideoBroadcaster
- 이 Repository는 본인의 프로젝트에 맞게 수정 했기 때문에 위 URL에 들어가 Repository를 clone한다.
- clone한 뒤, 안드로이드 스튜디오에서 프로젝트를 열고 MainActivity.java 파일을 연다.
- RMMP_BASE_URL 변수에 자기자신의 Media Server IP 주소를 입력한다.
  
- 앱을 빌드하고 실행하면, 아래와 같은 화면이 나온다.  
  
![](http://antmedia.io/wp-content/uploads/2017/04/Screenshot_2017-04-16-17-06-22-e1492352365617.png)
  
- Live Video Broadcaster 버튼을 클릭하고 연결이 되었다면, 아래 화면이 나올 것이다.  
  
![](http://antmedia.io/wp-content/uploads/2017/04/record-e1492352687883.png)
  
- 예시로 Stream Name을 "test"로 입력하고 버튼을 클릭하면, 아래 화면이 나올 것이다.  
  
![](http://antmedia.io/wp-content/uploads/2017/04/broadcastig-e1492352769543.png)


### Step 3: 모바일 기기에서 Live Streaming 보기

- 현재 Live Streaming을 하고 있다면, Player를 실행하여 Streaming을 볼 수 있다.
- 만약 Live Streaming을 하고 있지 않다면, 아래와 같은 검은 화면을 보게 될 것이다.

![](http://antmedia.io/wp-content/uploads/2017/04/Screenshot_2017-04-16-17-08-13-e1492352875527.png)

- 동일한 Stream name을 입력하고 Play 버튼을 클릭한다.
- 그러면 아래 그림과 같이 현재 Streaming을 진행하고 있는 다른 기기를 현재 기기로 시청할 수 있다.

![](http://antmedia.io/wp-content/uploads/2017/04/Screenshot_2017-04-16-17-08-56-1-e1492352925734.png)

