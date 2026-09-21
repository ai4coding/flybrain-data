# flybrain-data

브릭셀AI(https://ai4coding.github.io) 의 무료 교육용 블록코딩 확장 「초파리 전뇌 실험실」(Fly Electronic Brain Lab)이 실행 중에 내려받는 초파리 뇌 회로 파일 저장소입니다.
Brain circuit files fetched at run time by the free educational block-coding extension "Fly Electronic Brain Lab" of BrixelAI.

| 파일 | 내용 |
|---|---|
| `manifest.json` | 색인 파일의 위치와 sha256 |
| `v783/index-1.json` | (1판 - 옛 편집기용으로 남겨 둔다) 회로 묶음 목록, 모델 상수, 입력·출력·집단 정의, 전체 뇌 모델과의 일치 검증 결과 |
| `v783/pack-reflex-1.fbz` | 기본 반사 회로 묶음(먹이 반응 · 쓴맛 억제 · 더듬이 닦기). 형식 FBZ1(gzip) |
| `v783/index-2.json` | 색인 2판 - 1판의 내용 전부 + 「움직이는 초파리」 묶음(눈·다가오는 물체 입력, 돌기·걷기·도망 출력). `manifest.json` 이 지금 가리키는 색인 |
| `v783/pack-fly-1.fbz` | 움직이는 초파리 회로 묶음(보기 · 걷기 · 먹기 · 닦기 · 도망). 뉴런 6,442개 |

## 출처와 라이선스 (Source and license)

- 연결지도: FlyWire 공개판 v783 — Dorkenwald et al. 2024, Schlegel et al. 2024 (Nature 634). **CC BY-NC 4.0**
- 모델: Shiu et al. 2024 (Nature 634:210-219), https://github.com/philshiu/Drosophila_brain_model (MIT)
- 원본에서 바꾼 점과 비영리 조건은 [NOTICE.md](NOTICE.md), 라이선스 전문 위치는 [LICENSE](LICENSE) 를 보십시오.
- 이 파일들은 비영리 교육 목적으로만 씁니다. Non-commercial educational use only.
