### datediff(날짜1, 날짜2)

- `날짜1 - 날짜2`  일단위로 날짜 차이를 계산할 때 사용

### timestampdiff(단위, 시작 날짜, 끝 날짜)

- 단위로 날짜 차를 구할 때 사용
- ex:  `timestampdiff(minute, start_date, end_date)`
    - 날짜 분 차이 구할 때
- ex: `timestampdiff(week, start_date, end_date)`
    - 주 차이 구할 때
- second, hour, day, month , quarter, year도 가능
