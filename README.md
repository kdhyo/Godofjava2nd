# godofjava2nd
자바의신 2를 읽고 정리 및 문제 정리

# Chapter 01 프로그래밍이란 무엇인가?
### 1. 클래스가 뭔가요?
```
클래스란 각각의 객체를 만들 수 있는 도면과도 같으며,  
하나의 객체를 나타낼 수 있는 자바의 가장 작은 단위를 말한다.  
클래스 내에는 상태와 행동으로 이루어져 있으며,  
상태는 클래스 변수와 같은 값들을 의미하며,
행동은 메소드를 의미한다.
```

### 2. 메소드가 뭔가요?
```
클래스 내에서 하나의 행동을 하기 위해 정의된 것을 메소드라고 부른다.
```

### 3. 메소드의 매개 변수는 어디에 적어주나요?
```
메소드 명 오른쪽에 위치한 소괄호 내에 적어준다.
두 개 이상이 있을 경우 콤마(,)로 구분해준다.
```

### 4. 메소드 이름 앞에 꼭 적어 줘야 하는 건 뭐죠?
```
리턴 타입을 명시해 주어야 한다.
```

### 5. 클래스가 갖고 있어야 한다고 한 두 가지가 뭐죠?
```
상태(state) 와 행동(behavior)
```

### 6. 메소드에서 결과를 돌려주려면 어떤 예약어를 사용해야 하나요?
```
return 을 사용한다.
```

# Chapter 02 Hello God Of Java
### 1. main() 메소드의 메소드 이름 앞에는 어떤 예약어들이 들어 가나요?
```
접근자(public), static, 리턴 값(void)
```

### 2. main() 메소드의 매개 변수에는 어떤 값이 들어가나요?
```
String[] 이 들어간다.
```

### 3. 만약 여러분들이 만든 클래스에 main() 메소드가 없다면 java 명령어로 그 클래스를 수행할 수 있나요?
```
수행할 수 없다.
```

### 4. System.out.println() 메소드는 어떤 용도로 사용하나요?
```
콘솔창에 해당 문자열을 보여주고, 마지막에는 줄바꿈을 한다.
```

### 5. System.out.print() 메소드는 System.out.println() 메소드와 어떤 차이가 있나요?
```
print는 입력받은 문자열을 출력만 하는 반면,
println은 문자열을 출력 후 줄바꿈을 한다.
```

### 6. // 는 무엇을 하는 데 사용하는 기호인가요?
```
한 줄 주석에 사용 된다.
```

### 7. /* 로 시작하고,/ 로 끝나는 사이에 있는 소스들은 어떻게 되나요?
```
블록 주석으로서 사이에 있는 소스들은 실행될 때 무시 된다.
```

### 8. 메소드를 선언할 때 반드시 꼭 있어야 하는 세 가지는 무엇인가요?
```
메소드 명, 리턴 타입, 메소드 내용은 필수로 있어야 한다.
```

# Chapter 03 자바를 제대로 알려면 객체가 무엇인지를 알아야 해요.

### 1. 클래스와 객체의 차이점을 말해 주세요.
```
클래스는 객체를 생성하기 위해 필요한 도면이며,
객체는 클래스를 통해 생성(인스턴스화)된 것을 의미한다.
클래스 내에 메소드나 변수들을 사용하기 위해서는 객체를 만든 후에 가능하다.
```

### 2. 객체를 생성하기 위해서 꼭 사용해야 하는 예약어는 뭐라고 했죠?
```
new 키워드를 사용한다.
```

### 3. 객체를 생성하기 위해서 사용하는 메소드 같이 생긴 클래스 이름에 소괄호가 있는 것을 뭐라고 했죠?
```
생성자(Constructor) 메소드를 사용한다.
```

### 4. 객체의 메소드를 사용하려면 어떤 기호를 객체 이름과 메소드 이름 사이에 넣어주어야 하나요?
```
객체이름.메소드이름() : 점(.)을 사이에 넣어준다.
```

### 5. 여러분들이 메소드를 사용하기 위해서는 어떤 것을 만들어야 하나요?
```
객체를 만들어야 한다.
```

