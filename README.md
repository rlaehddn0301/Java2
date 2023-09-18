## Java 연습 문제

1. 자바에서 클래스를 선언할 때 사용되는 자바의 키워드는?


```java
public class MyClass {
    // 클래스 멤버 변수, 메서드 등을 정의할 수 있다.
}
```


2. 다음은 10과 20을 더해 합을 출력하려고 작성한 자바프로그램이지만 오류가 있다.
```java
package week0301;

public class SampleProgram {

    public static void main(String[] args) {
        int i;
        int j;
        i = 10;
        j = 20;

        System.out.println(i + j);
    }
}
```

    1) 오류를 찾아내어 고쳐라
        - 이 코드에서 특별한 오류는 없다

    2) 이 자바 클래스를 저장하는 소스 파일 이름은?
        - 주어진 코드에서 클래스의 이름은 "SampleProgram" 이다. 자바에서 클래스와 파일 이름을 맞추는 관례이기도 하다.

    3) 명령창에서 이 프로그램을 컴파일하는 명령은?
        - javac SampleProgram.java
    4) 명령창에서 이 프로그램을 실행하는 명령은?
        - java week0301.SampleProgram


3. 다음 중 식별자 사용이 잘못된 경우를 모두 골라라
```int _i;
   int %j;     
   char 안녕;
   double 1var;
   char student_ID;
   final int abcdefghijklmnopqrstuvwxyz;
```
```
    - int %j; : 밑줄 또는 숫자로 시작해야한다.
    - double 1var; : 식별자는 숫자로 시작할 수 없다.
```

4. 다음 각 항목이 나타내는 변수를 선언해라.
``` 1) int형 변수 height
    2) 0.25로 초기화된 double형 변수 size
    3) heght 변수의 값과 size 변수의 값을 더한 값으로 초기화된 double형 변수 total
    4) 문자 'a'로 초기화된 char형 변수 c
    5) 자신의 이름으로 초기화된 문자열 변수 name
```

``` 1) int height;
    2) double size = 0.25;
    3) double total = height + size;
    4) char c = 'a';
    5) String name = "김동우";
```

5. 다음 수식의 결과 값과 타입은?
``` 1) 67+12.8
    2) 10/3
    3) 10.0/3
    4) 10==9
```

``` 1) 결과 값: 79.8 (정수 67과 부동 소수점 12.8을 더함)
       타입: double (정수와 부동 소수점 연산 결과는 부동 소수점으로 자동 형변환된다.)

    2) 결과 값: 3 (정수 나누기 연산은 정수 결과를 반환하므로 나머지는 버려진다.)
       타입: int

    3) 결과 값: 3.3333333333333335 (부동 소수점 나누기 연산)
       타입: double

    4) 결과 값: false (10과 9는 같지 않으므로 false)
       타입: boolean (논리 비교 연산 결과는 boolean 타입이다.)
```
