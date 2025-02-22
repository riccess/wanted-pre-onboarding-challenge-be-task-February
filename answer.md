1. 관계형 데이터베이스(RDBMS)와 비관계형 데이터베이스(NoSQL)의 장단점 비교

[관게형 데이터베이스]
- 장점
1) 데이터 무결성 보장
2) 각 데이터는 중복 없이 한 번만 저장
3) 데이터베이스를 추가하기 전에 유효성 검사를 통해 데이터 품질을 향상할 수 있다.
- 단점
1) 관계를 맺고 있기 때문에 JOIN문이 많은 복잡한 쿼리가 만들어질 수 있다.
2) JOIN이 많고 복잡한 쿼리가 만들어졌을 경우 수정이 번거롭거나 불가능한 경우가 생긴다.
3) 수평적 확장이 어렵고 대체로 수직적 확장만 가능하기 때문에 데이터 처리량 성장에 한계가 있다.
[비관꼐형 데이터베이스]
- 장점
1) 데이터 모델링이 완료되기 이전에도 테스트 데이터 조회가 가능
2) 스키마가 없기 때문에 훨씬 더 유연하며 언제든 저장한 데이터를 조정할 수 있다.
3) 다양한 가변성이 잇는 데이터의 저장이 쉽다
4) 데이터가 애플리케이션이 필요로 하는 형식으로 저장되기 때문에 데이터를 읽어오는 속도가 빠르다.
- 단점
1) 유연성 때문에 데이터 구조 결정이 어렵다.
2) 문서 저장이 단위 요소 수준에서 세밀한 보안을 제공하지 않는다.
3) 데이터베이스의 컬렉션이 다양할 경우, 수정할 때에 모든 컬렉션의 데이터를 수정해야한
 
5. 트랜잭션(transaction)이란 무엇인가요?

- 트랜잭션이란 데이터베이스 내에서 하나의 그룹으로 처리되어야하는 명령문들을 모아 놓은 논리적인 작업 단위이다.

3. MySQL에서 조인(join)의 역할은 무엇인가요? 다양한 join의 방식에 대해 설명해주세요.

- 조인이란 두개의 테이블을 연결하는 것이다.
- left join: 왼쪽 테이블을 기준으로 두 테이블의 교집합을 제외한 왼쪽 테이블들의 데이터
- right join: 오른쪽 테이블을 기준으로 두 테이블의 교집합을 제외한 오쪽 테이블들의 데이터
- outer join: 두 테이블의 합집

4. MySQL에서 인덱스(index)란 무엇인가요?

- 인덱스란 데이터베이스 테이블에 대한 겁색 성능의 속도를 높여주는 자료구조이다.
