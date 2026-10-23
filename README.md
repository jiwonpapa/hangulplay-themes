# 또박토끼 추가 테마

또박토끼 · 한글 따라쓰기의 추가 테마 배포 저장소입니다.

- 기본·우주 탐험·바다 여행: 앱 내장. 인터넷 없이 전환합니다.
- 반짝 할로윈: 앱 0.11.0(code26)부터 설정 → 공통 설정 → 배경과 친구 꾸미기에서 설치합니다.
- 새 그림·의상·팔레트·경로 아이템은 이 저장소의 테마 목록으로 추가합니다. 화면 구성이나 새로운 기능은 앱 업데이트가 필요합니다.

## 배포

앱은 `catalog-v1/catalog.json` Release asset의 ECDSA 서명을 확인합니다. 목록에는 버전 고정 ZIP URL, SHA-256, 크기, 호환 앱 버전, 썸네일이 있습니다. ZIP은 이미지와 JSON만 포함합니다. 학습 기록·아동 정보·앱 코드는 이 저장소로 전송하지 않습니다.

[할로윈 테마 패키지](https://github.com/jiwonpapa/hangulplay-themes/releases/tag/halloween-v1)

설치 중단·통신 실패 시 사용하던 테마를 유지합니다. 설치한 테마는 오프라인으로 전환하고 삭제할 수 있습니다. 내장 테마는 삭제하지 않습니다.

## 파일 계약

ZIP 최상위: `theme.json`, `background.png`, `companions.png`, `trace.png`, `thumbnail.png`, `CREDITS.md`.

- 배경: 중앙 글자와 버튼의 대비를 방해하지 않는 밝은 장식.
- 친구: 토끼·곰·고양이·강아지·펭귄 순서의 동일 너비 5칸 투명 atlas.
- 경로 아이템: 4열 회전 프레임 × 4행 아이템, 정사각형 투명 atlas.
- 팔레트: primary/onPrimary, surface/onSurface, secondary/onSurface, surface/muted 대비4.5 이상.
- 시작점·방향·한글 자형·획 판정·화면 위치는 모든 테마에서 같습니다.

## 제작·사용 범위

2026-10-23 프로젝트 원본 캐릭터에 의상을 입힌 built-in OpenAI ImageGen 결과와 텍스트로 생성한 독립 배경입니다. 경로 아이템은 외부 모델/텍스처 없이 만든 Blender 원본입니다. 사람의 권리 검수 완료를 주장하지 않습니다. 에셋은 또박토끼 앱에서 사용하도록 배포하며, 다른 제품에서의 재사용·재배포에는 별도 허락이 필요합니다. 세부 출처는 패키지의 CREDITS.md를 확인하십시오.
