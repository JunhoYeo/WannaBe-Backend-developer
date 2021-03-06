## CPU
CPU(Control Processing Unit) : 소프트웨어 명령의 실행이 이루어지는 컴퓨터의 부분

- 기계어로 쓰여진 컴퓨터 프로그램의 명령어를 해석하여 실행

- 프로그램에 따라 정보를 입력받고, 기억, 연산, 외부로 출력

- 타 컴퓨터 부품과 정보를 교환하면서 컴퓨터 전체의 동작을 제어

### CPU 구성요소

- ALU(Arithmetic Logic Unit, 산술논리연산장치)<br>
산술연산, 논리연산을 수행하는 디지털 회로<br>
컴퓨터 중앙처리장치의 기본 설계 블럭

- 레지스터<br>
컴퓨터의 프로세서 내에서 자료를 보관하는 아주 빠른 기억 장치<br>
현재 계산을 수행중인 값을 저장하는데 사용

- 제어부

- 내부 버스

### CPU 동작방식
프로그램이 실행되면 실행 프로그램이 메모리에 적재되고 메모장의 내용을 CPU에서 가져와 레지스터에 저장한 후, 제어부을 통해 ALU에 전달<br>
<b>로드-스토어 설계</b> : 메인 메모리에서 레지스터로 데이터를 옮겨와 데이터를 처리한 후 그 내용을 다시 레지스터에서 메인 메모리로 저장하는 프로세서의 설계방식

## 어셈블리

## 스택 구현 방식
스택(Stack) : LIFO(Last In First Out) 방식의 자료구조

- Full Stack : ESP가 마지막으로 Push된 데이터를 가리킴
- Empty Stack : ESP가 다음 데이터가 들어갈 곳을 가리킴
- Ascending Stack : 낮은 메모리주소 -> 높은 메모리주소
- Decending Stack : 높은 메모리주소 -> 낮은 메모리주소

인텔 아키텍처의 스택 : Full Decending Stack

## 스택 프레임
스택 프레임(Stack Frame) : 호출된 함수가 실행되는 동안 필요한 지역변수나 호출한 함수의 실행에 필요한 정보가 손실되지 않도록 스택에 저장할 때 사용하는 구조

## 함수 호출 규약
함수 호출 규약(Calling Convention)

- 프로그램이 함수에게 파라미터를 전달하고 결과값을 다시 받는 일련의 표준화된 방법

- 함수 호출을 위해서 밟는 절차를 정해둔 것
