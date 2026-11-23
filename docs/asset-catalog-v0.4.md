# 채채 에셋 분류·제작 기준 v0.4

갱신일: 2026-11-23

## 관리 원칙

- 파일 ID는 유지하고 설명형 파일명으로 관리합니다. A02를 제외해도 A03 이후 번호를 당기지 않습니다.
- 원본은 master에 그대로 보존하고, 배경·문구를 정리한 합성용 파일은 render에 따로 둡니다.
- asset_manifest.json을 ID, 원본, 렌더 경로의 단일 기준으로 사용합니다.
- neutral은 정색, dejected는 시무룩입니다. M00의 마스터 역할과 이미지 분류는 분리해 기록합니다.

## 활성 목록

| ID | 분류 | master 파일명 | render 파일명 |
|---|---|---|---|
| M00 | 서기 · 정면 · 미소 | chaechae_stand_smile_front_v001.png | chaechae_stand_smile_front_v001.png |
| A01 | 서기 · 정면 · 정색 | chaechae_stand_neutral_front_v001.png | chaechae_stand_neutral_front_v001.png |
| A03 | 서기 · 정면 · 시무룩 | chaechae_stand_dejected_front_v001.png | chaechae_stand_dejected_front_v001.png |
| A04 | 엎드림 · 반정면 · 멍함 | chaechae_prone_blank_threequarter_v001.png | chaechae_prone_blank_threequarter_v001.png |
| A05 | 엎드림 · 반정면 · 개껌 씹기 | chaechae_prone_chewing_threequarter_v001.png | chaechae_prone_chewing_threequarter_v001.png |
| A06 | 엎드림 · 정면에 가까운 반정면 · 잠듦 | chaechae_prone_sleeping_threequarter_v001.png | chaechae_prone_sleeping_threequarter_v001.png |
| A07 | 옆으로 누움 · 측면 · 잠듦 | chaechae_lie_sleeping_side_v001.png | chaechae_lie_sleeping_side_v001.png |
| A08 | 서기 · 왼쪽 측면 · 정색 | chaechae_stand_neutral_left_v001.png | chaechae_stand_neutral_left_v001.png |
| A09 | 앉기 · 왼쪽 측면 · 정색 | chaechae_sit_neutral_left_v001.png | chaechae_sit_neutral_left_v001.png |

A02는 활성 목록과 9개 합계에서 제외했으며, 원본은 assets/characters/chaechae/archive/A02_excluded_v001.png에 보존합니다.

## 렌더 규격

- 경로: assets/characters/chaechae/render/
- 캔버스: 1024×1024 px, RGBA 투명 배경
- 바닥 기준선: y=912 px
- 캐릭터 최대 표시 치수: 820 px
- 흰 페이지 배경과 그림 안 문구 제거
- 원본 master의 승인 그림은 변경하지 않음

A05는 개껌을 씹는 장면이며 개껌을 소품으로 유지합니다. A06은 배를 바닥에 댄 엎드림 수면, A07은 몸을 길게 옆으로 눕힌 수면입니다.

## 디렉터리

- master: assets/characters/chaechae/master/
- render: assets/characters/chaechae/render/
- 제외본: assets/characters/chaechae/archive/
