# 운영 로그

시간순으로 모든 인제스트, 쿼리, 린트 기록을 남깁니다.

## 로그 포맷

각 항목은 다음과 같은 접두사로 시작:

- `## [YYYY-MM-DD HH:MM] ingest | 제목` - 새 지식 인제스트
- `## [YYYY-MM-DD HH:MM] query | 키워드` - 검색/질의
- `## [YYYY-MM-DD HH:MM] lint | 이슈` - 린트 점검

## 최근 로그

```dataview
LIST creation + " : " + title
FROM "00_SYSTEM/log.md"
SORT file.mtime DESC
LIMIT 10
```

---
*이 로그는 자동으로 관리됩니다.*
## [2026-04-14 10:42] ingest | 나스닥 장기 투자 전략

