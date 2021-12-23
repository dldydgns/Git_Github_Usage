# 용훈이의 공부방

* ### 1. [2021/12/23] : Git, Github 사용방법 숙지
>### Git Commands - Git Bash
>+ git remote add __"repoName"__ __"repo"__ : 새 저장소 등록
>+ git init : 해당 디렉토리에서 새로운 local repo 생성
>+ git clone __"repo"__ _'dir'_ : 프로젝트 가져오기 - (default=master Branch)
>+ git add __"FileName"__ : 변경된 파일 storage에 추가
>+ git commit -m __"modified info msg"__ : add한 파일을 local repo에 저장
>+ git push _'repoName(remote)'_ _'branch'_ : local repo를 remote repo에 업로드 
>
>* remote repo 소스 가져오기
	>	+ git pull <repoName> <branch> : Merge(O)
	>	+ git fetch <repoName> : Merge(X)