# report


## ASP(Active Server Page)
마이크로소프트가 제작한 서버 사이드 스크립트 엔진이다. <br>
브라우저가 웹 서버에서 ASP 파일을 요청하면 서버는 프로세서를 호출하고, 프로세서는 요청된 파일을 읽고 스크립트 명령을 실행하여 <br>결과를 웹페이지 형태로 브라우저에 전송한다.<br><br>


#### ASP의 목적
인터넷 정보 서비스(IIS)에서 동적 웹 페이지 생성 용도로 사용한다. <br><br>

#### ASP의 특징
* .asp 확장자를 사용한다.
* 텍스트 파일을 업데이트하는 것만으로도 웹페이지나 데이터베이스의 목차를 편집할 수 있다.   ? -빼고
* 웹 페이지 상에서 데이터베이스를 보여주고 그 안에 실제로 존재하는 데이터를 조작할 수 있다.    ? -빼고
* 사용자에 대한 정보를 피드백하여 해당 사용자에게 맞는 정보를 보내줄 수 있다.    ? -
* ASP 2.0은 6개의 내장 객체들을 제공한다.(Application, ASPError, Request, Response, Server, Session)   ?
* 2002년에 ASP.NET으로 대체되었으며, ASP는 2020년까지 지원이 예정되어 있다. 
* 윈도우에서 지원하는 기존 프로그래밍 언어를 웹에서 쓸 수 있도록 하는 일종의 기술에 가깝다(ASP.NET으로 발전하면서 크게 강화). <br><br>


#### ASP의 장점
* CGI 프로그램보다 작성하기 쉽다. 
* 비주얼 스튜디오와 묶여 있어 도움말이 강력한 편이다. 
* 많은 양의 서드파티 개발 툴과 오픈 소스가 존재한다. 
* 여러 언어를 지원한다(기본 언어는 VB 스크립트, 다른 언어도 사용 가능- 마이크로소프트의 액티브 스크립팅 표준과 호환되는 어떠한 스크립팅 언어라도 ASP에서 사용할 수 있다.).<br><br>

#### ASP의 단점
* 윈도 운영체제에서만 사용할 수 있다(윈도우에 최적화, 다른 OS는 정식으로 지원하지 않는다.). <br><br><br><br>


##### ASP.NET 
###### 2002년에 처음 선보인 ASP의 후속작으로 .NET Framework 위에서 구동되는 서버 사이드 웹 프레임워크이다. <br><br>

##### ASP.NET 특징
###### 1. 닷넷 프레임워크, 닷넷 코어 기반으로 지원 언어라면 어떤 것이든 사용 가능하다(C#, Visual Basic.NET 많이 사용된다). 
###### 2. ASP와 마찬가지로 윈도우 환경에서만 구동되었으나, 모노 기반으로 타 플랫폼에서도 사용할 수 있도록 되었고, 2016년 발표된 ASP.NET Core에서는 기본적으로 멀티플랫폼을 지원하게 변경되었다. 
###### 3. .NET 언어 어떤 것이든지 ASP.NET으로 개발이 가능하다. <br><br><br><br><br><br>


## PHP(Hypertext Preprocessor)
C 언어를 기반으로 만들어진 서버 사이드 스크립트 언어로 웹 시스템의 기반이 된다. </br>
</br>

#### PHP의 목적
동적 웹 페이지를 쉽고 빠르게 만들 수 있도록 해주는 것이다.</br>
HTML 코드 안에 PHP로 작성된 코드를 추가하면 웹 서버는 해당 PHP 코드를 해석하여 동적 웹 페이지를 생성한다.</br></br>

#### PHP의 특징
* 서버쪽에서 실행 되는 프로그래밍 언어이다.
* HTML을 프로그래밍적으로 생성해 준다. 
* 데이터베이스와 상호작용하면서 데이터를 저장, 표현한다. 
* 웹을 위한 언어로 웹 프로그래밍을 위한 높은 생산성을 제공한다. 
* 명령 줄 인터페이스 방식의 자체 인터프리터를 제공한다.</br>
    + 범용 프로그래밍 언어로 사용할 수 있다.</br>
    + 그래픽 애플리케이션을 제작할 수 있다.</br></br>
      
