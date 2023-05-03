아래에 Java의 switch-case 문에 관한 문제 4개를 제시하였습니다. 각 문제는 break의 유무와 default의 생략에 초점을 맞추고 있습니다.

1. 문제: 다음 코드에서 'day' 변수의 값이 3일 때 출력되는 내용은 무엇인가요? (break가 있는 경우)
```java
int day = 3;
switch (day) {
    case 1:
        System.out.println("Monday");
        break;
    case 2:
        System.out.println("Tuesday");
        break;
    case 3:
        System.out.println("Wednesday");
        break;
    case 4:
        System.out.println("Thursday");
        break;
    default:
        System.out.println("Invalid day");
}
```

2. 문제: 다음 코드에서 'day' 변수의 값이 3일 때 출력되는 내용은 무엇인가요? (break가 없는 경우)
```java
int day = 3;
switch (day) {
    case 1:
        System.out.println("Monday");
    case 2:
        System.out.println("Tuesday");
    case 3:
        System.out.println("Wednesday");
    case 4:
        System.out.println("Thursday");
    default:
        System.out.println("Invalid day");
}
```

3. 문제: 다음 코드에서 'day' 변수의 값이 5일 때 출력되는 내용은 무엇인가요? (default가 생략된 경우)
```java
int day = 5;
switch (day) {
    case 1:
        System.out.println("Monday");
        break;
    case 2:
        System.out.println("Tuesday");
        break;
    case 3:
        System.out.println("Wednesday");
        break;
    case 4:
        System.out.println("Thursday");
        break;
}
```

4. 문제: 다음 코드에서 'day' 변수의 값이 5일 때 출력되는 내용은 무엇인가요? (break가 없고 default가 생략된 경우)
```java
int day = 5;
switch (day) {
    case 1:
        System.out.println("Monday");
    case 2:
        System.out.println("Tuesday");
    case 3:
        System.out.println("Wednesday");
    case 4:
        System.out.println("Thursday");
}
```

위 문제들은 Java의 switch-case 문에 대한 이해를 돕기 위해 작성되었습니다. break 문의 유무와 default 절의 생략에 따른 실행 결과를 확인하세요.
