# codingTestStudy
알고리즘 실력향상을 위한 난이도별 문제연습

## 초급
- 약수구하기
- 이진수
<br>
<br>

# 코테를 위한 Python 기본
<br>
# 자료형
## 수 자료형

- 정수형 : 정수를 다루는 자료형. 양의 정수, 음의 정수, 0 으로 이루어져있다.
- 실수형 : 소수점 아래의 데이터를 포함하는 수 자료형.
- **round**(a, 2)  :  a변수를 소수점 셋째 자리에서 반올림한다.
- 1**e**9  :  1 * 10의9제곱
- **//**  :  몫 연산자,  ******  :  거듭제곱 연산자

## 리스트 자료형

- 리스트는 대괄호안에 원소를 넣어 초기화하며 쉼표로 원소를 구분한다.
- **list**() 혹은 **대괄호**를 이용하여 리스트를 선언한다.
- [0] * 3  :  [0, 0, 0]
- 리스트 인덱싱 시, 음의 정수를 넣으면 거꾸로 탐색한다.
- a[n : m]  :  a리스트의 n+1부터 m+1 까지 원소를 인덱싱 한다.
- [i **for** i **in** range(20) **if** i % 2 **==** 1]  배열 내에 반복, 조건문을 넣어 초기화 할 수 있다.(리스트 컴프리헨션)
- 언더바( _ )  :  반복을 위한 변수를 생략할때 사용한다.
- **append**(), sort(), reverse(), **insert**(), count(), **remove**() 등의 리스트 메서드가 있다.

## 문자열 자료형

- 문자열 변수를 초기화 할 때나는 **“**나 **‘**를 이용한다.
- 문자열 변수를 양의정수와 곱하면 그 값만큼 여러번 더해진다.
- 숫자형과 마찬가지로 인덱싱과 슬라이싱을 이용할 수 있다.

## 튜플 자료형

- 리스트와 거의 비슷하지만 한 번 선언된 값은 변경할 수 없다.
- 튜플은 **소괄호**를 이용한다.
- 변경하면 안되는 리스트에 주로 사용한다.

## 사전 자료형

- **키**와 **값**의 쌍을 데이터로 가지는 자료형이다.
- **해시테이블**을 이용하므로 데이터의 검색 및 수정에 있어서 빠르게 동작한다.
- **dict**()로 선언한다.

## 집합 자료형

- 집합을 처리하기 위한 자료형이다.
- 중복을 허용하지 않고, 순서가 없다.
- 키가 존재하지 않고, 값 데이터만을 담는다.
- **set**(), **{}** 로 선언한다.
- **|** : 합집합,  **&** : 교집합,  **-** 차집합
- **add**(), **remove**(), **update**() 등의 메서드가 있다.

<br>

# 표준 라이브러리
## 중요 표준 라이브러리 6가지

- **내장 함수** : print(), input()과 같은 기본 입출력 기능부터 정렬 기능을 포함하고 있는 기본 내장 라이브러리이다. 필수 기능들을 포함한다.
- **itertools** : 파이썬에서 반복되는 형태의 데이터를 처리하는 기능을 제공하는 라이브러리이다.
- **heap** : 힙 기능을 제공하는 라이브러리이다. 우선순위 큐 기능을 구현하기 위해 사용한다.
- **bisect** : 이진 탐색 기능을 제공하는 라이브러리이다.
- **collections** : 덱, 카운터 등의 유용한 자료구조를 포함하고 있는 라이브러리이다.
- **math** : 필수적인 수학적 기능을 제공하는 라이브러리이다.

## 내장 함수

- 별도의 import 없이 바로 사용할 수 있는 내장 함수가 존재한다.
- **input**(), **print**(), **sum**(), **min**(), **max**(), **eval**(), **sorted**() 등의 함수가 존재한다.

## itertools

- 반복되는 데이터를 처리하는 기능을 포함하는 라이브러리이다.
- **permutations** : 리스트를 일렬로 나열하는 모든 경우를 출력한다.
- **combinations** : 리스트를 순서를 고려하지 않고 나열하는 모든 경우를 출력한다.
- **product** : permutations와 동일하나 원소를 중복하여 뽑는다.
- **combinations_with_replacement** : combinations와 동일하나 원소를 중복하여 뽑는다.

## heapq

- 다익스트라 최단 경로 알고리즘을 포함해 다양한 알고리즘에서 우선순위 큐 기능을 구현하고자 할 때 사용된다.
- **heappush**(), **heappop**() 메서드를 이용한다.

## bisect

- 이진 탐색을 쉽게 구현할 수 있는 기능을 제공한다.
- 정렬된 배열에서 특정한 원소를 찾아야 할 때 효과적으로 사용된다.
- **bisect_left**(), **bisect_right**(), **count_by_range** 함수가 중요하게 사용된다.

## collections

- 유용한 자료구조를 제공한다.
- **deque**, **Counter** 클래스가 주로 사용된다.

## math

- 자주 사용되는 수학적인 기능을 포함한다.
- **factorial**(), **sqrt**(), **gcd**() 등의 기능 제공