### 6. 5번 문제에서 만들어야 하는 것은 어떤 예약어를 사용하고, 클래스의 무엇을 사용해야 하나요?
```
new 예약어를 사용하여, 클래스의 생성자 메소드를 사용하여 객체를 만든다.
```

# Chapter 04 정보를 어디에 넣고 싶은데

### 01. 네 가지 종류의 변수는 어떻게 구분할 수 있나요?
```
클래스 변수, 인스턴스 변수, 매개 변수, 지역 변수가 존재하며,
선언된 위치와 static 여부에 따라서 구분할 수 있다.
```

### 02. 변수의 이름을 지을 때 대문자로 시작해도 되나요?
```
시작을 해도 오류는 나지 않지만,
변수의 이름은 소문자로 시작하도록 규칙을 정했기 때문에 소문자로 시작해야 한다.
두 번째 단어부터는 대문자로 시작하는 게 일반 명명규칙이다.
```

### 03. 자료형에는 기본 자료형과 어떤 자료형이 있나요?
```
"기본 자료형"과 "참조 자료형"이 존재한다.
```

### 04. 기본 자료형에는 몇 가지가 있나요?
```
8가지가 존재하며,
byte, short, int, long, float, double, boolean, char가 존재한다.
```

### 05. 기본 자료형 중 정수형에는 어떤 것들이 있나요?
```
byte, short, int, long, char 이렇게 5 가지가 존재한다.
```

### 06. byte는 몇 비트(bit)로 되어 있나요?
```
8bit으로 되어 있다.
```

### 07. byte는 왜 만들었을까요?
```
적은 공간에 보다 많은 값들을 저장하기 위한,
저장공간의 효율성을 높이기 위해서 사용 된다.
```

### 08. int와 long 중 어떤 타입이 더 큰 숫자를 처리할 수 있나요?
```
long이 더 크다.
```

### 09. 소수점을 처리하는 타입은 어떤 것이 있나요?
```
float, double 2 가지가 존재한다.
```

### 10. char는 정수형인가요?
```
네
```

### 11. a라는 것을 char로 정의할 때 어떤 기호로 감싸주어야 하나요?
```
홑따옴표(')를 사용한다.
```

### 12. true와 false 두 개의 값만을 가지는 타입은 어떤 것인가요?
```
boolean
```

# Chapter 05 계산을 하고 싶어요

### 01. 값을 할당할 때 사용하는 연산자의 기호는 무엇인가요?
```
할당 연산자는 '=' 이며,
좌측에는 할당 받을 변수, 우측에는 할당할 값을 입력한다.
```

### 02. 기본적인 덧셈, 뺄셈, 곱셈, 나눗셈, 나머지를 계산할 때 사용하는 연산자의 기호는 순서대로 각각 무엇인가요?
```
+ - / %
```

### 03. += 는 무엇을 할 때 사용하는 연산자 인가요? 
```
오른쪽에 있는 값을 왼쪽 변수에 더해서 왼쪽 변수에 할당 해준다.
```

### 04. 연산의 순서를 모르거나 확실히 하고 싶을 때에는 어떤 기호를 사용해야 하나요?
```
연산이 많아 연산자의 우선순위가 혼동될 경우 소괄호()로 묶어서 계산의 가독성을 높여준다.
```

### 05. ==와 !=의 차이는 무엇인가요?
```
==는 "같다" 라는 의미이며, !=는 "다르다"라는 의미이다.
결과는 둘 다 boolean 타입을 리턴한다.
```

### 06. <와 <=의 차이는 무엇인가요?
```
<는 왼쪽이 오른쪽보다 작은 경우, <=는 왼쪽이 오른쪽보다 작거나 같은 경우를 말한다.
```

### 07. ! 연산자는 어떤 타입에 사용 할 수 있나요?
```
boolean 타입에서만 사용이 가능하다.
해당 결과를 반대로 변환시켜준다.
ex) true -> false / false -> true
```

### 08. ? : 로 표시하는 삼항 연산자의 ?와 : 뒤에 명시해 주는 값은 무엇을 의미 하나요?
```
결과가 true인 경우 ? 뒤에 있는 값을 사용하고, false인 경우에는 : 뒤에 있는 값을 사용한다.
```