#### PHP의 장점
* 주요 운영체제와 대부분의 웹 서버에서 지원한다.  
* 다양한 데이터 베이스를 지원한다. 
* HTML 처리에 강점을 가지고 있다(텍스트 처리에 특화되어 있어 HTML 문서 처리에 적합). 
* 웹개발에 필요한 수많은 로직들이 함수의 형태로 미리 제공된다.
* 다른 프로그래밍 언어보다 직관적으로 코드를 작성할 수 있다. 
* 크로스 플랫폼이다(여러 종류의 컴퓨터 플랫폼에서 동작 가능). <br><br>

#### PHP의 단점
* 복잡한 사이트를 만드는 데는 효율적이지 못하다. 
* 보안에 안전하지 않은 언어 구조를 가진다.
<br><br><br><br>


# 문법
<br><br>
## ASP 문법
1. ASP 코드 선언
```ASP
<% 
ASP 코드
%>
```
여기서 \<%는 ASP가 시작된다는 사실을 알려주는 역할을 한다.</br>
%>는 ASP의 끝을 알려주는 역할을 한다. 
<br><br>

2. 출력
Response.write() 함수를 사용하면 원하는 문자열을 화면에 출력할 수 있다. 
```ASP
response.write("Hello World")
say = Hello
response.write(say & " World") ' 변수와 문자를 연결할 때는 &(연결 연산자)를 사용하면 된다. 
```

<br><br>

3. 주석
주석 처리를 해야할 경우 '(작은 따옴표) 를 문장의 앞에 붙여준다. '는 한 줄 주석이며, 여러줄 주석은 지원하지 않는다. 
```ASP
' 주석 처리하려면 앞에 '(작은 따옴표)를 붙이면 된다. 
```
<br><br>

4. 변수
Dim [변수명]을 이용해서 변수를 선언할 수 있으며, 따로 변수를 선언하지 않아도 값을 대입하면 변수로 사용 가능하다. 
```ASP
Dim say
say = "Hello"
world = "World"
```
<br><br>
5. 배열
5.1 고정 배열 
Dim 배열명(숫자)을 이용하여 고정 배열을 선언할 수 있다. 
```ASP
Dim a(1)

a(0) = 0
a(1) = 1
```
<br>

5.2 동적 배열
ReDim 배열명(숫자)를 이용하여 새롭게 배열의 크기를 지정해준다.
```ASP
Dim a()
ReDim a(1) ' 배열의 크기를 다시 지정
a(1) = 2

ReDim Preserve a(2) ' Preserve를 붙이면 a 배열에 있던 데이터를 지켜준다.(기존값 유지)
a(2) = 4
```

<br><br>

6. If문 : 조건문으로 조건 값이 true면 해당하는 코드를 실행한다.
If ... Then ... End if 의 구조를 가지고 있다. 
```ASP
Dim i
i = 1

if i <= 10 then
    response.write("10이하 입니다.")
else
    response.write("10보다 큽니다.")
end if
```
ASP에서의 if 문의 조건에서 같은지 비교하는 조건 연산자는 **=** 를 사용하고,<br>
다른지 비교하는 조건 연산자는 **<>** 를 사용한다. 
elseif는 붙여서 사용한다.
<br><br>

7. Do while문 : 반복문으로 조건이 참(true)인 동안 반복한다.
```ASP
Dim i
i = 1

Do While i <= 5
    Response.Write i & "<br>"
    i = i + 1
Loop

i = 0
Do While i <= 5
    i = i + 1
    if i = 3 then
        Exit Do  ' Exit Do를 이용해 While 문(반복문)을 종료할 수 있다. 
    End if
Loop

```

<br><br>
8. for문 : 반복문으로 조건이 참일 동안 반복한다.
For 변수 = 시작 값 To 종료 값 Step 증가 값
    실행구문
Next
와 같이 이루어진다. 
```ASP
for i = 1 to 5 step 1  ' 1부터 5까지 1씩 증가하면서 반복한다. 
    response.write i & "번째 <br>"
next
```
<br><br>

9. Select Case 문 : 분기점이 많을 때 사용된다. 일치하는 값을 찾아 해당 분기문을 수행한다.
```ASP
Dim rank
rank = "2"

Select Case rank
    case "1"
        response.write "1등입니다."
    case "2"
        response.write "2등입니다."
    case "3"
        response.write "3등입니다."
    case else
        response.write "안타깝지만, 순위에 들지 못했습니다."
end select
```     

