# Daily productive app(Momentum APP clone)
#### 현재 할 일에 집중하고 하루의 투두리스트를 관리할 수 있는 생산성 앱

### 1.  특징 및 기능
  
- 현재 최우선으로 두고 있는 일을 설정하고 집중에 도움을 준다.
- 현재 시간을 확인하고 하고 있는 일에 집중하는데 도움을 준다.  
- 투두리스트를 작성하고, 목록을 완료하고 삭제할 수 있다.  
- 현재 위치를 검색해 해당 지역의 현재 날씨를 확인할 수 있다.  
- 로컬 스토리지를 이용해 브라우저 종료 후 재접속을 하더라도 저장한 목록이 제거되지 않는다.
- 새로고침할 때 배경화면이 랜덤하게 변경된다.

### 2. 사용 스택

해당 프로젝트는 **HTML**, **CSS**, **Vanila-Javascript**를 사용해서 만들었습니다.

### 3. 프로젝트 스크린샷

#### 3.1  메인 페이지
<p align="center">
<img src="https://user-images.githubusercontent.com/66715905/112455424-0e0c4880-8d9d-11eb-894b-576745e02729.png" width="80%">
</p>

#### 3.2  유저 이름 저장 및 최우선 작업 등록
|Before|After|
|:---:|:---:|
|<img src="https://user-images.githubusercontent.com/66715905/112457383-0cdc1b00-8d9f-11eb-9c2e-7229c7790ea7.png" width="90%">|<img src="https://user-images.githubusercontent.com/66715905/112457681-562c6a80-8d9f-11eb-823c-6b00eb040e6f.png" width="90%">|

#### 3.3  투두리스트 작성 및 로컬 스토리지 저장
|To-Do List|Local Storage|
|:---:|:---:|
|<img src="https://user-images.githubusercontent.com/66715905/112458566-43fefc00-8da0-11eb-8f14-e143d19c9493.png">|<img src="https://user-images.githubusercontent.com/66715905/112458724-70b31380-8da0-11eb-86c6-8b08469bb86b.png">|

#### 3.4 현재 지역의 날씨 확인(openweathermap.org에서 제공하는 API 사용)
<p align="center">
  <img src="https://user-images.githubusercontent.com/66715905/112459068-c5568e80-8da0-11eb-85c5-a4fdaa830cf2.png" width="50%">
</p>

### 4. 피드백 및 리뷰

#### 4.1 잘한 점
- 기능 별로 클래스를 작성하고 index.js 파일에 import해서 사용해서 모듈화를 구현한 것이 코드의 가독성을 높이는 부분에 도움이 됐음
- 로컬 스토리지를 활용해 데이터를 저장할 수 있도록 구현해 실제로 활용할 수 있도록 한 점이 유용했음
- fetch를 사용해 API를 활용하고, 이를 기반으로 원하는 기능을 구현할 수 있는 부분이 좋았음
- 직접 서버와 데이터베이스를 갖추지 않은 상태지만, 브라우저의 로컬 스토리지를 이용해 작은 데이터를 저장할 수 있는 부분을 알게되어 유용했음

#### 4.2 아쉬운 점
- 투두리스트의 UI 및 애니메이션 효과를 개선하고 싶었으나, 방법을 잘 몰라 어려움을 겪음
- 배경의 색상을 감지할 수 있도록 구현해 글자의 가독성을 높이고 싶었으나, 그렇게 하지 못했고 이로 인해 배경화면을 정하는 데 제한이 있었음
- 비동기적 자바스크립트 처리에 대한 이해가 부족한 상태에서 fetch와 then 문법을 사용한 비동기처리를 구현해, 이 부분에 대한 공부가 필요하다는 생각이 들었음

*본 프로젝트는 Vanila-JS-project repository에서 삭제 후 repository만 새로 만들어 등록한 프로젝트입니다*
