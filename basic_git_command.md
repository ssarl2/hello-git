먼저 터미널에서 기본 깃 셋팅이 필요합니다. 여러분의 이메일과 이름을 등록해주세요. 누가 코드를 수정했는지 알리기 위함입니다.(혹시 이유가 틀렸다면 수정해주세요.)  
- `git config --global user.email "you@example.com"`
- `git config --global user.name "your name"`

자세한 설명은 생략하고 깃 사용에 있어 기본적인 사용방법을 알려드리겠습니다.  
vscode에서 터미널을 열고 `git clone https://github.com/ssarl2/hello-git.git`을 복사&붙여넣기 해주세요.  
- git : 내가 깃을 사용하겠다.
- clone : 깃의 명령어 중 하나.
- https://github.com/ssarl2/hello-git.git : 클론 할 주소.  

내가 저 주소(repository)에서 코드를 클론(다운로드)하겠다 라는 명령입니다. 
클론이 완료되었으면 vscode 왼쪽 상단에 File을 누르고 Open Folder를 눌러주세요. 
test_folder 안의 hello-git을 선택하고 Select Folder를 누르시면 됩니다.  
Ctrl+J로 터미널을 열고 `git checkout -b <자신의 이름>`을 쳐주세요. 깃을 사용하실때 영어만 쓰시는 것을 권장드립니다.
방금 새로운 branch(브랜치)를 만들었습니다. 누군가와 같이 코딩을 하기 위한 작업입니다.  
hello-git 폴더 안의 README.md파일에 예시와 같이 `- 이름 또는 닉네임`을 적어주세요. 그리고 Ctrl+S를 눌러 변경된 파일을 저장.  
터미널에서 `git add README.md`, `git commit -m "Useful information"` 그리고 `git push origin <자신의 이름>`을 입력해주세요.  
깃 푸쉬후에 로그인 하라는 비슷한 문구가 뜨는데 그냥 엔터를 하시면 인터넷 창이 하나 나타납니다. 
자신의 깃 계정을 로그인하고 Authorize GitCredentialManager를 눌러주세요.  
마침내 여러분들이 작업하신 것들이 깃에 저장되었습니다. 게임으로 치면 세이브 포인트 입니다.  
  
그 세이브 포인트를 다른 공동 작업자들에게 공유하는 것이 Pull requests입니다.
