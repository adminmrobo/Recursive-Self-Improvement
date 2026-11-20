# 표지 지시문 — 스스로 고치는 AI는 어디까지 왔나 (재귀적 자기개선 기초 정리)

- 판: L (글 표지) · 1600×900 · 16:9 · 파일 이름 `cover_rsi.webp` (페이지 `#cover`의 `data-img="cover_rsi"` 자리)
- 그림체: **16비트 RPG 픽셀아트**, 굵은 어두운 외곽선(#1d1a22 계열), 명암 2~3단계, 낮의 연구실(흰 벽·큰 창의 자연광)
- 그림 안에 글자·숫자·로고 넣지 않음 (제목은 페이지가 HTML로 얹음)
- 참고 그림으로 함께 올릴 것: 캐릭터 저장소 `fruitfly-lab-expressions`의 박사·조수·초파리 3면도(k02~k04), 주판봇 v2 기본 표정(E13), 네 식구 단체 사진

## Genspark 등에 붙여 넣는 한국어 지시

16:9 가로 표지, 16비트 RPG 픽셀아트. 햇빛이 드는 하얀 연구실. 화면 오른쪽 절반에 바닥에서 떠 있는 커다란 원형 순환 장치가 있고, 원은 네 구간(보라·초록·주황·파랑)으로 나뉘어 화살표처럼 한 방향으로 돈다. 장치 가운데에는 작은 체크 표시가 달린 계기판(확인 장치)이 붙어 있다. 화면 왼쪽 절반에 연구실 식구 넷이 나란히 서 있다: 박사(얇은 청록 테 사각 안경, 검은 머리에 흰 브릿지 한 줄, 짧은 꽁지머리, 흰 가운 안 검은 조끼와 넥타이)가 순환 장치를 손바닥으로 가리키며 웃고, 조수(긴 분홍 머리에 둥근 번 두 개, 남색 브릿지, 연보라 후드티 위 흰 가운, 청바지)가 클립보드를 들고 계기판 숫자를 확인하고, 주판봇(베이지 상자형 CRT 몸체, 짙은 초록 화면에 민트 픽셀 눈, 주판알 달린 안테나, 무한궤도)이 주판을 들고 신나서 장치를 올려다보고, 초파리 연구원(검은 몸, 빨간 겹눈, 금줄 파란 헬멧, 흰 가운 안 검은 조끼, 검은 장갑, 투명한 날개)이 돋보기로 계기판을 의심스럽게 들여다본다. 키 비율은 박사 1.00, 조수 0.90, 주판봇 0.72, 초파리 0.41. 왼쪽 위에는 제목을 얹을 빈 벽 공간을 남긴다. 글자, 숫자, 로고, 어두운 밤 분위기, 네온은 넣지 않는다.

## English prompt

16:9 wide cover, 16-bit RPG pixel art, bold dark outlines, 2–3 tone shading. A bright daytime laboratory with white walls and large sunlit windows. On the right half, a large floating circular loop machine divided into four arc segments (purple, green, orange, blue) like arrows circulating in one direction, with a small gauge panel bearing a check-mark icon at its center. On the left half, four characters stand in a row: a chibi scientist with thin teal square glasses, black hair with one white streak and a short ponytail, white lab coat over black vest and tie, smiling and gesturing at the machine with an open palm; a young researcher with long pink hair in two round buns with navy streaks, lavender hoodie under a white lab coat, jeans, holding a clipboard and checking the gauge; a beige boxy CRT robot with a dark green screen face and mint pixel eyes, an antenna tipped with abacus beads, crawler treads, holding a wooden abacus and looking up excitedly; a small anthropomorphic fruit fly researcher with black body, red compound eyes, blue helmet with gold stripe, white coat over black vest, black gloves, transparent wings, peering skeptically at the gauge through a magnifying glass. Height ratio scientist 1.00, researcher 0.90, robot 0.72, fruit fly 0.41. Leave empty wall space at upper left for a title. No text, no numbers, no logos, no night scene, no neon.

## 받은 뒤

1. `build_character_pack.py --ingest ./받은그림 --plates cover_rsi=L --out received_rsi`
2. 나온 `Object.assign(SPRITE,{cover_rsi:…})` 조각을 페이지 스크립트 첫 블록 끝에 붙이면 대체 표지가 그림으로 바뀝니다.
3. 공유 미리보기용 `og:image`(cover_rsi.webp)는 같은 그림을 1200×630으로 잘라 저장소에 둡니다.
