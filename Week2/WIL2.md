# 2023-1-OC-Web-Study
add commit push
----------
git add: 변경된 파일을 stage에 추가하는 명령어입니다. 이 명령어를 실행하면 Git은 변경된 파일을 추적하고 다음 commit에 포함되어야 하는 변경 내용을 추적합니다.

git commit: 변경 내용을 로컬 Git 저장소에 저장하는 명령어입니다. commit 메시지와 함께 실행됩니다. 이 명령어를 실행하면 Git은 stage에 있는 변경 내용을 로컬 저장소에 커밋합니다.

git push: 로컬 Git 저장소의 변경 내용을 원격 저장소로 업로드하는 명령어입니다. 로컬에서 변경된 내용을 원격 저장소와 동기화하기 위해 사용됩니다.

pull fetch
----------

git pull: 원격 저장소의 변경 내용을 로컬 Git 저장소로 가져오는 명령어입니다. 이 명령어를 실행하면 원격 저장소의 변경 내용을 가져와 로컬 저장소의 내용과 병합합니다.

git fetch: 원격 저장소의 변경 내용을 로컬 Git 저장소로 가져오는 명령어입니다. 하지만, 가져온 변경 내용을 로컬 저장소의 내용과 병합하지는 않습니다. 가져온 변경 내용을 확인하고 원하는 경우 병합하는 명령어입니다.

get pull 과 fetch의 차이점
----------------------

git pull은 가져온 변경 내용을 로컬 저장소와 병합하는 반면, git fetch는 가져온 변경 내용을 로컬 저장소와 병합하지 않습니다.
git pull은 일반적으로 원격 저장소의 변경 내용을 가져오고 로컬 저장소와 병합하는 데 사용됩니다. 반면에, git fetch는 원격 저장소의 변경 내용을 가져와 로컬 저장소와 병합하지 않고, 변경 내용을 검토하고 병합을 원하는 경우 병합을 실행하는 데 사용됩니다.
git pull은 기본적으로 git fetch 후에 git merge를 실행합니다. 반면에, git fetch는 가져온 변경 내용을 로컬 저장소와 병합하지 않으므로 병합할 때 다른 merge 옵션을 사용해야 합니다.

1주차
------
URL : Uniform Resource Location
URI : Unifrom Resource Identifier
URN : Uniform Resource Name
URI 의 subtype 가 URN과 URL이다

DNS : Domain Name System
길고 복잡한 IP 숫자 대신 사용하는 서버

HTML CSS JavaScript
HTML - 자료
CSS - UI
JavaScript - 제어
Chrome/Internet Explorer - 위 세가지 정보를 받고 그려주는 애들

2주차
------
GitHub이용법
Repository 생성 및 stage 에 파일 업로드 및 동기화 하는 법

선택과제를 하면서 생긴 문제점과 배운점
---------------------
문제점:
폴더명을 어떻게 해야하는지 헷갈려서 파일 생성을 여러번 했다

배운점:
git desktop으로 commit 하는게 수월하다

unity 프로젝트의 file양이 엄청나다

unity 를 사용하려면 C#을 공부 해야겠다
