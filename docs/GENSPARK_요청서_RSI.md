# Genspark 요청서 — 「스스로 고치는 AI는 어디까지 왔나」 표지·만화 (픽셀아트)

## 0. 진행 순서
1. **요청 1(표지)을 먼저** 받아 그림체를 확인합니다.
2. 마음에 들면 그 표지를 **참고 그림으로 함께 올려** 요청 2~5(만화)를 받습니다. 요청 하나 = 만화 한 편 = 4장입니다.
3. 받은 그림은 아래 저장 이름 그대로 한 폴더에 모아 주세요. 페이지에 끼우는 일은 제가 합니다(`--ingest`).

## 1. 매번 함께 올릴 참고 그림 (이 꾸러미의 `refs/`)
| 파일 | 쓰임 |
|---|---|
| `ref_lab4_lineup.png` | 네 식구 단체 사진, 키 비율 기준 |
| `ref_k02_doctor.png` | 박사 3면도 |
| `ref_k03_haru.png` | 조수(하루) 3면도 |
| `ref_k04_fly.png` | 초파리 연구원 3면도 |
| `ref_jupanbot_E13.png` | 주판봇 v2 기본 표정 |

## 2. 모든 요청에 붙이는 공통 문단 (영어 그대로 붙여 넣기)

```
STYLE: 16-bit RPG pixel art, crisp visible pixels, bold dark outlines (#1d1a22), 2–3 tone shading with small highlights. Bright daytime laboratory: white walls, large sunlit windows, soft natural light, small props in lavender, mint and pink. Absolutely NO text, letters, numbers, speech bubbles, logos or UI in the image. No night scene, no neon, no weapons.
CHARACTERS (keep exactly as in the attached references):
- Professor: chibi scientist, thin teal square glasses, black hair with one white streak, short tied-back ponytail, white lab coat over black vest and tie.
- Haru (assistant): long pink hair with two round buns and navy streaks, blue eyes, lavender hoodie under white lab coat, jeans.
- Fruit fly researcher: small anthropomorphic fruit fly, black body, red compound eyes, blue helmet with gold stripe and pink/blue cables, white coat over black vest, black gloves, transparent wings.
- AbaBot: beige boxy CRT robot, dark green screen face with mint pixel eyes and mouth, short antenna tipped with abacus beads, grey segmented arms, two crawler treads, holds a wooden abacus. (NOT a white round-headed robot, no yellow eyes, no coins, does not float.)
Height ratio: Professor 1.00, Haru 0.90, AbaBot 0.72, fruit fly 0.41.
Do not mirror the Professor or Haru (their hair streaks stay on the same side as the references).
```

만화 컷(요청 2~5)에는 공통 문단 뒤에 이것도 붙입니다.
```
COMIC PANEL FORMAT: square 1:1 (1024×1024). Keep the TOP 30% of the image as calm, empty background (wall or sky) — a speech bubble will be placed there later. Characters stand in the lower 70%, full body or from the knees up, large and readable. One panel per image, no panel borders.
```

---

## 요청 1 · 표지 (16:9, 1장)
저장 이름: `cover_rsi.png`

```
[공통 문단]
16:9 wide cover (1600×900). On the right half, a large floating circular loop machine made of four arc segments — purple, green, orange, blue — that flow like arrows in one direction; at its center a small gauge panel with a green check-mark lamp. On the left half the four characters stand in a row: the Professor smiling and presenting the machine with an open palm; Haru holding a clipboard and checking the gauge; AbaBot holding its abacus and looking up excitedly; the fruit fly researcher peering skeptically at the gauge through a magnifying glass. Leave empty white wall space in the upper-left quarter for a title.
```

---

## 요청 2 · 만화 ① 「스스로 고치는 AI?」 (1:1, 4장)
| 저장 이름 | 컷 내용 (말풍선은 페이지가 얹음) |
|---|---|
| `cm1_1.png` | 주판봇이 주판을 머리 위로 번쩍 들고 신나함 |
| `cm1_2.png` | 조수가 땀 흘리며 놀람, 옆에서 주판봇이 눈이 동그래짐 |
| `cm1_3.png` | 초파리 연구원이 돋보기를 들고 책상의 모니터를 의심스럽게 봄 |
| `cm1_4.png` | 박사가 화이트보드의 네 색 순환 그림을 검지로 가리키며 설명 |

```
[공통 문단] [만화 형식 문단]
Make 4 separate square images, one per panel:
1) AbaBot alone, right of center, raising its wooden abacus over its head in triumph, small sparkles, lab bench with colorful test tubes behind.
2) Haru on the left looking shocked with a sweat drop; AbaBot smaller on the right with round surprised eyes.
3) The fruit fly researcher in the center holding up a magnifying glass, suspiciously inspecting a desk monitor that shows a green screen with no text.
4) The Professor on the left, index finger raised, explaining in front of a whiteboard on which a four-color circular arrow loop (purple, green, orange, blue) is drawn — no writing on the board.
```

