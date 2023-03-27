# 2주차 과제 (B811186)

1주차 정리
URL : uniform resource name / 주소창에 입력하는 주소
URL -> 프로토콜 + DNS 주소
URL 주소 예시 : 203.249.65.153
문제점 1. 길고 복잡한 IP 주소들을 외우거나 관리하기 힘들다
문제점 2. IP 주소는 사정에 따라 바뀔수도 있다.

DNS 서버 등장 domain name system
-> 이름으로 접속가능하게 되었다
예시 : www.hongik.ac.kr

서버 : 우리가 필요한 자료를 갖고 있는 컴퓨터
-> 필요한 자료를 서버의 주소로 접근을 통해 받는다
리소스 : HTM:, CSS JS 파일들

2주차 정리

기본 동작 원리
1. Working Directory에서 코드를 수정한다
2. 수정 사항이 반영된 코드를 반영하기 위해서 git add 명령어를 이용하여 Staging Area로 보냅니다.
3. 이후 Staging Area에서 Commit 명령어를 통해서 git 디렉터리 상에 commit 당시의 수정 내역들이 기록됩니다. 우리가 가진 컴퓨터 내의 Repository에 저장됩니다. (Local Repository)
4. 이렇게 commit 된 내용들을 git push라는 명령을 이용해 최종적으로 github와 같은 원격 저장소로 보내게 됩니다.(Remote Repository)

사용법
1. git add : 작업 디렉토리(working directory)의 변경 내용을 스테이징 영역(staging area)에 추가하기 위해서 사용하는 Git 명령어이다.
2. git commit : 파일 및 폴더의 추가/변경 사항들을 저장할 때 사용한다.
3. git push : commit한 내용을 원격 저장소(remote repository)에 올린다.

클론 저장소(clone repository) : 원격 저장소를 복제한 저장소
→ 다른 사람의 소스 코드 복사본을 생성하는 것과 같으며, 개발을 할 때 보통 우리는 클론 저장소에서 작업을 진행하게 됩니다.

4. git fetch : 로컬 Git에게 원격 저장소에서 최신 메타데이터 정보를 확인하라는 명령 (확인만 할뿐, 변경된 데이터를 로켈 Git에 실제로 가져오지는 않는다.)
5. git pull : 원격 저장소에서 변경된 메타데이터 정보를 확인할 뿐만 아니라 최신 데이터를 복사하여 로케 Git에 가져온다.