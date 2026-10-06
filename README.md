# ChunkFlow 공개 사이트

이 저장소는 배포용입니다. 직접 고치지 마세요.

- 플레이어: https://jinhoofkepco.github.io/chunkflow/
- `index.html` — 플레이어(소스 저장소의 `npm run deploy:player`가 갱신)
- `lessons/current.json` — 주소만 치면 열리는 최신 문장 목록(`npm run publish`가 갱신)
- `lessons/<id>.json` — `?lesson=<id>`로 여는 목록, `lessons/index.json` — 게시 기록(최신순)
