![](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbE4sdX%2FbtrK9x0qhsH%2Fre3CO1Ftbix3wyxmKNIRxK%2Fimg.png)
https://www.techbeamers.com/introduction-jvm-jdk-jre/

<br>

## **JVM(Java Virtual Machine)**

> 자바 바이트 코드(.class 파일)을 OS에 특화된 코드로 변환해 주는 자바 가상 머신

-   특정 플랫폼에 종속적이다
-   즉 리눅스의 JVM과 윈도우즈의 JVM은 다르다.
-   단, 컴파일된 바이너리 코드는 어떤 JVM에서도 동작시킬 수 있다.

<br>

## **JRE(Java runtime Environment) : JVM + library**

-   JVM이 자바 프로그램을 동작시킬 때 필요한 라이브러리 파일들과 기타 파일들을 가지고 있다.
-   JRE는 JVM의 실행환경을 구현했다고 할 수 있다.

<br>

## **JDK(Java Development Kit) : JRE + 개발 툴**

-   JDK는 JRE + 개발을 위해 필요한 도구(javac, java등)들을 포함한다.