### 09. 자바는 형변환을 한다고 했는데, short의 값을 long에 할당할 때에는 어떤 것을 해 주어야 하나요?
```
작은 값에서 큰 값으로 형변환 할 시 아무것도 안 해주어도 된다.
```

### 10. 반대로 long값을 short에 할당할 때에는 어떤 것을 해 주어야 하나요?
```
큰 값에서  작은 값으로 할당할 시에는 값 앞에 (할당타입)을 명시해 주어야 한다.
```

### 11. 위의 두 문제에서 어떤 경우가 기존 값이 사라지고, 엉뚱한 값으로 바뀔 수 있나요?
```
long에서 short으로 형변환하는 것처럼
범위가 큰 타입에서 작은 타입으로 변환할 경우 값이 달라질 확률이 높다.
```

# Chapter 06 제가 조건을 좀 따져요

### 01. if 문장의 소괄호 안에는 어떤 타입의 결과가 제공되어야 하나요?
```
boolean 타입만 가능하다.
```

### 02. if 조건에 맞지 않는 모든 경우를 처리할 때 사용하는 예약어는 뭔가요?
```
else
```

### 03. switch를 사용할 수 있는 기본 자료형의 타입에는 어떤 것들이 있나요?
```
long을 제외한 정수와  Enum을 사용할 수 있다.
JDK 7부터는 String도 가능하다.
```

### 04. switch블록 안에서 비교 대상값 앞에 사용하는 예약어는 무엇인가요?
```
case
```

### 05. switch 조건을 빠져나가도록 하는 예약어는 무엇인가요?
```
break
```

### 06. switch 조건들에 맞지 않을 때 기본 처리를 하기 위한 예약어는 무엇인가요?
```
default
```

### 07. while 문의 소괄호 안에는 어떤 형태의 결과가 제공되어야 하나요?
```
boolean 타입만 가능하다.
```

### 08. while 문을 무조건 한번은 실행하게 하려면 어떻게 해야 하나요?
```
do-while문을 사용한다.
```

### 09. while문을 마음대로 빠져나가게 하려면 어떤 예약어를 사용하면 되나요?
```
break
```

### 10. while문의 중간에 while문의 소괄호 점검 구문으로 건너뛰도록 할 때 사용하는 예약어는 무엇인가요?
```
continue
```
### 11. for루프의 소괄호안의 가장 첫 구문(첫 세미 콜론 앞의 문장)은 for루프가 수행되는 동안 몇 번 수행되나요?
```
변수를 초기화하는 것으로서 한 번만 수행된다.
```

### 12. for루프의 소괄호 안의 중간에 있는 구문은 어떤 타입의 결과가 제공되어야 하나요?
```
종료조건이 들어가는 공간으로서 boolean이 들어간다.
```

### 13. for루프의 소괄호 안의 마지막에 있는 구문에서는 어떤 작업을 수행하나요?
```
중괄호 내 작업이 끝난 후 초기화된 변수의 값을 증가 혹은 감소 시키는 반복적인 작업을 수행한다.
```

# Chapter 07 여러 데이터를 하나에 넣을 수는 없을까요?

### 01. 배열을 선언할 때 어떤 기호를 변수명의 앞이나 뒤에 사용해야 하나요?
```
대괄호 []
```

### 02. 배열의 첫번째 위치는 0인가요? 1인가요?
```
인덱스는 0부터 시작한다.
```

### 03. 배열을 선언할 때 boolean 배열의 크기만 지정했다면 boolean 배열의 [0] 위치에 있는 값은 무엇인가요? 
```
숫자의 초기값은 0, boolean의 초기값은 false
```

### 04. ArrayIndexOutOfBoundsException 이라는 것은 언제 발생하나요?
```
배열의 크기를 벗어난 위치를 참조할 경우
```

### 05. 중괄호를 이용하여 배열을 초기화 할 때 중괄호 끝에 반드시 어떤 것을 입력해 주어야 하나요?
```
; (세미클론)
```

