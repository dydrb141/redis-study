# Redis란

## 소개

* REmote DIctionary Server의 약자
* 오픈소스 소프트웨어다
* 메모리 기반의 데이터 자장소
* NoSQL & Cache솔루션 
* key value 저장소 

### 장점

1. 리스트, 배열ㄹ과 같은 데이터를 처리하는데 유용
2. Aotomic처리로 데이터 부정합 방지 \(key 갱신 요청시\)
3. 메모리를 활용하면서 영속성 데이터 보존
4. 1개의 싱글 스레드로 수행 해서 여러개의 서버를 띄우는것이 가

### 단점

1. 메모리 파편화가 발생하기 쉽다.
2. 대규모 데이터에 대한 응답 속도의 불안정성

### 데이터 타입

String

* Text 숫자등 일반적인 Value

Set

* 하나의 키 값에 여러개의 Set자료 구조 제공

SortedSet

* score라는 필드가 추가되어 정렬의 기준이 됨
* score를 통해 질의 가
* 그 외에는 Set과 동

Hashes

* Value가 Map자료구조와 같은 Key/Value형식이 

List

* Value가 linkedList자료 구조가 됨
* Push/Pop 연산 가능
* index 활용 질의 가



















