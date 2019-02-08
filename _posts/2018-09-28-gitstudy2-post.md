---
layout: post
title: "github 기본단어"
author: kilsu.shin
date: "2018-09-28 15:45:13 +0900"
tags: [github, study, git]
comments : true
---

## git 단어


git init: 깃 저장소를 초기화한다. 
 - 저장소나 디렉토리 안에서 이 명령을 실행하기 전까지는 그냥 일반 폴더이다. 이것을 입력한 후에야 추가적인 깃 명령어들을 줄 수 있다.

git config: “configure”의 준말, 처음에 깃을 설정할 때 가장 유용하다.

git help: 명령어를 잊어버렸다? 커맨드 라인에 이걸 타이핑하면 21개의 가장 많이 사용하는 깃 명령어들이 나타난다. 

git status: 저장소 상태를 체크. 
 - 어떤 화일이 저장소 안에 있는지, 커밋이 필요한 변경사항이 있는지, 현재 저장소의 어떤 브랜치에서 작업하고 있는지 등을 볼 수 있다.

git add: 이 명령이 저장소에 새 화일들을 추가하진 않는다. 
 - 대신, 깃이 새 화일들을 지켜보게 한다. 화일을 추가하면, 깃의 저장소 “스냅샷”에 포함된다.

git commit: 깃의 가장 중요한 명령어. 
 - 어떤 변경사항이라도 만든 후, 저장소의 “스냅샷”을 찍기 위해 이것을 입력한다. 보통 “git commit -m “Message hear.” 형식으로 사용한다.

git branch: 여러 협업자와 작업하고 자신만의 변경을 원한다? 
- 이 명령어는 새로운 브랜치를 만들고, 자신만의 변경사항과 화일 추가 등의 커밋 타임라인을 만든다. 

git checkout: 글자 그대로, 현재 위치하고 있지 않은 저장소를 “체크아웃”할 수 있다. 
 - 이것은 체크하길 원하는 저장소로 옮겨가게 해주는 탐색 명령이다. 

git merge: 브랜치에서 작업을 끝내고, 모든 협업자가 볼 수 있는 master 브랜치로 병합할 수 있다. 
 - git merge cats는 “cats” 브랜치에서 만든 모든 변경사항을 master로 추가한다.

git push: 로컬 컴퓨터에서 작업하고 당신의 커밋을 깃허브에서 온라인으로도 볼 수 있기를 원한다면, 이 명령어로 깃허브에 변경사항을 “push”한다.

git pull: 로컬 컴퓨터에서 작업할 때, 작업하고 있는 저장소의 최신 버전을 원하면, 이 명령어로 깃허브로부터 변경사항을 다운로드한다(“pull”).