### 06. 2차원 배열을 정의할 때에는 대괄호를 몇 개 지정해야 하나요?
```
2개
```

### 07. 배열을 쉽게 처리해주는 for 문의 문법은 어떻게 되나요?
```
for (String car : cars)
```

### 08. 자바 프로그램에 데이터를 전달해 주려면 클래스 이름 뒤에 어떻게 구분하여 나열하면 되나요? 
```
넘기고 싶은 데이터를 스페이스바 하나씩 띄어서 나열한다.
ex ) java ArrayTest a b c
```

### 09. 자바 프로그램이 시작할 때 전달 받는 내용은 어떤 타입의 배열인가요?
```
String 1차원 배열
```

# Chapter 08 참조 자료형에 대해서 더 자세히 알아봅시다

### 01. 생성자는 반드시 만들어야 하나요?
```
안 만들어도 기본 생성자가 생기지만, 만드는 습관을 가지는 게 좋다.
```

### 02. 만약 매개변수가 있는 생성자를 만들고, 매개변수가 없는 기본 생성자를 호출하면 어떻게 될까요?
```
컴파일 에러가 발생하며, 기본 생성자를 호출하고 싶다면 기본 생성자도 만들어 주어야 한다.
```

### 03. 생성자의 개수는 제한이 있나요?
```
없다.
```

### 04. 인스턴스의 변수와 매개변수나 메소드 내에서 생성한 변수와 구분하기 위해서 사용하는 키워드는 무엇인가요?
```
this
```

### 05. 메소드 선언시 리턴 타입으로 지정한 데이터를 넘겨줄 때 사용하는 키워드는 무엇인가요?
```
return
```

### 06. 메소드 선언시 아무 데이터도 리턴 타입으로 넘겨주지 않겠다는 것을 지정하는 키워드는 무엇인가요?
```
void
```

### 07. 메소드 선언에 static 이 있는 것과 없는 것의 차이는 무엇인가요? 
```
static이 있을 경우 객체(인스턴스)를 만들지 않고도 사용할 수 있고, 반대로 없는 경우는 생성자를 통해 객체(인스턴스)를 생성 후에 사용할 수 있다.
```

### 08. 필자가 엄청나게 중요하다고 한 것 중 메소드의 이름은 같으나 매개변수를 다르게 하는 것의 명칭은 무엇인가요?
```
Overloading
```

### 09. 기본 자료형을 매개변수로 넘겨 줄 때 Pass by value인가요? 아니면 Pass by reference인가요? 
```
Pass by value
```

### 10. 참조 자료형을 매개변수로 넘겨 줄 때 Pass by value인가요? 아니면 Pass by reference인가요?
```
Pass by reference
```

### 11. 매개변수의 수가 가변적일 때 메소드 선언시 타입과 변수 이름 사이에 어떤 것을 적어줘야 하나요?
```
변수타입... 변수명
```

# Chapter 09 자바를 배우면 패키지와 접근 제어자는 꼭 알아야 해요

### 01. 패키지를 선언할 때 사용하는 예약어는 무엇인가요?
```
package
```

### 02. 패키지를 선언할 때 사용하는 예약어는 무엇인가요?
```
맨 위 첫 번째 줄
```

### 03. 패키지를 선언할 때 가장 상위 패키지의 이름으로 절대 사용하면 안되는 단어는 무엇인가요? 
```
패키지의 이름은 java로 시작하면 안 된다.
```

### 04. 패키지 이름에 예약어가 포함되어도 되나요?
```
안 된다.
```

### 05. import는 클래스 내에 선언해도 되나요?
```
안 된다.
import는 클래스 선언 위에 명시 해야 한다.
```

### 06. 같은 패키지에 있는 클래스를 사용할 때 import를 해야 하나요? 
```
같은 패키지 내 클래스와 java.lang 패키지에 있는 클래스는 별도로 import하지 않아도 된다.
```

### 07. 특정 패키지에 있는 클래스들을 모두 import할 때 사용하는 기호는 무엇인가요? 
```
* 기호를 사용한다.
ex) import java.util.*
하지만, 이렇게 할 경우 import 되는 클래스 이름들이 중복될 수 있으므로,
되도록이면 명시적으로 지정하는 것이 좋다.
```

