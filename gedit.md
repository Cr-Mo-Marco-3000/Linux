# gedit

## gedit

- 윈도우 상에서 MS 메모장과 같은 기능 수행
- 프로그램 코딩, 마크업 언어와 같은 구조화된 텍스트 문서를 편집하는 용도에 중점을 두고 개발된 에디터
- `gedit 파일명`
  - 설치 안되어 실행 안될것임
- 많이 안씀

## vi

- 많이 씀
- 기존 에디터의 기능을 향상시킨 vim에디터라고 명명해야 정확한 명칭
- 항상 사용해 오던 vi 에디터의 기능을 향상시킨 에디터로 인식되어 사용되고 있기 때문에 그냥 vi 에디터로 호칭
- 명령 모드, 입력 모드, 라인 모드로 구분되어 모드를 전환하면서 사용하므로 초보자에게는 어려울 수 있음

### I. 에디터 작업 모드

#### 1) 명령 모드

- dd
- hjkl
- w
  - word
- b
  - back

#### 2) 입력 모드

- 명령 모드에서 입력 모드로 전환하는 명령키

- i
  - 현재 커서의 위치부터 입력
- a
  - 현재 커서의 위치 다음 칸부터 입력
- o
  - 현재 커서의 다음 행에 입력
- s
  - 현재 커서 위치에서 한 글자를 지우고 입력

#### 3) 라인 모드

- q
  - vi 에디터에서
- w
  - 쓰기

- 입력모드 - 라인모드 간 왔다갔다는 불가능
  - 

- set number
  - 옆에 번호붙이기

### II. 실행

`vi 파일명`

- 내용 삭제
  - dd