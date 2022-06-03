># **top**

시스템 프로세스/메모리 사용 현황을 실시간으로 출력한다.

|옵션|의미|
|---|---|
|-n|지정한 숫자만큼 화면 출력을 갱신|
|-u|지정한 사용자의 프로세스를 모니터링|
|-b|출력결과를 파일이나 다른 프로그램으로 전달|
|-p|지정한 PID 프로세스를 모니터링|
|-d|화면갱신주기를 초 단위로 설정|

![top](https://user-images.githubusercontent.com/106798938/171818387-183e8018-f2bc-4d4d-bb6b-0ae5e005c2de.png)

---

># **ps**

현재 시스템에서 실행 중인 프로세스에 관한 정보를 출력하여 사용자에게 정보를 제공하는 명령어

+ 기본 프로세스 출력

|옵션|의미|
|---|---|
|a|터미널과 연관된 프로세스만 출력|
|x|터미널과 연관되지 않는 프로세스만 출력|
|-A|모든 프로세스 출력 (-e와 동일)|
|-e|모든 프로세스 출력|
|-a|세션 리더와 커미널과 연관되지 않은 프로세스를 제외하고 모든 프로세스를 출력|

+ 지정한 프로세스 출력

|옵션|의미|
|---|---| 
|p|지정한 PID 목록의 정보만 출력|
|-C|지정한 프로세스의 실행 파일 이름의 정보만 출력|
|-u|특정 사용자의 프로세스 정보를 출력|

+ 프로세스 장식

|옵션|의미|
|---|---|
|f|프로세스 계층을 텍스트 형식의 트리구조를 보여줌.|
|-f|전체 포맷으로 출력|

---

># **jobs**

jobs 명령어는 현재 돌아가고 있는 백그라운드 프로세스 리스트를 모두 출력해준다.

백그라운드 프로세스는 스택처럼 쌓인다.

|옵션|의미|
|---|---|
|-l|프로세스 그룹 ID를 state 필드 앞에 출력|
|-n|프로세스 그룹 중에 대표 프로세스 ID를 출력|
|-p|각 프로세스 ID에 대해 한 행씩 출력|

---

># **kill**

kill 명령어는 프로세스를 강제로 종료시킨다.

좀비 프로세스나, 응답 없음, 비정상적으로 동작하는 프로세스들의 실행을 끝내게 해준다.

|옵션|의미|
|---|---|
|-signal, -s signal|지정한 시그널을 보냄|
|-l|사용 가능한 시그널의 목록을 출력|

![kill](https://user-images.githubusercontent.com/106798938/171818338-bbaf0d09-ffe0-45e0-a4fe-39805b74adbb.png)

---

># **q & @**

매크로 q는 명령모드에서 q[매크로 이름]으로 실행이 가능하다. 

커맨드 모드 (esc 누른 상태) 에서.
1) 'q' 를 누르고 a~z 사이 문자로 매크로 recording 시작
2) 커맨드 모드로 돌아와서 'q'를 누르면 매크로 recording 끝
3) 매크로를 사용하려면 커맨드 모드에서 @+a~z 를 입력하면 됨


---
