## 알고리즘, 자료구조가 왜 중요할까요? ( 매우 주관적 )

한 나무주인이 숲에 제가 심어놓은 나무를 심고 이름을 새긴 뒤 볼일이 있어 여행을 떠납니다.  
몇 년만에 돌아온 나무주인은 다시 자신의 나무를 찾고 싶습니다. 그러나 그 나무는 어느덧 무럭무럭 자라  
다른 나무들과 키가 커져있었습니다. 그러다 보니 이름을 새긴 부분을 찾기 위해 모든 나무를 훑어보기 시작합니다.  
숲 전체에 10그루의 나무만 있다면 금방 찾을 것입니다.  
그러나 100그루, 1000그루 라면 좀 더 걸리겠죠. 

여기서 만약 100만 그루라고 하면 어떨까요? 숲 전체를 뒤진다는 건 죽기 직전까지도 불가능합니다.  
그런데 머리좋게도 나무 주인은 지나쳐오는 나무마다 노란 리본을 달아놨다는 걸 기억해냈습니다.  
그 리본을 따라가다보니 본인의 나무를 찾는데 성공하게 됩니다.  

현재 서비스가 빗발치는 현대 사회는 어떨까요? 100만데이터는 이미 우습게 넘긴 상태입니다.  
100TB 용량을 가진 서버라고 해도 모든 데이터를 저장 할 순 없고, 저장했다고 해도 데이터 하나를 찾기 위해서  
어떤 방식을 사용해야 할까요.   

100만 사용자를 가진 서비스라고 가정해볼까요, 모든 데이터를 순차적으로 조회하면서 100만번 만큼 순회를 하게 된다면  
동시 접속자 10만명이라고 쳐도 이미 1000만번의 반복하게 됩니다.  

이럴때 필요한게 노란 리본입니다. 그 노란 리본은 자료구조라고도 하지요. 우리가 데이터 하나를 찾기 위해 만들어둔 지름길  
빅 데이터 시대에 대응하기 위해 이러한 지름길 찾는 방법을 알아두기 위해 자료구조를 공부하고, 직접 체득하기 위해 구현해둔 자료입니다.

소스 상에 문제가 있거나 더 효율적인 방법이 있다면 의견 부탁드립니다.


## 목차
1. Ordered Array - 정렬된 배열
2. Binary Search - 이진 검색
3. Buble Sort - 버블 정렬
4. Linear Programming - 선형 계획법
5. Selection Sort - 선택 정렬
6. Injection Sort - 삽입 

## 참조서적
누구나 자료구조와 알고리즘 - 제이 웬그로우
