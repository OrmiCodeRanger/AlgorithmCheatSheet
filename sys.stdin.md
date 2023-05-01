# Python 입력

## 한 개의 정수를 입력받을 때

```python
import sys
a = int(sys.stdin.readline().rstrip())
```

## 정해진 개수의 정수를 한줄에 입력받을 때

```python
import sys
a,b,c = map(int,sys.stdin.readline().rstrip().split())
```

## 임의의 개수의 정수를 한줄에 입력받아 리스트에 저장할 때

```python
import sys
data = list(map(int,sys.stdin.readline().rstrip().split()))
```

## 임의의 개수의 정수를 n줄 입력받아 2차원 리스트에 저장할 때

```python
import sys
n = int(sys.stdin.readline().rstrip())
data = [list(map(int, sys.stdin.readline().rstrip().split())) for _ in range(n)]
```

## 문자열 n줄을 입력받아 리스트에 저장할 때

```python
import sys
n = int(sys.stdin.readline())
data = [sys.stdin.readline().strip() for i in range(n)]
```
