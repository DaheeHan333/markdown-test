# 20210125 git 과제 :baby:

1. git과 github의 차이점
	* git : 버전 관리 시스템 중 가장 유명한 프로그램. 프로젝트의 버전을 손쉽게 다룰 수 있게 해주는 시스템
	* github : git의 데이터를 저장하는 서버 
2. init, add, commit -m 명령어에 대한 설명 
	* init : git으로 프로젝트의 소스 관리 공간인 저장소를 만드는 것
	* add : 파일을 staged 상태로 만드는 것
	* commit -m "<MESSAGE>" : <MESSAGE>라는 커밋메시지로 스테이징된 파일들을 커밋하여 하나의 버전으로 만들어 git 데이터베이스에 저장 
3. remote, clone, push, pull에 대한 설명
	* remote : 원격 저장소를 관리할 수 있는 명령어. git remote add origin <URL> 을 입력하면, origin이라는 이름으로 해당 URL을 원격 저장소로 저장
	* clone : git clone <URL> 을 입력하면, remote repository에 있는 모든 파일들을 가져옴
	* push : git push -u <원격 저장소 별명> <로컬 브랜치명> 을 입력하면, 로컬에 있는 파일을 remote repository에 업로드	
	* pull : 로컬 repository와 비교하여 병합하고, local repository에 저장(add)까지 수행
4. 사진 첨부하기
![maxresdefault](https://user-images.githubusercontent.com/74919266/105702673-79799b80-5f4f-11eb-9fc0-bec07ce55c33.jpg)
5. branch, checkout 명령어 설명
	* branch : 작업을 분기해서 처리하는 경우
	* checkout : 브랜치를 전환할때
6. merge (fast-forward / merge conflict)
	* fast-forward : master 브랜치가 다른 브랜치가 포인팅하고 있는 커밋을 포인팅할때
	* merge conflict : 병합한 파일에 충돌 영역이 존재하여 병합에 실패할때		