###### ASP는 코드 뒤에 ;(세미콜론)을 붙이지 않는다. 

<br><br><br><br>
## PHP 문법

1.	PHP 코드 선언
```PHP
<?PHP
PHP 코드
?>
```
위와 같은 식으로 작성한다. <br>
여기서 \<?PHP 는 PHP 엔진에게 이제부터 PHP가 시작된다는 사실을 알려주는 역할을 한다. <br>
 ?>  는 PHP의 끝을 알려주는 역할을 한다. 

* 파일에 PHP 코드만 포함된 경우 파일 끝에 있는 PHP 닫기 태그(?>)를 생략해도 된다. 


<br><br>
2. 출력<br>
echo 명령어를 사용하면 브라우저 화면에 원하는 내용을 출력할 수 있다.
```PHP
<?PHP
Echo “Hello World”; 
?>
```
Hello World가 화면에 출력된다. 
<br><br>

3. 주석<br>
주석 처리해야 하는 행이 한 행인 경우
```PHP
//를 이용해 주석처리
또는
#를 이용해 주석처리
```
<br>
주석 처리해야 하는 행이 여러 행인 경우<br>

```PHP
/*를 이용해
여러 행을
주석 처리
할 수 있다. */
```
<br><br>

4. BOOl : 참, 거짓 형식<br>
TRUE, FALSE로 지정 가능하며 대소문자를 구분하지 않는다. 
```PHP
$a_true = true;
$a_false = 0;
```
False : false, 0, 0.0, -0.0, "0", 빈 문자열, NULL 등
True : true, 0이 아닌 모든 수
<br><br>

5. INT : 2진법, 8진법, 10진법, 16진법으로 지정 가능
```PHP
$a2 = 0b11111111; // 2진법으로 숫자 앞에 0b 삽입
$a8 = 0123; // 8진법으로 숫자 앞에 0 삽입
$a10 = 1234; // 10진법
$a16 = 0x1A; // 16진법으로 숫자 앞에 0x 삽입
$a_ = 1_234_567; // PHP 7.4.0 이상부터 숫자 사이에 _ 삽입 가능
```
<br><br>

