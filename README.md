# 스스로 고치는 AI는 어디까지 왔나 — 재귀적 자기개선(RSI) 기초 정리

연구실 식구(박사 · 조수 하루 · 초파리 연구원 · 주판봇)와 함께 **재귀적 자기개선(Recursive Self-Improvement, RSI)**을 처음 접하는 분을 위해 정리한 해설 페이지입니다. 문헌 10편을 자료로 삼아, 움직이는 대시보드 6개와 4컷 만화로 읽습니다.

**페이지 보기:** https://adminmrobo.github.io/Recursive-Self-Improvement/

## 이 페이지가 다루는 것

| 단계 | 질문 | 직접 만지는 것 |
|---|---|---|
| ① 고친 내가 또 나를 고친다 | 자기개선이라는 순환은 무엇인가 | 순환 시뮬레이터 — 잰 점수 vs 진짜 점수 |
| ② 확실할 때만 고칠까, 해 보고 고를까 | 증명 대신 실험으로 고르면 무엇이 달라지나 | 성능 지형 탐색 — 한 줄 오르기 vs 보관소 |
| ③ 머릿속, 업무 매뉴얼, 조직 | AI는 무엇을 고치나 | RSI 연구 지도 |
| ④ 누가 채점하나 | 확인 신호가 약하면 무슨 일이 생기나 | 모델 붕괴 실험실 |
| ⑤ 고치다 망가뜨리지 않으려면 | 얻은 것과 잃은 것을 따로 세면 | 수정 심사실 |
| 대결 · 버튼 게임 · AI 판단 코너 | 자기 데이터만으로 버틸까, 모두가 누르면, AI 요약은 맞을까 | 대결, 이익표, 요약 카드 5장 |

한 줄 요약: 지금까지의 자기개선 성과는 **확인 신호가 강한 곳에서만** 나왔고, 규모가 큰 사례일수록 사람이 승인 단계를 쥐고 있으며, RSI의 위험은 아직 이해되지 않았습니다.

## 자료로 쓴 문헌
1. Good (1965), Speculations Concerning the First Ultraintelligent Machine
2. Schmidhuber (2003), Gödel Machines — arXiv:cs/0309048
3. Zelikman 외 (2022), STaR — NeurIPS 2022
4. Chen 외 (2026), Recursive Self-Improvement in AI — arXiv:2607.07663 (프리프린트)
5. Zhang 외 (2025), Darwin Gödel Machine — ICLR 2026
6. Shumailov 외 (2024), AI models collapse when trained on recursively generated data — *Nature* 631
7. Yuan 외 (2024), Self-Rewarding Language Models — ICML 2024
8. SII & Xinxu AI (2026), No Second Run — arXiv:2611.10719 (프리프린트)
9. Zhang 외 (2026), GUARD — arXiv:2611.23476 (프리프린트)
10. Conitzer (2026), Is Recursive Self-Improvement Safe? — arXiv:2611.10261 (프리프린트)

대시보드의 그래프와 숫자는 모두 설명용 모형 값입니다(시드 고정). "논문 수치"라고 표시한 값만 원문 그대로입니다.

## 저장소 구성

| 경로 | 내용 |
|---|---|
| `index.html` | 해설 페이지 (단일 파일, 외부 요청은 글꼴 하나) |
| `kg/` | 지식 색인·온톨로지 원본 (`kg.json`, `refs.json`, `meta.json`, 점검 보고서) |
| `docs/` | 표지 지시문, 이미지 명세서, Genspark 요청서 (16비트 픽셀아트) |
| `cover_manifest.json` | 표지·장면 그림 목록 ([ahnboat lab 이미지 표지 현황](https://adminmrobo.github.io/ahnboat_lab_cover_status/)이 읽음) |

## 그림
지금은 대체 표지와 캐릭터 팩 표정 그림으로 만든 4컷 만화를 씁니다. 픽셀아트 표지 1장과 만화 16컷은 `docs/GENSPARK_요청서_RSI.md`로 제작 중입니다.

---

글 · 안상선 ((주)M-Robo 대표) · https://adminmrobo.github.io/who_am_i/who_am_i.html

캐릭터 이름·설정·그림(박사, 조수 하루, 초파리 연구원, 주판봇)의 저작권은 안상선에게 있으며 허락 없이 사용할 수 없습니다. 이 페이지는 교육용 해설이며 투자 판단이나 정책 권고가 아닙니다.
