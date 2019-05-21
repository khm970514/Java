# 자바(JAVA Programming Language)

## 자바란?
- 썬 마이크로시스템즈에서 개발하여 발표한 **객체지향 프로그래밍 언어**이다.
- **운영체제에 독립적**이기때문에 운영체제의 종류에 관계없이 프로그램을 변경하지 않고 실행이 가능하다.
- 기존의 다른프로그래밍 언어인 C++의 장점을 채택하고 불필요한부분은 과감히 삭제하였다.
- JAVA API를 기본적으로 제공하기때문에 이 클래스만 사용하여도 강력한 프로그램을 작성할 수 있다.

## 자바언어의 특징
- **운영체제에 독립적이다.**  
    일종의 에뮬레이터인 자바가상머신(JVM)을 통하여 프로그램을 운영체제나 하드웨어가 아닌 JVM과 통신한다.  
    JVM은 자바응용프로그램으로부터 전달받은 명령을 운영체제가 이해할 수 있도록 변환하여 전달한다.  
    그렇기때문에 자바로 작성된 프로그램은 OS와 하드웨어에 관계없이 실행가능하다.  
    >Write once, run any where
  
- **객체지향 언어이다.**  
    객체지향 프로그래밍 언어 (object-oriented pro-gramming language) 중의 하나로  
    상속, 캡슐화, 다형성이 적용된다.  

- **비교적 배우기 쉽다.**  
    기본구문은 C++에서, 객체지향구문은 스몰톡(small talk)에서 가져왔다.  
  
- **자동메모리 관리**  
    가비지 컬렉터(garbage collector)가 자동적으로 메모리를 관리해준다.  

- **네트워크와 분산처리를 지원한다**  
    네트워크 프로그래밍 라이브러리 (JAVA API)를 통해 비교적 짧은 시간에 관련프로그램을 쉽게 개발할 수 있다.

## JVM
    JVM은 Java virtual machine을 줄인것으로 자바를 실행하기 위한 가상 컴퓨터이다.  
    자바로 작성된 어플리케이션은 JVM에서만 실행되기 때문에 반드시 JVM이 필요하다.
| Java 애플리케이션 |                   |
|:-----------------:|:-----------------:|
|        JVM        | 일반 애플리케이션 |
|         OS        |         OS        |
|       컴퓨터      |       컴퓨터      |
    일반애플리케이션에 비해 JVM을 한번 더 거쳐야 하기 때문에 속도가 느리다는 단점이 있다.  
    
    