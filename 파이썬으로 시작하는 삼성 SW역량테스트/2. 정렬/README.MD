>https://m.blog.naver.com/wpghks7/221584382367

## 2. 정렬

### 오름차순 정렬하기 
* 값 자체를 정렬하기
```
a.sort()
```

* 정렬한 값을 변환하기 (원본 변화 x)
```
b = sorted(a)
```

### 내림차순 정렬하기
```
a.sort(reverse = True)
```

### 정렬 기준 정하기
```
a.sort(key = lambda x: (x[1], -x[0]))
```
