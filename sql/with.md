# with

- sql에서 복잡한 쿼리를 짜다보면 비슷한 서브쿼리를 연속으로 만들 때가 종종 있다.
- 서브쿼리를 하나의 변수에 담아 사용하듯이 with절로 가상 테이블을 만들어 사용할 수 있다.

```sql
with df as (
	select col1, col2
  from table1
  where col1 > 10
)
select d.col1, d.col2
from df as d
```



- 변수선언과 비슷하고, view를 만들어놓고 호출하는 것과도 비슷하다.
- 쿼리를 더 간결하게 짜기위해 넘나 좋은 문법인 것 같다.

