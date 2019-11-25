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

### 데이터 모델

1. Key-Value 

   1. 하나의 Key에 하나의 Value를 갖는 데이터 모델
   2. Key로만 접근 가능

2. Column

   1. 하나의 Key에 여러개의 Value를 갖을 수 있는 데이터 모델
   2. 중첩된 HashMap구조

3. Document
   1. Value가 Json이나 XML Doucment를 갖는 데이터 모델
   2. Value의 일부로 질의하고 일부만 가져올 수 있



















