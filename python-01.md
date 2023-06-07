# type01_none

## 주석
```python
# 한줄 주석 : 사람을 위한 설명
''' 
여러 줄 주석 
여러 줄로 설명
'''
```

## 실행 = shift + f10

```python
a = 1
# a라는 값(객체)에 숫자 1을 대입했다.

print(a)
# a라는 변수의 값을 콘솔에 출력해주세요.

print(type(a))
# >>> <class 'int'>
# type은 a라는 변수의 값이 어떤 형태인지 알고 싶을때 쓰는 것.
# 'int'는 정수. class는 값의 형태/모양
```

## None과 Null과 0
```python
b = None
print(b)
print(type(b))

#print(c) >>> undefined
c = None
print(c)

# None : 있는건데 값이 없음.(변수는 있는데, 해당 변수에 값이 없음.)
# 0은 0이라는 값이 있는 것.
# None과 Null의 차이: Null은 undefined. (변수 자체가 정의 되지 않았음.)
```

## print(id(★))
```python
# singleton (객체가 하나만 만들어짐).
print(id(b))
print(id(c))
#id는 컴퓨터의 메모리 위치 주소값을 알 수 있는 함수.
#둘 다 140712390848192라는 수로 뜸. b와 c가 모두 none로 입력되었기 때문. none은 내 컴퓨터에서 저런 위치에 있음.
```

# type02_number


## int : 정수
```python
a = 100
print(a)
print(type(a))
```

## int 생성자 : b를 int로 정의
```python
b = int(101)
print(b)
print(type(b))
```

## float : 실수
```python
c = 200.2
print(c)
print(type(c))
```


## float 생성자 = d를 float로 정의?
```python
d = float(200.2)
print(d)
print(type(d))
```

## 정수 + 실수
```python
print(a + d)
print(type(a + d))
```
- literal = 값
- a가 100이었고, d가 200.1이었는데 더했더니 300.1이 나왔음.
이 100과 200.1과 300.1은 컴퓨터에서는 그냥 값. 즉 리터럴이라고 할 수 있다.


## complex : 복소수
```python
e = 1 + 2j
print(e)
print(type(e))
```

- 복소수는 real + imaginary (실수부 + 허수부 j)
- i대신 j를 쓴다. 다른 전류밀도 기호와 구분하기 위해서.

## 생성자
```python
f = complex(3, 4)
print(f)
print(type(f))
```
- complex(real, imaginary) 콤마로 연결하면 콤마 왼쪽은 실수부, 오른쪽은 허수부가 된다.

## bool : 논리 타입
```python

g = True
h = False

print(g)
print(h)
print(type(g))
print(type(h))
```
- 파이썬은 c 기반으로 만들어져있다. C 언어에서는 0은 거짓, 1은 트루라고 한다.
- 타입값 앞은 다 대문자로 되어있다는 것 기억.


## =과 ==

```python
# = 하나는 "변수=값"이었다. 즉 대입이었다.
# = 두개는 같다라는 뜻이다. 아래는 1과 g가 같은지 보여줘! 라는 뜻.
print(1 == g)
print(0 == h)
print(0 != h)

#!= 는 != 기호를 기준으로 좌우의 값이 같지 않은지 참과 거짓으로 판단하는 비교 연산자
```

# 진법
2진수
```python
binary = 0b1111
print(binary)
```

#8진수
```python
octal = 0o77
print(octal)
```

#16 진수
```python
hexadecimal = 0xff
print(hexadecimal)
```
