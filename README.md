# ay-oh

웹 서버를 운영하려면 어떻게 해야 할까요?  
우선 컴퓨터가 있어야 하고 열을 낮추기 위한 냉방 장치가 항상 켜져 있어야 합니다.  
이처럼 우리가 직접 웹 서버를 운영하는 것은 쉽지 않은 일입니다.  

그래서 이런 일을 대신 해주는 기업들이 있습니다.  
인터넷이 연결된 컴퓨터 하나하나를 <u>**host(호스트)**</u>라고 합니다.  
웹 서버를 운영하기 위한 컴퓨터, 즉 host를 빌려주는 것을 <u>**웹 호스팅**</u>이라고 합니다.  
구글에서 <u>**web hosting**</u>으로 검색하면 수많은 웹 호스팅 업체가 나옵니다.

그 중 많이 쓰는 GitHub Pages를 이용하면 직접 웹 서버와 서버 컴퓨터를 운영하지 않아도 됩니다.  
무료로 포트폴리오 웹 사이트 주소를 사용하여 누구나 접속할 수 있습니다.

## 사용 방법
### 1. 원격 저장소 생성
이 때, 원격 저장소의 이름은 <u>**{자신의 GitHub username}.github.io**</u>로 합니다.  
예를 들어, ay-oh라는 username을 가지고 있으면 <u>**ay-oh.github.io**</u>로 저장소 이름을 설정합니다.

### 2. `html` 파일 원격 저장소로 업로드
이제 포트폴리오의 메인 페이지가 될 `index.html`을 만든 원격 저장소에 올립니다(`git add` -> `git commit` -> `git push`).

### 3. 원격 저장소 설정 변경
GitHub는 내가 올린 `html` 파일로 웹 사이트를 운영할 수 있게 컴퓨터와 웹 서버를 무료로 제공합니다.  
그런데 이 원격 저장소를 웹 사이트처럼 사용하겠다고 GitHub에게 설정을 해줘야 합니다.  
저장소 카테고리 중 [Settings]에 들어가 스크롤을 내립니다.  
[GitHub Pages] - [Source] 아래의 None 부분을 <u>**[Branch: main]**</u> 로 선택하고 [Save] 버튼을 누릅니다.  

### 4. 정상적으로 페이지가 나오는지 확인
다시 GitHub Pages 탭에 가보면 다음과 같은 알림 창이 나타납니다.  
이 웹 사이트 주소로 사용하면 된다는 의미입니다.
> Your site is published at https://yeseo-ko.github.io

링크를 한 번 클릭해 보면 업로드한 `index.html` 페이지가 나타납니다.
