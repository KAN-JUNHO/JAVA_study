# JAVA_study

1주차

JVM이란 무엇인가
Java Virtual Machine 의 줄임말 이며 Java Byte Code를 OS에 맞게 해석 해주는 역할을 합니다.
Java compiler는 .java 파일을 .class 라는 Java byte code로 변환 시켜 줍니다. 

JVM 구조
1.Class Loader
  RunTime 시점에 클래스를 로딩하게 해주며 클래스의 인스턴스를 생성하면 클래스 로더를 통해 메모리에 로드하게 됩니다.
2.Runtime Data Areas
  JVM이 프로그램을 수행하기 위해 OS로 부터 별도로 할당 받은 메모리 공간을 말하며, Runtime Data Areas는 크게 5가지 영역으로 나눌 수 있습니다.
3.Execution Engine
  Load된 Class의 ByteCode를 실행하는 Runtime Module이 바로 Execution Engine입니다. Class Loader를 통해 JVM 내의 Runtime Data Areas 에 배치된 바이트 코드는 Executin Engine에 의해    실행되며, 실행 엔진은 자바 바이트 코드를 명령어 단위로 읽어서 실행합니다.

실행하는 방법
javac 클래스명.java

https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fs4PPN%2FbtqMM4pDZw3%2FGPoU2fUXPZAw6xcasL4Av1%2Fimg.png
