# Tetris

## Made_By Jun_Hyeok_Choi

### 1. 프로젝트

WINAPI로 제작한 테트리스 게임입니다.

게임 실행은 Tetris.exe을 다운하면 되고 소스 코드는 FILE폴더에 있습니다.

SOUND파일은 저작권적인 문제로 업로드 할 수는 없습니다.

<br>

### 2. 게임 디자인

테트리스판의 크기는 세로20 가로10으로 일반적인 테트리스판의 크기로 만들었다.

LEVEL은 1~20으로 LEVEL이 올라갈수록 블록이 내려오는 속도가 빨라진다.

CHANGE는 처음 3개, SCORE가 10,000점씩 올라갈 때 마다 3개를 추가한다.

LINE은 플레이어가 없앤 줄의 수를 뜻한다. LINE7줄이 사라질 때 마다 LEVEL이 1씩 올라간다.

SCORE는 1줄 사라질 떄 611점, 2줄 1,333점, 3줄 2,499점, 4줄 4,997점씩 올라간다.


LEVEL이 21이 되면 플레이어가 승리하고

생성된 블록이 처음부터 움직일 수 없는 상태라면 플레이어가 패배한다.

게임은 언제든지 PAUSE할 수 있고 RESET할 수 있다.

<br>

### 3. 게임 방법

실행 : START버튼 클릭

일시 정지 : PAUSE버튼 클릭

이동 : ←,↓,→

회전 : ↑

블록 변경 : CTRL

종료 : ESE

<br>

게임 실행 영상은 아래 링크로 들어가시면 있습니다.

<a> https://junhyeokportfolio.blogspot.com/2020/01/gametetris.html
