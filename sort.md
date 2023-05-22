# sort

## 정렬을 수행하는 데 인덱스를 동시에 추적하는 방법

별 거 아닐 수도 있겠지만, 인덱스와 값을 튜플에 담아 사용하면 된다.

```python
nums = [7, 2, 9, 14, 1, 8]
idx_nums = [(i, num) for i, num in enumerate(nums)]
idx_nums.sort(key=lambda tup: tup[1])
```
