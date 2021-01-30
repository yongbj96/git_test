# Git clone 사용방법

`git clone <url.git>`: Git에 작성된 파일을 로컬로 불러오기



# Git remote 사용방법

`git remote (-v)`: 연결된 리모트저장소 조회

`git remote add <로컬저장소> <url>`: <url>에 작성된 원격저장소를 <로컬저장소>와 연결

`git remote remove <로컬저장소>`: <로컬저장소>의 연결을 제거



# Github에 업로드하는 방법

`git status`: 파일 상태 확인

`git add .`: 변경된 모든 파일 추가

`git commit (-m "message")`: 파일 커밋

##### Commit Message Convention(출처: https://doublesprogramming.tistory.com/256)

- feat : 새로운 기능 추가
- fix : 버그수정
- docs : 문서수정
- style : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
- refactor : 코드 리펙토링
- test : 테스트 코드, 리펙토링 테스트 코드 추가
- chore : 빌드 업무 수정, 패키지 매니저 수정



`git push <로컬저장소> <브랜치명>`: 파일푸시
