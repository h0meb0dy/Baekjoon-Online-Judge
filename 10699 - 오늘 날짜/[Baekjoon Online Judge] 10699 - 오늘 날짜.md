# [Baekjoon Online Judge] 10699 - 오늘 날짜

:writing_hand: [h0meb0dy](mailto:h0meb0dysj@gmail.com)

> https://www.acmicpc.net/problem/10699

## 문제

서울의 오늘 날짜를 출력하는 프로그램을 작성하시오.

## 입력

입력은 없다.

## 출력

서울의 오늘 날짜를 "YYYY-MM-DD" 형식으로 출력한다.

### 예제 입력 1

```
```

### 예제 출력 1

```
2015-01-24
```

## 힌트

채점 서버는 시간대(Timezone)는 UTC+0 이다.

다음은 채점 서버에서 KST 시간으로 2018년 3월 21일 오후 2시 7분 38초에 `date` 명령어를 실행시킨 결과이다.

```
Wed Mar 21 05:07:38 UTC 2018
```

## 출처

- 문제를 만든 사람: [baekjoon](https://www.acmicpc.net/user/baekjoon)

## 알고리즘 분류

- [구현](https://www.acmicpc.net/problem/tag/102)

## Solve

```python
from datetime import date

print(date.today().isoformat())
```