### 08. 클래스에 선언되어 있는 static한 메소드나 변수를 import하려면 어떻게 선언해야 하나요?
```
import static
```

### 09. 접근 제어자 중 가장 접근 권한이 넓은 (어떤 클래스에서도 접근할 수 있는) 것은 무엇인가요?
```
public
```

### 10. 접근 제어자 중 가장 접근 권한이 좁은 (다른 클래스에서는 접근할 수 없는) 것은 무엇인가요?
```
private
```

### 11. 접근 제어자 중 같은 패키지와 상속관계에 있는 클래스만 접근할 수 있도록 제한하는 것은 무엇인가요?
```
protected
```

### 12. Calculate.java라는 자바 소스가 있을 경우, 그 소스 내에는 Calculate라는 클래스외에는 ( )으로 선언된 클래스가 있으면 안된다. 여기서 괄호 안에 들어가야 하는 것은 무엇인가요?
```
public 으로 선언 된 클래스는 하나만 존재할 수 있다.
```

# Chapter 10 자바는 상속이라는 것이 있어요

### 01. 상속을 받는 클래스의 선언문에 사용하는 예약어는 무엇인가요?
```
extends
```

### 02. 상속을 받은 클래스의 생성자를 수행하면 부모의 생성자도 자동으로 수행된다. 
```
상속 받은 클래스의 생성자를 호출하면, 부모 클래스의 "기본 생성자"가 호출 된다.
```

### 03. 부모 클래스의 생성자를 자식 클래스에서 직접 선택하려고 할 때 사용하는 예약어는 무엇인가요?
```
super()
```

### 04. 메소드 Overriding과 Overloading을 정확하게 설명해 보세요.
```
Overriding 은 상속받은 부모 클래스의 메소드를 선언 구문은 동일하게 재정의하는 것이고, Overloading 은 같은 메소드 명으로 매개변수를 다르게 정의하는 것을 말한다.
```

### 05. A가 부모, B가 자식 클래스라면 A a=new B(); 의 형태로 객체 생성이 가능한가요? 
```
부모 변수 명 = new 자식(); 은 가능하다.
자식 변수 명 = new 부모(); 은 불가능하다.
이유는 부모는 자식이 갖고 있는 모든 것(변수, 메소드 등)을 갖지 못하기 때문에 불가능하다.
```

### 06. 명시적으로 형변환을 하기 전에 타입을 확인하려면 어떤 예약어를 사용해야 하나요?
```
instanceof
```

### 07. 위의 문제에서 사용한 예약어의 좌측에는 어떤 값이, 우측에는 어떤 값이 들어가나요? 
```
변수 이름 instanceof 클래스 이름
```

### 08. instanceof 예약어의 수행 결과는 어떤 타입으로 제공되나요?
```
boolean
```

### 09. Polymorphism이라는 것은 뭔가요?
```
Polymorphism(폴리몰피즘)은 다형성을 의미한다.
부모 클래스의 타입으로 변수를 선언하고, 자식 클래스의 생성자를 사용할 경우  
overriding된 메소드를 호출하면 자식 클래스에 선언된 메소드가 호출되고,  
부모 클래스의 메소드도 공유가 가능하다는 것을 의미한다.
------
형 변환을 하더라도 실제 호출되는 것은 원래 객체에 있는 메소드가 호출된다라는 다형성을 의미한다.
```

# Chapter 11 매번 만들기 귀찮은데 누가 만들어 놓은 거 쓸 수 없나요?

### 01. API 문서를 자동으로 생성하는 명령어는 무엇인가요?
```
javadoc
```

### 02. API의 왼쪽 상단 창에는 어떤 내용이 제공 되나요?
```
패키지 목록
```

### 03. API의 왼쪽 하단에는 어떤 내용이 제공 되나요?
```
클래스 목록
제공되는 상세 내용은 다음과 같다.
- 인터페이스 목록 (기울임 글자체인 italic 체로 표시된다)
- 클래스 목록
- Enum 클래스 목록
- 예외 클래스 목록
- 에러(Error) 클래스 목록
- 어노테이션 타입 목록(Annotation Types)
```

