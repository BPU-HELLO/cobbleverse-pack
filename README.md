# cobbleverse-pack

코블버스 서버 모드팩 (Prism Launcher + packwiz 자동 업데이트)

- Prism Launcher에서 실행할 때마다 `pack.toml`을 읽어 모드·설정을 자동으로 맞춥니다.
- 모드 대부분은 Modrinth 공식 링크에서 받습니다 (`mods/*.pw.toml`).
- 직접 넣은 파일:
  - `mods/cobbleplus-*.jar` — 코블플러스 (이 서버 전용 모드)
  - `mods/cobblemon-battle-positions-1.1.3.jar` — MIT, 원본: https://github.com/ramen/cobblemon-battle-positions
  - `mods/PastureLoot-fabric-2.0.0+1.21.1.jar` — AGPL-3.0, 원본·소스: https://github.com/dremixam/CobblemonPastureLoot
- `config/`, `options.txt`, `servers.dat`는 처음 설치할 때만 넣고, 그 뒤엔 각자 바꾼 설정을 덮어쓰지 않습니다.
