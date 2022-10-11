# 7. 해시 테이블

해시 테이블은 사용함에 따라 배열을 대체 할 수도 있으며  
활용 용도에 따라 엄청난 속도 개선을 이뤄낼 수 있는 자료구조 중 하나이다.  
  
이 자료구조는 어떻게 되어있을까?  
우리는 어렸을 적 암호를 대시오 놀이를 한번쯤은 해봤을 것이다.  

`아빠 왔다`  
`꼼작 마! 쏜다`  
`으악! 왝`  
`아빠 맞네`  

해시 테이블은 이러한 놀이를 떠올리면 쉽다.  

아래에서 좀 더 자세한 예시를 통해 알아보자.  
해시 테이블을 이와 같이 설정한다.  
```
{
    "abc": "Hello"
}
```

실제로 동작하는 구조는 좀 더 복잡하지만 기본적인 로직은 아래와 동일하다.  
알파벳 순서대로 a = 1, b = 2, c = 3 라고하면  

a * b * c 를 하면 6의 값이 나온다.  
이제 abc 값 `Hello`는 메모리 주소 6번에 저장된다.  

```
{
    "bd": "World"
}
```

다른 예시를 들어보자  
de도 위와 같은 공식으로 진행하면 b = 2, d = 4 이므로  
8이 나온다. 이제 메모리 주소 8번에 `World`를 저장한다.

저장된 결과값은 아래와 같다.

| 메모리주소 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|---|---|---|---|---|---|---|---|---|---|---|
|   |   |   |   |   |   | Hello  |   | World  |   |   |

만약 10개의 원소로 이루어진 배열에서 Hello 선형 검색을 통해 찾는다고 해보자.  
최악의 경우 10번의 순회를 하게 될 것이다.

하지만 해시 테이블은 단 한번의 조회를 통해 Hello를 가져 올 수 있게 된다.  
이는 엄청난 차이가 된다!


---
## 해시 테이블의 효율성
---
해시 테이블의 효율성은 기본적으로 O(1) 이다.


---
## 목차
---
해시 테이블 과정은 여러 개의 예제로 이루어져 있어 아래와 같이 목차를 제공한다.
1. Create Hashtable - 해시 테이블 직접 생성해보기 
2. Create Hashtable as Array - 해시 테이블을 배열로 활용한 성능 개선