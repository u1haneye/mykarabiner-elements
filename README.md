#macOS 에서 Karabiner-Elements 를 이용한 키 변환

>맥북프로 2018 15인치

_ _ _
- Royal TSX 에서 왼쪽 shift+space 또는 오른쪽 option 키로 한영전환하기

Microsoft Remote Desktop 10 과는 다르게 shift+space 키조합을 원격환경으로 건네주지 않고 맥에서 설정한 shift+space 가 실행되어 맥에서 한영전환이 이루어짐.
이때 원격환경의 키보드 레이아웃은 한글 키보드(101키) 종류 1로 설정하여야 함, 원격컴퓨터를 로컬로 사용할 경우에는 `jwshiftspacekey` 프로그램을 사용하여 한영전환.

_ _ _

- Fn 키와 왼쪽 control 바꾸기

맥의 Fn 키 위치는 애매함.
블루투스 등의 외부입력장치를 사용할 경우에는 Fn 키를 자체적으로 처리하는 등 맥의 키보드와 키값이 다른 경우가 많으니 끌 것.

_ _ _

- shift 키를 누른채로 backspace 를 누르면 커서 뒤의 내용 지우기

맥에는 윈도우 등에서 사용가능한 delete 키가 없음.

_ _ _

- 오른쪽 shift 키와 return 키를 누르면 특수문자 입력창 보이기

_ _ _

- iTunes 에서 왼쪽 오른쪽 방향키로 앞뒤로 5초 건너뛰기

_ _ _

- Caps Lock 키로 Dock 보이기/감추기

사용하지 않는 Caps Lock 키로 Dock 보이기/감추기로 활용

_ _ _

- parallels 에서 왼쪽 command + d,w,z 을 왼쪽 ctrl 로 맵핑하기

패러렐즈에서 잘 알려진 키 조합은 command 키로 사용하여도 ctrl 로 알아서 전환해주는 듯 하나 엑셀의 복제, 창 닫기, 되돌리기 등은 해당되지 않는 듯 하여 추가함.

_ _ _

###### 출처 및 참고한곳
[카라비너(Karabiner-Elements)를 이용하여 맥 키보드 맵핑하기 (오른쪽 커맨드와 옵션을 한/영, 한자 키로 사용하기 등)](http://blog.naver.com/PostView.nhn?blogId=hankboy&logNo=221200885234&categoryNo=14&parentCategoryNo=0&viewDate=&currentPage=1&postListTopCurrentPage=1&from=postView)
[karabiner.json Reference Manual](https://pqrs.org/osx/karabiner/json.html#complex_modifications-manipulator-priority)