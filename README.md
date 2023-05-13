![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Python%20Data&fontSize=60)

Trying to handle Python efficiently as an analysis tool...🛠

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white">

<br/>
<br/>
<br/>

_PYTHON ASSIGNMENTS_
<br/>
2023.03.17

#### 삼성전자라는 변수로 50,000원을 바인딩. 삼성전자 주식 10주를 보유하고 있을 때 총 평가금액을 출력.
삼성전자 = 50000 <br/>
총평가금액 = 삼성전자 *10 <br/>
print(총평가금액)<br/>

#### 다음 표는 삼성전자의 일부 투자정보. 변수를 사용해서 시가총액, 현재가, PER 등을 바인딩.
시가총액 = 298000000000000<br/>
현재가 = 50000<br/>
PER = 15.79<br/>
print(시가총액, type(시가총액))<br/>
print(현재가, type(현재가))<br/>
print(PER, type(PER))<br/>

#### 변수 만들기
s = "hello"<br/>
t = "python"<br/>
print(s + '!', t)<br/>

#### 자료형
num_str = "720"<br/>
num_int = int(num_str)<br/>
print(num_int, type(num_int))<br/>

#### 에이컨이 월 48,584원에 무이자 36개월의 조건으로 홈쇼핑에서 판매. 총 금액은 계산한 후 이를 화면에 출력. (변수사용하기)
월지급액 = 48584<br/>
총금액 = 월지급액 * 36<br/>
print(총금액)<br/>

#### 문자 추출
letter = 'python'<br/>
print(letter[0], letter[2])<br/>

license_plate = "24가 2210"<br/>
print(license_plate[-4:])<br/>

string = "PYTHON"<br/>
print(string[::-1])<br/>

string = "홀짝홀짝홀짝"<br/>
print(string[::2])<br/>

phone_number = "010-1111-2222"<br/>
phone_number1 = phone_number.replace("-", " ")<br/>
print(phone_number1)<br/>

phone_number = "010-1111-2222"<br/>
phone_number1 = phone_number.replace('-', '')<br/>
print(phone_number1)<br/>

#### Split
url = "http://sharebook.kr"<br/>
url_split = url.split('.')<br/>
print(url_split[-1])<br/>

#### Replace
string = 'abcdfe2a354a32a'<br/>
string_replace = string.replace("a","A")<br/>
print(string_replace)<br/>

상장주식수 = "5,969,782,550"<br/>
콤마없앰 = 상장주식수.replace(",","")<br/>
정수 = int(콤마없앰)<br/>
print(정수, type(정수))<br/>

#### f스트링
name1 = "김민수" <br/>
age1 = 10<br/>
name2 = "이철희"<br/>
age2 = 13<br/>
print("이름: %s 나이: %d" % (name1, age1))<br/>
print("이름: %s 나이: %d" % (name2, age2))<br/>

name1 = "김민수" <br/>
age1 = 10<br/>
name2 = "이철희"<br/>
age2 = 13<br/>
print("이름: {} 나이: {}".format(name1, age1))<br/>
print("이름: {} 나이: {}".format(name2, age2))<br/>

name1 = "김민수" <br/>
age1 = 10<br/>
name2 = "이철희"<br/>
age2 = 13<br/>
print(f"이름: {name1} 나이: {age1}")<br/>
print(f"이름: {name2} 나이: {age2}")<br/>

#### 공백없앰
data = "   삼성전자    "<br/>
data1 = data.strip()<br/>
print(data1)<br/>

#### 대소문자
ticker = "btc_krw"<br/>
ticker1 = ticker.upper()<br/>
print(ticker1)<br/>

ticker = "BTC_KRW"<br/>
ticker = ticker.lower()<br/>
print(ticker)<br/>

a = "hello"<br/>
a = a.capitalize()<br/>

#### if else 조건문 연습
user = input("")<br/>
if int(user) % 2 == 0:<br/>
    print("짝수")<br/>
else:<br/>
    print("홀수")<br/>
    
user = input("입력값: ")<br/>
num = 20 + int(user)<br/>
if num > 255:<br/>
    print(255)<br/>
else:<br/>
    print(num)<br/>

user = input("입력값: ")<br/>
num = int(user) - 20<br/>
if num > 255:<br/>
    print(255)<br/>
elif num < 0:<br/>
    print(0)<br/>
else:<br/>
    print(num)<br/>

time = input("현재시간: ")<br/>
if time[-2:] == "00":<br/>
    print("정각 입니다.")<br/>
else:<br/>
    print("정각이 아닙니다.")<br/>

fruit = ["사과", "포도", "홍시"]<br/>
user = input("좋아하는 과일은?")<br/>
if user in fruit:<br/>
    print("정답입니다.")<br/>
else:<br/>
    print("오답입니다.")<br/>

warn_investment_list = ["Microsoft", "Google", "Naver", "Kakao", "SAMSUNG", "LG"]<br/>
종목 = input("종목명: ")<br/>
if 종목 in warn_investment_list:<br/>
    print("투자 경고 종목입니다.")<br/>
else:<br/>
    print("투자 경고 종목이 아닙니다.")<br/>
    
fruit = {"봄" : "딸기", "여름" : "토마토", "가을" : "사과"}<br/>
user = input("제가좋아하는계절은: ")<br/>
if user in fruit:<br/>
    print("정답입니다.")<br/>
else:<br/>
    print("오답입니다.")<br/>

fruit = {"봄" : "딸기", "여름" : "토마토", "가을" : "사과"}<br/>
user = input("좋아하는 과일은?")<br/>
if user in fruit.values():<br/>
    print("정답입니다.")<br/>
else:<br/>
    print("오답입니다.")<br/>



<br/>
#### 💥 실습: 사칙연산 입력받아 계산하기 아래 같은 입력을 받아 사칙연산을 하는 프로그램을 작성하시오.
<br/>
    1. 더하기<br/>
    2. 빼기<br/>
    3. 곱하기<br/>
    4. 나누기<br/>
- 계산기 기능을 선택하세요(1/2/3/4): 3<br/>
-> 첫 번째 숫자를 입력하세요: 5<br/>
-> 두 번째 숫자를 입력하세요: 10 5 * 10 = 50<br/>
<br/>
function = input("계산기 기능을 선택하세요(1/2/3/4):")<br/>
if function == "1" :<br/>
               input1 = input("첫 번째 숫자를 입력하세요:")<br/>
               input2 = input("두 번째 숫자를 입력하세요:")<br/>
               print(f"{input1} + {input2} = {int(input1) + int(input2)}")<br/>
elif function == "2" :<br/>
               input1 = input("첫 번째 숫자를 입력하세요:")<br/>
               input2 = input("두 번째 숫자를 입력하세요:")<br/>
               print(f"{input1} - {input2} = {int(input1) - int(input2)}")<br/>
elif function == "3" :<br/>
               input1 = input("첫 번째 숫자를 입력하세요:")<br/>
               input2 = input("두 번째 숫자를 입력하세요:")<br/>
               print(f"{input1} * {input2} = {int(input1) * int(input2)}")<br/>
elif function == "4" :<br/>
               input1 = input("첫 번째 숫자를 입력하세요:")<br/>
               if input1 == "0":<br/>
                        print("알맞은 값이 아닙니다.")<br/>
               else:<br/>
                         input2 = input("두 번째 숫자를 입력하세요:")<br/>
                         print(f"{input1} / {input2} = {int(input1) / int(input2)}")<br/>
else:<br/>
    print("알맞은 값이 아닙니다.")<br/>
    
    
    
