# 채채 인스타툰 에셋

원본 마스터와 PIL 합성용 렌더를 분리해 보관합니다. 파일 ID(A01, A03 등)는 유지하고 파일명은 자세·시점·표정을 설명합니다.

- 활성 에셋: M00과 A01, A03–A09, 총 9개
- A02: 활성 목록에서 제외, 원본은 archive에 보존
- neutral은 정색, dejected는 시무룩
- M00은 서기·정면·미소 이미지이며 기본 외형·화풍 마스터 역할을 겸함

## 에셋 목록

| ID | 분류 | master 원본 | 합성용 render |
|---|---|---|---|
| M00 | 서기 · 정면 · 미소 | [master](assets/characters/chaechae/master/chaechae_stand_smile_front_v001.png) | [render](assets/characters/chaechae/render/chaechae_stand_smile_front_v001.png) |
| A01 | 서기 · 정면 · 정색 | [master](assets/characters/chaechae/master/chaechae_stand_neutral_front_v001.png) | [render](assets/characters/chaechae/render/chaechae_stand_neutral_front_v001.png) |
| A03 | 서기 · 정면 · 시무룩 | [master](assets/characters/chaechae/master/chaechae_stand_dejected_front_v001.png) | [render](assets/characters/chaechae/render/chaechae_stand_dejected_front_v001.png) |
| A04 | 엎드림 · 반정면 · 멍함 | [master](assets/characters/chaechae/master/chaechae_prone_blank_threequarter_v001.png) | [render](assets/characters/chaechae/render/chaechae_prone_blank_threequarter_v001.png) |
| A05 | 엎드림 · 반정면 · 개껌 씹기 | [master](assets/characters/chaechae/master/chaechae_prone_chewing_threequarter_v001.png) | [render](assets/characters/chaechae/render/chaechae_prone_chewing_threequarter_v001.png) |
| A06 | 엎드림 · 정면에 가까운 반정면 · 잠듦 | [master](assets/characters/chaechae/master/chaechae_prone_sleeping_threequarter_v001.png) | [render](assets/characters/chaechae/render/chaechae_prone_sleeping_threequarter_v001.png) |
| A07 | 옆으로 누움 · 측면 · 잠듦 | [master](assets/characters/chaechae/master/chaechae_lie_sleeping_side_v001.png) | [render](assets/characters/chaechae/render/chaechae_lie_sleeping_side_v001.png) |
| A08 | 서기 · 왼쪽 측면 · 정색 | [master](assets/characters/chaechae/master/chaechae_stand_neutral_left_v001.png) | [render](assets/characters/chaechae/render/chaechae_stand_neutral_left_v001.png) |
| A09 | 앉기 · 왼쪽 측면 · 정색 | [master](assets/characters/chaechae/master/chaechae_sit_neutral_left_v001.png) | [render](assets/characters/chaechae/render/chaechae_sit_neutral_left_v001.png) |

## 경로와 기준

- 원본 master: assets/characters/chaechae/master/
- 합성용 render: assets/characters/chaechae/render/
- 제외 원본: assets/characters/chaechae/archive/A02_excluded_v001.png
- ID·경로 연결의 기준 목록: asset_manifest.json
- 최신 분류와 제작 기준: docs/asset-catalog-v0.4.md

렌더는 흰 배경과 그림 안 문구를 정리하고 1024×1024 RGBA 투명 캔버스에 배치했습니다. 캐릭터 최대 치수는 820px, 바닥 기준선은 y=912px입니다. A05의 개껌은 그림에 포함된 소품이라 보존했습니다.
