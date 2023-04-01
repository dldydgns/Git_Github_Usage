# ~~1. [2021/12/23] : Git, Github 사용방법 숙지~~
# 2. [2023/04/01] : 협업시의 Git/Github 사용법
>## 팀장의 할일
>1. 프로젝트를 진행할 Repository를 깃허브에 등록
>2. 진행하면서의 요구사항이나 버그 수정사항 등을 Issue에 상시 업로드
>3. 팀원의 Push요청을 확인하고 Master Branch와 비교하며 Merge

>## 팀원의 할일
>1. 팀장에게서 권한을 받아 Repository에 연결
>2. 작업이 필요한 부분을 Clone하여 내 로컬에 저장 후 해당 작업에 맞는 Branch에서 작업
>3. 작업이 일단락되면 Add로 Working tree에 있던 작업 내용들을 Staging Area로 이동
>4. Clone으로 Staging Area에 있는 파일들을 새로운 버전으로 만들어 내 로컬 Repository에 저장
>5. Push명령어로 깃허브에 내가 작업한 Branch로 업로드
>6. 팀장에게 Merge요청을 알림

--------------------------------------------------------------

>## **Git Commands - Git Bash**
>+ git remote add __"Repository name"__ __"URL"__ : 새 저장소 등록(default=Origin)
>+ git clone __"URL"__ : 현재 디렉토리에 URL의 프로젝트 가져오기(default=All Branches)
>+ git init : 해당 디렉토리에서 새로운 로컬 Repository 생성
>+ git add __"FileName"__ : 변경된 파일 Staging Area에 추가
>+ git commit -m __"modified info msg"__ : add한 파일을 새로운 버전으로 local repo에 저장
>+ git push __'Repository name'__ __'Branch Name'__ : local repo를 remote repo의 Branch에 업로드 
>+ git merge __"Branch Name"__ : 현재브랜치에서 Branch Name의 변경사항을 병합
>
>* Remote Repository의 소스 가져오기
	>	+ git pull __"Repository name"__ __"Branch Name"__ : Merge(O)
	>	+ git fetch __"Repository name"__ : Merge(X)