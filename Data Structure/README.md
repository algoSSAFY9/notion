## Stack
- LIFO(Last In First Out)
    - 후입선출(LIFO) - 가장 늦게 넣은 데이터가 가장 먼저 나가는 방식으로 데이터를 저장한다.
## Queue
- FIFO(First In First Out)
    - 선입선출(FIFO) - 가장 먼저 넣은 데이터가 가장 먼저 나가는 방식으로 데이터를 저장한다.

## Map
- 순서가 없고 value 중복은 허용하지만 key의 중복을 허용하지 않는다. 
- 인덱스가 따로 존재하지 않기 때문에 iterator 사용한다.
- 종류 : HashMap, HashTable, LinkedHashMap, TreeMap

## Set
- 순서가 없고 key의 중복을 허용하지 않는다.
- 종류 : HashSet, LinkedHashSet, TreeSet

## Deque
- 양쪽 끝에서 삽입과 삭제가 모두 가능한 자료구조
- Deque<String> stack = new ArrayDeque<>();