### 04. API 우측화면에는 보통 어떤 내용이 제공되나요?
```
클래스 목록에서 선택한 클래스의 상세 설명
```

### 05. Deprecated라는 것의 의미는 무엇인가요?
```
더 이상 사용하지 않는다.
컴파일 에러는 발생하지 않지만, 사용하는 것은 절대 권장하지 않는다.
  
자바의 호환성을 지키기 위해서  
버전업을 했다고 기존 버전에서 최신 버전으로 올릴 때 에러가 나는 것을 발생하기 위해  
Deprecated 어노테이션을 이용해 사용하지 않는다고 알리며,  
대체할 메소드를 알려주는 방식으로 사용된다.
```

# Chapter 12 모든 클래스의 부모 클래스는 Object 에요.

### 01. 모든 클래스의 최상위 부모 클래스인 Object 클래스는 어떤 패키지에 선언되어 있나요 ?
```
java.lang 패키지 안에 구현되어 있다.
```

### 02. 클래스가 어떻게 선언되어 있는지 확인할 수 있는 명령어(실행파일)의 이름은 무엇인가요?
```
javap
```

### 03. Object 클래스에 선언되어 있는 모든 메소드를 Overriding해야 하나요? 
```
필요한 메소드만 Overriding 해서 사용한다.
```

### 04. Object 클래스의 clone() 메소드의 용도는 무엇인가요?
```
객체를 복제하는 용도
```

### 05. System.out.println() 메소드를 사용하여 클래스를 출력했을 때 "최종적으로" 호출되는 Object 클래스에 있는 메소드는 무엇인가요?
```
toString()
```

### 06. 객체의 주소를 비교하는 것이 아닌, 값을 비교하려면 Object 클래스에 선언되어 있는 어떤 메소드를 overrding해야 하나요?
```
equals()
구현한 클래스를 정확하게 비교하려면 equals() 메소드를 오버라이딩해서 사용해야 한다.
```

### 07. Object 클래스에 선언되어 있는 hashCode()라는 메소드는 어떤 타입의 값을 리턴 하나요?
```
int
```

# Chapter 13 인터페이스와 추상클래스, enum

### 01. 인터페이스에 선언되어 있는 메소드는 body(몸통)이 있어도 되나요?
```
메소드만 선언할 수 있다.
```

### 02. 인터페이스를 구현하는 클래스의 선언시 사용하는 예약어는 무엇인가요? 
```
인터페이스는 class 대신 interface 를 사용하고,
인터페이스를 구현하는 클래스는 extends 대신 implements 를 사용한다.
```

### 03. 메소드의 일부만 완성되어 있는 클래스를 무엇이라고 하나요? 
```
abstract (추상클래스)
```

### 04. 위에 있는 문제의 답에 있는 클래스에 body(몸통)이 없는 메소드를 추가하려면 어떤 예약어를 추가해야 하나요?
```
abstract
```

### 05. 클래스를 final로 선언하면 어떤 제약이 발생하나요?
```
확장(extends)을 할 수 없다.
```

### 06. 메소드를 final로 선언하면 어떤 제약이 발생하나요?
```
override를 할 수 없다.
```

### 07. 변수를 final로 선언하면 어떤 제약이 발생하나요?
```
재할당을 할 수 없다.
```

### 08. enum 클래스 안에 정의하는 여러 개의 상수들을 나열하기 위해서 상수 사이에 사용하는 기호는 무엇인가요?
```
,(콤마)
```

### 09. enum 으로 선언한 클래스는 어떤 클래스의 상속을 자동으로 받게 되나요?
```
java.lang.Enum 을 자동으로 상속 받는다.
```

### 10. enum 클래스에 선언되어 있지는 않지만 컴파일시 자동으로 추가되는. 상수의 목록을 배열로 리턴하는 메소드는 무엇인가요?
```
values()
```

# Chapter 14 다 배운 것 같지만, 예외라는 중요한 것이 있어요

