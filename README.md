# channel-board

유튜브 채널 두 곳(Star Moments · K-POP推し便)의 지표 보드. 정적 페이지(index.html) + data/*.json.

- 데이터는 PC 예약 작업 `shorts_dash`(3시간마다)가 `apps/shorts/work/dash_build.py` 로 만들고 이 저장소에 올린다.
- 조회·좋아요·댓글: PC가 1시간마다 찍는 기록(view_snaps.jsonl). 유지율·유입·검색어·시청자: 유튜브 분석 API, 하루 1번.
- 검색엔진 차단(robots.txt, noindex).