## 요청 3 · 만화 ② 「제 꼬리를 먹는 데이터」 (1:1, 4장)
| 저장 이름 | 컷 내용 |
|---|---|
| `cm2_1.png` | 주판봇이 자기 화면에서 나오는 종이를 기쁘게 다시 읽음 |
| `cm2_2.png` | 똑같은 모양의 종이 더미가 쌓이고, 주판봇이 상승 그래프를 가리킴 |
| `cm2_3.png` | 조수가 아주 좁은 종 모양 곡선이 그려진 종이를 들고 경악, 주판봇은 땀 |
| `cm2_4.png` | 초파리가 팔짱 끼고 자신만만, 열린 창으로 다양한 색의 데이터 카드가 날아들어 옴 |

```
[공통 문단] [만화 형식 문단]
Make 4 separate square images, one per panel:
1) AbaBot happily printing sheets of paper out of a slot under its screen and feeding them back into a slot on its own side, like reading its own output; a monitor with a rising green line in the background.
2) A tall pile of identical, perfectly uniform plain sheets next to AbaBot, who proudly points at a rising bar chart on a board (no numbers, no text).
3) Haru on the left, shocked, holding up a sheet showing one very narrow, spiky bell-shaped curve; AbaBot on the right with a sweat drop and dotted eyes.
4) The fruit fly researcher in the center, arms crossed, confident with small sparkles; behind it an open window through which many small data cards in different colors and shapes fly into the lab on sunlight.
```

## 요청 4 · 만화 ③ 「촛불과 불에 잘 타는 집」 (1:1, 4장)
| 저장 이름 | 컷 내용 |
|---|---|
| `cm3_1.png` | 한 지붕 두 세대 집 단면, 오른쪽 세대의 주판봇이 촛불을 켜며 흐뭇 |
| `cm3_2.png` | 왼쪽 세대의 초파리가 돋보기로 벽 자재를 살피며 걱정 |
| `cm3_3.png` | 두 세대 모두 촛불이 켜짐, 주판봇은 시큰둥, 초파리는 폭포 눈물 |
| `cm3_4.png` | 연구실 화이트보드 앞에서 박사가 턱을 괴고 고민(물음표) |

```
[공통 문단] [만화 형식 문단]
Make 4 separate square images, one per panel. Panels 1–3 show the same cutaway of a cozy two-unit house (a duplex) under one shared wooden roof, left unit and right unit separated by a thin wall; the walls look like dry, light wood.
1) Right unit: AbaBot contentedly lighting a candle on a small table. Left unit empty, in daylight.
2) Left unit: the fruit fly researcher examining the wooden wall closely with a magnifying glass, looking worried. A candle on AbaBot's side.
3) Both units now have lit candles. AbaBot in the right unit with flat unimpressed eyes and arms crossed; the fruit fly researcher in the left unit crying comic waterfall tears. No fire, no flames on the house — only the candle flames.
4) Back in the bright lab: the Professor on the left with hand on chin and a small question mark above the head, in front of a blank whiteboard.
```

## 요청 5 · 마무리 4컷 (1:1, 4장)
| 저장 이름 | 컷 내용 |
|---|---|
| `cmo_1.png` | 박사가 양손에 보랏빛 불꽃을 띄우고 활짝 웃음 |
| `cmo_2.png` | 초파리가 팔짱 끼고 반짝이며 자신만만 |
| `cmo_3.png` | 주판봇이 점 눈과 땀방울로 머쓱, 뒤에 그래프 모니터 |
| `cmo_4.png` | 조수가 클립보드를 안고 뿌듯하게 미소, 책상 위 모니터 |

```
[공통 문단] [만화 형식 문단]
Make 4 separate square images, one per panel:
1) The Professor on the left, beaming, with small purple magic flames floating above both open palms, lab window behind.
2) The fruit fly researcher in the center, arms crossed, proud, small sparkles, beside a lab bench with test tubes.
3) AbaBot on the right with dotted eyes and a sweat drop, sheepish, next to a monitor showing a green line chart (no text).
4) Haru on the left holding a clipboard to her chest with a proud, satisfied smile, a desk with a monitor on the right.
```

---

## 3. 저장 이름 체크리스트 (17장)
- [ ] cover_rsi.png (16:9)
- [ ] cm1_1 · cm1_2 · cm1_3 · cm1_4 (1:1)
- [ ] cm2_1 · cm2_2 · cm2_3 · cm2_4 (1:1)
- [ ] cm3_1 · cm3_2 · cm3_3 · cm3_4 (1:1)
- [ ] cmo_1 · cmo_2 · cmo_3 · cmo_4 (1:1)

## 4. 받은 그림 점검 (반영 전에 제가 확인)
- 픽셀아트인가(매끈한 일러스트·3D로 나오지 않았나)
- 그림 안에 글자·숫자·말풍선이 없나
- 위쪽 30%가 비어 있나(말풍선 자리)
- 주판봇이 옛 Money-Robo(흰 둥근 머리·노란 눈·금화)로 나오지 않았나
- 박사·조수 브릿지 방향이 참고 그림과 같은가
- 낮 분위기인가(밤·네온 아님)

어긋난 컷은 "기존 그림 + 참고 그림 첨부, 표정(또는 그 부분)만 편집"으로 다시 요청하면 됩니다.