### 01. 예외를 처리하기 위한 세가지 블록에는 어떤 것이 있나요?
```
try, catch, finally
```

### 02. 첫번째 문제의 답 중에서 "여기에서 예외가 발생할 것이니 조심하세요"라고 선언하는 블록은 어떤 블록인가요?
```
try
```

### 03. 첫번째 문제의 답 중에서 "예외가 발생하던 안하던 얘는 반드시 실행되어야 됩니다."라는 블록은 어떤 블록인가요?
```
finally
```

### 04. 예외의 종류 세가지는 각각 무엇인가요?
```
error, checked Exception, unchecked(runtime) Exception
```

### 05. 프로세스에 치명적인 영향을 주는 문제가 발생한 것을 무엇이라고 하나요?
```
error
기본적으로는 프로그램 내에서 발생한다기 보다  
JVM이나 시스템에서 문제가 발생했을 때 error가 발생한다.
```

### 06. try나 catch 블록 내에서 예외를 발생시키는 예약어는 무엇인가요?
```
throw
```

### 07. 메소드 선언시 어떤 예외를 던질 수도 있다고 선언할 때 사용하는 키워드는 무엇인가요?
```
throws
```

### 08. 직접 예외를 만들 때 어떤 클래스의 상속을 받아서 만들어야만 하나요?
```
Exception 이나 Exception을 상속 받는 클래스를 확장해서 만들 수 있다.  
하지만, Exception을 확장하게 된다면 무조건 try-catch로 묶어야 한다는 단점이 있기에  
RuntimeException 클래스를 확장하는 것을 권장한다.
```

# Chapter 15 String

### 01. String 클래스는 final 클래스인가요? 만약 그렇다면, 그 이유는 무엇인가요?
```
final로 선언되어 있으며 더이상 확장하여 사용하지 않기 위해서 이다.
```

### 02. String 클래스가 구현한 인터페이스에는 어떤 것들이 있나요?
```
Serializable, Comparable<String>, CharSequence 구현(implements)했다.  
```

### 03. String 클래스의 생성자 중에서 가장 의미없는 (사용할 필요가 없는) 생성자는 무엇인가요? 
```
기본 생성자 (아무 값도 없는 생성자 new String())  
이유는 할당 되자마자 GC의 대상이 되어 버리기 때문이다.
```

### 04. String 문자열을 byte 배열로 만드는 메소드의 이름은 무엇인가요?
```
getBytes()
```

### 05. String 문자열의 메소드를 호출하기 전에 반드시 점검해야 하는 사항은 무엇인가요?
```
null 체크
```

### 06. String 문자열의 길이를 알아내는 메소드는 무엇인가요?
```
length()
```

### 07. String 클래스의 equals() 메소드와 compareTo() 메소드의 공통점과 차이점은 무엇인가요?
```
공통점 : 두 개의 문자열을 비교한다.  
차이점 : 리턴 타입  
equals() : boolean타입이며 같으면 true, 다르면 false를 리턴한다.  
compareTo() : int타입이며 비교 대상보다 크면 양수, 작으면 음수, 같으면 0을 리턴한다.
```

### 08. 문자열이 "서울시"로 시작하는지를 확인하려면 String의 어떤 메소드를 사용해야 하나요?
```
startsWith()
```

### 09. 문자열에 "한국"이라는 단어의 위치를 찾아내려고 할 때에는 String의 어떤 메소드를 사용해야 하나요?
```
contains() 또는 matches()  
고전적인 방법으로는 indexOf()가 있다.
```

### 10. 위의 문제의 답에서 "한국"이 문자열에 없을 때 결과값은 무엇인가요?
```
contains() 또는 matches()의 리턴타입은 boolean으로서 false를 리턴하며,
indexOf() 는 int가 리턴타입이며, -1을 리턴한다.
```

### 11. 문자열의 1번째부터 10번째 위치까지의 내용을 String으로 추출하려고 합니다. 어떤 메소드를 사용해야 하나요? 
```
substring()
```

