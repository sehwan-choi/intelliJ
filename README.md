# 인텔리제이 단축기 모음

alt + insert = generate(생성자, 게터, 세터) <br>
alt + insert = 파일, 패키지 만들기 <br>
ctrl + alt + m = 메소드생성, 메소드추출 <br>
ctrl + p = 생성자의 데이터 확인할수있음 <br>
ctrl + alt + v = 앞에 클래스명과 이름을 만들어줌 <br>
ctrl + alt + n = return 합쳐줌 <br>
ctrl + shift + enter = 문자 완성 + ; <br>
ctrl + p = 무슨 인자가 필요한지 보여줌 <br>
ctrl + shift + t = 테스트 클래스 생성 <br>
ctrl + e = 히스토리 <br>
shift + f10 = 마지막 실행한것 다시 실행 <br>
ctrl + alt + -> = 앞으로 가기 <br>
ctrl + alt + <- = 뒤로 가기 <br>
ctrl + / = 주석처리 <br>
ctrl + d = 블록 복사 <br>
ctrl + n = 모든 클래스, 인터페이스등 찾을수 있음 <br>
ctrl + f12 = 해당 클래스의 메소드를 모두 볼수있음 <br>
ctrl + alt + b = interface에서 사용시 해당 구현체를 보여줌 <br>
shift + Ctrl + F = 경로에서 문자열 찾기(왼쪽 Project에서 어디서 찾을지 선택해야함 <br>
ctrl + alt = 블럭지정된 곳을 함수로 뺀다 <br>
ctrl + alt + p = 메소드에서 현재 위치해있는 곳을 인자로 뺄수있다 <br>
shift + f6 = 클래스, 메소드 이름변경 <br>


# 인텔리제이 환경설정
File - Setting - gradle 검색후 <br>
Build and run suing : intelliJ IDEA <br>
Run test using : intelliJ IDEA <br>
로 변경 <br>


# Lombok 설치
file - setting - plugin 검색후 - lombok설치 <br>
				 Build, Execution, Deployment 하위 Compiler 하위 Annotation Processors에서  <br>
				 Enable annotation processing 체크 <br>



# html수정후 재시작 하지 않고 소스 반영하도록 설정
build.gradle 에  <br>
	implementation 'org.springframework.boot:spring-boot-devtools' <br>
추가후 서버 재기동 하면 restartedMain으로 나온다면 설정완료 <br>
html 수정후 Build -> recompile 하면 된다 <br>
