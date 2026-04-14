# D-Day

200살까지 남은 시간: **59685일**

- 기준일: 1989-09-12
- 200세 달성일: 2189-09-12
- 현재까지 생존일: 13140일 (약 36년)
- 남은 years: 164년

```dataviewjs
const birthday = dv.expando("1989-09-12");
const expectancy = 200;
const target = new Date(birthday);
target.setFullYear(target.getFullYear() + expectancy);
const now = new Date();
const diff = Math.floor((target - now) / (1000 * 60 * 60 * 24));
dv.paragraph("**" + diff + "일** 남음 (200세까지)");
```

*마지막 업데이트: 2026-04-14 10:42*