### 12. 문자열의 모든 공백을 * 표시로 변환하려고 합니다. 어떤 메소드를 사용하는 것이 좋을까요?
```
replace() 또는 replaceAll() 을 사용할 수 있다.  
둘다 원본 값은 변경시키지 않으므로 사용하려면 리턴 값을 사용해야 한다.
```

### 13. String의 단점을 보완하기 위한 두개의 클래스는 무엇인가요? 
```
StringBuffer, StringBuilder
```

### 14. 문제의 답에서 문자열을 더하기 위한 메소드의 이름은 무엇인가요?
```
append()
```

# Chapter 16 클래스 안에 클래스가 들어갈 수도 있구나

### 01. Nested 클래스에 속하는 3가지 클래스에는 어떤 것들이 있나요?
```
static nested class, local inner class, anonymous inner class
```

### 02. Nested 클래스를 컴파일하면 Nested클래스 파일의 이름은 어떻게 되나요?
```
"감싼클래스$Nested클래스.class"
```

### 03. Static Nested 클래스는 다른 Nested 클래스와 어떤 차이가 있나요?
```
인스턴스를 생성하는 방법이 다르다.
```

### 04. StaticNested 클래스의 객체 생성은 어떻게 하나요?
```
new OuterClass.StaticNestedClass();
```

### 05. 일반적인 내부 클래스의 객체 생성은 어떻게 하나요?
```
OuterClass outer = new OuterClass();
OuterClass.NestedClass nested = outer.new NestedClass();
```

### 06. Nested 클래스를 만드는 이유는 무엇인가요? 
```
- 한 곳에서만 사용되는 클래스를 논리적으로 묶어서 처리가 필요할 때
- 캡슐화를 통해 외부에서 접근하는 걸 막기 위해서
- 소스의 가독성과 유지보수성을 높이고 싶을 때
```

### 07. Nested 클래스에서 감싸고 있는 클래스의 private 로 선언된 변수에 접근할 수 있나요?
```
내부 클래스와 익명 클래스는 감싸고 있는 클래스의 어떤 변수라도 참조할 수 있다.
```

### 08. 감싸고 있는 클래스에서 Nested 클래스에 선언된 private 로 선언된 변수에 접근할 수 있나요?
```
감싸고 있는 클래스에서 Static Nested 클래스의 인스턴스 변수나  
내부 클래스의 인스턴스 변수로의 접근하는 것도 가능하다.
```

# Chapter 17 어노테이션이라는 것도 알아야 한다.

### 01. @Override 어노테이션의 용도는 무엇인가요?
```
메소드가 부모 클래스의 메소드를 Override했다는 걸 명시적으로 선언할 때 사용한다.  
다른 메소드와 알아보기 쉽게 하고, Override를 제대로 했는지 확인할 수 있다.
```

### 02. @SupressWarnings 어노테이션의 용도는 무엇인가요?
```
컴파일 시 발생할 수 있는 경고(warning)를 컴파일러에게 얘기해서 warning이 발생하지 않도록 할 수 있다.
```

### 03. @Deprecated 어노테이션의 용도는 무엇인가요?
```
더 이상 사용하지 않는 메소드에 선언한다.  
만약 다른 메소드에서 해당 메소드를 참조할 경우 경고가 발생한다.
```

### 04. 어노테이션을 선언할 때 사용하는 어노테이션을 무엇이라고 부르나요?
```
메타 어노테이션(Meta annotation)
```

### 05. 4번 문제의 답에 있는 어노테이션들을 사용할 때 import 해야 하는 패키지는 무엇인가요?
```
java.lang.annotation
```

### 06. @Target 어노테이션의 용도는 무엇인가요? 
```
어노테이션의 적용 범위를 선언한다.
```

### 07. @Retention 어노테이션의 용도는 무엇인가요? 
```
어노테이션 정보가 언제까지 유효한지를 선언한다.
```

### 08. @Inherited 어노테이션의 용도는 무엇인가요?
```
모든 자식 클래스에서 부모 클래스의 어노테이션을 사용 가능하다는 것을 선언한다.
```

### 09. 어노테이션을 선언할 때에는 class 대신 어떤 예약어를 사용해야 하나요? 
```
@interface
```