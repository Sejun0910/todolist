features : 구현해야 할 기능이에요.

- UI 구현하기
- Todo 추가 하기
- Todo 삭제 하기
- Todo 완료 상태 변경하기 (완료 ↔ 진행중)

Requirement : 과제에 요구되는 사항이에요.
1. 제목과 내용을 입력하고, [추가하기] 버튼을 클릭하면 Working에 새로운 Todo가 추가되고 제목 input과 내용 input은 다시 빈 값으로 바뀌도록 구성해주세요.
2. Todo의 isDone 상태가 true이면, 상태 버튼의 라벨을 취소, isDone이 false 이면 라벨을 완료 로 조건부 렌더링 해주세요. 위 영상을 보면 버튼 내 라벨이 다른 걸 볼 수 있죠?
3. Todo의 상태가 `Working` 이면 위쪽에 위치하고, `Done`이면 아래쪽에 위치하도록 구현합니다.
4. Layout의 최대 넓이는 1200px, 최소 넓이는 800px로 제한하고, 전체 화면의 가운데로 정렬해주세요.
5. 컴포넌트 구조는 자유롭게 구현해보세요.

## 작업 하면서 생겼던 문제들
내가 생긴 문제들 & 어려웠던 문제들
1. 추가하기 버튼을 컴포넌트 구분해서 만들었더니 css가 안 먹음
2. 토글 true 와 false 기능 왔다갔다 하는 것
3. 카드가 움직이면 완료와 취소로 이름이 변경되게 하는 것
4. input값에 입력하고 추가하면 input값은 다시 빈 값으로 만들기
5. 제목과 내용을 적고 추가하기 버튼을 누르면 홈페이지에 카드가 생기지 않고 새로고침이 되어버림 <br>
해결 방법 과정 블로그 -> : 

### 따로 구분한 컴포넌트 : 추가하기 버튼, 추가했을 때 생기는 제목과 내용이 담긴 카드들
<br>

과제완료 영상

https://user-images.githubusercontent.com/128359222/232403554-58f8dea3-d940-4fe8-8f70-4dbf6d119ec5.mp4