6. Float : floating-point number
```PHP
$a = 1_2.345;
$b = 7E-10;
```
<br><br>
7. String : 작은 따옴표('), 큰 따옴표("), Heredoc, Nowdoc 사용하여 표현 가능
```PHP
echo 'Hello \n World'; // '
echo "Hello \n World"; // "

echo <<<EOT
Hello World
EOT; // Heredoc

echo <<<'EOT'
Hello World
EOT; // Nowdoc
```
<br><br>

8. Numeric strings : 문자열이 int 또는 float로 해석 될 수 있는 경우 숫자로 간주된다. 
```PHP
$foo = 1 + "10.5"; // $foo는 float(11.5)
```
<br><br>
9. Arrays : 실제로 정렬된 map. map이란 값을 키에 연결하는 유형
array()와 같이 선언할 수 있으며, array 짧은 배열 구문은 ()을 []로도 대체 가능하다. 
```PHP
$array = array(
    "foo" => "bar",
    "bar" => "foo",
);

$array = [
    "foo" => "bar"
    "bar" => "foo"
]
```
<br><br>

10. Iterables : 함수에 필요한 값 집합을 나타내기 위한 매개 변수 유형으로 사용 가능하다.<br>
foreach와 함께 사용되기 때문에 값 집합의 형식은 신경쓰지 않는다. 
```PHP
function foo(iterable $iterable) {
    foreach ($iterable as $value) {
        // ...
    } 
}

// iterable로 선언된 매개 변수는 null 또는 배열을 기본 값으로 사용할 수 있다. 

function foo(iterable $iterable = []) {
    // ...
}

// 함수가 반복 가능한 값을 반환 할 것임을 나타내는 반환 유형으로 사용할 수 있다.     ?
function bar(): iterable {
    return [1, 2, 3];
}

// iterable을 반환 유형으로 선언하는 함수는 생성자일 수도 있다.         ?
function gen(): iterable {
    yield 1;
    yield 2;
    yield 3;
}

```
<br><br>
11. Objects : 새 객체를 만들려면 new 문을 사용하여 클래스를 인스턴스화 하면 된다.
```PHP
class foo
{
    function do_foo()
    {
        echo "Doing foo."; 
    }
}

$bar = new foo;
$bar->do_foo();
```

<br><br>
12. 변수 : **$변수이름** 과 같이 표시된다. 변수 이름은 대소문자를 구분한다. <br>
유효한 변수 이름은 문자 또는 _ 로 시작하고 그 뒤에 임의 수의 문자, 숫자 또는 _ 이 이어진다. 
```PHP
$var = 'Hello';
$Var = 'World';
echo "$var, $Var";      // 출력은 "Hello, World"

$4site = 'not yet';     // 유효하지 못한 변수. 변수 이름의 제일 앞에 숫자가 오면 안된다. 
$_4site = 'not yet';    // 유효한 변수. 변수 이름의 제일 앞에 _가 와도 된다. 
```
<br>
변수에 값을 대입할 때 다른 변수의 값을 참조하여 할당하려면 변수의 앞에 &를 추가하면 된다. 
```PHP
$var = 'Hello';
$VAR = &$var; // 이런 식으로 참조할 수 있다.
```
참조하면 한 변수의 값을 변경하면 다른 변수도 같이 변경된다. <br><br>

13. 상수 : const 키워드 또는 define() 함수를 사용하여 정의할 수 있다. 
```PHP
define("CONSTANT", "Hello world.");
echo CONSTANT; // 출력 값 : "Hello world."
```
const 키워드를 사용할 때는 스칼라(bool, int, float, string) 표현식과 스칼라 표현식만 포함하는 상수 배열만 가능하다. 
또한, if 문이나 try/catch 문 안에서는 선언 불가하다. 
```PHP
const CONSTANT = 'Hello World';
echo CONSTANT; // 출력 값 : "Hello world."
```


###### 상수와 변수의 차이점
* 상수 앞에는 $ 기호가 없다. 
* 상수는 가변 범위 지정 규칙에 관계 없이 어디서나 정의 및 액세스할 수 있다.
* 상수를 설정한 후에는 다시 정의할 수 없다.
* 상수는 스칼라 값이나 배열로만 평가할 수 있다.
<br><br>


14. 연산자 
- 연산자의 우선순위

|연관성|연산자|추가 정보|
|-------|-------|----------|
|해당 없음|clone new|복제 및 신규|
|오른쪽|\*\*|산수|
|해당 없음|+ - ++ -- ~ (int) (float) (string) (array) (object) (bool) @|산술 (단항 +및 -), 증가 / 감소 , 비트 , 유형 캐스팅 및 오류 제어|
|왼쪽|instanceof|유형|
|해당 없음|!|논리적|
|왼쪽|* / %|산수|
|왼쪽|	+ - .|산술 (이진 +및 -), 배열 및 문자열 ( .PHP 8.0.0 이전)|
|왼쪽|<< >>|비트 단위|
|왼쪽|.|문자열 (PHP 8.0.0 기준)|
|비연관|< <= > >=|비교|
|비연관|== != === !== <> <=>|비교|
|왼쪽|&|비트 및 참조|
|왼쪽|^|비트 단위|
|왼쪽|\||비트 단위|
|왼쪽|&&|논리적|
|왼쪽|\|\||논리적|
|오른쪽|??|널 병합|
|비연관|? :|삼항 (PHP 8.0.0 이전의 왼쪽 연관)|
|오른쪽|= += -= \*= \*\*= /= .= %= &= \|= \^= <<= >>= ??=|할당|
|해당 없음|yield from|tield from|
|해당 없음|yield|yield|
|해당 없음|print|print|
|왼쪽|and|논리적|
|왼쪽|xor|논리적|
|왼쪽|or|논리적|

<br>

14.1 산술 연산자 : 기본적인 산수 계산
```PHP
echo $ a + $ b;
echo $ a % $ b; // $a의 부호를 갖는다. 
```
<br>

14.2 할당 연산자 : 왼쪽 피연산자의 값을 오른쪽 표현식의 값에 넣어준다. 
```PHP
$a = ($b = 4) + 5; // $a : 9, $b : 4
```
<br>

14.3 비트 연산자 : 정수 내 특정 비트를 조작할 수 있다. 
```PHP
$a << $b // $a의 비트를 $b만큼 왼쪽으로 이동
$a & $b // $a와 $b 둘 다에 설정된 bit 설정
```
<br>

14.4 비교 연산자 : 두 값을 비교할 수 있다.
```PHP
$a == $b // 결과 값이 true이면, $a와 $b의 값은 동일하다.
$a === $b // 결과 값이 true이면, $a와 $b의 값과 타입이 동일하다. 
```
<br>

14.5 증가/감소 연산자 : 변수 값의 사전 및 사후 증감이 가능하다.
```PHP
++ $a // 사전 증분 - $a를 1만큼 증가시킨 다음 $a 반환
$a -- // 사후 감소 - $a를 1만큼 감소시킨 다음 $a 반환 
```
<br>

14.6 논리 연산자
```PHP
$a OR $b // $a와 $b 중에 하나라도 true면 true
$a XOR $b // $a와 $b 중에 하나만 true면 true. 둘 다 true면 false
```

<br><br>

15. if 문 : 조건이 true면  if 문을 실행한다.
```PHP
// if 문
if ($a > $b){
  echo "a is bigger than b"; // if 문 내의 코드가 한 행이면 {} 생략 가능하다.
}

// else 문
if ($a > $b){
  echo "a is greater than b";
}else{
  echo "a is NOT greater than b";
}

// else if 문
if ($a > $b){
  echo "a is bigger than b";
}elseif($a == $b) {
    echo "a is equal to b";
} else {
    echo "a is smaller than b";
}
```
<br><br>

16. while문 : 반복문 중 하나. 조건식이 true일 동안 반복한다.
```PHP
$i = 1;
while ($i <= 10) { // i가 10보다 커지면 while문을 중단한다. 
    echo $i++; 
}

$i = 1;
while ($i <= 10):
    echo $i;
    $i++;
endwhile;

// do-while 문은 while문의 끝에서 조건이 참인지 확인한다. 
// 그렇기 때문에 조건의 참, 거짓 여부와 상관없이 첫 번째 반복이 실행된다. 
$i = 0;
do {
    echo $i;
} while ($i > 0);

```
<br><br>

17. for문 : 반복문 중 하나로 아래와 같이 쓰인다. 
```PHP
for ($i = 1; $i <= 10; $i++) { // for(변수의 초기화-for문 시작할 때 한 번만 실행, 조건으로 true일 동안 실행 반복문-for문 한 번 돌때마다 조건 만족하는지 확인, 변수 세팅-for문 한 번 끝날때마다 해당하는 행동 수행)
    echo $i;
}
```
<br><br>

18. foreach : 배열을 쉽게 반복할 수 있게 해준다. 배열과 객체에서만 작동한다. 
```PHP
$arr = array(1, 2, 3, 4);
foreach ($arr as &$value) { // foreach (iterable_expression as $value)
    $value = $value * 2;
}

$a = array(
    "one" => 1,
    "two" => 2,
    "three" => 3,
    "seventeen" => 17
);

foreach ($a as $k => $v) { // foreach (iterable_expression as $key => $value)
    echo "\$a[$k] => $v.\n";
}

```
<br><br>

19. switch 문 : if문과 유사하다. 여러 값 중에 동일한 값을 찾아 해당하는 코드를 실행한다. 
```PHP
switch ($i) {
    case 0: // $i의 값이 0이면 실행
        echo "i equals 0";
        break;
    case 1: // $i의 값이 1이면 실행
        echo "i equals 1";
        break;
    case 2: // $i의 값이 2이면 실행
        echo "i equals 2";
        break;
}
```

<br><br>

20. break와 continue 
* break는 for, foreach, while, do-while, switch 구조에서 현재 실행을 종료한다. 조건문이나 반복문이 중첩되어 사용되어 있으면 숫자를 통해 어떤 구조를 종료할지 지정한다. <br>
* continue는 루프안에서 현재 실행 중이던 동작을 멈추고 루프의 조건으로 되돌아 가 조건 평가부터 다시 시작하여 실행을 이어나간다. break와 마찬가지로 중첩된 경우 숫자를 통해 어떤 루프를 의미하는지 알려준다. 


<br><br>

###### PHP 코드의 각 행 끝에는 ;(세미콜론)이 필수로 들어가야 한다.
