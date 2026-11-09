# SPEAK·PATTERN — 여행·학회 상황별 패턴 영어 학습 체계 v1.0

> 상황 **3,092개** · 고유 영어 표현 **3,029개** · 학습 패턴 **114개**(11개 계열) · 카테고리 **49개** · 핵심(★) **296개**  
> 데이터 원본: `speak_pattern_situations.csv`, `speak_pattern_patterns.csv`, `speak_pattern_data.json` (HTML 학습 사이트용)

## 목차

- [Part 0. 학습 설계와 사용법](#part-0-학습-설계와-사용법)
- [패턴 카탈로그](#패턴-카탈로그)
- Part 1. 공통 의사소통 기반
  - `U-REP` 의사소통 수리 — 못 알아들었을 때 (59)
  - `U-BAS` 인사·사과·감사·말 걸기 (43)
  - `U-NUM` 숫자·시간·날짜·위치 확인 (34)
  - `U-EXP` 선택·허락·상태 표현 (50)
- Part 2. 여행 영어
  - `T-AIR1` 공항 출국 — 체크인·수하물 (80)
  - `T-AIR2` 보안검색·면세·라운지·탑승 (69)
  - `T-FLT` 기내 (73)
  - `T-ARR` 입국심사·세관·수하물 찾기 (77)
  - `T-TRN` 기차·장거리 열차 (91)
  - `T-MET` 지하철·S반·버스·트램 (75)
  - `T-TAX` 택시·라이드셰어·공항 이동 (66)
  - `T-CAR` 렌터카·운전 (43)
  - `T-DIR` 길 묻기·위치 찾기 (61)
  - `T-HTL1` 호텔 체크인·체크아웃 (74)
  - `T-HTL2` 호텔 생활·문제 해결 (75)
  - `T-RST1` 레스토랑 예약·입장·주문 (95)
  - `T-RST2` 계산·문제·식이 제한 (60)
  - `T-CAF` 카페·베이커리·바 (54)
  - `T-SHP` 쇼핑·면세·환불 (77)
  - `T-SGT` 관광·박물관·공연·투어 (72)
  - `T-MON` 환전·ATM·결제 (44)
  - `T-COM` 통신·SIM·와이파이·충전 (41)
  - `T-MED` 약국·병원·응급 (81)
  - `T-TRB` 분실·도난·사고·항공 지연 (67)
  - `T-SOC` 여행지 스몰토크·현지인 대화 (55)
  - `T-SVC` 우체국·세탁·미용·생활 서비스 (35)
- Part 3. 학회·연구 활동 영어
  - `C-REG` 학회 등록·배지·장소 안내 (60)
  - `C-NET` 네트워킹 — 첫인사·자기소개 (91)
  - `C-SML` 학회 스몰토크 (61)
  - `C-PRE1` 발표 시작·기술 점검 (57)
  - `C-PRE2` 발표 본론 — 방법·흐름 설명 (84)
  - `C-PRE3` 결과·데이터·통계 설명 (86)
  - `C-PRE4` 한계·결론·마무리 (48)
  - `C-QA1` 질문 받기·답변하기 (81)
  - `C-QA2` 어려운 질문·비판 대응 (62)
  - `C-ASK` 청중으로서 질문하기 (74)
  - `C-PST` 포스터 세션 (67)
  - `C-CHR` 좌장·세션 진행 (56)
  - `C-DSC` 연구 방법론·전문 토론 (102)
  - `C-AGR` 동의·반대·의견 표현 (57)
  - `C-COL` 공동연구·후속 협력 (63)
  - `C-MTG` 미팅·온라인 회의 (72)
  - `C-EML` 이메일·메시지 (90)
  - `C-DIN` 만찬·리셉션 (58)
  - `C-VST` 기관 방문·시설 견학 (48)
  - `C-ONL` 온라인·하이브리드 발표 (38)
  - `C-PUB` 논문·심사·출판 관련 대화 (38)
  - `C-PNL` 패널 토론 참여 (27)
  - `C-ADM` 출장 행정·증빙·정산 (21)
- [부록 A. 핵심(★) 표현 압축 목록](#부록-a-핵심-표현-압축-목록)
- [부록 B. 패턴 × 카테고리 교차 색인](#부록-b-패턴--카테고리-교차-색인)
- [부록 C. 데이터 스키마와 검증 기록](#부록-c-데이터-스키마와-검증-기록)

---

## Part 0. 학습 설계와 사용법

### 0.1 문제 인식 — 왜 '상황 × 패턴'인가

출장에서 실제로 입 밖에 내야 했던 영어는 생각보다 종류가 적고, 같은 문형이 장소만 바꿔 반복된다는 관찰은 응용언어학의 어휘 접근법(Lexical Approach)이 설명하는 현상과 일치한다. Pawley와 Syder(1983)는 모국어 화자의 유창성이 문법 규칙을 매번 조합하는 능력보다 미리 저장된 수많은 '기성 문장 덩어리'를 꺼내 쓰는 능력에서 나온다고 지적했고, Wray(2002)는 이러한 정형화된 연쇄(formulaic sequences)가 처리 부담을 줄여 실시간 발화를 가능하게 한다는 점을 체계화했다. Lewis(1993)는 이를 교수법으로 옮겨 단어나 문법보다 '덩어리(chunk)' 단위의 입력과 연습을 중심에 둘 것을 제안했다. 실증 측면에서는 Boers 등(2006)이 정형화된 표현을 의식적으로 학습한 집단이 구술 평가에서 더 유창하다고 판정받았음을 보고했다.

이 문서는 그 원리를 두 축으로 구현한다. 첫째 축은 **상황**이다. 공항 체크인, 열차 환승, 포스터 앞 설명처럼 실제로 마주칠 장면을 3,000개 이상 열거하여 '언제 무엇을 말해야 하는가'를 구체화했다. 둘째 축은 **패턴**이다. 114개의 문형 틀(예: *Could I get ___?*, *Do I need to ___?*, *I see what you mean, but ___*)로 모든 상황을 다시 묶어, 한 패턴을 익히면 수십 개 장면이 동시에 해결되도록 설계했다. 제2외국어 학습자가 수천 개 문장을 각각 외우는 것은 비현실적이지만, 수십 개의 고빈도 틀과 그 틀에 끼울 상황 어휘를 익히는 것은 충분히 가능하다는 것이 이 구조의 전제이다.

표현 선정에서는 패턴에 맞추기 위해 억지로 만든 문장을 배제하고, 원어민이 해당 장면에서 실제로 쓰는 구어체 형태(예: *Could we get the check?*, *I'm good, thanks.*, *Mind if I join you?*)를 우선했다. 패턴으로 분해하면 오히려 부자연스러워지는 표현(*Keep the change.*, *Here you go.*, 수치 읽기 문장 등)은 억지로 패턴에 넣지 않고 **Z00 고정 표현**으로 분리했다. 이 범주가 전체의 상당 부분을 차지하는 것은 실제 언어 사용의 특성을 반영한 결과이다.

### 0.2 문서 구조

문서는 영역(Part) → 카테고리 → 패턴 블록 → 개별 상황의 4층 구조를 가진다. Part 1은 장소와 무관하게 모든 대화의 바탕이 되는 의사소통 수리·인사·숫자 확인·선택 표현을 다루고, Part 2는 출국부터 귀국까지 여행 동선을 따라, Part 3은 학회 등록에서 논문 심사 대응·출장 정산까지 연구 활동 전반을 카테고리로 나눈다. 각 카테고리 안에서는 같은 패턴을 쓰는 상황끼리 모아 보여주므로, 패턴 블록 하나를 읽는 것이 곧 '이 틀을 이 장소에서 어떻게 쓰는가'를 익히는 과정이 된다. 예시 장소는 이번 출장지인 베를린(ERPW 2026)을 기준으로 했으나, 표현 자체는 유럽 어느 도시에서나 그대로 통용된다.

### 0.3 표기 규칙

각 줄은 `- ★ **영어 표현** — 한국어 상황 설명 ID` 형식이다. ★는 해당 카테고리에서 가장 먼저 입에 붙여야 할 핵심 표현이며 전체의 약 10%로 제한했다. ID는 `영역-카테고리-일련번호`(예: `T-AIR1-004`) 규칙을 따르며, HTML 학습 사이트에서 진도 관리와 즐겨찾기의 키로 그대로 사용할 수 있다. 패턴 블록 제목의 `A01`, `F05` 등은 패턴 카탈로그의 ID와 대응한다. 미국식과 영국식이 갈리는 경우(check/bill, restroom/toilets, line/queue)는 상황 설명에 병기했으며, 유럽 현지에서는 두 형태 모두 통용된다.

### 0.4 학습 경로

학습은 네 단계로 진행할 것을 권한다. **1단계(생존 기반)**에서는 Part 1 전체와 패턴 카탈로그의 A(요청)·B(질문)·D(수리) 계열을 익힌다. 이 세 계열만으로도 여행 상황의 대부분이 처리되며, 특히 D 계열은 '못 알아들었을 때 대화를 살려내는' 기술이므로 제2외국어 사용자에게 투자 대비 효과가 가장 크다. **2단계(여행 동선)**에서는 Part 2를 실제 이동 순서(AIR1 → AIR2 → FLT → ARR → MET/TAX → HTL1 → RST1 …)대로 ★ 표현 위주로 훑고, 출국 직전에는 부록 A만 반복한다. **3단계(발표자 트랙)**에서는 PRE1–PRE4, QA1–QA2, PST, ONL을 집중 학습한다. 특히 F05(헤징)와 F11(정중한 반대)은 학회 영어의 품격을 좌우하는 패턴이다. **4단계(관계 구축)**에서는 NET, SML, DSC, AGR, COL, EML, DIN, PNL을 통해 학회 밖으로 이어지는 협력 관계를 다룬다.

### 0.5 학습 방법

한 패턴 블록을 학습하는 표준 루틴은 네 단계로 구성된다. 먼저 패턴 카탈로그에서 틀과 기능을 확인하고(인지), 블록 안의 예문을 소리 내어 읽으며 빈칸에 들어가는 말이 어떻게 바뀌는지 관찰한다(대체 연습). 다음으로 영어를 가리고 한국어 상황 설명만 본 채 영어를 직접 산출해 본다(인출 연습). Karpicke와 Roediger(2008)는 반복해서 읽는 것보다 기억에서 꺼내려는 시도 자체가 장기 기억을 훨씬 강하게 만든다는 것을 보였으므로, 이 단계를 생략하지 않는 것이 핵심이다. 마지막으로 틀린 항목만 모아 하루, 사흘, 일주일 간격으로 다시 시도한다(간격 반복). 분산 학습의 효과는 Cepeda 등(2006)의 메타분석에서 일관되게 확인되었다.

실전에서는 세 가지 원칙만 기억해도 충분하다. 첫째, 긴 문장을 만들려 하지 말고 짧은 틀 하나에 please를 붙인다. 둘째, 이해가 안 되면 추측하지 말고 D 계열로 즉시 되묻는다. 셋째, 숫자·시각·장소·금액은 반드시 D03(*Just to confirm, …?*)으로 되짚는다. 출장 중 발생하는 실질적 문제의 대부분은 문법 오류가 아니라 숫자와 장소를 잘못 알아들은 데서 생긴다.

**참고문헌**

- Boers, F., Eyckmans, J., Kappel, J., Stengers, H., & Demecheleer, M. (2006). Formulaic sequences and perceived oral proficiency: Putting a Lexical Approach to the test. *Language Teaching Research*, 10(3), 245–261.
- Cepeda, N. J., Pashler, H., Vul, E., Wixted, J. T., & Rohrer, D. (2006). Distributed practice in verbal recall tasks: A review and quantitative synthesis. *Psychological Bulletin*, 132(3), 354–380.
- Karpicke, J. D., & Roediger, H. L. (2008). The critical importance of retrieval for learning. *Science*, 319(5865), 966–968.
- Lewis, M. (1993). *The Lexical Approach: The State of ELT and a Way Forward*. Hove: Language Teaching Publications.
- Pawley, A., & Syder, F. H. (1983). Two puzzles for linguistic theory: Nativelike selection and nativelike fluency. In J. C. Richards & R. W. Schmidt (Eds.), *Language and Communication* (pp. 191–226). London: Longman.
- Wray, A. (2002). *Formulaic Language and the Lexicon*. Cambridge: Cambridge University Press.


### 0.6 카테고리별 분량

| 영역 | 코드 | 카테고리 | 상황 수 | ★ |
|---|---|---|---:|---:|
| U | REP | 의사소통 수리 — 못 알아들었을 때 | 59 | 12 |
| U | BAS | 인사·사과·감사·말 걸기 | 43 | 7 |
| U | NUM | 숫자·시간·날짜·위치 확인 | 34 | 4 |
| U | EXP | 선택·허락·상태 표현 | 50 | 8 |
| T | AIR1 | 공항 출국 — 체크인·수하물 | 80 | 8 |
| T | AIR2 | 보안검색·면세·라운지·탑승 | 69 | 5 |
| T | FLT | 기내 | 73 | 7 |
| T | ARR | 입국심사·세관·수하물 찾기 | 77 | 8 |
| T | TRN | 기차·장거리 열차 | 91 | 9 |
| T | MET | 지하철·S반·버스·트램 | 75 | 10 |
| T | TAX | 택시·라이드셰어·공항 이동 | 66 | 6 |
| T | CAR | 렌터카·운전 | 43 | 2 |
| T | DIR | 길 묻기·위치 찾기 | 61 | 3 |
| T | HTL1 | 호텔 체크인·체크아웃 | 74 | 10 |
| T | HTL2 | 호텔 생활·문제 해결 | 75 | 3 |
| T | RST1 | 레스토랑 예약·입장·주문 | 95 | 12 |
| T | RST2 | 계산·문제·식이 제한 | 60 | 9 |
| T | CAF | 카페·베이커리·바 | 54 | 3 |
| T | SHP | 쇼핑·면세·환불 | 77 | 14 |
| T | SGT | 관광·박물관·공연·투어 | 72 | 4 |
| T | MON | 환전·ATM·결제 | 44 | 4 |
| T | COM | 통신·SIM·와이파이·충전 | 41 | 3 |
| T | MED | 약국·병원·응급 | 81 | 9 |
| T | TRB | 분실·도난·사고·항공 지연 | 67 | 9 |
| T | SOC | 여행지 스몰토크·현지인 대화 | 55 | 5 |
| C | REG | 학회 등록·배지·장소 안내 | 60 | 6 |
| C | NET | 네트워킹 — 첫인사·자기소개 | 91 | 12 |
| C | SML | 학회 스몰토크 | 61 | 3 |
| C | PRE1 | 발표 시작·기술 점검 | 57 | 5 |
| C | PRE2 | 발표 본론 — 방법·흐름 설명 | 84 | 8 |
| C | PRE3 | 결과·데이터·통계 설명 | 86 | 7 |
| C | PRE4 | 한계·결론·마무리 | 48 | 5 |
| C | QA1 | 질문 받기·답변하기 | 81 | 9 |
| C | QA2 | 어려운 질문·비판 대응 | 62 | 4 |
| C | ASK | 청중으로서 질문하기 | 74 | 8 |
| C | PST | 포스터 세션 | 67 | 3 |
| C | CHR | 좌장·세션 진행 | 56 | 6 |
| C | DSC | 연구 방법론·전문 토론 | 102 | 7 |
| C | AGR | 동의·반대·의견 표현 | 57 | 4 |
| C | COL | 공동연구·후속 협력 | 63 | 4 |
| C | MTG | 미팅·온라인 회의 | 72 | 9 |
| C | EML | 이메일·메시지 | 90 | 10 |
| C | DIN | 만찬·리셉션 | 58 | 2 |
| C | VST | 기관 방문·시설 견학 | 48 | 3 |
| C | ONL | 온라인·하이브리드 발표 | 38 | 2 |
| C | PUB | 논문·심사·출판 관련 대화 | 38 | 1 |
| T | SVC | 우체국·세탁·미용·생활 서비스 | 35 | 2 |
| C | PNL | 패널 토론 참여 | 27 | 1 |
| C | ADM | 출장 행정·증빙·정산 | 21 | 1 |
| **합계** | | U 186 · T 1465 · C 1441 | **3092** | **296** |

---

## 패턴 카탈로그

각 패턴은 '틀(template)'과 '기능'으로 정의되며, 수록 수는 본문에서 해당 패턴으로 실현된 상황의 개수이다. Z00은 패턴으로 분해하지 않고 통째로 기억하는 고정 표현(chunk)을 모은 범주이다.

### A. 요청·부탁 (Requests)

| ID | 패턴 | 기능 | 사용 메모 | 수록 |
|---|---|---|---|---:|
| A01 | **Could I get ___? / Can I have ___?** | 물건·서비스 요청 (가장 범용) | 식당·카페·호텔·기내 어디서나 통한다. 'Give me'는 명령으로 들린다. 정중도는 Could > Can. | 90 |
| A02 | **Could you ___ (for me)?** | 상대에게 행동을 부탁 | Can you보다 부드럽다. 끝에 please를 붙이면 충분히 정중하다. | 127 |
| A03 | **Would you mind ___ing?** | 부담이 있는 부탁 | 'No, not at all'이 수락이라는 점에 주의(부정으로 답해야 OK). | 3 |
| A04 | **I'd like (to) ___** | 원하는 것을 정중히 밝힘 | 예약·주문·변경·취소 등 서비스 창구의 기본 문형. | 44 |
| A05 | **___, please.** | 최소 단위 요청 | 매표·주문처럼 맥락이 분명하면 명사+please만으로 충분하다. | 12 |
| A06 | **Would it be possible to ___? / Is it possible to ___?** | 규정 밖·예외 요청 | 업그레이드, 시간 변경, 기한 연장 등 상대 재량이 필요한 부탁. | 38 |
| A07 | **I was wondering if ___** | 매우 조심스러운 부탁 | 처음 보는 연구자·이메일에서 부담을 낮춘다. 과거진행형이 정중함을 만든다. | 10 |
| A08 | **I need (to) ___** | 필요를 직접 밝힘 | 급할 때 가장 명확하다. 정중도는 낮으므로 사정 설명과 함께 쓴다. | 22 |
| A09 | **Can I ___? / Is it okay if I ___?** | 허락 구하기 | 사진 촬영·좌석·결제수단 등 가능 여부 확인. | 49 |
| A10 | **Do you mind if I ___?** | 상대를 배려한 허락 | 'No, go ahead'가 허락이다. | 14 |
| A11 | **I'll have ___ / I'll take ___** | 주문·구매 확정 | have는 음식·음료, take는 물건·선택지에 자연스럽다. | 19 |
| A12 | **I'd prefer ___ / I'd rather ___** | 선호 표현 | rather 뒤에는 동사원형. 선택지를 좁힐 때 유용. | 12 |
| A13 | **Could you help me with ___?** | 도움 요청 | with 뒤에 명사. 기계·짐·서류 등. | 4 |
| A14 | **I'm looking for ___** | 찾는 물건·장소 설명 | 쇼핑·길찾기에서 대화를 여는 표준 문형. | 8 |

### B. 정보 묻기 (Questions)

| ID | 패턴 | 기능 | 사용 메모 | 수록 |
|---|---|---|---|---:|
| B01 | **Where is ___? / Where can I ___?** | 위치 묻기 | Where can I ~?는 '어디서 ~할 수 있나'로 활용 범위가 넓다. | 82 |
| B02 | **How do I get to ___? / How do I ___?** | 경로·사용법 묻기 | 기계·앱·절차 사용법에도 그대로 쓴다. | 28 |
| B03 | **Is there ___ (around here)?** | 존재 여부 | nearby, around here를 붙이면 근처. | 91 |
| B04 | **Do you have ___?** | 보유·재고 여부 | 가게·호텔·약국에서 가장 자주 쓰는 질문. | 49 |
| B05 | **What time ___? / When ___?** | 시각·시점 |  | 58 |
| B06 | **How long ___?** | 소요 시간·기간 |  | 45 |
| B07 | **How much ___?** | 가격·양 |  | 50 |
| B08 | **Which ___?** | 선택지 중 특정 | 플랫폼·게이트·노선·출구. | 23 |
| B09 | **Is this ___? / Does this ___?** | 예·아니오 확인 | Does this go to ~?는 교통의 핵심 문장. | 162 |
| B10 | **Do I need to ___? / Do I have to ___?** | 의무·필요 여부 |  | 93 |
| B11 | **Is ___ included? / Does it come with ___?** | 포함 여부 |  | 39 |
| B12 | **What do you recommend? / Can you recommend ___?** | 추천 요청 |  | 26 |
| B13 | **Do you know ___? / Do you happen to know ___?** | 정보 보유 여부 | happen to를 넣으면 더 부드럽다. | 14 |
| B14 | **Could you tell me ___?** | 간접 의문 (정중) | 어순 주의: Could you tell me where the gate is? | 6 |
| B15 | **What's the ___?** | 정보 항목 묻기 | 와이파이 비밀번호, 환율, 응급번호 등. | 49 |
| B16 | **What if ___? / What happens if ___?** | 조건·예외 상황 |  | 10 |

### C. 상황 설명·문제 제기 (Stating)

| ID | 패턴 | 기능 | 사용 메모 | 수록 |
|---|---|---|---|---:|
| C01 | **I have a reservation ___ / I booked ___** | 예약 사실 제시 | under + 이름. | 9 |
| C02 | **I'm here for ___ / I'm here to ___** | 방문 목적 | 입국심사·등록대·리셉션. | 10 |
| C03 | **I'm heading to ___** | 목적지·이동 중 |  | 2 |
| C04 | **There's a problem with ___ / ___ isn't working** | 고장·문제 신고 |  | 57 |
| C05 | **I think there's a mistake ___** | 오류 지적 (완곡) | I think로 시작해 공격적으로 들리지 않게 한다. | 22 |
| C06 | **I lost ___ / I can't find ___ / I left ___** | 분실 | left는 '어딘가에 두고 왔다'. | 20 |
| C07 | **I have ___ / I feel ___** | 증상·상태 |  | 32 |
| C08 | **I've been ___ since / for ___** | 지속 기간 | 현재완료(진행). since + 시점, for + 기간. | 4 |
| C09 | **It's my first time ___** | 처음임을 밝힘 | 도움과 설명을 이끌어내는 좋은 신호. | 2 |
| C10 | **I'm afraid ___** | 나쁜 소식·거절의 완곡 |  | 12 |
| C11 | **I don't eat ___ / I'm allergic to ___** | 식이 제한 |  | 11 |
| C12 | **I'm just ___** | 가벼운 상태 설명 | just looking, just checking. | 6 |
| C13 | **I'm running late / I missed ___** | 지연·놓침 |  | 13 |
| C14 | **I was told ___** | 근거 제시 | 다른 직원·안내문 내용을 근거로 삼을 때. | 5 |

### D. 의사소통 수리 (Repair)

| ID | 패턴 | 기능 | 사용 메모 | 수록 |
|---|---|---|---|---:|
| D01 | **Sorry, could you say that again?** | 반복 요청 |  | 22 |
| D02 | **Sorry, I didn't catch ___** | 못 들었음 |  | 14 |
| D03 | **Just to confirm, ___? / Just to make sure ___** | 확인 | 숫자·시간·장소는 반드시 이 패턴으로 되짚는다. | 23 |
| D04 | **What does ___ mean? / What do you mean by ___?** | 의미 확인 |  | 19 |
| D05 | **Could you speak more slowly / write it down?** | 전달 방식 변경 요청 |  | 10 |
| D06 | **So you mean ___? / Do you mean ___?** | 이해 확인 (되묻기) |  | 28 |
| D07 | **Let me ___** | 시간 벌기·행동 예고 | Let me check / think / see. | 12 |
| D08 | **How do you say ___? / What do you call ___?** | 어휘·발음 묻기 |  | 8 |

### E. 사교·반응 (Social)

| ID | 패턴 | 기능 | 사용 메모 | 수록 |
|---|---|---|---|---:|
| E01 | **Nice to meet you / Good to see you** | 인사 | 처음은 meet, 재회는 see. | 7 |
| E02 | **What brings you ___? / Are you here for ___?** | 방문 목적 묻기 |  | 8 |
| E03 | **How's ___ going? / How was ___?** | 안부·경험 |  | 13 |
| E04 | **Where are you ___?** | 출신·소속·숙소 | from / based / staying. | 10 |
| E05 | **That sounds ___ / That's ___** | 반응·맞장구 |  | 33 |
| E06 | **Have you ___? / Have you been to ___?** | 경험 묻기 |  | 11 |
| E07 | **Thanks for ___** | 감사 | for + 명사/동명사. | 23 |
| E08 | **Sorry about ___ / Sorry to ___** | 사과 |  | 10 |
| E09 | **Excuse me, ___** | 말 걸기 |  | 15 |
| E10 | **How about ___? / Shall we ___? / Why don't we ___?** | 제안 |  | 15 |
| E11 | **It was great ___ / Have a ___** | 작별 |  | 18 |
| E12 | **I'm ___ / I work for ___** | 자기소개 |  | 15 |
| E13 | **I really enjoyed ___ / I loved ___** | 칭찬 |  | 9 |

### F. 연구 소개·토론 (Research talk)

| ID | 패턴 | 기능 | 사용 메모 | 수록 |
|---|---|---|---|---:|
| F01 | **I work on ___ / My research focuses on ___** | 연구 분야 소개 | work on=주제, work in=분야, work at/for=기관. | 7 |
| F02 | **We're currently ___ing** | 진행 상황 |  | 6 |
| F03 | **We used ___ to ___** | 방법 설명 |  | 20 |
| F04 | **We found that ___ / The main finding is ___** | 결과 제시 |  | 9 |
| F05 | **The results suggest ___ / It seems that ___** | 헤징 (단정 회피) | 학회 영어의 핵심. prove 대신 suggest, indicate. | 28 |
| F06 | **Compared with ___ / ___ performed better than ___** | 비교 |  | 15 |
| F07 | **One limitation is ___** | 한계 인정 |  | 17 |
| F08 | **One possible explanation is ___ / This might be due to ___** | 해석·원인 추정 |  | 10 |
| F09 | **In future work, we plan to ___ / Next, we'd like to ___** | 향후 계획 |  | 10 |
| F10 | **I agree ___ / That's a good point** | 동의 |  | 13 |
| F11 | **I see what you mean, but ___** | 정중한 반대 |  | 22 |
| F12 | **It would be interesting to ___ / I wonder whether ___** | 제안·호기심 |  | 14 |
| F13 | **How did you ___?** | 방법 질문 |  | 22 |
| F14 | **Did you consider ___? / Have you tried ___?** | 대안 제시형 질문 |  | 15 |
| F15 | **Could you say more about ___?** | 부연 요청 |  | 6 |
| F16 | **In our case, ___** | 자기 맥락 비교 |  | 16 |
| F17 | **This is based on ___** | 근거·출처 |  | 7 |

### G. 발표 진행 (Presenting)

| ID | 패턴 | 기능 | 사용 메모 | 수록 |
|---|---|---|---|---:|
| G01 | **Today I'd like to ___** | 발표 도입 |  | 6 |
| G02 | **Let me start with ___ / First, ___** | 시작·순서 |  | 7 |
| G03 | **Let's move on to ___ / Next, ___** | 전환 |  | 9 |
| G04 | **This slide shows ___ / As you can see, ___** | 시각자료 설명 |  | 29 |
| G05 | **What this means is ___ / The key point here is ___** | 의미 해석 |  | 18 |
| G06 | **As I mentioned ___ / Let me go back to ___** | 되돌아가기·연결 |  | 7 |
| G07 | **To sum up ___ / The take-home message is ___** | 요약·결론 |  | 7 |
| G08 | **Can everyone ___? / Is ___ working?** | 기술 점검 |  | 13 |
| G09 | **I'm running short on time, so ___** | 시간 관리 |  | 6 |

### H. 질의응답 (Q&A)

| ID | 패턴 | 기능 | 사용 메모 | 수록 |
|---|---|---|---|---:|
| H01 | **That's a good question / Thanks for the question** | 답변 도입 |  | 6 |
| H02 | **If I understand correctly, ___** | 질문 재확인 |  | 6 |
| H03 | **I'm not sure, but ___ / I don't have ___, but ___** | 모를 때 |  | 5 |
| H04 | **That's outside the scope of ___** | 범위 밖 |  | 4 |
| H05 | **I'd be happy to ___** | 후속 제안 |  | 4 |
| H06 | **I have a question about ___ / My question is ___** | 질문하기 |  | 9 |
| H07 | **Does that answer your question?** | 답변 마무리 |  | 4 |
| H08 | **Can I just add ___? / If I may, ___** | 끼어들기·보충 |  | 7 |

### J. 좌장·회의·협력 (Chairing & Collaboration)

| ID | 패턴 | 기능 | 사용 메모 | 수록 |
|---|---|---|---|---:|
| J01 | **Our next speaker is ___** | 연사 소개 |  | 3 |
| J02 | **We have time for ___** | 시간 안내 |  | 5 |
| J03 | **Let's ___ (진행)** | 진행 지시 |  | 13 |
| J04 | **Could we ___? / Can we ___?** | 일정·회의 제안 |  | 6 |
| J05 | **Would you be interested in ___?** | 협력 제안 |  | 11 |
| J06 | **I'll ___ (send / follow up)** | 후속 약속 |  | 11 |

### K. 이메일·서면 (Writing)

| ID | 패턴 | 기능 | 사용 메모 | 수록 |
|---|---|---|---|---:|
| K01 | **I'm writing to ___ / I'm following up on ___** | 이메일 목적 |  | 6 |
| K02 | **Please find attached ___ / I've attached ___** | 첨부 |  | 4 |
| K03 | **I'd appreciate it if ___** | 정중한 요청 (서면) |  | 3 |
| K04 | **Thank you for your ___** | 이메일 감사 |  | 5 |
| K05 | **Looking forward to ___** | 기대·마무리 |  | 6 |
| K06 | **Apologies for ___** | 서면 사과 |  | 4 |
| K07 | **Could you let me know ___? / Please let me know ___** | 회신 요청 |  | 7 |
| K08 | **Would ___ work for you?** | 일정 제안 |  | 4 |

### Z. 고정 표현 (Chunks)

| ID | 패턴 | 기능 | 사용 메모 | 수록 |
|---|---|---|---|---:|
| Z00 | **(고정 표현 · chunk)** | 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리 | Keep the change, Here you go처럼 변형 없이 쓰이는 표현. | 815 |

---

## Part 1. 공통 의사소통 기반

### `U-REP` 의사소통 수리 — 못 알아들었을 때

*상황 59개 · ★ 12개*


**B13 · Do you know ___? / Do you happen to know ___?** — 정보 보유 여부

- **Do you speak English?** — 영어 가능 여부 `U-REP-001`

**D01 · Sorry, could you say that again?** — 반복 요청

- ★ **Sorry, could you say that again?** — 다시 말해 달라고 할 때 (기본) `U-REP-002`
- ★ **Sorry, could you repeat that a bit more slowly?** — 천천히 한 번 더 `U-REP-003`
- **Could you repeat the last part?** — 마지막 부분만 다시 `U-REP-004`
- **Sorry, could you repeat the number?** — 숫자를 다시 `U-REP-005`
- **Sorry, what was your name again?** — 상대 이름을 다시 `U-REP-006`
- **Sorry?** — 구어체로 짧게 되묻기 `U-REP-007`
- **I beg your pardon?** — 조금 더 격식 있게 되묻기 `U-REP-008`
- **Sorry, you lost me there. Could you go over that again?** — 설명을 놓쳤을 때 `U-REP-009`

**D02 · Sorry, I didn't catch ___** — 못 들었음

- ★ **Sorry, I didn't catch that.** — 못 알아들었다고 솔직히 `U-REP-010`
- **Sorry, I didn't catch your name.** — 이름을 못 들음 `U-REP-011`
- **Sorry, it's a bit noisy — I didn't quite catch that.** — 시끄러워서 못 들음 `U-REP-012`
- **Sorry, I missed the last word.** — 마지막 단어를 놓침 `U-REP-013`
- **Sorry, I didn't catch the announcement. What did it say?** — 안내방송을 못 들음 `U-REP-014`
- **Sorry, I didn't catch the name of the street.** — 거리 이름을 놓침 `U-REP-015`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- ★ **Just to confirm, it's platform 7, right?** — 확인 기본 `U-REP-016`
- **Just to make sure — we're meeting at nine?** — 약속 시각 확인 `U-REP-017`
- **So that's 45 euros in total?** — 총액 확인 `U-REP-018`
- **Let me make sure I've got this right.** — 제대로 이해했는지 예고 `U-REP-019`
- **Okay, so first the form, then the payment — right?** — 절차 순서 확인 `U-REP-020`

**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- ★ **Sorry, what does that word mean?** — 단어 뜻 묻기 `U-REP-021`
- **What do you mean by that?** — 의도 묻기 `U-REP-022`
- **What does that abbreviation stand for?** — 약어 뜻 `U-REP-023`
- **What does this sign say?** — 표지판 내용 `U-REP-024`
- **What does "Gleis" mean?** — 현지어 표지 단어 (독일어 Gleis=승강장) `U-REP-025`
- **What does "on the house" mean?** — 관용구 뜻 `U-REP-026`

**D05 · Could you speak more slowly / write it down?** — 전달 방식 변경 요청

- ★ **Could you speak a little more slowly, please?** — 천천히 말해 달라 `U-REP-027`
- ★ **Could you write it down for me?** — 적어 달라 `U-REP-028`
- **Could you spell that for me?** — 철자를 불러 달라 `U-REP-029`
- **Could you show me on the map?** — 지도에서 보여 달라 `U-REP-030`
- **Could you write down the number?** — 숫자를 써 달라 `U-REP-031`
- **Could you put that more simply?** — 쉬운 말로 다시 `U-REP-032`
- **Could you point to it on the screen?** — 화면에서 가리켜 달라 `U-REP-033`
- **Could you give me the short version?** — 짧게 요약 요청 `U-REP-034`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- ★ **So I should go back to the first counter?** — 이해한 내용 되묻기 `U-REP-035`
- **So you're saying the train is cancelled?** — 요약해서 확인 `U-REP-036`
- **Do you mean this one or that one?** — 둘 중 어느 것인지 `U-REP-037`
- **Do you mean today or tomorrow?** — 오늘·내일 혼동 `U-REP-038`
- **Sorry, fifteen or fifty?** — 15와 50 구분 `U-REP-039`
- **Is that seven in the morning or in the evening?** — 오전·오후 확인 `U-REP-040`
- **Is that in euros or dollars?** — 통화 단위 확인 `U-REP-041`

**D07 · Let me ___** — 시간 벌기·행동 예고

- ★ **Let me think for a second.** — 잠깐 생각할 시간 `U-REP-042`
- **Let me check.** — 확인해 보겠다 `U-REP-043`
- **Let me look it up.** — 검색해 보겠다 `U-REP-044`
- **Let me use a translation app — just a second.** — 번역 앱 사용 양해 `U-REP-045`
- **Let me write that down.** — 메모하며 시간 벌기 `U-REP-046`

**D08 · How do you say ___? / What do you call ___?** — 어휘·발음 묻기

- ★ **How do you say this in English?** — 영어로 뭐라고 하는지 `U-REP-047`
- **What do you call this?** — 물건 이름 `U-REP-048`
- **How do you pronounce this?** — 발음 확인 `U-REP-049`
- **How do you spell that?** — 철자 묻기 `U-REP-050`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **My English isn't perfect, so please bear with me.** — 영어가 완벽하지 않다고 양해 `U-REP-051`
- ★ **Just a moment, please.** — 잠깐만요 `U-REP-052`
- **Got it.** — 알아들었다 (구어) `U-REP-053`
- **I see. Thank you.** — 이해했다 (정중) `U-REP-054`
- **Sorry, I don't understand.** — 이해하지 못했다 `U-REP-055`
- **Sorry, I don't speak German.** — 현지어 불가 `U-REP-056`
- **I think I get the idea.** — 대략 이해함 `U-REP-057`
- **Thanks for being patient with me.** — 인내에 감사 `U-REP-058`
- **I'm not sure I understood everything, to be honest.** — 다 이해 못했다고 솔직히 `U-REP-059`

### `U-BAS` 인사·사과·감사·말 걸기

*상황 43개 · ★ 7개*


**E01 · Nice to meet you / Good to see you** — 인사

- ★ **Nice to meet you.** — 처음 만남 `U-BAS-001`
- **Good to see you again.** — 다시 만남 `U-BAS-002`
- **Pleased to meet you.** — 소개 받았을 때 (격식) `U-BAS-003`

**E03 · How's ___ going? / How was ___?** — 안부·경험

- **How's it going?** — 안부 묻기 `U-BAS-004`
- **How's your day going?** — 하루 안부 `U-BAS-005`

**E07 · Thanks for ___** — 감사

- ★ **Thanks so much.** — 감사 기본 `U-BAS-006`
- **Thanks for your help.** — 도움에 감사 `U-BAS-007`
- **Thanks for waiting.** — 기다려 줘서 `U-BAS-008`
- **Thanks for explaining.** — 설명해 줘서 `U-BAS-009`
- **Thanks for your time.** — 시간 내줘서 `U-BAS-010`
- **Thanks for holding the door.** — 문 잡아줘서 `U-BAS-011`

**E08 · Sorry about ___ / Sorry to ___** — 사과

- ★ **Sorry about that.** — 가벼운 사과 `U-BAS-012`
- **Oh, sorry!** — 부딪혔을 때 `U-BAS-013`
- ★ **Sorry I'm late.** — 늦었을 때 `U-BAS-014`
- **Sorry to keep you waiting.** — 기다리게 했을 때 `U-BAS-015`
- **Sorry to bother you.** — 방해할 때 `U-BAS-016`
- **Sorry, my mistake.** — 실수 인정 `U-BAS-017`
- **Sorry to interrupt.** — 말을 끊을 때 `U-BAS-018`
- **Sorry, wrong number.** — 전화 잘못 걸었을 때 `U-BAS-019`

**E09 · Excuse me, ___** — 말 걸기

- ★ **Excuse me, do you have a minute?** — 말 걸기 기본 `U-BAS-020`
- **Excuse me, could I just squeeze past?** — 좁은 곳을 지나갈 때 `U-BAS-021`
- **Excuse me — could you help me?** — 직원 부르기 `U-BAS-022`
- **Excuse me, are you in line?** — 줄 서 있는지 확인 `U-BAS-023`
- **Excuse me, I think that's my seat.** — 내 자리라고 알릴 때 `U-BAS-024`

**E11 · It was great ___ / Have a ___** — 작별

- **It was nice talking to you.** — 대화를 마칠 때 `U-BAS-025`
- **Have a good one.** — 좋은 하루 (구어) `U-BAS-026`
- **Have a safe trip!** — 좋은 여행 기원 `U-BAS-027`
- **Have a nice weekend!** — 좋은 주말 `U-BAS-028`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **That's very kind of you.** — 친절에 감사 `U-BAS-029`
- ★ **You're welcome.** — 감사에 답 `U-BAS-030`
- **No worries.** — 사과에 답 `U-BAS-031`
- **It's fine, really.** — 정말 괜찮다 `U-BAS-032`
- ★ **No, thank you.** — 정중한 거절 `U-BAS-033`
- **I'm good, thanks.** — 가볍게 거절 `U-BAS-034`
- **Morning!** — 아침 가게 입장 인사 `U-BAS-035`
- **Thanks, have a nice day!** — 가게를 나설 때 `U-BAS-036`
- **You too!** — 상대 인사에 답 `U-BAS-037`
- **Pretty good, thanks. And you?** — 안부에 답 `U-BAS-038`
- **Not bad — a bit tired, actually.** — 피곤하다고 솔직히 `U-BAS-039`
- **Go ahead.** — 먼저 하라고 양보 `U-BAS-040`
- **No, please — after you.** — 줄·문 양보 `U-BAS-041`
- **Bless you!** — 재채기한 사람에게 `U-BAS-042`
- **Congratulations!** — 축하 (일반) `U-BAS-043`

### `U-NUM` 숫자·시간·날짜·위치 확인

*상황 34개 · ★ 4개*


**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- ★ **Where's the restroom?** — 화장실 (미국식) `U-NUM-001`
- **Where are the toilets?** — 화장실 (유럽식) `U-NUM-002`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there a pharmacy around here?** — 근처 존재 여부 `U-NUM-003`

**B05 · What time ___? / When ___?** — 시각·시점

- ★ **Do you know what time it is?** — 지금 몇 시인지 `U-NUM-004`
- **What time do you close?** — 마감 시각 `U-NUM-005`
- **What time does it start?** — 시작 시각 `U-NUM-006`
- **When's the next one?** — 다음 회차 `U-NUM-007`
- **What time do you open?** — 영업 시작 시각 `U-NUM-008`

**B06 · How long ___?** — 소요 시간·기간

- ★ **How long will it take?** — 소요 시간 `U-NUM-009`
- **How long is the wait?** — 대기 시간 `U-NUM-010`
- **How long does it take on foot?** — 걸어서 걸리는 시간 `U-NUM-011`
- **How many days will it take?** — 며칠 걸리는지 `U-NUM-012`
- **How long does it usually take?** — 보통 걸리는 시간 `U-NUM-013`

**B07 · How much ___?** — 가격·양

- ★ **How much is this?** — 가격 `U-NUM-014`
- **How much is it altogether?** — 총액 `U-NUM-015`
- **How much is it per person?** — 1인당 가격 `U-NUM-016`
- **Roughly how much would it be?** — 대략적인 금액 `U-NUM-017`
- **How much is the fee?** — 수수료 `U-NUM-018`
- **What do I owe you?** — 가게에서 합계 묻기 `U-NUM-019`

**B08 · Which ___?** — 선택지 중 특정

- **Which way is it?** — 어느 쪽인지 `U-NUM-020`
- **Which floor are you going to?** — 엘리베이터에서 층 묻기 `U-NUM-021`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is that local time?** — 시간대 확인 `U-NUM-022`
- **Are you open on Sundays?** — 일요일 영업 `U-NUM-023`
- **Are you open on the holiday?** — 공휴일 영업 `U-NUM-024`
- **Is today the 14th?** — 오늘 날짜 확인 `U-NUM-025`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **That's Tuesday the 14th, right?** — 날짜 확인 `U-NUM-026`
- **So that's three, four, seven, nine?** — 숫자 하나씩 확인 `U-NUM-027`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **Is that the ground floor or the first floor?** — 층 표기 확인 (유럽 1층=ground floor) `U-NUM-028`
- **So 17:30 — that's 5:30 p.m.?** — 24시간제 시각 확인 `U-NUM-029`
- **The 3rd or the 13th?** — 3일과 13일 구분 `U-NUM-030`
- **Half past six — so 6:30?** — half past 확인 `U-NUM-031`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Is that day first, then month?** — 유럽식 날짜 순서 확인 `U-NUM-032`
- **It's quarter to nine.** — 시각 말하기 `U-NUM-033`
- **That's twelve fifty.** — 가격 말하기 (구어) `U-NUM-034`

### `U-EXP` 선택·허락·상태 표현

*상황 50개 · ★ 8개*


**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- ★ **Could you do me a favor?** — 부탁 하나 `U-EXP-001`
- **Could you take a picture for me?** — 사진 부탁 (가볍게) `U-EXP-002`

**A03 · Would you mind ___ing?** — 부담이 있는 부탁

- **Would you mind watching my bag for a minute?** — 짐 잠깐 봐 달라 `U-EXP-003`
- **Would you mind taking a photo of us?** — 사진 부탁 (정중) `U-EXP-004`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- ★ **I'd like this one, please.** — 원하는 것 `U-EXP-005`
- **I'd like to change this, if possible.** — 변경 희망 `U-EXP-006`

**A05 · ___, please.** — 최소 단위 요청

- ★ **This one, please.** — 최소 지칭 `U-EXP-007`
- **Two of these, please.** — 두 개 `U-EXP-008`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Is it possible to do it today?** — 오늘 가능 여부 `U-EXP-009`

**A07 · I was wondering if ___** — 매우 조심스러운 부탁

- **I was wondering if you could help me.** — 조심스러운 부탁 `U-EXP-010`

**A08 · I need (to) ___** — 필요를 직접 밝힘

- **I need to get there by ten.** — 시간 맞춰 가야 함 `U-EXP-011`
- **I need to find a restroom — quickly.** — 급히 화장실 `U-EXP-012`
- **I need a minute.** — 잠깐 쉬어야 함 `U-EXP-013`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- ★ **Can I take a photo here?** — 사진 촬영 허락 `U-EXP-014`
- **Is it okay if I sit here?** — 앉아도 되는지 `U-EXP-015`
- **Can I use this?** — 사용해도 되는지 `U-EXP-016`
- **Can I come in?** — 들어가도 되는지 `U-EXP-017`
- **Can I take one?** — 하나 가져가도 되는지 `U-EXP-018`

**A10 · Do you mind if I ___?** — 상대를 배려한 허락

- **Do you mind if I open the window?** — 창문 열어도 되는지 `U-EXP-019`
- **Do you mind if I plug in my charger here?** — 충전기 꽂아도 되는지 `U-EXP-020`
- **Do you mind if I go ahead of you? I'm in a hurry.** — 먼저 가도 되는지 `U-EXP-021`

**A12 · I'd prefer ___ / I'd rather ___** — 선호 표현

- ★ **I'd prefer the earlier one.** — 선호 `U-EXP-022`
- **I'd rather take the train, if possible.** — 교통수단 선호 `U-EXP-023`
- **I'd prefer somewhere quiet.** — 조용한 곳 선호 `U-EXP-024`
- **I'd rather do it tomorrow.** — 내일 선호 `U-EXP-025`

**A13 · Could you help me with ___?** — 도움 요청

- ★ **Could you help me with this?** — 도움 요청 `U-EXP-026`
- **Could you help me with my bag?** — 짐 도움 `U-EXP-027`
- **Could you help me with this machine?** — 기계 사용 도움 `U-EXP-028`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to book in advance?** — 미리 예약 필요 여부 `U-EXP-029`
- **Do I have to queue here?** — 여기서 줄 서야 하는지 `U-EXP-030`

**B16 · What if ___? / What happens if ___?** — 조건·예외 상황

- **What if I miss it?** — 만약 놓치면 `U-EXP-031`

**C07 · I have ___ / I feel ___** — 증상·상태

- **I'm a bit jet-lagged.** — 시차 피로 `U-EXP-032`
- **I'm a bit lost.** — 길을 잃음 `U-EXP-033`
- **I'm a bit cold.** — 추움 `U-EXP-034`

**C09 · It's my first time ___** — 처음임을 밝힘

- ★ **It's my first time here.** — 처음 왔음 `U-EXP-035`

**C10 · I'm afraid ___** — 나쁜 소식·거절의 완곡

- ★ **I'm afraid I can't.** — 정중하게 불가 `U-EXP-036`
- **I'm afraid I don't know.** — 모른다고 정중히 `U-EXP-037`
- **I'm afraid I can't make it.** — 참석 불가 `U-EXP-038`

**C12 · I'm just ___** — 가벼운 상태 설명

- **I'm just looking, thanks.** — 그냥 구경 중 `U-EXP-039`
- **I'm just checking something.** — 그냥 확인 중 `U-EXP-040`
- **I'm just passing through.** — 잠깐 지나가는 중 `U-EXP-041`

**C13 · I'm running late / I missed ___** — 지연·놓침

- **I'm running a bit late.** — 조금 늦을 것 같음 `U-EXP-042`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Either is fine.** — 둘 다 괜찮음 `U-EXP-043`
- **I don't mind.** — 상관없음 `U-EXP-044`
- **I'll think about it.** — 결정 보류 `U-EXP-045`
- **I'll come back later.** — 나중에 다시 옴 `U-EXP-046`
- **That's perfect, thanks.** — 딱 좋다 `U-EXP-047`
- **That's enough, thanks.** — 충분하다 `U-EXP-048`
- **I'm not sure yet.** — 아직 미정 `U-EXP-049`
- **Good idea.** — 좋은 생각 `U-EXP-050`

---

## Part 2. 여행 영어

### `T-AIR1` 공항 출국 — 체크인·수하물

*상황 80개 · ★ 8개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- ★ **Could I get a window seat?** — 창가 좌석 `T-AIR1-001`
- **Could I get an aisle seat, please?** — 통로 좌석 `T-AIR1-002`
- **Could we sit together?** — 일행과 나란히 `T-AIR1-003`
- **Could I get a printed boarding pass?** — 종이 탑승권 `T-AIR1-004`
- **Could I get a fragile sticker for this?** — 취급주의 스티커 `T-AIR1-005`
- **Could I get a receipt for that?** — 수하물 요금 영수증 `T-AIR1-006`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you print both boarding passes?** — 두 장 모두 출력 `T-AIR1-007`
- **Could you add my frequent flyer number?** — 마일리지 적립 `T-AIR1-008`
- **Could you put me on the waitlist?** — 대기 명단 `T-AIR1-009`
- **Could you arrange wheelchair assistance?** — 휠체어 지원 `T-AIR1-010`
- **Could you print my seat number on the boarding pass?** — 좌석 번호 인쇄 `T-AIR1-011`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- ★ **Hi, I'd like to check in for my flight to Frankfurt.** — 체크인 시작 `T-AIR1-012`
- **I'd like to check this bag.** — 수하물 부치기 `T-AIR1-013`
- ★ **I'd like to change my flight.** — 항공편 변경 `T-AIR1-014`
- **I'd like to add a bag to my booking.** — 수하물 추가 구매 `T-AIR1-015`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would it be possible to get an exit row seat?** — 비상구 좌석 `T-AIR1-016`
- **Is it possible to get a seat near the front?** — 앞쪽 좌석 `T-AIR1-017`
- **Is it possible to upgrade to business class?** — 좌석 업그레이드 `T-AIR1-018`
- **Is it possible to get on an earlier flight?** — 더 이른 항공편 `T-AIR1-019`
- **Is it possible to request a vegetarian meal?** — 특별 기내식 `T-AIR1-020`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can I take this on board?** — 기내 반입 가능 여부 `T-AIR1-021`
- **Can I pay by card?** — 카드 결제 `T-AIR1-022`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where's the bag drop?** — 백드롭 위치 `T-AIR1-023`
- **Where do I drop off oversized baggage?** — 대형 수하물 `T-AIR1-024`
- **Where's the priority check-in?** — 우선 체크인 `T-AIR1-025`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- ★ **How do I use this kiosk?** — 키오스크 사용법 `T-AIR1-026`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Are there any aisle seats left?** — 남은 통로석 `T-AIR1-027`
- **Is there a bag wrapping service?** — 비닐 랩핑 `T-AIR1-028`
- **Are there any other flights today?** — 오늘 다른 편 `T-AIR1-029`
- **Is there a fast-track lane?** — 패스트트랙 `T-AIR1-030`
- **Is there a scale where I can weigh my bag?** — 수하물 저울 `T-AIR1-031`

**B05 · What time ___? / When ___?** — 시각·시점

- ★ **What time does boarding start?** — 탑승 시각 `T-AIR1-032`
- **What time does check-in close?** — 체크인 마감 `T-AIR1-033`

**B06 · How long ___?** — 소요 시간·기간

- **How long does it take to get to the gate?** — 게이트까지 시간 `T-AIR1-034`
- **How long is the security line right now?** — 보안검색 대기 시간 `T-AIR1-035`

**B07 · How much ___?** — 가격·양

- **How much is the excess baggage fee?** — 초과 수하물 요금 `T-AIR1-036`
- **How much would an upgrade be?** — 업그레이드 비용 `T-AIR1-037`
- **How much is it for an extra bag?** — 추가 수하물 가격 `T-AIR1-038`
- **How much is it to choose a seat?** — 좌석 지정 비용 `T-AIR1-039`

**B08 · Which ___?** — 선택지 중 특정

- ★ **Which gate is it?** — 게이트 `T-AIR1-040`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is my seat confirmed?** — 좌석 확정 여부 `T-AIR1-041`
- **Is it overweight?** — 무게 초과 여부 `T-AIR1-042`
- **Is a power bank okay in my carry-on?** — 보조배터리 반입 `T-AIR1-043`
- **Is the flight on time?** — 정시 출발 여부 `T-AIR1-044`
- **Is the mobile boarding pass okay?** — 모바일 탑승권 `T-AIR1-045`
- **Is this the line for bag drop?** — 백드롭 줄인지 `T-AIR1-046`
- **Is this the line for economy?** — 이코노미 줄인지 `T-AIR1-047`
- **Is 23 kilos the limit?** — 무게 한도 `T-AIR1-048`
- **Is this a direct flight?** — 직항 여부 `T-AIR1-049`
- **Is a laptop bag okay as a personal item?** — 노트북 가방 개인 소지품 인정 `T-AIR1-050`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to move anything to my carry-on?** — 기내 가방으로 옮겨야 하는지 `T-AIR1-051`
- **Do I need to pick up my bag in Frankfurt?** — 경유지에서 짐 찾기 `T-AIR1-052`
- **Do I need to fill in a luggage tag?** — 수하물 태그 작성 `T-AIR1-053`
- **Do you need to see my return ticket?** — 귀국 항공권 확인 요구 `T-AIR1-054`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- ★ **Is checked baggage included in my ticket?** — 무료 수하물 포함 여부 `T-AIR1-055`
- **Will my bag go all the way to Berlin?** — 최종 목적지까지 수하물 연결 `T-AIR1-056`

**B15 · What's the ___?** — 정보 항목 묻기

- **What terminal is it?** — 터미널 `T-AIR1-057`

**B16 · What if ___? / What happens if ___?** — 조건·예외 상황

- **What happens if the gate changes?** — 게이트 변경 시 `T-AIR1-058`

**C01 · I have a reservation ___ / I booked ___** — 예약 사실 제시

- **I have a booking under Kim.** — 예약 사실 제시 `T-AIR1-059`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **The kiosk isn't working.** — 키오스크 오류 `T-AIR1-060`
- **It won't scan my passport.** — 여권 인식 실패 `T-AIR1-061`
- **The app won't let me check in.** — 앱 체크인 오류 `T-AIR1-062`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **I think there's a mistake in the spelling of my name.** — 이름 철자 오류 `T-AIR1-063`

**C11 · I don't eat ___ / I'm allergic to ___** — 식이 제한

- **I don't eat pork. Is that noted on my booking?** — 식이 제한 기록 `T-AIR1-064`

**C13 · I'm running late / I missed ___** — 지연·놓침

- **I'm running late — can I still check in?** — 늦게 도착 `T-AIR1-065`

**C14 · I was told ___** — 근거 제시

- **I already checked in online.** — 온라인 체크인 완료 `T-AIR1-066`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **Just to confirm, the tag says BER, right?** — 수하물 태그 확인 `T-AIR1-067`
- **So gate B22, boarding at 10:15?** — 게이트·시각 확인 `T-AIR1-068`

**D07 · Let me ___** — 시간 벌기·행동 예고

- **Let me take a few things out.** — 짐 재정리 `T-AIR1-069`
- **Let me spell it for you: K-I-M.** — 철자 불러주기 `T-AIR1-070`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **Here you go.** — 서류를 건넬 때 `T-AIR1-071`
- **Just one bag to check.** — 부칠 짐 개수 `T-AIR1-072`
- **Just this carry-on.** — 기내용만 있음 `T-AIR1-073`
- **Here's my frequent flyer card.** — 마일리지 카드 제시 `T-AIR1-074`
- **That's everything? Great, thank you.** — 체크인 완료 확인 `T-AIR1-075`
- **Yes, I packed it myself.** — 짐을 직접 쌌는지 질문에 답 `T-AIR1-076`
- **No, nothing like that.** — 위험물 질문에 답 `T-AIR1-077`
- **No, it's been with me the whole time.** — 짐을 맡긴 적 없음 `T-AIR1-078`
- **Window, if possible.** — 좌석 선호 답 (창가) `T-AIR1-079`
- **Any seat is fine.** — 아무 좌석이나 `T-AIR1-080`

### `T-AIR2` 보안검색·면세·라운지·탑승

*상황 69개 · ★ 5개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I book a shower?** — 샤워 예약 `T-AIR2-001`
- **Could I get it in a sealed bag?** — 밀봉 봉투 `T-AIR2-002`
- **Could I get a new boarding pass?** — 탑승권 재발급 `T-AIR2-003`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you be careful with that? It's fragile.** — 파손 주의 부탁 `T-AIR2-004`
- **Could you seat us together?** — 일행 좌석 배정 `T-AIR2-005`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would it be possible to board early? I have a bad back.** — 우선 탑승 `T-AIR2-006`
- **Would it be possible to change seats?** — 좌석 변경 `T-AIR2-007`
- **Is it possible to go through fast track? My connection is very tight.** — 촉박한 환승 패스트트랙 `T-AIR2-008`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can I use the lounge with this card?** — 라운지 이용 가능 `T-AIR2-009`
- **Can I pay in euros?** — 유로 결제 `T-AIR2-010`

**A11 · I'll have ___ / I'll take ___** — 주문·구매 확정

- **I'll take this one.** — 면세 구매 확정 `T-AIR2-011`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where do I get a tray?** — 트레이 위치 `T-AIR2-012`
- ★ **Where's gate B22?** — 게이트 위치 `T-AIR2-013`
- **Where's transfer security?** — 환승 보안검색 `T-AIR2-014`
- **Where's the lounge?** — 라운지 위치 `T-AIR2-015`
- **Where does the bus to the plane leave from?** — 램프버스 탑승 `T-AIR2-016`
- **Where can I refill my water bottle?** — 급수대 `T-AIR2-017`
- **Where's the smoking area?** — 흡연 구역 `T-AIR2-018`
- **Where's passport control?** — 출국 심사대 `T-AIR2-019`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How do I get to my connecting flight?** — 환승편 가는 길 `T-AIR2-020`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there a quiet area?** — 조용한 공간 `T-AIR2-021`
- **Is there anywhere to charge my phone?** — 충전 장소 `T-AIR2-022`
- **Is there a pharmacy in this terminal?** — 공항 약국 `T-AIR2-023`
- **Are there any empty seats?** — 빈 좌석 `T-AIR2-024`
- **Is there a prayer room?** — 기도실 `T-AIR2-025`
- **Is there anywhere I can sleep for a few hours?** — 잠깐 잘 곳 `T-AIR2-026`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have this in stock?** — 면세 재고 `T-AIR2-027`

**B05 · What time ___? / When ___?** — 시각·시점

- ★ **What time does boarding start?** — 탑승 시작 시각 `T-AIR2-028`

**B06 · How long ___?** — 소요 시간·기간

- **How long is the walk to gate B22?** — 게이트까지 도보 `T-AIR2-029`
- **How long can I stay?** — 라운지 체류 시간 `T-AIR2-030`
- **How long is the delay?** — 지연 시간 `T-AIR2-031`
- **How long until the gate closes?** — 게이트 마감까지 `T-AIR2-032`

**B07 · How much ___?** — 가격·양

- **How much is this duty-free?** — 면세 가격 `T-AIR2-033`

**B08 · Which ___?** — 선택지 중 특정

- ★ **Which group am I in?** — 탑승 그룹 `T-AIR2-034`
- **Which way is row 32?** — 좌석 방향 `T-AIR2-035`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is this bottle okay? It's 100 ml.** — 액체 용량 `T-AIR2-036`
- **Is this tray mine?** — 내 트레이인지 `T-AIR2-037`
- **Is liquid medicine okay to bring?** — 액상 약 반입 `T-AIR2-038`
- **Is it tax-free if I'm flying outside the EU?** — EU 밖 면세 여부 `T-AIR2-039`
- **Will this be okay through transfer security?** — 환승 보안 통과 여부 `T-AIR2-040`
- ★ **Is this the line for Group 3?** — 탑승 그룹 줄 확인 `T-AIR2-041`
- **Has boarding started?** — 탑승 시작 여부 `T-AIR2-042`
- **Are we still on time?** — 정시 여부 재확인 `T-AIR2-043`
- **Is there anywhere to eat near the gate?** — 게이트 근처 식당 `T-AIR2-044`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- ★ **Do I need to take my laptop out?** — 노트북 꺼내야 하는지 `T-AIR2-045`
- **Do I have to take my shoes off?** — 신발 벗어야 하는지 `T-AIR2-046`
- **Do I need to take off my belt?** — 벨트 `T-AIR2-047`
- **Do I need to take out my liquids?** — 액체류 꺼내기 `T-AIR2-048`
- **Do you need my boarding pass?** — 면세 탑승권 제시 `T-AIR2-049`
- **Do I need to check this bag at the gate?** — 게이트에서 짐 부쳐야 하는지 `T-AIR2-050`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Is lounge access included?** — 라운지 포함 여부 `T-AIR2-051`
- **Is gate check free?** — 게이트 체크 무료 여부 `T-AIR2-052`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's the Wi-Fi password?** — 라운지 와이파이 `T-AIR2-053`
- **What's the reason for the delay?** — 지연 사유 `T-AIR2-054`

**B16 · What if ___? / What happens if ___?** — 조건·예외 상황

- **What if I miss my connection?** — 연결편을 놓치면 `T-AIR2-055`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **My boarding pass won't scan.** — 탑승권 인식 실패 `T-AIR2-056`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **I think there's a mix-up — someone's in my seat.** — 좌석 중복 `T-AIR2-057`

**C06 · I lost ___ / I can't find ___ / I left ___** — 분실

- **I can't find my boarding pass.** — 탑승권 분실 `T-AIR2-058`
- **I think I left my phone at security.** — 보안검색대에 물건 두고 옴 `T-AIR2-059`

**C13 · I'm running late / I missed ___** — 지연·놓침

- **My connection is really tight.** — 연결 시간 촉박 `T-AIR2-060`

**D02 · Sorry, I didn't catch ___** — 못 들었음

- **Sorry, I didn't catch the announcement. Was that for Berlin?** — 탑승 방송 놓침 `T-AIR2-061`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **Arms up like this?** — 자세 지시 확인 `T-AIR2-062`
- **So the gate changed to C5?** — 게이트 변경 확인 `T-AIR2-063`

**E09 · Excuse me, ___** — 말 걸기

- **Excuse me, is this the flight to Berlin?** — 직원에게 확인 `T-AIR2-064`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **I'll just throw it away.** — 물 버리기 `T-AIR2-065`
- **Sure, go ahead.** — 가방 검사 동의 `T-AIR2-066`
- **It's probably my watch.** — 알람 원인 설명 `T-AIR2-067`
- **I have a prescription for it.** — 처방전 있음 `T-AIR2-068`
- **Here's my boarding pass.** — 탑승권 제시 `T-AIR2-069`

### `T-FLT` 기내

*상황 73개 · ★ 7개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- ★ **Could I get some water, please?** — 물 `T-FLT-001`
- **Could I have a blanket?** — 담요 `T-FLT-002`
- **Could I get an extra pillow?** — 베개 추가 `T-FLT-003`
- **Could I get some headphones?** — 헤드폰 `T-FLT-004`
- **Could I get another coffee?** — 커피 한 잔 더 `T-FLT-005`
- **Could I have an arrival card?** — 입국카드 `T-FLT-006`
- **Could I have a sick bag?** — 구토 봉투 `T-FLT-007`
- **Could I borrow a pen?** — 펜 빌리기 `T-FLT-008`
- **Could I get some ice, please?** — 얼음 `T-FLT-009`
- **Could I get some milk for my coffee?** — 커피에 우유 `T-FLT-010`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you help me put this up?** — 짐칸 올리기 도움 `T-FLT-011`
- **Could you put your seat up a little? I'm trying to eat.** — 앞사람 등받이 `T-FLT-012`
- **Could you wake me up for breakfast?** — 아침 식사 때 깨워 달라 `T-FLT-013`
- **Could you take this away?** — 트레이 치워 달라 `T-FLT-014`
- **Could you open the shade a little?** — 창문 덮개 조금 열어 달라 `T-FLT-015`

**A03 · Would you mind ___ing?** — 부담이 있는 부탁

- **Would you mind turning off your reading light?** — 옆 사람 독서등 `T-FLT-016`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would it be possible to move to another seat?** — 다른 좌석으로 `T-FLT-017`
- **Would it be possible to let me off first?** — 먼저 내리기 `T-FLT-018`

**A08 · I need (to) ___** — 필요를 직접 밝힘

- **I need some water to take my medicine.** — 약 먹을 물 `T-FLT-019`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Is it okay if I recline my seat?** — 등받이 젖혀도 `T-FLT-020`
- ★ **Sorry, can I get out?** — 화장실 가려고 나갈 때 `T-FLT-021`
- **Can I buy duty-free items on board?** — 기내 면세 `T-FLT-022`

**A10 · Do you mind if I ___?** — 상대를 배려한 허락

- **Do you mind if I put my seat back?** — 뒷사람에게 양해 `T-FLT-023`
- **Do you mind if I close the window shade?** — 창문 덮개 닫아도 `T-FLT-024`

**A11 · I'll have ___ / I'll take ___** — 주문·구매 확정

- ★ **I'll have the chicken, please.** — 식사 선택 `T-FLT-025`
- **I'll have a white wine.** — 음료 선택 `T-FLT-026`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How do I connect to the Wi-Fi?** — 와이파이 접속법 `T-FLT-027`
- **How do I recline this seat?** — 좌석 조작법 `T-FLT-028`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there any space up there?** — 짐칸 공간 `T-FLT-029`
- **Are there any free seats?** — 빈자리 `T-FLT-030`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have orange juice?** — 오렌지주스 `T-FLT-031`
- **Do you have green tea?** — 녹차 `T-FLT-032`
- **Do you have any painkillers?** — 진통제 `T-FLT-033`
- **Do you have any snacks?** — 간식 `T-FLT-034`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time do we arrive?** — 도착 시각 `T-FLT-035`
- **When will the duty-free cart come by?** — 면세 카트 `T-FLT-036`

**B06 · How long ___?** — 소요 시간·기간

- ★ **How long until we land?** — 남은 비행 시간 `T-FLT-037`

**B07 · How much ___?** — 가격·양

- **How much is the Wi-Fi?** — 와이파이 가격 `T-FLT-038`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is there Wi-Fi on this flight?** — 기내 와이파이 `T-FLT-039`
- **Are we going to land on time?** — 정시 도착 여부 `T-FLT-040`
- **Is the restroom free?** — 화장실 사용 중인지 `T-FLT-041`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- ★ **Do I need to fill this out?** — 입국카드 작성 여부 `T-FLT-042`
- **Do I need to keep my seatbelt on?** — 좌석벨트 `T-FLT-043`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Is that included, or do I pay for it?** — 음료 유료 여부 `T-FLT-044`

**B13 · Do you know ___? / Do you happen to know ___?** — 정보 보유 여부

- **Do you know where my connecting gate is?** — 환승 게이트 `T-FLT-045`

**B14 · Could you tell me ___?** — 간접 의문 (정중)

- **Could you tell me what to write here?** — 작성 방법 `T-FLT-046`

**B15 · What's the ___?** — 정보 항목 묻기

- **What are the options?** — 식사 선택지 `T-FLT-047`
- **What's the local time there?** — 현지 시각 `T-FLT-048`
- **What's this button for?** — 버튼 용도 `T-FLT-049`

**C01 · I have a reservation ___ / I booked ___** — 예약 사실 제시

- **I ordered a vegetarian meal.** — 특별식 신청함 `T-FLT-050`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- ★ **My screen isn't working.** — 모니터 고장 `T-FLT-051`
- **The headphone jack doesn't work.** — 헤드폰 잭 고장 `T-FLT-052`
- **My reading light won't turn on.** — 독서등 고장 `T-FLT-053`
- **The air vent is stuck.** — 송풍구 고장 `T-FLT-054`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **I think my special meal is missing.** — 특별식 누락 `T-FLT-055`

**C07 · I have ___ / I feel ___** — 증상·상태

- **It's quite cold here.** — 자리가 추움 `T-FLT-056`
- **I'm not feeling well.** — 속이 안 좋음 `T-FLT-057`
- **I feel a bit dizzy.** — 어지러움 `T-FLT-058`
- **My ears are hurting.** — 귀 통증 `T-FLT-059`
- **It's a bit warm in here.** — 더움 `T-FLT-060`

**C11 · I don't eat ___ / I'm allergic to ___** — 식이 제한

- **I'm allergic to nuts.** — 견과류 알레르기 `T-FLT-061`

**C13 · I'm running late / I missed ___** — 지연·놓침

- **I have a tight connection. Could I get off first?** — 환승 촉박 `T-FLT-062`

**D07 · Let me ___** — 시간 벌기·행동 예고

- **Let me get that down for you.** — 짐을 내려줄 때 `T-FLT-063`

**E02 · What brings you ___? / Are you here for ___?** — 방문 목적 묻기

- **Are you traveling for work?** — 옆 승객 여행 목적 `T-FLT-064`

**E04 · Where are you ___?** — 출신·소속·숙소

- **Where are you headed?** — 옆 승객 목적지 `T-FLT-065`

**E09 · Excuse me, ___** — 말 걸기

- ★ **Excuse me, I think I'm in the window seat.** — 좌석 안내 요청 `T-FLT-066`
- **Excuse me, could I just get past?** — 옆 사람에게 비켜 달라 `T-FLT-067`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Sure, no problem.** — 양해에 답 `T-FLT-068`
- **I'll skip the meal, thanks.** — 식사 건너뜀 `T-FLT-069`
- **Please don't wake me for the meal.** — 식사 때 깨우지 말 것 `T-FLT-070`
- **I'm done, thanks.** — 다 먹었다 `T-FLT-071`
- **Heading home, or traveling?** — 옆 승객과 대화 시작 `T-FLT-072`
- **I'm going to try to get some sleep. Nice chatting with you.** — 대화 정중히 마치기 `T-FLT-073`

### `T-ARR` 입국심사·세관·수하물 찾기

*상황 77개 · ★ 8개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get an overnight kit?** — 하룻밤 키트 `T-ARR-001`
- **Could I get a stamp in my passport, please?** — 여권 도장 요청 `T-ARR-002`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you deliver it to my hotel?** — 호텔로 배송 `T-ARR-003`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- **I'd like to report a missing bag.** — 분실 신고 `T-ARR-004`
- **I'd like to file a damage report.** — 파손 신고 `T-ARR-005`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can I use the automatic gates?** — 자동출입국 심사대 `T-ARR-006`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- ★ **Where's the baggage claim?** — 수하물 찾는 곳 `T-ARR-007`
- **Where can I get a trolley?** — 카트 위치 `T-ARR-008`
- **Where's the lost baggage counter?** — 분실 수하물 창구 `T-ARR-009`
- ★ **Where's the exit?** — 출구 `T-ARR-010`
- **Where can I change money?** — 환전소 `T-ARR-011`
- **Where can I buy a SIM card?** — 유심 구매처 `T-ARR-012`
- **Where's the taxi stand?** — 택시 승차장 `T-ARR-013`
- **Where can I buy a train ticket?** — 열차표 구매처 `T-ARR-014`
- **Where's the arrivals meeting point?** — 도착 미팅 포인트 `T-ARR-015`
- **Where's the nearest ATM?** — ATM 위치 `T-ARR-016`
- **Where do I go for connecting flights?** — 환승객 안내 `T-ARR-017`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How do I track it?** — 배송 추적 방법 `T-ARR-018`
- ★ **How do I get to the city center?** — 시내 가는 법 `T-ARR-019`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there a train to the city?** — 시내행 열차 `T-ARR-020`
- **Is there a tourist information desk?** — 관광안내소 `T-ARR-021`

**B06 · How long ___?** — 소요 시간·기간

- **How long will it take to find it?** — 찾는 데 걸리는 기간 `T-ARR-022`
- **How long does it take to get downtown?** — 시내까지 시간 `T-ARR-023`

**B07 · How much ___?** — 가격·양

- **How much is it to the city center?** — 시내까지 요금 `T-ARR-024`

**B08 · Which ___?** — 선택지 중 특정

- **Which line should I be in?** — 줄 선택 `T-ARR-025`
- **Which carousel is for the flight from Frankfurt?** — 수하물 벨트 번호 `T-ARR-026`
- **Which way is "nothing to declare"?** — 신고 없음 통로 `T-ARR-027`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is this the line for non-EU passports?** — 비EU 여권 줄 `T-ARR-028`
- **Is this the belt for the Frankfurt flight?** — 벨트 확인 `T-ARR-029`
- **Is it okay to bring in packaged food?** — 포장 식품 반입 `T-ARR-030`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- ★ **Do I need to scan my fingerprints?** — 지문 등록 `T-ARR-031`
- **Do I need a transit visa?** — 경유 비자 `T-ARR-032`
- **Do I need an ETIAS for this trip?** — ETIAS 필요 여부 `T-ARR-033`
- **Do I need a stamp?** — 입국 도장 `T-ARR-034`
- **Do I need a coin for the trolley?** — 카트 동전 `T-ARR-035`
- ★ **Do I need to declare this?** — 세관 신고 여부 `T-ARR-036`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Is there any compensation for essentials?** — 생필품 보상 `T-ARR-037`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's the reference number?** — 조회 번호 `T-ARR-038`

**C01 · I have a reservation ___ / I booked ___** — 예약 사실 제시

- **I'm staying at a hotel near Alexanderplatz.** — 숙소 `T-ARR-039`

**C02 · I'm here for ___ / I'm here to ___** — 방문 목적

- ★ **I'm here for a conference.** — 방문 목적 (학회) `T-ARR-040`
- **I'm here on business.** — 방문 목적 (출장) `T-ARR-041`
- **I'm here on vacation.** — 방문 목적 (관광) `T-ARR-042`
- **I'm attending a scientific conference in Berlin.** — 학회 구체 설명 `T-ARR-043`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **My suitcase is damaged.** — 가방 파손 `T-ARR-044`
- **One of the wheels is broken.** — 바퀴 파손 `T-ARR-045`

**C06 · I lost ___ / I can't find ___ / I left ___** — 분실

- ★ **My bag didn't come out.** — 짐이 안 나옴 `T-ARR-046`
- **I can't find my suitcase. It was on the flight from Frankfurt.** — 짐 분실 상세 `T-ARR-047`

**C09 · It's my first time ___** — 처음임을 밝힘

- **It's my first time in Germany.** — 첫 방문 `T-ARR-048`

**D01 · Sorry, could you say that again?** — 반복 요청

- **Sorry, could you repeat the question?** — 질문 반복 요청 `T-ARR-049`

**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- **Sorry, what do you mean by "onward travel"?** — 질문 단어 이해 못함 `T-ARR-050`

**E12 · I'm ___ / I work for ___** — 자기소개

- **I'm a researcher.** — 직업 `T-ARR-051`
- **I work for a research institute in Korea.** — 직업 상세 `T-ARR-052`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **Here's my passport.** — 심사대에서 여권 제시 `T-ARR-053`
- **About a week.** — 체류 기간 (대략) `T-ARR-054`
- **Six days. I fly back on the 20th.** — 체류 기간 (정확) `T-ARR-055`
- **Here's the address of my hotel.** — 숙소 주소 제시 `T-ARR-056`
- **Here's my return ticket.** — 귀국 항공권 제시 `T-ARR-057`
- **Here's my invitation letter from the conference.** — 초청장 제시 `T-ARR-058`
- **I have my registration confirmation here.** — 등록 확인서 제시 `T-ARR-059`
- **I'm traveling alone.** — 혼자 여행 `T-ARR-060`
- **I'm traveling with two colleagues.** — 동료와 여행 `T-ARR-061`
- **I was here two years ago for a meeting.** — 이전 방문 `T-ARR-062`
- **I have about 500 euros in cash.** — 소지 현금 `T-ARR-063`
- **After Berlin, I'm going to Paris for two days.** — 다음 목적지 `T-ARR-064`
- **Sure.** — 사진 촬영 요청에 응함 `T-ARR-065`
- **It's a medium-sized black suitcase with a red tag.** — 가방 묘사 `T-ARR-066`
- **Here's my baggage tag.** — 수하물 태그 제시 `T-ARR-067`
- **I have nothing to declare.** — 신고할 것 없음 `T-ARR-068`
- **I have something to declare.** — 신고할 것 있음 `T-ARR-069`
- **It's a gift for a colleague.** — 선물이라고 설명 `T-ARR-070`
- **These are for personal use.** — 개인 용도 `T-ARR-071`
- **This is my prescription medication.** — 처방약 설명 `T-ARR-072`
- **It's just Korean snacks — sealed and packaged.** — 식품 설명 `T-ARR-073`
- **These are just conference materials.** — 학회 자료 설명 `T-ARR-074`
- **It's my work laptop.** — 업무용 노트북 `T-ARR-075`
- **I'm staying with a friend.** — 친구 집 숙박 `T-ARR-076`
- **I'm going sightseeing for a couple of days after the conference.** — 학회 후 관광 계획 `T-ARR-077`

### `T-TRN` 기차·장거리 열차

*상황 91개 · ★ 9개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get a window seat?** — 창가 좌석 `T-TRN-001`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you move your bag, please?** — 가방 치워 달라 `T-TRN-002`
- **Could you tell me when we get to Leipzig?** — 도착 시 알려 달라 `T-TRN-003`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- ★ **I'd like a ticket to Dresden, please.** — 표 구매 `T-TRN-004`
- **I'd like to reserve a seat.** — 좌석 예약 `T-TRN-005`
- **I'd like a refund for this ticket.** — 환불 요청 `T-TRN-006`

**A05 · ___, please.** — 최소 단위 요청

- **One to Hamburg, please.** — 목적지만 말하기 `T-TRN-007`
- **A return ticket to Leipzig, please.** — 왕복 `T-TRN-008`
- **One-way, please.** — 편도 `T-TRN-009`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Is it possible to change my ticket?** — 표 변경 `T-TRN-010`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can I pay by card?** — 카드 결제 `T-TRN-011`
- **Can I buy the ticket on the app?** — 앱 구매 `T-TRN-012`
- **Can I take a later train with this ticket?** — 다음 열차 탑승 가능 `T-TRN-013`

**A11 · I'll have ___ / I'll take ___** — 주문·구매 확정

- **I'll have a coffee and a sandwich.** — 열차 내 주문 `T-TRN-014`

**A12 · I'd prefer ___ / I'd rather ___** — 선호 표현

- **I'd prefer the quiet car.** — 조용한 칸 `T-TRN-015`
- **I'd prefer first class.** — 1등석 `T-TRN-016`
- **I'd prefer a seat facing forward.** — 순방향 좌석 `T-TRN-017`

**A13 · Could you help me with ___?** — 도움 요청

- **Could you help me with my suitcase?** — 짐 올리기 도움 `T-TRN-018`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where do I validate it?** — 각인기 위치 `T-TRN-019`
- **Where does car 7 stop?** — 객차 정차 위치 `T-TRN-020`
- **Where can I put my suitcase?** — 큰 짐 둘 곳 `T-TRN-021`
- **Where does the replacement bus leave from?** — 대체 버스 승차장 `T-TRN-022`
- **Where's the ticket office?** — 매표소 `T-TRN-023`
- **Where's the left-luggage office?** — 짐 보관소 `T-TRN-024`
- **Where are the lockers?** — 사물함 `T-TRN-025`
- **Where's the dining car?** — 식당칸 위치 `T-TRN-026`
- **Where's the toilet on this train?** — 열차 화장실 `T-TRN-027`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- ★ **How do I use this machine?** — 발권기 사용법 `T-TRN-028`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Are there any cheaper options?** — 저렴한 선택지 `T-TRN-029`
- **Is there a cheaper train later?** — 저렴한 다른 시간대 `T-TRN-030`
- **Is there a dining car?** — 식당칸 `T-TRN-031`
- **Is there a replacement bus?** — 대체 버스 `T-TRN-032`
- **Is there an elevator to the platform?** — 플랫폼 엘리베이터 `T-TRN-033`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have anything vegetarian?** — 채식 메뉴 (식당칸) `T-TRN-034`

**B05 · What time ___? / When ___?** — 시각·시점

- ★ **When's the next train to Dresden?** — 다음 열차 `T-TRN-035`
- **What time is the last train?** — 막차 `T-TRN-036`
- **What time is the first train tomorrow?** — 내일 첫차 `T-TRN-037`

**B06 · How long ___?** — 소요 시간·기간

- **How long does it take to get to Dresden?** — 소요 시간 `T-TRN-038`
- **How long do I have to make the connection?** — 환승 여유 시간 `T-TRN-039`
- **How long until Dresden?** — 도착까지 남은 시간 `T-TRN-040`
- **How long is the delay?** — 지연 시간 `T-TRN-041`
- **How long does the train stop here?** — 정차 시간 `T-TRN-042`

**B07 · How much ___?** — 가격·양

- ★ **How much is a ticket to Prague?** — 표 가격 `T-TRN-043`
- **How much more is first class?** — 1등석 차액 `T-TRN-044`
- **How much is the change fee?** — 변경 수수료 `T-TRN-045`
- **How much is it to store a bag?** — 짐 보관 비용 `T-TRN-046`

**B08 · Which ___?** — 선택지 중 특정

- **Which station do I change at?** — 환승역 `T-TRN-047`
- ★ **Which platform does it leave from?** — 플랫폼 `T-TRN-048`
- **Which end is first class?** — 1등석 방향 `T-TRN-049`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is it a direct train?** — 직행 여부 `T-TRN-050`
- **Is there Wi-Fi on the train?** — 열차 와이파이 `T-TRN-051`
- **Are there power outlets on board?** — 열차 콘센트 `T-TRN-052`
- **Is there an English option?** — 영어 메뉴 `T-TRN-053`
- ★ **Does this train go to Dresden?** — 열차 행선지 확인 `T-TRN-054`
- **Does this train stop at Leipzig?** — 정차 여부 `T-TRN-055`
- **Is this car number 7?** — 객차 번호 확인 `T-TRN-056`
- **Is this seat 45?** — 좌석 번호 확인 `T-TRN-057`
- **Is this seat free?** — 빈자리인지 `T-TRN-058`
- **Is anyone sitting here?** — 자리 주인 있는지 `T-TRN-059`
- **Is the next stop Leipzig?** — 다음 역 확인 `T-TRN-060`
- ★ **Is the train delayed?** — 지연 여부 `T-TRN-061`
- **Is the train cancelled?** — 운행 취소 여부 `T-TRN-062`
- **Is my rail pass valid on this train?** — 레일패스 유효 `T-TRN-063`
- **Is it on time?** — 정시 출발 여부 `T-TRN-064`
- **Is this seat reserved? There's a sign above it.** — 예약석 표시 확인 `T-TRN-065`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I have to change trains?** — 환승 여부 `T-TRN-066`
- **Do I need a seat reservation?** — 좌석 예약 필요 여부 `T-TRN-067`
- ★ **Do I need to validate this ticket?** — 개찰·각인 필요 여부 `T-TRN-068`
- **Do I need a reservation with a rail pass?** — 레일패스 좌석 예약 `T-TRN-069`
- **Do I need my passport on this train?** — 국경 열차 여권 `T-TRN-070`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Does this include a seat reservation?** — 좌석 지정 포함 `T-TRN-071`
- **Does the regional day ticket include ICE trains?** — 지역 1일권 ICE 포함 여부 `T-TRN-072`
- **Does this ticket include the U-Bahn in the city?** — 시내 대중교통 포함 `T-TRN-073`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's this station?** — 현재 역 이름 `T-TRN-074`
- **What's the best alternative?** — 최선의 대안 `T-TRN-075`
- **What's the German name for the central station?** — 중앙역 독일어 이름 `T-TRN-076`

**B16 · What if ___? / What happens if ___?** — 조건·예외 상황

- **What happens if I don't have a reservation?** — 예약 없이 탔을 때 `T-TRN-077`
- **What if I miss my connection?** — 연결 열차를 놓치면 `T-TRN-078`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **The machine won't take my card.** — 발권기 카드 거부 `T-TRN-079`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **I think I bought the wrong ticket.** — 표를 잘못 삼 `T-TRN-080`

**C13 · I'm running late / I missed ___** — 지연·놓침

- **I missed my train.** — 열차를 놓침 `T-TRN-081`

**D02 · Sorry, I didn't catch ___** — 못 들었음

- **Sorry, what did the announcement say?** — 역 방송 못 들음 `T-TRN-082`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **Sorry, I have seat 45 in car 7 — is this car 7?** — 좌석 재확인 `T-TRN-083`

**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- **What does "Zugausfall" mean on the board?** — 전광판 운행취소 단어 `T-TRN-084`
- **What does "+20" mean next to the train?** — 지연 표시 의미 `T-TRN-085`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **So it's platform 9 now, not 4?** — 플랫폼 변경 확인 `T-TRN-086`

**E02 · What brings you ___? / Are you here for ___?** — 방문 목적 묻기

- **Going all the way to Munich?** — 옆 승객 대화 `T-TRN-087`

**E09 · Excuse me, ___** — 말 걸기

- ★ **Excuse me, I think you're in my seat.** — 내 자리라고 알릴 때 `T-TRN-088`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Here's my ticket.** — 검표원에게 표 제시 `T-TRN-089`
- **It's on my phone.** — 모바일 티켓 `T-TRN-090`
- **Have a good trip!** — 헤어질 때 인사 `T-TRN-091`

### `T-MET` 지하철·S반·버스·트램

*상황 75개 · ★ 10개*


**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you let me know when we get to the university?** — 내릴 곳 알려 달라 `T-MET-001`

**A05 · ___, please.** — 최소 단위 요청

- **One single ticket, please.** — 단일권 `T-MET-002`
- **Two day passes, please.** — 1일권 두 장 `T-MET-003`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- ★ **Can I just tap my card?** — 비접촉 결제 `T-MET-004`
- **Can I buy a ticket on the bus?** — 버스 기사에게 표 구매 `T-MET-005`
- **Can I pay the fine by card?** — 벌금 카드 결제 `T-MET-006`
- **Can I use this ticket on the tram too?** — 트램 겸용 `T-MET-007`

**A10 · Do you mind if I ___?** — 상대를 배려한 허락

- **Do you mind if I sit here?** — 옆자리 앉아도 `T-MET-008`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- ★ **Where can I buy a ticket?** — 표 구매처 `T-MET-009`
- **Where should I change for the S-Bahn?** — 환승역 `T-MET-010`
- ★ **Where's the bus stop for the 100?** — 버스 정류장 `T-MET-011`
- **Where can I get a map of the network?** — 노선도 `T-MET-012`
- **Where does the airport bus leave from?** — 공항버스 승차장 `T-MET-013`
- **Where's the lost property office for public transport?** — 교통 분실물 센터 `T-MET-014`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How do I validate this?** — 각인 방법 `T-MET-015`
- ★ **How do I get to the Reichstag from here?** — 목적지 가는 법 `T-MET-016`

**B03 · Is there ___ (around here)?** — 존재 여부

- ★ **Is there a day pass?** — 1일권 `T-MET-017`
- **Is there a night bus?** — 야간 버스 `T-MET-018`
- **Is there an elevator?** — 엘리베이터 `T-MET-019`
- **Is there an app for public transport?** — 교통 앱 `T-MET-020`
- **Is there a bus to the airport from here?** — 공항버스 `T-MET-021`
- **Is there a toilet in the station?** — 역 화장실 `T-MET-022`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have a seven-day ticket?** — 7일권 `T-MET-023`
- **Do you have a paper map?** — 종이 노선도 `T-MET-024`

**B05 · What time ___? / When ___?** — 시각·시점

- **How often does the bus come?** — 배차 간격 `T-MET-025`
- **When's the next bus?** — 다음 버스 `T-MET-026`
- **What time is the last bus?** — 막차 버스 `T-MET-027`
- **What time does the airport bus leave?** — 공항버스 출발 `T-MET-028`

**B06 · How long ___?** — 소요 시간·기간

- **How many stops is it?** — 몇 정거장 `T-MET-029`
- **How long does it take to walk to the station?** — 역까지 도보 `T-MET-030`
- **How long is a single ticket valid for?** — 단일권 유효 시간 `T-MET-031`

**B07 · How much ___?** — 가격·양

- **How much is a day pass?** — 1일권 가격 `T-MET-032`
- **How much is the fine?** — 벌금 액수 `T-MET-033`

**B08 · Which ___?** — 선택지 중 특정

- **Which zones does this ticket cover?** — 존 범위 `T-MET-034`
- ★ **Which line goes to Museum Island?** — 노선 `T-MET-035`
- **Which direction do I need?** — 방향 `T-MET-036`
- **Which exit should I take for the museum?** — 출구 번호 `T-MET-037`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- ★ **Does this go to Alexanderplatz?** — 이 노선 확인 `T-MET-038`
- **Is this the right direction for Potsdamer Platz?** — 방향 확인 `T-MET-039`
- **Is this the right platform for the U2?** — 플랫폼 확인 `T-MET-040`
- ★ **Does this bus go to the university?** — 버스 행선지 확인 `T-MET-041`
- **Do you take cash?** — 현금 가능 `T-MET-042`
- **Is this seat taken?** — 자리 주인 여부 `T-MET-043`
- **Is this the tram stop for the Charité?** — 트램 정류장 확인 `T-MET-044`
- **Is it okay to bring a big suitcase on the bus?** — 큰 짐 반입 `T-MET-045`
- **Are the trains running today?** — 운행 여부 (공휴일) `T-MET-046`
- **Is there a strike today?** — 파업 여부 `T-MET-047`
- **Is it near a U-Bahn station?** — 역 근처 여부 `T-MET-048`
- **Is it far from here?** — 거리 확인 `T-MET-049`
- **Is it walkable?** — 걸어갈 만한지 `T-MET-050`
- **Does the S-Bahn go to the airport?** — S반 공항행 `T-MET-051`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need an ABC ticket to get to the airport?** — 공항(C존) 추가표 `T-MET-052`
- ★ **Do I need to validate it?** — 각인 필요 여부 `T-MET-053`
- **Do I need to change lines?** — 환승 여부 `T-MET-054`
- **Do I need to press the button to get off?** — 하차 버튼 `T-MET-055`
- **Do I need to show my ticket when I get on?** — 승차 시 표 제시 `T-MET-056`
- **Do I need a ticket for my luggage?** — 짐 요금 `T-MET-057`
- **Do I need a new ticket if I change lines?** — 환승 시 새 표 `T-MET-058`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Does it cover the airport?** — 공항 포함 여부 `T-MET-059`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- **What's the best way to get there?** — 추천 경로 `T-MET-060`

**B13 · Do you know ___? / Do you happen to know ___?** — 정보 보유 여부

- **Do you know where the nearest U-Bahn station is?** — 가까운 역 `T-MET-061`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's the next stop?** — 다음 정류장 `T-MET-062`
- **What's the quickest way to get to the station?** — 가장 빠른 방법 `T-MET-063`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **The gate won't open.** — 개찰구 안 열림 `T-MET-064`
- **My ticket isn't working.** — 표 인식 안 됨 `T-MET-065`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **I think I was charged twice.** — 이중 결제 `T-MET-066`

**C12 · I'm just ___** — 가벼운 상태 설명

- **I'm sorry, I'm a tourist — I didn't know I had to validate it.** — 검표 시 해명 `T-MET-067`

**C13 · I'm running late / I missed ___** — 지연·놓침

- **I missed the last train. How else can I get back?** — 막차 놓침 `T-MET-068`

**D02 · Sorry, I didn't catch ___** — 못 들었음

- **Sorry, what was that stop?** — 정류장 방송 놓침 `T-MET-069`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **So I get off at the fourth stop?** — 하차 정류장 확인 `T-MET-070`

**E09 · Excuse me, ___** — 말 걸기

- ★ **Excuse me, I'm getting off.** — 하차하며 비켜 달라 `T-MET-071`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Sorry, this is my stop.** — 하차 (구어) `T-MET-072`
- **Please, take my seat.** — 자리 양보 `T-MET-073`
- **Thanks, that's really helpful.** — 도움 받은 뒤 `T-MET-074`
- **It's packed — let's wait for the next one.** — 만원 차량 `T-MET-075`

### `T-TAX` 택시·라이드셰어·공항 이동

*상황 66개 · ★ 6개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- ★ **Could I get a receipt?** — 영수증 `T-TAX-001`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- ★ **Could you call a taxi for me?** — 택시 호출 부탁 `T-TAX-002`
- **Could you book a taxi to the airport for 6 a.m.?** — 공항 택시 예약 `T-TAX-003`
- **Could you turn on the meter, please?** — 미터기 켜 달라 `T-TAX-004`
- **Could you open the trunk?** — 트렁크 열어 달라 `T-TAX-005`
- **Could you help me with my bags?** — 짐 실어 달라 `T-TAX-006`
- **Could you turn up the air conditioning?** — 에어컨 `T-TAX-007`
- **Could you drive a bit slower, please?** — 천천히 `T-TAX-008`
- **I'm in a bit of a hurry. Could you take the fastest route?** — 가장 빠른 길 `T-TAX-009`
- **Could you stop here, please?** — 여기 세워 달라 `T-TAX-010`
- **Could you drop me off at the corner?** — 모퉁이에 내려 달라 `T-TAX-011`
- **Could you pull up at the main entrance?** — 정문 앞 `T-TAX-012`
- **Could you wait here for five minutes?** — 잠깐 기다려 달라 `T-TAX-013`
- **Could you put the company name on the receipt?** — 회사명 영수증 `T-TAX-014`
- **Could you help me contact the driver?** — 기사 연락 도움 `T-TAX-015`
- **Could you avoid the highway?** — 고속도로 피해 `T-TAX-016`
- **Could you open the window a bit?** — 창문 조금 `T-TAX-017`
- **Could you turn the music down a little?** — 음악 소리 줄이기 `T-TAX-018`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- **I'd like to go to the central station.** — 중앙역으로 `T-TAX-019`
- **I'd like to book the airport shuttle.** — 공항 셔틀 예약 `T-TAX-020`

**A05 · ___, please.** — 최소 단위 요청

- ★ **To the Hilton, please.** — 목적지 (최소) `T-TAX-021`
- **To this address, please.** — 주소 제시 `T-TAX-022`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can I pay by card?** — 카드 결제 `T-TAX-023`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- ★ **Where's the taxi rank?** — 택시 승차장 `T-TAX-024`
- **Where's the pickup point for ride-hailing?** — 라이드 픽업 위치 `T-TAX-025`
- **Where do I catch the shuttle?** — 셔틀 탑승 위치 `T-TAX-026`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there a hotel shuttle?** — 호텔 셔틀 `T-TAX-027`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time does the shuttle leave?** — 셔틀 출발 시각 `T-TAX-028`
- **What time should I leave for a 9 a.m. flight?** — 출발 권장 시각 `T-TAX-029`
- **What time do you think we'll get there?** — 도착 예상 시각 `T-TAX-030`

**B06 · How long ___?** — 소요 시간·기간

- **How long will it take?** — 소요 시간 `T-TAX-031`
- **How long does it take to get to the airport in the morning?** — 아침 공항 소요 `T-TAX-032`

**B07 · How much ___?** — 가격·양

- ★ **How much is it to the city center?** — 예상 요금 `T-TAX-033`
- **Roughly how much would it be to the airport?** — 공항까지 대략 `T-TAX-034`
- **How much should I tip?** — 팁 금액 `T-TAX-035`
- **How much is the shuttle?** — 셔틀 요금 `T-TAX-036`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is there a flat rate to the airport?** — 정액 요금 여부 `T-TAX-037`
- **Do you use the meter?** — 미터기 사용 여부 `T-TAX-038`
- **Do you take cards?** — 카드 단말기 `T-TAX-039`
- **Is the traffic bad right now?** — 교통 체증 `T-TAX-040`
- **Is this the right place?** — 여기 맞는지 `T-TAX-041`
- **Is Uber available here?** — 우버 이용 가능 `T-TAX-042`
- **Are you my driver? Is this for Kim?** — 기사 확인 `T-TAX-043`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to tip?** — 팁 필수 여부 `T-TAX-044`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Is the airport surcharge included?** — 공항 할증 포함 `T-TAX-045`
- **Is the shuttle free?** — 셔틀 무료 여부 `T-TAX-046`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- **Any restaurants you'd recommend near my hotel?** — 기사에게 맛집 추천 `T-TAX-047`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's this extra charge for?** — 추가 요금 사유 `T-TAX-048`

**C02 · I'm here for ___ / I'm here to ___** — 방문 목적

- **I'm here for a conference.** — 기사 질문에 답 `T-TAX-049`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **I think the fare is a bit high.** — 요금 이상 `T-TAX-050`
- **I think we're going the long way.** — 돌아가는 길 의심 `T-TAX-051`

**C06 · I lost ___ / I can't find ___ / I left ___** — 분실

- **I left my phone in a taxi.** — 택시에 휴대폰 두고 내림 `T-TAX-052`

**C13 · I'm running late / I missed ___** — 지연·놓침

- **I'm running late for my flight.** — 비행기 시간 촉박 `T-TAX-053`

**C14 · I was told ___** — 근거 제시

- **I was told it's a flat rate of 40 euros.** — 정액이라고 안내 받음 `T-TAX-054`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **Just to confirm, the plate ends in 47?** — 차량 번호 확인 `T-TAX-055`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **Do you mean the front entrance?** — 입구 확인 `T-TAX-056`

**E04 · Where are you ___?** — 출신·소속·숙소

- **Are you from here originally?** — 기사 출신 `T-TAX-057`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Here's the address.** — 주소 보여주기 `T-TAX-058`
- ★ **Keep the change.** — 거스름돈은 됐다 `T-TAX-059`
- **Make it 30, please.** — 팁 포함해 금액 말하기 `T-TAX-060`
- **I'm standing by the main entrance.** — 내 위치 설명 `T-TAX-061`
- **I'm next to the blue sign.** — 내 위치 설명 2 `T-TAX-062`
- **Busy day today?** — 기사와 가벼운 대화 `T-TAX-063`
- **Thanks, have a good day.** — 도착 인사 `T-TAX-064`
- **Terminal 1, please.** — 터미널 지정 `T-TAX-065`
- **This is fine, thanks.** — 여기서 내려도 됨 `T-TAX-066`

### `T-CAR` 렌터카·운전

*상황 43개 · ★ 2개*


**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you note this scratch before I leave?** — 흠집 기록 `T-CAR-001`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- **I'd like to pick up my rental car.** — 차량 인수 `T-CAR-002`

**A05 · ___, please.** — 최소 단위 요청

- **Fill it up, please.** — 가득 주유 `T-CAR-003`

**A08 · I need (to) ___** — 필요를 직접 밝힘

- **I need roadside assistance.** — 긴급 출동 `T-CAR-004`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can I drop it off at the airport?** — 타 지점 반납 `T-CAR-005`
- **Can I park here?** — 주차 가능 여부 `T-CAR-006`
- **Can I add a second driver?** — 추가 운전자 `T-CAR-007`

**A12 · I'd prefer ___ / I'd rather ___** — 선호 표현

- **I'd prefer an automatic.** — 자동변속 선호 `T-CAR-008`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where can I buy a vignette?** — 비넷 구매처 `T-CAR-009`
- **Where do I drop it off?** — 반납 장소 `T-CAR-010`
- **Where's the nearest gas station?** — 주유소 `T-CAR-011`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How do I change the GPS to English?** — 내비 언어 변경 `T-CAR-012`
- **How do I pay for parking here?** — 주차 정산 `T-CAR-013`
- **How does this pump work?** — 셀프 주유기 `T-CAR-014`
- **How do I use a parking disc?** — 주차 디스크 사용 `T-CAR-015`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there parking nearby?** — 주차장 `T-CAR-016`
- **Is there an EV charging station nearby?** — 전기차 충전소 `T-CAR-017`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time do I need to return it?** — 반납 시각 `T-CAR-018`

**B07 · How much ___?** — 가격·양

- **How much is full coverage per day?** — 완전 면책 비용 `T-CAR-019`
- **How much is parking per hour?** — 주차 요금 `T-CAR-020`
- **How much is it for an additional driver?** — 추가 운전자 비용 `T-CAR-021`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is it an automatic?** — 자동변속 여부 `T-CAR-022`
- **Is it diesel or petrol?** — 연료 종류 `T-CAR-023`
- **Is it okay to drive into the city center? Do I need an environmental sticker?** — 도심 진입 규제 `T-CAR-024`
- **Does it have winter tires?** — 겨울 타이어 `T-CAR-025`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do you need my international driving permit?** — 국제면허 필요 `T-CAR-026`
- **Do I need to return it with a full tank?** — 가득 채워 반납 `T-CAR-027`
- **Do I need a vignette for the highway in Austria?** — 오스트리아 비넷 `T-CAR-028`
- **Do I need a parking ticket?** — 주차권 필요 `T-CAR-029`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- ★ **Is insurance included?** — 보험 포함 여부 `T-CAR-030`
- **Does it come with full coverage?** — 완전 면책 `T-CAR-031`
- **Are tolls included?** — 통행료 포함 `T-CAR-032`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's the fuel policy?** — 연료 규정 `T-CAR-033`
- **What's the number for breakdown assistance?** — 고장 긴급번호 `T-CAR-034`

**C01 · I have a reservation ___ / I booked ___** — 예약 사실 제시

- ★ **I have a reservation under Kim.** — 렌터카 예약 `T-CAR-035`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **The car won't start.** — 시동 안 걸림 `T-CAR-036`
- **A warning light came on.** — 경고등 `T-CAR-037`
- **I've got a flat tire.** — 타이어 펑크 `T-CAR-038`
- **The pump isn't accepting my card.** — 주유기 카드 거부 `T-CAR-039`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **I think I've been charged for fuel, but I returned it full.** — 연료 청구 오류 `T-CAR-040`

**D07 · Let me ___** — 시간 벌기·행동 예고

- **Let me take some photos first.** — 사진 기록 `T-CAR-041`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Here's my license and international permit.** — 면허 제시 `T-CAR-042`
- **Number 4, please.** — 주유기 번호 `T-CAR-043`

### `T-DIR` 길 묻기·위치 찾기

*상황 61개 · ★ 3개*


**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you show me on the map?** — 지도에서 보여 달라 `T-DIR-001`
- **Could you draw me a quick map?** — 약도 그려 달라 `T-DIR-002`
- **Could you point me in the right direction?** — 방향만 알려 달라 `T-DIR-003`

**A14 · I'm looking for ___** — 찾는 물건·장소 설명

- ★ **I'm looking for the conference center — the ICC.** — 찾는 장소 설명 `T-DIR-004`
- **I'm looking for a drugstore.** — 찾는 가게 `T-DIR-005`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where's the nearest S-Bahn station?** — 가까운 역 `T-DIR-006`
- **Where are we on this map?** — 지도상 현재 위치 `T-DIR-007`
- **Where's the entrance?** — 입구 위치 `T-DIR-008`
- **Where do I buy tickets?** — 매표 위치 `T-DIR-009`
- **Where are the elevators?** — 엘리베이터 위치 `T-DIR-010`
- **Where can I get a taxi around here?** — 택시 잡을 곳 `T-DIR-011`
- **Where's the entrance to the underground passage?** — 지하도 입구 `T-DIR-012`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- ★ **How do I get to the Pergamon Museum?** — 경로 묻기 `T-DIR-013`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there a supermarket around here?** — 근처 슈퍼 `T-DIR-014`
- **Is there a shortcut?** — 지름길 `T-DIR-015`
- **Are there any areas I should avoid at night?** — 피할 지역 `T-DIR-016`
- **Is there a lift?** — 리프트 유무 `T-DIR-017`
- **Is there a public restroom nearby?** — 공중화장실 `T-DIR-018`
- **Is there a park nearby?** — 근처 공원 `T-DIR-019`
- **Is there somewhere I can sit down for a bit?** — 쉴 곳 `T-DIR-020`
- **Is there an ATM nearby?** — 근처 ATM `T-DIR-021`
- **Is there a pharmacy near here?** — 근처 약국 `T-DIR-022`
- **Is there anything open late around here?** — 늦게까지 여는 곳 `T-DIR-023`

**B05 · What time ___? / When ___?** — 시각·시점

- **How late is it open?** — 몇 시까지 영업 `T-DIR-024`

**B06 · How long ___?** — 소요 시간·기간

- **How long does it take on foot?** — 도보 시간 `T-DIR-025`

**B08 · Which ___?** — 선택지 중 특정

- **Which way is the river?** — 강 방향 `T-DIR-026`
- **Which exit is closest to the hotel?** — 가장 가까운 출구 `T-DIR-027`
- **Which building is it?** — 건물 `T-DIR-028`
- **Which floor is it on?** — 층 `T-DIR-029`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is this the way to the cathedral?** — 방향 확인 `T-DIR-030`
- **Is it within walking distance?** — 도보 거리 여부 `T-DIR-031`
- **Is it far?** — 먼지 `T-DIR-032`
- **Is this area safe at night?** — 밤 치안 `T-DIR-033`
- **Are you going that way too?** — 같은 방향인지 `T-DIR-034`
- **Is it open now?** — 지금 영업 여부 `T-DIR-035`
- **Is this the right street for the hotel?** — 호텔 거리 맞는지 `T-DIR-036`
- **Is it faster to walk or take the bus?** — 도보 vs 버스 `T-DIR-037`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to pay to use the restroom?** — 유료 화장실 여부 `T-DIR-038`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- **What's the best way to get there?** — 가장 좋은 방법 `T-DIR-039`
- **Can you recommend a nice walk around here?** — 산책 경로 추천 `T-DIR-040`

**B13 · Do you know ___? / Do you happen to know ___?** — 정보 보유 여부

- **Do you know where the Hotel Adlon is?** — 아는지 묻기 `T-DIR-041`
- **Do you happen to know where the post office is?** — 부드럽게 묻기 `T-DIR-042`
- **Do you know which building the medical history museum is in?** — 건물 위치 `T-DIR-043`

**B14 · Could you tell me ___?** — 간접 의문 (정중)

- **Could you tell me where the conference center is?** — 정중히 묻기 `T-DIR-044`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's this street called?** — 거리 이름 `T-DIR-045`

**C03 · I'm heading to ___** — 목적지·이동 중

- **I'm heading to the conference venue.** — 목적지 알리기 `T-DIR-046`
- **I'm meeting a friend at the Brandenburg Gate.** — 약속 장소로 가는 중 `T-DIR-047`

**C06 · I lost ___ / I can't find ___ / I left ___** — 분실

- **I can't find my hotel.** — 호텔을 못 찾음 `T-DIR-048`

**C07 · I have ___ / I feel ___** — 증상·상태

- **I think I'm lost.** — 길을 잃은 것 같음 `T-DIR-049`

**D01 · Sorry, could you say that again?** — 반복 요청

- **Sorry, could you go over that again, slowly?** — 천천히 다시 설명 `T-DIR-050`

**D02 · Sorry, I didn't catch ___** — 못 들었음

- **Sorry, I didn't catch that — left or right?** — 좌우를 못 들음 `T-DIR-051`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **Just to make sure — past the church, then left?** — 이해 확인 `T-DIR-052`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **So I go straight and then turn left at the lights?** — 방향 되묻기 `T-DIR-053`
- **The second street on the right?** — 두 번째 골목 `T-DIR-054`
- **Do you mean the big tower with the ball on top?** — 랜드마크 확인 `T-DIR-055`

**E07 · Thanks for ___** — 감사

- **Thanks, that's really helpful.** — 길 안내 감사 `T-DIR-056`

**E09 · Excuse me, ___** — 말 걸기

- ★ **Excuse me, could you help me? I'm a bit lost.** — 길 묻기 시작 `T-DIR-057`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **This is the address I'm looking for.** — 찾는 주소 보여주기 `T-DIR-058`
- **Sorry, I'm a tourist myself.** — 남이 길을 물었을 때 (모름) `T-DIR-059`
- **That building over there?** — 가리키며 확인 `T-DIR-060`
- **Great, I think I can find it now.** — 이제 찾을 수 있음 `T-DIR-061`

### `T-HTL1` 호텔 체크인·체크아웃

*상황 74개 · ★ 10개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get a quiet room?** — 조용한 방 `T-HTL1-001`
- **Could I get a room on a higher floor?** — 높은 층 `T-HTL1-002`
- **Could I get a room away from the elevator?** — 엘리베이터에서 먼 방 `T-HTL1-003`
- **Could I get two key cards?** — 카드키 두 장 `T-HTL1-004`
- **Could I get a receipt?** — 영수증 `T-HTL1-005`
- **Could I get an invoice with my company's name?** — 회사명 인보이스 `T-HTL1-006`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- ★ **Could you print this for me?** — 인쇄 부탁 `T-HTL1-007`
- **Could you give me a wake-up call at six?** — 모닝콜 `T-HTL1-008`
- **Could you book a taxi for tomorrow morning?** — 택시 예약 `T-HTL1-009`
- **Could you make a dinner reservation for me?** — 식당 예약 대행 `T-HTL1-010`
- **Could you email me the invoice?** — 인보이스 이메일 `T-HTL1-011`
- **Could you print an itemized bill?** — 상세 청구서 `T-HTL1-012`
- **Could you have my bags sent up to the room?** — 짐 객실로 `T-HTL1-013`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- **I'd like to check in, please.** — 체크인 요청 `T-HTL1-014`
- ★ **I'd like to check out, please.** — 체크아웃 `T-HTL1-015`
- **I'd like to cancel one night.** — 하루 취소 `T-HTL1-016`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- ★ **Would it be possible to check in early?** — 얼리 체크인 `T-HTL1-017`
- **Would it be possible to check out late?** — 레이트 체크아웃 `T-HTL1-018`
- **Would it be possible to upgrade my room?** — 객실 업그레이드 `T-HTL1-019`
- **Would it be possible to change rooms?** — 객실 변경 `T-HTL1-020`
- **Would it be possible to stay one more night?** — 하루 연장 `T-HTL1-021`
- **Would it be possible to add an extra bed?** — 엑스트라 베드 `T-HTL1-022`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- ★ **Can I leave my bags here until check-in?** — 체크인 전 짐 맡기기 `T-HTL1-023`
- **Can I use a different card for the deposit?** — 다른 카드로 보증 `T-HTL1-024`
- **Can I leave my luggage here until four?** — 체크아웃 후 짐 맡기기 `T-HTL1-025`

**A12 · I'd prefer ___ / I'd rather ___** — 선호 표현

- **I'd prefer twin beds.** — 트윈 베드 `T-HTL1-026`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where's breakfast served?** — 조식 장소 `T-HTL1-027`
- **Where are the elevators?** — 엘리베이터 위치 `T-HTL1-028`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there a gym?** — 헬스장 `T-HTL1-029`
- **Is there a laundry service?** — 세탁 서비스 `T-HTL1-030`
- **Is there somewhere to store luggage after checkout?** — 체크아웃 후 짐 보관 `T-HTL1-031`
- **Do you have any rooms available tonight?** — 오늘 빈방 `T-HTL1-032`
- **Is there a vending machine?** — 자판기 `T-HTL1-033`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have parking?** — 주차 `T-HTL1-034`
- **Do you have a plug adapter I could borrow?** — 어댑터 대여 `T-HTL1-035`
- **Do you have an umbrella I could borrow?** — 우산 대여 `T-HTL1-036`
- **Do you have a printer guests can use?** — 투숙객 프린터 `T-HTL1-037`
- **Do you have a city map?** — 시내 지도 `T-HTL1-038`

**B05 · What time ___? / When ___?** — 시각·시점

- ★ **What time is checkout?** — 체크아웃 시각 `T-HTL1-039`
- **What time is check-in?** — 체크인 시각 `T-HTL1-040`
- **What time is breakfast?** — 조식 시간 `T-HTL1-041`
- **When will the deposit be released?** — 보증금 해제 시점 `T-HTL1-042`
- **What are the gym hours?** — 헬스장 운영 시간 `T-HTL1-043`

**B07 · How much ___?** — 가격·양

- **Is there a charge for early check-in?** — 얼리 체크인 비용 `T-HTL1-044`
- **How much is late checkout?** — 레이트 체크아웃 비용 `T-HTL1-045`
- **How much is the city tax?** — 도시세 금액 `T-HTL1-046`
- **How much is the deposit?** — 보증금 액수 `T-HTL1-047`
- **How much is it per night?** — 1박 요금 `T-HTL1-048`
- **Is there a cancellation fee?** — 취소 수수료 `T-HTL1-049`
- **How much is it to add breakfast?** — 조식 추가 비용 `T-HTL1-050`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- ★ **Is the room ready?** — 방 준비 여부 `T-HTL1-051`
- **Is this a non-smoking room?** — 금연 객실 여부 `T-HTL1-052`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do you need a deposit?** — 보증금 필요 `T-HTL1-053`
- **Do I need a ticket to pick it up?** — 짐표 필요 여부 `T-HTL1-054`
- **Do you need a copy of my passport?** — 여권 사본 필요 `T-HTL1-055`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- ★ **Is breakfast included?** — 조식 포함 여부 `T-HTL1-056`
- **Is the Wi-Fi free?** — 와이파이 무료 여부 `T-HTL1-057`
- **Is the city tax included?** — 도시세 포함 `T-HTL1-058`
- **Does that include breakfast?** — 요금에 조식 포함 `T-HTL1-059`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- **Can you recommend a good restaurant nearby?** — 근처 식당 추천 `T-HTL1-060`

**B15 · What's the ___?** — 정보 항목 묻기

- ★ **What's the Wi-Fi password?** — 와이파이 비밀번호 `T-HTL1-061`
- **What's this charge for?** — 청구 항목 질문 `T-HTL1-062`

**C01 · I have a reservation ___ / I booked ___** — 예약 사실 제시

- ★ **Hi, I have a reservation under Kim.** — 체크인 기본 `T-HTL1-063`
- **I booked through Booking.com.** — 예약 경로 `T-HTL1-064`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- ★ **I think there's a mistake on my bill.** — 청구 오류 `T-HTL1-065`
- **I didn't use the minibar.** — 미니바 미사용 `T-HTL1-066`

**C13 · I'm running late / I missed ___** — 지연·놓침

- **I know it's early, but is my room ready?** — 일찍 도착 `T-HTL1-067`

**C14 · I was told ___** — 근거 제시

- **I was told breakfast was included.** — 조식 포함이라고 안내 받음 `T-HTL1-068`

**D01 · Sorry, could you say that again?** — 반복 요청

- **Sorry, what was the room number again?** — 방 번호 다시 `T-HTL1-069`

**E07 · Thanks for ___** — 감사

- **Thanks for all your help.** — 도움 감사 `T-HTL1-070`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Here's my confirmation number.** — 예약번호 제시 `T-HTL1-071`
- **Here's my credit card.** — 카드 제시 `T-HTL1-072`
- **Here's my key card.** — 카드키 반납 `T-HTL1-073`
- **We had a great stay, thank you.** — 숙박 만족 인사 `T-HTL1-074`

### `T-HTL2` 호텔 생활·문제 해결

*상황 75개 · ★ 3개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get a new key card?** — 새 카드키 `T-HTL2-001`
- ★ **Could I get some extra towels?** — 수건 추가 `T-HTL2-002`
- **Could I get an extra pillow?** — 베개 추가 `T-HTL2-003`
- **Could I have another blanket?** — 담요 추가 `T-HTL2-004`
- **Could I get some more toilet paper?** — 휴지 추가 `T-HTL2-005`
- **Could I get a toothbrush and toothpaste?** — 칫솔·치약 `T-HTL2-006`
- **Could I borrow a hair dryer?** — 헤어드라이어 `T-HTL2-007`
- **Could I borrow an iron?** — 다리미 `T-HTL2-008`
- **Could I get some more coffee pods?** — 커피 캡슐 추가 `T-HTL2-009`
- **Could I get a couple of bottles of water?** — 생수 `T-HTL2-010`
- **Could I get a pair of slippers?** — 슬리퍼 `T-HTL2-011`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you send someone to take a look?** — 직원 보내 달라 `T-HTL2-012`
- **Could you check it as soon as possible?** — 빠른 확인 요청 `T-HTL2-013`
- **Could you clean my room this afternoon?** — 청소 시간 요청 `T-HTL2-014`
- **Could you come back later?** — 나중에 와 달라 `T-HTL2-015`
- **Could you have this shirt pressed by tomorrow morning?** — 셔츠 다림질 `T-HTL2-016`
- **Could I order room service?** — 룸서비스 주문 시작 `T-HTL2-017`
- **Could you hold a package for me? I'm expecting a delivery.** — 택배 보관 `T-HTL2-018`
- **A colleague is coming to meet me. Could you call my room when she arrives?** — 방문객 안내 `T-HTL2-019`
- **Could you call a doctor for me?** — 의사 호출 `T-HTL2-020`
- **Could you prepare a breakfast box? I'm leaving before breakfast starts.** — 조식 박스 `T-HTL2-021`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- **I'd like to use the laundry service.** — 세탁 서비스 신청 `T-HTL2-022`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would it be possible to move to another room?** — 다른 방으로 이동 `T-HTL2-023`
- **Would it be possible to use the business center?** — 비즈니스센터 사용 `T-HTL2-024`

**A11 · I'll have ___ / I'll take ___** — 주문·구매 확정

- **I'll have the club sandwich and a sparkling water.** — 룸서비스 주문 `T-HTL2-025`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How do I switch the TV to English channels?** — TV 영어 채널 `T-HTL2-026`
- **How do I turn the AC down?** — 에어컨 조작 `T-HTL2-027`
- **How do I set the safe?** — 금고 설정 `T-HTL2-028`
- **How does the shower work?** — 샤워기 조작 `T-HTL2-029`
- **How do I get in if I come back late?** — 늦은 귀가 출입 `T-HTL2-030`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there a space where I could have a short meeting?** — 짧은 회의 공간 `T-HTL2-031`
- **Is there somewhere quiet I could work?** — 조용한 작업 공간 `T-HTL2-032`
- **Is there a microwave I could use?** — 전자레인지 `T-HTL2-033`
- **Is there a pharmacy close by?** — 가까운 약국 `T-HTL2-034`
- **Is there a 24-hour pharmacy around here?** — 24시간 약국 `T-HTL2-035`

**B05 · What time ___? / When ___?** — 시각·시점

- **When will my laundry be ready?** — 세탁 완료 시점 `T-HTL2-036`
- **Until what time is room service available?** — 룸서비스 마감 `T-HTL2-037`

**B06 · How long ___?** — 소요 시간·기간

- **How long will it take to fix?** — 수리 시간 `T-HTL2-038`
- **How long will it take?** — 룸서비스 소요 `T-HTL2-039`

**B07 · How much ___?** — 가격·양

- **How much is it per shirt?** — 셔츠당 세탁비 `T-HTL2-040`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Has a package arrived for me?** — 택배 도착 여부 `T-HTL2-041`
- **Are there any messages for me?** — 메시지 여부 `T-HTL2-042`
- **Is the tap water safe to drink?** — 수돗물 음용 `T-HTL2-043`
- **Is the front door locked at night?** — 야간 출입문 `T-HTL2-044`
- **Has anyone turned in a black charger?** — 분실물 접수 여부 `T-HTL2-045`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to pay to store my bags?** — 짐 보관 유료 여부 `T-HTL2-046`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Is the water in the room free?** — 객실 생수 무료 여부 `T-HTL2-047`
- **Is the minibar complimentary?** — 미니바 무료 여부 `T-HTL2-048`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- ★ **The air conditioning isn't working.** — 에어컨 고장 `T-HTL2-049`
- **The heating isn't working.** — 난방 고장 `T-HTL2-050`
- **There's no hot water.** — 온수 안 나옴 `T-HTL2-051`
- **The Wi-Fi keeps dropping.** — 와이파이 끊김 `T-HTL2-052`
- **The TV isn't working.** — TV 고장 `T-HTL2-053`
- **My key card isn't working.** — 카드키 작동 안 함 `T-HTL2-054`
- **I can't open the safe.** — 금고가 안 열림 `T-HTL2-055`
- **The toilet won't flush.** — 변기 물이 안 내려감 `T-HTL2-056`
- **The shower isn't draining.** — 샤워 배수 불량 `T-HTL2-057`
- **One of the lights is out.** — 전등 나감 `T-HTL2-058`
- **The power outlet near the desk doesn't work.** — 책상 콘센트 고장 `T-HTL2-059`
- **There's a lot of noise from next door.** — 옆방 소음 `T-HTL2-060`
- **The room smells of smoke.** — 담배 냄새 `T-HTL2-061`
- **The curtains don't close properly.** — 커튼이 안 닫힘 `T-HTL2-062`
- **The window won't open.** — 창문이 안 열림 `T-HTL2-063`
- **The fridge isn't cold.** — 냉장고 고장 `T-HTL2-064`
- **Water is leaking from the bathroom ceiling.** — 욕실 천장 누수 `T-HTL2-065`

**C06 · I lost ___ / I can't find ___ / I left ___** — 분실

- ★ **I locked myself out.** — 방 안에 키를 두고 잠김 `T-HTL2-066`
- **I lost my key card.** — 카드키 분실 `T-HTL2-067`
- **I think I left my charger in the room.** — 충전기 두고 나감 `T-HTL2-068`

**C07 · I have ___ / I feel ___** — 증상·상태

- **I'm not feeling well. Is there a doctor you could call?** — 몸이 안 좋음 `T-HTL2-069`

**C10 · I'm afraid ___** — 나쁜 소식·거절의 완곡

- **I'm afraid the room is still too noisy.** — 소음 불만 (완곡) `T-HTL2-070`

**C14 · I was told ___** — 근거 제시

- **I asked for extra towels an hour ago.** — 이전 요청 상기 `T-HTL2-071`

**E07 · Thanks for ___** — 감사

- **Thanks for sorting that out so quickly.** — 빠른 해결 감사 `T-HTL2-072`

**E08 · Sorry about ___ / Sorry to ___** — 사과

- **Sorry to bother you again.** — 다시 번거롭게 해서 `T-HTL2-073`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **No need to clean the room today, thanks.** — 청소 사양 `T-HTL2-074`
- **I'm fine for now, thank you.** — 지금은 괜찮다 `T-HTL2-075`

### `T-RST1` 레스토랑 예약·입장·주문

*상황 95개 · ★ 12개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could we get a table by the window?** — 창가 테이블 `T-RST1-001`
- ★ **Could we see the menu, please?** — 메뉴 요청 `T-RST1-002`
- **Could I see the wine list?** — 와인 리스트 `T-RST1-003`
- **Could I get it without the sauce?** — 소스 빼고 `T-RST1-004`
- **Could we get some more bread?** — 빵 추가 `T-RST1-005`
- ★ **Could we get some tap water, please?** — 수돗물 `T-RST1-006`
- **Could we get a bottle of the house white?** — 하우스 와인 한 병 `T-RST1-007`
- **Could we get an extra plate to share?** — 나눠 먹을 접시 `T-RST1-008`
- **Could I get another fork?** — 포크 추가 `T-RST1-009`
- **Could I get some napkins?** — 냅킨 `T-RST1-010`
- **Could I get some more of the sauce?** — 소스 추가 `T-RST1-011`
- **Could we see the dessert menu?** — 디저트 메뉴 `T-RST1-012`
- **Could we get it split onto two plates?** — 두 접시로 나눠 `T-RST1-013`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could we change our booking to eight instead?** — 예약 시각 변경 `T-RST1-014`
- **Could you go easy on the salt?** — 덜 짜게 `T-RST1-015`
- **Could you bring them out together?** — 함께 서빙 `T-RST1-016`
- **Could we have the starters first?** — 전채 먼저 `T-RST1-017`
- **Could you pass the salt, please?** — 일행에게 소금 부탁 `T-RST1-018`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- ★ **I'd like to make a reservation for two tonight.** — 예약 전화 `T-RST1-019`
- **I'd like to book a table for four at 7:30.** — 시각·인원 예약 `T-RST1-020`
- **I'd like to cancel my reservation.** — 예약 취소 `T-RST1-021`
- ★ **I'd like it medium-rare.** — 굽기 정도 `T-RST1-022`
- **I'd like the dressing on the side.** — 드레싱 따로 `T-RST1-023`
- **I'd like to book for a group of ten on Friday.** — 단체 예약 `T-RST1-024`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would it be possible to swap the fries for a salad?** — 사이드 교체 `T-RST1-025`
- **Would it be possible to push two tables together? We're a group of eight.** — 테이블 붙이기 `T-RST1-026`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can we wait at the bar?** — 바에서 대기 `T-RST1-027`
- **Can we sit outside?** — 야외 좌석 `T-RST1-028`
- **Is it okay if we move to that table?** — 테이블 이동 `T-RST1-029`
- **Actually, can I change my order?** — 주문 변경 `T-RST1-030`

**A11 · I'll have ___ / I'll take ___** — 주문·구매 확정

- ★ **I'll have the schnitzel, please.** — 주문 `T-RST1-031`
- **I'll have the same.** — 같은 것으로 `T-RST1-032`
- **I'll start with the soup.** — 전채 `T-RST1-033`
- **And then the fish for my main.** — 메인 `T-RST1-034`
- **I'll have a glass of the house red.** — 하우스 와인 한 잔 `T-RST1-035`
- **I'll have a small draft beer.** — 생맥주 `T-RST1-036`
- **I'll have the apple strudel.** — 디저트 주문 `T-RST1-037`
- **I'll have an espresso.** — 커피 주문 `T-RST1-038`
- **I'll go with your recommendation.** — 추천대로 주문 `T-RST1-039`

**A12 · I'd prefer ___ / I'd rather ___** — 선호 표현

- **We'd prefer somewhere a bit quieter.** — 조용한 자리 `T-RST1-040`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where's the restroom?** — 화장실 `T-RST1-041`

**B03 · Is there ___ (around here)?** — 존재 여부

- ★ **Do you have a table for two tonight?** — 오늘 빈 테이블 `T-RST1-042`
- **Do you have a set menu for groups?** — 단체 코스 `T-RST1-043`
- **Do you have a private room?** — 별실 `T-RST1-044`
- **Do you have Wi-Fi?** — 와이파이 `T-RST1-045`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have a table for two?** — 워크인 자리 `T-RST1-046`
- **Do you have an English menu?** — 영어 메뉴 `T-RST1-047`
- **Do you have any vegetarian dishes?** — 채식 메뉴 `T-RST1-048`
- **Do you have anything vegan?** — 비건 메뉴 `T-RST1-049`
- **Do you have gluten-free options?** — 글루텐프리 `T-RST1-050`
- **Do you have half portions?** — 반 접시 `T-RST1-051`
- **Do you have any non-alcoholic beer?** — 무알코올 맥주 `T-RST1-052`
- **Do you have any local wines?** — 지역 와인 `T-RST1-053`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time is the kitchen open until?** — 주방 마감 `T-RST1-054`
- **What time do you open for dinner?** — 저녁 영업 시작 `T-RST1-055`

**B06 · How long ___?** — 소요 시간·기간

- **How long is the wait?** — 대기 시간 `T-RST1-056`
- **How long does the food take?** — 조리 시간 `T-RST1-057`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is it spicy?** — 매운지 `T-RST1-058`
- **Is it a big portion?** — 양이 많은지 `T-RST1-059`
- **Is it enough for two to share?** — 둘이 나눠 먹기 `T-RST1-060`
- **Is tap water free here?** — 수돗물 무료 여부 `T-RST1-061`
- **Is it cash only?** — 현금만 받는지 `T-RST1-062`
- **Is one portion enough for one person?** — 1인분 양 `T-RST1-063`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need a reservation?** — 예약 필요 여부 `T-RST1-064`
- **Do we need to pay a deposit for a group booking?** — 단체 예약금 `T-RST1-065`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Does it come with a side?** — 사이드 포함 `T-RST1-066`
- **Is the bread included?** — 빵 포함 여부 `T-RST1-067`
- **Does it come with fries or salad?** — 감자튀김 또는 샐러드 `T-RST1-068`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- ★ **What do you recommend?** — 추천 `T-RST1-069`
- **Can you recommend something local?** — 현지 음식 추천 `T-RST1-070`
- **Which wine would you recommend with this?** — 와인 페어링 `T-RST1-071`
- **Which two mains would you recommend for sharing?** — 나눠 먹을 메인 추천 `T-RST1-072`

**B13 · Do you know ___? / Do you happen to know ___?** — 정보 보유 여부

- **Do you know if people usually tip here?** — 팁 관행 `T-RST1-073`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's the house specialty?** — 대표 메뉴 `T-RST1-074`
- **What's today's special?** — 오늘의 메뉴 `T-RST1-075`
- **What's in this dish?** — 재료 `T-RST1-076`
- **What do you have on tap?** — 생맥주 종류 `T-RST1-077`

**C01 · I have a reservation ___ / I booked ___** — 예약 사실 제시

- ★ **We have a reservation under Kim.** — 예약 확인 `T-RST1-078`

**C13 · I'm running late / I missed ___** — 지연·놓침

- **We're running about 15 minutes late. Is that okay?** — 늦을 것 같음 `T-RST1-079`

**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- ★ **What exactly is Eisbein?** — 메뉴 이름 뜻 `T-RST1-080`

**E05 · That sounds ___ / That's ___** — 반응·맞장구

- **That looks amazing.** — 음식 나왔을 때 반응 `T-RST1-081`

**E13 · I really enjoyed ___ / I loved ___** — 칭찬

- **I really enjoyed the fish.** — 요리 칭찬 `T-RST1-082`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **A table for two, please.** — 입장 시 인원 `T-RST1-083`
- **We don't have a reservation.** — 예약 없음 `T-RST1-084`
- ★ **Could we have a few more minutes?** — 아직 고르는 중 `T-RST1-085`
- **I think we're ready to order.** — 주문 준비 완료 `T-RST1-086`
- **And she'll have the risotto.** — 일행 주문 대신 `T-RST1-087`
- **Still water, please.** — 물 종류 질문에 답 (일반) `T-RST1-088`
- **Sparkling, please.** — 물 종류 질문에 답 (탄산) `T-RST1-089`
- **Cheers!** — 건배 `T-RST1-090`
- **That's all for now, thanks.** — 주문 끝 `T-RST1-091`
- **Just drinks for now.** — 일단 음료만 `T-RST1-092`
- ★ **I'm full, thanks.** — 디저트 사양 `T-RST1-093`
- **That was delicious.** — 맛있었다 `T-RST1-094`
- **Everything's great, thanks.** — 서버 확인에 답 `T-RST1-095`

### `T-RST2` 계산·문제·식이 제한

*상황 60개 · ★ 9개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- ★ **Could we get the check, please?** — 계산서 (미국식) `T-RST2-001`
- **Could we have the bill, please?** — 계산서 (영국식) `T-RST2-002`
- **Could I get a receipt?** — 영수증 `T-RST2-003`
- **Could I get an itemized receipt?** — 상세 영수증 (정산용) `T-RST2-004`
- ★ **Could I get a box for this?** — 남은 음식 포장 `T-RST2-005`
- **Could I get separate receipts?** — 영수증 분리 `T-RST2-006`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you add a ten percent tip?** — 카드에 팁 추가 `T-RST2-007`
- **Could you warm this up, please?** — 데워 달라 `T-RST2-008`
- **Could you make it again, please?** — 다시 만들어 달라 `T-RST2-009`
- **Could you check on our order?** — 주문 확인 요청 `T-RST2-010`
- **Could you check with the kitchen?** — 주방에 확인 `T-RST2-011`
- **Could you close the window a little?** — 창문 조금 닫기 `T-RST2-012`
- **Could you try this card instead?** — 다른 카드로 `T-RST2-013`
- **Could we get the bill? We're in a bit of a hurry.** — 급히 계산 `T-RST2-014`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- **I'd like to move to a quieter table, if possible.** — 조용한 테이블로 `T-RST2-015`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Could you split it between three cards?** — 카드 세 장으로 분할 `T-RST2-016`
- **Could you make it without the cheese?** — 치즈 빼고 `T-RST2-017`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- ★ **Can I pay by card?** — 카드 결제 `T-RST2-018`
- ★ **Can we pay separately?** — 각자 계산 `T-RST2-019`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have an allergen list?** — 알레르기 정보표 `T-RST2-020`

**B06 · How long ___?** — 소요 시간·기간

- **How much longer will it be?** — 남은 대기 `T-RST2-021`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Do you take cards?** — 카드 가능 여부 `T-RST2-022`
- ★ **Does this have nuts in it?** — 견과류 포함 여부 `T-RST2-023`
- **Is it made with meat stock?** — 고기 육수 여부 `T-RST2-024`
- **Is this gluten-free?** — 글루텐프리 여부 `T-RST2-025`
- **Is the service charge already on here?** — 봉사료 기재 여부 `T-RST2-026`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to sign?** — 서명 필요 `T-RST2-027`
- **Do I need to enter my PIN?** — PIN 입력 `T-RST2-028`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- ★ **Is service included?** — 봉사료 포함 여부 `T-RST2-029`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's this charge for?** — 청구 항목 `T-RST2-030`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- ★ **Our food hasn't arrived yet.** — 음식이 안 나옴 `T-RST2-031`
- **This isn't what I ordered.** — 잘못 나온 메뉴 `T-RST2-032`
- **My soup is a bit cold.** — 식은 음식 `T-RST2-033`
- **I think this chicken is a bit undercooked.** — 덜 익음 `T-RST2-034`
- **There's something in my salad.** — 이물질 `T-RST2-035`
- **My card isn't going through.** — 카드 승인 안 됨 `T-RST2-036`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- ★ **I think there's a mistake on the bill.** — 계산 오류 `T-RST2-037`
- **I don't think we ordered this.** — 안 시킨 메뉴 `T-RST2-038`
- **I think we've been charged twice for the wine.** — 와인 이중 청구 `T-RST2-039`
- **I think this is well-done — I asked for medium.** — 굽기 다름 `T-RST2-040`
- **I think the tip was already included.** — 팁 이중 부과 `T-RST2-041`

**C07 · I have ___ / I feel ___** — 증상·상태

- **It's a bit cold here.** — 자리가 추움 `T-RST2-042`

**C10 · I'm afraid ___** — 나쁜 소식·거절의 완곡

- **I'm afraid this isn't quite right.** — 문제 제기 (완곡) `T-RST2-043`
- **I'm afraid I can't eat this — it has nuts.** — 먹을 수 없음 `T-RST2-044`

**C11 · I don't eat ___ / I'm allergic to ___** — 식이 제한

- ★ **I'm allergic to nuts.** — 견과류 알레르기 `T-RST2-045`
- **I'm allergic to shellfish.** — 갑각류 알레르기 `T-RST2-046`
- **I don't eat pork.** — 돼지고기 안 먹음 `T-RST2-047`
- **I don't eat meat, but fish is fine.** — 육류 안 먹음 `T-RST2-048`
- **I can't have dairy.** — 유제품 불가 `T-RST2-049`
- **I don't drink alcohol.** — 술 안 마심 `T-RST2-050`

**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- **What's this "coperto" charge?** — 자릿세 뜻 (이탈리아 coperto) `T-RST2-051`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Just the check, please.** — 계산만 (구어) `T-RST2-052`
- **I'll get this one.** — 내가 계산 `T-RST2-053`
- **It's on me.** — 내가 쏜다 `T-RST2-054`
- **You can get the next one.** — 다음엔 네가 `T-RST2-055`
- **Make it 50, please.** — 팁 포함 금액 `T-RST2-056`
- **Keep the change.** — 거스름돈은 됐다 `T-RST2-057`
- **That's okay, it happens.** — 사과 받을 때 `T-RST2-058`
- **Thanks, everything was lovely.** — 떠나며 인사 `T-RST2-059`
- **Compliments to the chef.** — 주방장 칭찬 `T-RST2-060`

### `T-CAF` 카페·베이커리·바

*상황 54개 · ★ 3개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- ★ **Could I get a flat white, please?** — 커피 주문 `T-CAF-001`
- **Could I get a large cappuccino?** — 큰 사이즈 `T-CAF-002`
- **Could I get that decaf?** — 디카페인 `T-CAF-003`
- **Could I get it with oat milk?** — 오트 우유 `T-CAF-004`
- **Could I get an iced latte?** — 아이스 라테 `T-CAF-005`
- **Could I get a glass of water too?** — 물 한 잔 `T-CAF-006`
- **Could I get something non-alcoholic?** — 무알코올 음료 `T-CAF-007`
- **Could I close my tab, please?** — 탭 계산 `T-CAF-008`
- **Could I get an extra shot?** — 샷 추가 `T-CAF-009`
- **Could I get some hot water?** — 뜨거운 물 `T-CAF-010`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you make it a bit less sweet?** — 덜 달게 `T-CAF-011`
- **Could you make it extra hot?** — 더 뜨겁게 `T-CAF-012`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- **I'd like a pint of the local lager.** — 바: 맥주 주문 `T-CAF-013`

**A05 · ___, please.** — 최소 단위 요청

- **That one, please.** — 가리키며 `T-CAF-014`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Is it okay if I work here for a while?** — 노트북 작업 `T-CAF-015`
- **Can I get you a drink?** — 한 잔 사주기 `T-CAF-016`
- **Can I start a tab?** — 외상 탭 열기 `T-CAF-017`

**A10 · Do you mind if I ___?** — 상대를 배려한 허락

- **Do you mind if I share this table?** — 합석 `T-CAF-018`

**A11 · I'll have ___ / I'll take ___** — 주문·구매 확정

- **I'll take one of those croissants.** — 빵 고르기 `T-CAF-019`
- **I'll take two of these.** — 두 개 주문 `T-CAF-020`
- **I'll have a glass of Riesling.** — 와인 한 잔 `T-CAF-021`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where's the sugar?** — 설탕 위치 `T-CAF-022`
- **Where should I put my cup?** — 컵 반납 `T-CAF-023`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have iced coffee?** — 아이스커피 여부 `T-CAF-024`
- **Do you have soy milk?** — 두유 `T-CAF-025`
- **Do you have any sweetener?** — 대체 감미료 `T-CAF-026`
- **Do you have any snacks?** — 안주 `T-CAF-027`
- **Do you have anything sugar-free?** — 무설탕 `T-CAF-028`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time do you close?** — 폐점 시각 `T-CAF-029`
- **When's happy hour?** — 해피아워 `T-CAF-030`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Do you have Wi-Fi?** — 와이파이 여부 `T-CAF-031`
- **Is there a power outlet I could use?** — 콘센트 `T-CAF-032`
- ★ **Is this seat taken?** — 자리 비었는지 `T-CAF-033`
- **Do I order at the counter?** — 카운터 주문인지 `T-CAF-034`
- **Is there a code for the restroom?** — 화장실 비밀번호 여부 `T-CAF-035`
- **Is it last orders?** — 라스트 오더 `T-CAF-036`
- **Is this one gluten-free?** — 글루텐프리 빵 `T-CAF-037`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I pay now or later?** — 선결제 `T-CAF-038`
- **Do I need to take a number?** — 번호표 `T-CAF-039`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- **What would you recommend from the local beers?** — 바: 현지 맥주 추천 `T-CAF-040`
- **Any good bars around here you'd recommend?** — 근처 바 추천 `T-CAF-041`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's the Wi-Fi password?** — 와이파이 비밀번호 `T-CAF-042`
- **What's the code for the restroom?** — 화장실 비밀번호 `T-CAF-043`
- **What wines do you have by the glass?** — 잔 와인 종류 `T-CAF-044`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **I think you forgot my muffin.** — 주문 누락 `T-CAF-045`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **Sorry, I think this is someone else's.** — 다른 사람 음료 `T-CAF-046`

**D08 · How do you say ___? / What do you call ___?** — 어휘·발음 묻기

- **What do you call this pastry?** — 빵 이름 `T-CAF-047`

**E05 · That sounds ___ / That's ___** — 반응·맞장구

- **This is really good.** — 맛 반응 `T-CAF-048`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **To go, please.** — 포장 `T-CAF-049`
- **For here, please.** — 매장 이용 `T-CAF-050`
- **No, the one next to it.** — 옆 것이라고 정정 `T-CAF-051`
- **That's mine, thanks.** — 내 이름 불렸을 때 `T-CAF-052`
- **Same again, please.** — 같은 것 한 잔 더 `T-CAF-053`
- **I'm fine, thanks. I've still got one.** — 술 사양 (아직 있음) `T-CAF-054`

### `T-SHP` 쇼핑·면세·환불

*상황 77개 · ★ 14개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- ★ **Could I get a bag?** — 봉투 `T-SHP-001`
- **Could I get these wrapped separately?** — 따로 포장 `T-SHP-002`
- ★ **Could I get a receipt?** — 영수증 `T-SHP-003`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- ★ **Could you gift-wrap it?** — 선물 포장 `T-SHP-004`
- **Could you take the price tag off?** — 가격표 제거 `T-SHP-005`
- **Could you wrap it so it won't break?** — 깨지지 않게 포장 `T-SHP-006`
- **Could you hold it for me until tomorrow?** — 내일까지 보관 `T-SHP-007`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- ★ **I'd like to exchange this.** — 교환 `T-SHP-008`
- ★ **I'd like a refund, please.** — 환불 `T-SHP-009`
- **I'd like to return this.** — 반품 `T-SHP-010`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would you take 30 euros for it?** — 벼룩시장 흥정 `T-SHP-011`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- ★ **Can I try this on?** — 입어 보기 `T-SHP-012`
- **Can I pay by card?** — 카드 결제 `T-SHP-013`
- ★ **Can I get a tax-free form?** — 택스리펀드 서류 `T-SHP-014`

**A11 · I'll have ___ / I'll take ___** — 주문·구매 확정

- ★ **I'll take it.** — 구매 결정 `T-SHP-015`
- **I'll take both.** — 둘 다 구매 `T-SHP-016`

**A12 · I'd prefer ___ / I'd rather ___** — 선호 표현

- **I'd prefer it in navy.** — 다른 색 선호 `T-SHP-017`

**A14 · I'm looking for ___** — 찾는 물건·장소 설명

- ★ **I'm looking for a gift for my wife.** — 선물 찾기 `T-SHP-018`
- **I'm looking for something typical from Germany.** — 기념품 찾기 `T-SHP-019`
- **I'm looking for a rain jacket.** — 특정 상품 `T-SHP-020`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where are the fitting rooms?** — 탈의실 `T-SHP-021`
- **Where do I get the stamp at the airport?** — 공항 리펀드 도장 위치 `T-SHP-022`
- **Where can I find the bottled water?** — 마트 물건 위치 `T-SHP-023`
- **Where do I return empty bottles?** — 빈병 반납 `T-SHP-024`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How does the tax refund work?** — 택스리펀드 절차 `T-SHP-025`
- **How does the self-checkout work?** — 셀프 계산대 `T-SHP-026`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there any discount if I buy two?** — 두 개 할인 `T-SHP-027`
- **Is there a supermarket nearby?** — 근처 슈퍼 `T-SHP-028`

**B04 · Do you have ___?** — 보유·재고 여부

- ★ **Do you have this in a medium?** — 사이즈 재고 `T-SHP-029`
- **Do you have this in black?** — 색상 재고 `T-SHP-030`
- **Do you have this in a larger size?** — 더 큰 사이즈 `T-SHP-031`
- **Do you have any more in the back?** — 창고 재고 `T-SHP-032`
- **Do you ship to Korea?** — 한국 배송 `T-SHP-033`
- **Do you have any other models?** — 다른 모델 `T-SHP-034`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time do you close?** — 폐점 시각 `T-SHP-035`

**B06 · How long ___?** — 소요 시간·기간

- **How long do I have to return it?** — 반품 기한 `T-SHP-036`
- **How long would it take?** — 배송 기간 `T-SHP-037`

**B07 · How much ___?** — 가격·양

- ★ **How much is this?** — 가격 `T-SHP-038`
- **How much is it with the discount?** — 할인 적용가 `T-SHP-039`
- **How much is a bag?** — 봉투 가격 `T-SHP-040`
- **How much is shipping to Korea?** — 한국 배송비 `T-SHP-041`

**B08 · Which ___?** — 선택지 중 특정

- **Which aisle is the coffee in?** — 통로 `T-SHP-042`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is this on sale?** — 세일 품목 여부 `T-SHP-043`
- **Do you take credit cards?** — 신용카드 가능 여부 `T-SHP-044`
- **Will the refund go back to my card?** — 카드로 환불 여부 `T-SHP-045`
- **Are you open on Sundays?** — 일요일 영업 여부 `T-SHP-046`
- **Is this made locally?** — 현지 생산 여부 `T-SHP-047`
- **Is it okay to take this on the plane?** — 기내 반입 (술) `T-SHP-048`
- **Will this work in Korea?** — 한국에서 사용 가능 `T-SHP-049`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do you need my passport?** — 여권 필요 여부 `T-SHP-050`
- **Do I need the receipt?** — 영수증 필요 여부 `T-SHP-051`
- **Do I need to weigh the fruit myself?** — 과일 직접 계량 `T-SHP-052`
- **Is there a deposit on these bottles?** — 병 보증금 (독일 Pfand) `T-SHP-053`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Does the price include tax?** — 세금 포함 여부 `T-SHP-054`
- **Does it come with a warranty?** — 보증 포함 `T-SHP-055`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- **What would you recommend as a gift?** — 선물 추천 `T-SHP-056`
- **What's popular with tourists?** — 관광객 인기 상품 `T-SHP-057`
- **What would you recommend for around 50 euros?** — 가격대 맞춤 추천 `T-SHP-058`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's the minimum amount for a tax refund?** — 택스리펀드 최소 금액 `T-SHP-059`
- **What's it made of?** — 소재 `T-SHP-060`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **It's damaged.** — 하자 `T-SHP-061`
- **It doesn't work.** — 작동 불량 `T-SHP-062`
- **The self-checkout isn't scanning this.** — 셀프 계산 인식 불가 `T-SHP-063`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **I bought the wrong size.** — 사이즈 착오 `T-SHP-064`

**C12 · I'm just ___** — 가벼운 상태 설명

- ★ **I'm just looking, thanks.** — 구경만 할 때 `T-SHP-065`
- **I'm just checking the price.** — 가격만 확인 `T-SHP-066`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **So that's 89 including tax?** — 세금 포함 총액 확인 `T-SHP-067`

**E09 · Excuse me, ___** — 말 걸기

- ★ **Excuse me, could you help me?** — 점원 부르기 `T-SHP-068`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **It fits perfectly.** — 잘 맞음 `T-SHP-069`
- **It's a bit tight.** — 꽉 낌 `T-SHP-070`
- **It's a little too big.** — 큼 `T-SHP-071`
- **It's a bit long.** — 김 `T-SHP-072`
- **I'll think about it.** — 생각해 보겠다 `T-SHP-073`
- ★ **In euros, please.** — 현지 통화 결제 선택 (DCC 회피) `T-SHP-074`
- **I don't need a bag, thanks.** — 봉투 불필요 `T-SHP-075`
- **I have the receipt.** — 영수증 있음 `T-SHP-076`
- **Thanks, but I'll pass.** — 정중한 거절 `T-SHP-077`

### `T-SGT` 관광·박물관·공연·투어

*상황 72개 · ★ 4개*


**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- ★ **Could you take a picture of us?** — 사진 부탁 `T-SGT-001`
- **Could you take one more?** — 한 장 더 `T-SGT-002`
- **Could you take it vertically?** — 세로로 `T-SGT-003`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- **I'd like to rent an audio guide.** — 오디오가이드 대여 `T-SGT-004`
- **I'd like to book the two o'clock tour.** — 투어 예약 `T-SGT-005`
- **I'd like two tickets for tonight's concert.** — 공연표 구매 `T-SGT-006`
- **I'd like to cancel the tour.** — 투어 취소 `T-SGT-007`

**A05 · ___, please.** — 최소 단위 요청

- ★ **Two adult tickets, please.** — 입장권 `T-SGT-008`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can I take pictures inside?** — 내부 촬영 `T-SGT-009`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where's the entrance?** — 입구 `T-SGT-010`
- **Where's the special exhibition?** — 특별전 위치 `T-SGT-011`
- **Where does the tour start?** — 투어 집합 장소 `T-SGT-012`
- **Where's the gift shop?** — 기념품점 `T-SGT-013`
- **Where's the pickup point?** — 픽업 장소 `T-SGT-014`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Are there any discounts?** — 할인 여부 `T-SGT-015`
- **Is there a cloakroom?** — 물품 보관소 `T-SGT-016`
- **Is there a guided tour in English?** — 영어 가이드 투어 `T-SGT-017`
- **Is there a café inside?** — 내부 카페 `T-SGT-018`
- **Is there somewhere to leave luggage?** — 짐 맡길 곳 `T-SGT-019`
- **Are there any tickets left for tonight?** — 당일 잔여석 `T-SGT-020`
- **Is there an intermission?** — 인터미션 `T-SGT-021`
- **Are there any day trips to Potsdam?** — 당일치기 투어 `T-SGT-022`
- **Is there a refund if I cancel?** — 취소 환불 `T-SGT-023`
- **Is there a free admission day?** — 무료 입장일 `T-SGT-024`
- **Is there a skip-the-line option?** — 줄 서지 않는 입장권 `T-SGT-025`
- **Is there a bag check at the entrance?** — 입구 가방 검사 `T-SGT-026`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have an audio guide in Korean?** — 한국어 오디오가이드 `T-SGT-027`
- **Do you have a map of the museum?** — 관내 지도 `T-SGT-028`

**B05 · What time ___? / When ___?** — 시각·시점

- ★ **What time does it close?** — 폐관 시각 `T-SGT-029`
- **When's the last entry?** — 마지막 입장 `T-SGT-030`
- **What time is the next English tour?** — 다음 영어 투어 `T-SGT-031`
- **When was this built?** — 건축 연도 `T-SGT-032`
- **What time does it start?** — 공연 시작 `T-SGT-033`
- **What time is the pickup?** — 픽업 시각 `T-SGT-034`

**B06 · How long ___?** — 소요 시간·기간

- **How long does it take to see everything?** — 관람 소요 시간 `T-SGT-035`
- **How long is the tour?** — 투어 길이 `T-SGT-036`
- **How long is the performance?** — 공연 길이 `T-SGT-037`

**B07 · How much ___?** — 가격·양

- ★ **How much is admission?** — 입장료 `T-SGT-038`
- **How much are the cheaper seats?** — 저렴한 좌석 `T-SGT-039`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is photography allowed?** — 촬영 허용 여부 `T-SGT-040`
- **Is flash okay?** — 플래시 사용 `T-SGT-041`
- **Is it wheelchair accessible?** — 휠체어 접근성 `T-SGT-042`
- **Is the view okay from these seats?** — 좌석 시야 `T-SGT-043`
- **Is it okay to go inside during the service?** — 예배 중 입장 `T-SGT-044`
- **Does the city card cover this museum?** — 시티카드 적용 `T-SGT-045`
- **Is this the line for tickets?** — 매표 줄 확인 `T-SGT-046`
- **Are the descriptions in English?** — 영어 설명 여부 `T-SGT-047`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to book in advance?** — 사전 예약 필요 `T-SGT-048`
- **Do I need to choose a time slot?** — 시간대 지정 필요 `T-SGT-049`
- **Do I need to leave my bag?** — 가방 보관 필수 `T-SGT-050`
- **Should I tip the guide?** — 가이드 팁 `T-SGT-051`
- **Do I need to register in advance to visit the Reichstag dome?** — 국회의사당 돔 예약 `T-SGT-052`
- **Do I need to cover my shoulders?** — 복장 규정 (어깨) `T-SGT-053`
- **Do I need ID to get in?** — 입장 시 신분증 `T-SGT-054`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Is the audio guide included?** — 오디오가이드 포함 `T-SGT-055`
- **Is the special exhibition included?** — 특별전 포함 `T-SGT-056`
- **What's included in the tour?** — 투어 포함 사항 `T-SGT-057`
- **Are entrance fees included?** — 입장료 포함 `T-SGT-058`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- **What would you recommend if I only have an hour?** — 한 시간만 있을 때 `T-SGT-059`
- **What would you recommend for a day in Berlin?** — 하루 코스 추천 `T-SGT-060`
- **Where would you recommend for a nice view?** — 전망 좋은 곳 `T-SGT-061`
- **Can you recommend a concert tonight?** — 오늘 밤 공연 `T-SGT-062`
- **Where's the best spot for photos?** — 사진 명소 `T-SGT-063`

**B14 · Could you tell me ___?** — 간접 의문 (정중)

- **Could you tell me more about this painting?** — 작품 추가 설명 `T-SGT-064`

**B15 · What's the ___?** — 정보 항목 묻기

- **Is there a dress code?** — 드레스 코드 `T-SGT-065`

**B16 · What if ___? / What happens if ___?** — 조건·예외 상황

- **What happens if it rains?** — 비 오면 `T-SGT-066`

**D01 · Sorry, could you say that again?** — 반복 요청

- **Sorry, could you repeat the name of the architect?** — 가이드 설명 반복 `T-SGT-067`

**E05 · That sounds ___ / That's ___** — 반응·맞장구

- **That's beautiful.** — 동행에게 반응 `T-SGT-068`
- **That was fascinating.** — 투어 후 감상 `T-SGT-069`

**E13 · I really enjoyed ___ / I loved ___** — 칭찬

- **I really enjoyed the tour, thank you.** — 투어 칭찬 `T-SGT-070`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Would you like me to take one of you?** — 사진 찍어 주겠다고 제안 `T-SGT-071`
- **Wow, this is incredible.** — 감탄 `T-SGT-072`

### `T-MON` 환전·ATM·결제

*상황 44개 · ★ 4개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get some smaller notes?** — 소액권 `T-MON-001`
- **Could I get some coins?** — 동전 `T-MON-002`
- **Could I get a receipt for that?** — 결제 영수증 `T-MON-003`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you break a fifty?** — 큰돈 잔돈 교환 `T-MON-004`
- **Could you try it again?** — 다시 시도 `T-MON-005`
- **Could you cancel that transaction?** — 결제 취소 `T-MON-006`
- **Could you check the total again?** — 합계 재확인 `T-MON-007`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- ★ **I'd like to change 300 dollars into euros.** — 환전 `T-MON-008`
- **I'd like to block my card.** — 카드 정지 요청 (전화) `T-MON-009`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can I use a different card?** — 다른 카드 `T-MON-010`
- **Can I pay contactless?** — 비접촉 결제 `T-MON-011`
- **Can I pay with my phone?** — 휴대폰 결제 `T-MON-012`
- **Can I add a tip on the card?** — 카드로 팁 `T-MON-013`

**B03 · Is there ___ (around here)?** — 존재 여부

- ★ **Is there an ATM nearby?** — 근처 ATM `T-MON-014`
- **Is there a bank around here?** — 근처 은행 `T-MON-015`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time does the bank open?** — 은행 개점 `T-MON-016`

**B07 · How much ___?** — 가격·양

- **How much is the commission?** — 수수료 `T-MON-017`
- **How much is that in won, roughly?** — 원화 환산 `T-MON-018`
- **How much is it to use the toilet?** — 공중화장실 요금 `T-MON-019`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Does this ATM charge a fee?** — ATM 수수료 `T-MON-020`
- ★ **Do you take cards?** — 카드 결제 가능 `T-MON-021`
- **Is it cash only?** — 현금 전용 여부 `T-MON-022`
- **Should I sign here?** — 서명 위치 `T-MON-023`
- **Is the rate better in the city than at the airport?** — 공항 대 시내 환율 `T-MON-024`
- **Does this work with foreign cards?** — 해외 카드 사용 가능 `T-MON-025`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to enter my PIN?** — PIN 입력 `T-MON-026`
- **Do you need my passport?** — 환전 시 여권 `T-MON-027`
- **Do I need coins for the restroom?** — 화장실 동전 필요 `T-MON-028`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Is the fee included in that rate?** — 수수료 포함 환율 `T-MON-029`

**B13 · Do you know ___? / Do you happen to know ___?** — 정보 보유 여부

- **Do you know a good place to change money?** — 좋은 환전소 `T-MON-030`

**B15 · What's the ___?** — 정보 항목 묻기

- ★ **What's the exchange rate today?** — 오늘 환율 `T-MON-031`
- **What's the minimum for card payments?** — 카드 최소 결제액 `T-MON-032`
- **What's the number to report a lost card?** — 분실 신고 번호 `T-MON-033`
- **What's the minimum amount I can exchange?** — 최소 환전액 `T-MON-034`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **The ATM kept my card.** — ATM이 카드를 삼킴 `T-MON-035`
- **The ATM didn't give me any cash, but my account was charged.** — 출금 오류 `T-MON-036`
- **My card was declined.** — 카드 거절 `T-MON-037`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **I think you gave me the wrong change.** — 거스름돈 오류 `T-MON-038`
- **I think I've been charged twice.** — 이중 결제 `T-MON-039`

**C06 · I lost ___ / I can't find ___ / I left ___** — 분실

- **I've lost my credit card.** — 카드 분실 `T-MON-040`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **Just to confirm, that's 120 euros?** — 금액 확인 `T-MON-041`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **In euros, please — not won.** — DCC 거절 (원화 결제 거부) `T-MON-042`
- **Here's a little something for you.** — 현금 팁 건넬 때 `T-MON-043`
- **Sorry, I don't have enough cash. Can I pay the rest by card?** — 현금 부족 `T-MON-044`

### `T-COM` 통신·SIM·와이파이·충전

*상황 41개 · ★ 3개*


**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you set it up for me?** — 설치 부탁 `T-COM-001`
- **Could I use your phone to make a quick call?** — 전화 빌리기 `T-COM-002`
- **Could you put your number in my phone?** — 번호 입력 부탁 `T-COM-003`
- **Could you text me instead? It's easier for me.** — 통화 대신 문자 `T-COM-004`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- ★ **I'd like a prepaid SIM card.** — 선불 유심 구매 `T-COM-005`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can I charge my phone here?** — 여기서 충전 `T-COM-006`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where can I buy a plug adapter?** — 어댑터 구매처 `T-COM-007`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How do I activate it?** — 개통 방법 `T-COM-008`
- **How do I top it up?** — 충전 방법 `T-COM-009`
- **How do I log in? It's asking for a room number.** — 로그인 페이지 `T-COM-010`

**B03 · Is there ___ (around here)?** — 존재 여부

- ★ **Is there free Wi-Fi here?** — 무료 와이파이 `T-COM-011`
- **Is there anywhere I can charge my phone?** — 충전 장소 `T-COM-012`
- **Is there anywhere I can print something nearby?** — 근처 인쇄소 `T-COM-013`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have eSIMs?** — eSIM 여부 `T-COM-014`
- ★ **Do you have a plug adapter?** — 플러그 어댑터 `T-COM-015`
- **Do you have a USB-C charger I could borrow?** — 충전기 대여 `T-COM-016`
- **Do you sell power banks?** — 보조배터리 판매 `T-COM-017`

**B06 · How long ___?** — 소요 시간·기간

- **How long is it valid for?** — 유효 기간 `T-COM-018`

**B07 · How much ___?** — 가격·양

- **How much is it for ten gigs?** — 데이터 요금 `T-COM-019`
- **How much is it per page?** — 장당 인쇄비 `T-COM-020`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Are you on WhatsApp?** — 왓츠앱 사용 여부 `T-COM-021`
- **Can you hear me now?** — 이제 들리는지 `T-COM-022`
- **Is the Wi-Fi fast enough for a video call?** — 화상회의 가능한 속도 `T-COM-023`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do you need my passport to register it?** — 등록 시 여권 `T-COM-024`
- **Do I need a PIN for this SIM?** — 유심 PIN `T-COM-025`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Does it work in other EU countries?** — EU 로밍 포함 `T-COM-026`
- **Does it include calls?** — 통화 포함 `T-COM-027`

**B14 · Could you tell me ___?** — 간접 의문 (정중)

- **Could you tell me how to call Korea from here?** — 한국 국제전화 `T-COM-028`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's the Wi-Fi password?** — 와이파이 비밀번호 `T-COM-029`
- **What's your number?** — 전화번호 `T-COM-030`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **My data isn't working.** — 데이터 안 됨 `T-COM-031`
- **I'm not getting any signal.** — 신호 없음 `T-COM-032`
- **I can't connect to the Wi-Fi.** — 와이파이 연결 실패 `T-COM-033`
- **I can't hear you very well.** — 잘 안 들림 `T-COM-034`
- **I'm not receiving any text messages.** — 문자 수신 불가 `T-COM-035`

**C07 · I have ___ / I feel ___** — 증상·상태

- **My phone's almost dead.** — 배터리 거의 없음 `T-COM-036`

**D01 · Sorry, could you say that again?** — 반복 요청

- **Sorry, the line's bad — could you say that again?** — 통화 품질 나쁨 `T-COM-037`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **Just to confirm, it's 0151 2345 678?** — 번호 확인 `T-COM-038`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **I'll text you.** — 문자 하겠다 `T-COM-039`
- **Sorry, you're breaking up.** — 통화 끊김 `T-COM-040`
- **I'll call you back.** — 다시 걸겠다 `T-COM-041`

### `T-MED` 약국·병원·응급

*상황 81개 · ★ 9개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get a medical report for my insurance?** — 보험용 진단서 `T-MED-001`
- **Could I get an itemized receipt for my insurance claim?** — 보험 청구용 영수증 `T-MED-002`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- ★ **Could you call a doctor, please?** — 의사 호출 `T-MED-003`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- **I'd like to make an appointment to see a doctor.** — 진료 예약 `T-MED-004`

**A08 · I need (to) ___** — 필요를 직접 밝힘

- ★ **I need something for a headache.** — 두통약 `T-MED-005`
- **I need something for a cold.** — 감기약 `T-MED-006`
- **I need something for an upset stomach.** — 소화불량 `T-MED-007`
- **I need something for diarrhea.** — 설사 `T-MED-008`
- **I need something for a sore throat.** — 인후통 `T-MED-009`
- **I need something for allergies.** — 알레르기 `T-MED-010`
- **I need something for insect bites.** — 벌레 물림 `T-MED-011`
- **I need something for motion sickness.** — 멀미 `T-MED-012`
- **I need something to help me sleep.** — 불면 `T-MED-013`
- **I need some plasters.** — 반창고 `T-MED-014`
- **I need something for blisters.** — 물집 `T-MED-015`
- **I need to keep this medication in a fridge.** — 냉장 보관 필요 `T-MED-016`
- ★ **I need a prescription for this.** — 처방 필요 `T-MED-017`
- **I need something sweet — quickly.** — 급히 당분 `T-MED-018`
- **I need a replacement for my prescription. I've run out.** — 처방약 소진 `T-MED-019`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- ★ **Where's the nearest emergency room?** — 가장 가까운 응급실 `T-MED-020`

**B03 · Is there ___ (around here)?** — 존재 여부

- ★ **Is there a pharmacy near here?** — 근처 약국 `T-MED-021`
- **Is there a pharmacy open now?** — 지금 여는 약국 `T-MED-022`
- **Is there a doctor who speaks English?** — 영어 가능한 의사 `T-MED-023`
- **Is there a dentist nearby who can see me today?** — 당일 치과 `T-MED-024`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have something with the same active ingredient?** — 동일 성분 약 `T-MED-025`

**B06 · How long ___?** — 소요 시간·기간

- **How long will I have to wait?** — 대기 시간 `T-MED-026`

**B07 · How much ___?** — 가격·양

- **How much does a consultation cost?** — 진료비 `T-MED-027`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Should I take it with food?** — 식후 복용 여부 `T-MED-028`
- **Does it make you drowsy?** — 졸음 여부 `T-MED-029`
- **Is it okay to drink alcohol with this?** — 음주 병용 `T-MED-030`
- **Is it okay to take this with ibuprofen?** — 다른 약과 병용 `T-MED-031`
- **Is it serious?** — 심각한지 `T-MED-032`
- **Is it okay for me to fly?** — 비행 가능 여부 `T-MED-033`
- **Is this available without a prescription?** — 일반의약품 여부 `T-MED-034`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need a prescription for this?** — 처방전 필요 여부 `T-MED-035`
- **Do I need to pay now?** — 선결제 여부 `T-MED-036`
- **Do I need to come back?** — 재진 필요 `T-MED-037`
- **Do you need to see my prescription?** — 처방전 제시 필요 `T-MED-038`

**B15 · What's the ___?** — 정보 항목 묻기

- **How often should I take this?** — 복용 빈도 `T-MED-039`
- **How many should I take?** — 복용 개수 `T-MED-040`
- **What's the emergency number here?** — 응급번호 `T-MED-041`
- **What's the diagnosis?** — 진단명 `T-MED-042`
- **What's the local name for ibuprofen?** — 현지 약품명 `T-MED-043`

**C06 · I lost ___ / I can't find ___ / I left ___** — 분실

- **I've lost my insulin pen.** — 인슐린 펜 분실 `T-MED-044`
- **I've lost my glucose meter.** — 혈당측정기 분실 `T-MED-045`

**C07 · I have ___ / I feel ___** — 증상·상태

- ★ **I have a bad headache.** — 심한 두통 `T-MED-046`
- **I have a fever.** — 발열 `T-MED-047`
- **I have a cough.** — 기침 `T-MED-048`
- **I have a runny nose.** — 콧물 `T-MED-049`
- **I have a sore throat.** — 목 통증 `T-MED-050`
- **I feel sick.** — 메스꺼움 `T-MED-051`
- **I feel dizzy.** — 어지러움 `T-MED-052`
- **I have a stomachache.** — 복통 `T-MED-053`
- **I have chest pain.** — 흉통 `T-MED-054`
- **I'm having trouble breathing.** — 호흡 곤란 `T-MED-055`
- **I think I sprained my ankle.** — 발목 염좌 `T-MED-056`
- **I've hurt my back.** — 허리 부상 `T-MED-057`
- **I burned my hand.** — 손 화상 `T-MED-058`
- **I cut my finger.** — 손가락 베임 `T-MED-059`
- **I have a rash.** — 발진 `T-MED-060`
- **My eye is red and itchy.** — 눈 충혈·가려움 `T-MED-061`
- **I have a toothache.** — 치통 `T-MED-062`
- **I have diabetes, and I take insulin.** — 당뇨·인슐린 사용 `T-MED-063`
- **My legs are really sore from all the walking.** — 많이 걸어 근육통 `T-MED-064`
- **I think my blood sugar is low.** — 저혈당 의심 `T-MED-065`

**C08 · I've been ___ since / for ___** — 지속 기간

- ★ **I've had a fever since yesterday.** — 발열 지속 `T-MED-066`
- **I've been coughing for three days.** — 기침 지속 `T-MED-067`
- **I've been feeling sick since this morning.** — 아침부터 메스꺼움 `T-MED-068`
- **It's been coming and going for a few hours.** — 간헐적 증상 `T-MED-069`

**C11 · I don't eat ___ / I'm allergic to ___** — 식이 제한

- **I'm allergic to penicillin.** — 약물 알레르기 `T-MED-070`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **So two tablets, three times a day?** — 용법 확인 `T-MED-071`

**D05 · Could you speak more slowly / write it down?** — 전달 방식 변경 요청

- **Sorry, could you explain that in simpler terms?** — 의학 용어 쉽게 `T-MED-072`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **I'm taking medication for blood pressure.** — 복용 중인 약 `T-MED-073`
- **Here's a list of the medicines I take.** — 복용약 목록 제시 `T-MED-074`
- ★ **Call an ambulance!** — 구급차 `T-MED-075`
- ★ **Help!** — 도와주세요 `T-MED-076`
- **I have travel insurance.** — 여행자 보험 있음 `T-MED-077`
- **My colleague fainted.** — 동료 실신 `T-MED-078`
- **He's conscious, but he's very pale.** — 의식 상태 설명 `T-MED-079`
- **She's having an allergic reaction.** — 알레르기 반응 `T-MED-080`
- **She has an EpiPen in her bag.** — 에피펜 위치 `T-MED-081`

### `T-TRB` 분실·도난·사고·항공 지연

*상황 67개 · ★ 9개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get a copy of the police report?** — 경찰 보고서 사본 `T-TRB-001`
- ★ **Could I get a written confirmation of the delay?** — 지연 확인서 `T-TRB-002`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you call me if it turns up?** — 찾으면 연락 `T-TRB-003`
- ★ **Could you call the police?** — 경찰 신고 부탁 `T-TRB-004`
- **Could you find someone who speaks English?** — 영어 가능자 요청 `T-TRB-005`
- **Could I have a copy of that?** — 서류 사본 `T-TRB-006`
- **Could you help me find another hotel nearby?** — 다른 호텔 찾기 `T-TRB-007`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- **I'd like to report a theft.** — 도난 신고 `T-TRB-008`
- **I'd like a refund instead.** — 환불로 처리 `T-TRB-009`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Could you put me on the next flight?** — 다음 편 배정 `T-TRB-010`
- **Is it possible to rebook me on another airline?** — 타 항공사 재예약 `T-TRB-011`
- **Is there any way to get there today?** — 오늘 중 도착 방법 `T-TRB-012`

**A08 · I need (to) ___** — 필요를 직접 밝힘

- ★ **I need to contact the Korean embassy.** — 대사관 연락 `T-TRB-013`
- **I need to cancel because I'm sick.** — 병으로 일정 취소 `T-TRB-014`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- ★ **Where's the nearest police station?** — 가까운 경찰서 `T-TRB-015`
- **Where's the lost and found?** — 분실물 센터 `T-TRB-016`
- **Where's the Korean embassy?** — 한국 대사관 `T-TRB-017`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How do I get an emergency passport?** — 긴급 여권 발급 `T-TRB-018`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there a train I could take instead?** — 열차 대안 `T-TRB-019`
- **Is there another way to get to Munich today?** — 오늘 다른 이동 수단 `T-TRB-020`

**B05 · What time ___? / When ___?** — 시각·시점

- **When does the new flight leave?** — 새 항공편 출발 `T-TRB-021`

**B06 · How long ___?** — 소요 시간·기간

- **How long does it take?** — 발급 소요 `T-TRB-022`
- **How long is the delay expected to be?** — 예상 지연 `T-TRB-023`
- **How long do you keep lost items?** — 분실물 보관 기간 `T-TRB-024`

**B08 · Which ___?** — 선택지 중 특정

- **Which desk should I go to?** — 어느 창구 `T-TRB-025`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Has anyone turned in a black backpack?** — 분실물 접수 여부 `T-TRB-026`
- **Am I entitled to compensation under EU rules?** — EU 규정 보상 자격 `T-TRB-027`
- **Is it safe to walk back to the hotel from here?** — 귀갓길 안전 `T-TRB-028`
- **Is there anyone here who speaks Korean?** — 한국어 가능 직원 `T-TRB-029`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need a police report for my insurance?** — 보험용 경찰 보고서 `T-TRB-030`
- **Do I need photos?** — 사진 필요 여부 `T-TRB-031`
- **Do I need to collect my bag?** — 짐 다시 찾기 `T-TRB-032`
- **Do I need to sign anything?** — 서명 필요 `T-TRB-033`
- **Do you need a doctor's note?** — 진단서 필요 여부 `T-TRB-034`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Will you provide a hotel?** — 호텔 제공 여부 `T-TRB-035`
- **Do I get a meal voucher?** — 식사 쿠폰 `T-TRB-036`

**B15 · What's the ___?** — 정보 항목 묻기

- ★ **What are my options?** — 선택지 `T-TRB-037`

**B16 · What if ___? / What happens if ___?** — 조건·예외 상황

- **What happens if I can't get a new passport in time?** — 여권 재발급이 늦으면 `T-TRB-038`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- ★ **My flight's been cancelled.** — 항공편 결항 `T-TRB-039`
- **My train's been cancelled because of the strike.** — 파업으로 열차 취소 `T-TRB-040`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **I think there's a problem with my booking — you don't have it on file.** — 호텔 예약 누락 `T-TRB-041`

**C06 · I lost ___ / I can't find ___ / I left ___** — 분실

- ★ **I've lost my wallet.** — 지갑 분실 `T-TRB-042`
- **I've lost my passport.** — 여권 분실 `T-TRB-043`
- **I can't find my phone.** — 휴대폰 분실 `T-TRB-044`
- **I left my bag on the train.** — 열차에 가방 두고 내림 `T-TRB-045`
- **I'm not sure where I lost it.** — 어디서 잃었는지 모름 `T-TRB-046`
- **I left my camera at the museum.** — 박물관에 카메라 두고 옴 `T-TRB-047`

**C10 · I'm afraid ___** — 나쁜 소식·거절의 완곡

- **I'm afraid that doesn't really work for me — I have a meeting at noon.** — 대안 거절 (완곡) `T-TRB-048`

**C13 · I'm running late / I missed ___** — 지연·놓침

- ★ **I missed my connecting flight.** — 연결편 놓침 `T-TRB-049`
- **My first flight was delayed, so I missed my connection.** — 지연으로 연결편 놓침 `T-TRB-050`
- **I missed my tour because of the delay. Can I get a refund?** — 지연으로 투어 놓침 `T-TRB-051`

**C14 · I was told ___** — 근거 제시

- **I was told to come to this desk.** — 이 창구로 안내 받음 `T-TRB-052`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **So the new flight is tomorrow at 8:40, gate D12?** — 새 일정 확인 `T-TRB-053`

**E08 · Sorry about ___ / Sorry to ___** — 사과

- **Sorry, I know it's not your fault.** — 직원에게 공감 `T-TRB-054`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **Someone stole my bag.** — 도난 `T-TRB-055`
- **I think I've been pickpocketed.** — 소매치기 의심 `T-TRB-056`
- **It's a black leather wallet with my ID inside.** — 분실물 묘사 `T-TRB-057`
- **I last had it at the café around noon.** — 마지막 위치·시각 `T-TRB-058`
- **Here's my number and my hotel.** — 연락처 남김 `T-TRB-059`
- **I understand. Thanks for trying.** — 이해 표시 `T-TRB-060`
- **I fell and hurt my knee.** — 넘어져 다침 `T-TRB-061`
- **There's been an accident.** — 사고 발생 `T-TRB-062`
- **No, thank you. I'm not interested.** — 접근하는 사람 거절 `T-TRB-063`
- **Please leave me alone.** — 강하게 거절 `T-TRB-064`
- **I'm sorry, I'm not comfortable with that.** — 불편함 표현 `T-TRB-065`
- **Here's the confirmation email.** — 예약 증빙 제시 `T-TRB-066`
- **Okay, let's figure this out.** — 스스로 진정 `T-TRB-067`

### `T-SOC` 여행지 스몰토크·현지인 대화

*상황 55개 · ★ 5개*


**A12 · I'd prefer ___ / I'd rather ___** — 선호 표현

- **I'd rather not talk about politics, if you don't mind.** — 민감한 화제 회피 `T-SOC-001`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is it always this warm in October?** — 늘 이런 날씨인지 `T-SOC-002`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- ★ **What would you recommend I see while I'm here?** — 볼거리 추천 받기 `T-SOC-003`
- **What local food should I try?** — 현지 음식 추천 `T-SOC-004`
- **Where do locals like to eat?** — 현지인 맛집 `T-SOC-005`

**B13 · Do you know ___? / Do you happen to know ___?** — 정보 보유 여부

- **Do you know if there's anything happening this weekend?** — 주말 행사 `T-SOC-006`
- **Do you know any hidden gems around here?** — 숨은 명소 `T-SOC-007`

**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- **What does that expression mean?** — 표현 뜻 `T-SOC-008`

**D08 · How do you say ___? / What do you call ___?** — 어휘·발음 묻기

- **How do you say "thank you" in German?** — 현지어 감사 인사 `T-SOC-009`

**E02 · What brings you ___? / Are you here for ___?** — 방문 목적 묻기

- ★ **What brings you here?** — 방문 목적 묻기 `T-SOC-010`
- **Are you here on holiday or for work?** — 휴가인지 출장인지 `T-SOC-011`

**E03 · How's ___ going? / How was ___?** — 안부·경험

- **How are you finding Berlin?** — 도시 인상 `T-SOC-012`
- **How's your day been?** — 하루 안부 `T-SOC-013`
- **How was your weekend?** — 주말 안부 `T-SOC-014`

**E04 · Where are you ___?** — 출신·소속·숙소

- ★ **Where are you from?** — 출신 묻기 `T-SOC-015`
- **Where are you staying?** — 숙소 묻기 `T-SOC-016`

**E05 · That sounds ___ / That's ___** — 반응·맞장구

- ★ **That sounds amazing.** — 반응 (감탄) `T-SOC-017`
- **Oh, really? That's interesting.** — 반응 (흥미) `T-SOC-018`
- **That must be tough.** — 공감 (힘듦) `T-SOC-019`
- **Lucky you!** — 부러움 `T-SOC-020`
- **No way!** — 놀람 `T-SOC-021`
- **Exactly.** — 강한 동의 `T-SOC-022`
- **I know, right?** — 맞장구 `T-SOC-023`
- **That's lovely.** — 좋다는 반응 `T-SOC-024`

**E06 · Have you ___? / Have you been to ___?** — 경험 묻기

- **Have you been to Korea?** — 한국 방문 경험 `T-SOC-025`
- **Have you been here before?** — 이곳 방문 경험 `T-SOC-026`
- **Have you ever tried Korean food?** — 한국 음식 경험 `T-SOC-027`
- **Have you watched any Korean dramas?** — 한국 드라마 `T-SOC-028`
- **Have you lived in Berlin long?** — 베를린 거주 기간 `T-SOC-029`

**E10 · How about ___? / Shall we ___? / Why don't we ___?** — 제안

- **Shall we stay in touch?** — 연락 유지 제안 `T-SOC-030`
- **How about a photo together?** — 같이 사진 `T-SOC-031`
- **Why don't we grab a drink later?** — 한잔 제안 `T-SOC-032`

**E11 · It was great ___ / Have a ___** — 작별

- **Enjoy the rest of your day!** — 헤어질 때 `T-SOC-033`
- **Enjoy your trip!** — 여행 기원 `T-SOC-034`

**E12 · I'm ___ / I work for ___** — 자기소개

- ★ **I'm from South Korea.** — 출신 답 `T-SOC-035`
- **I live in Seoul.** — 사는 도시 `T-SOC-036`
- **I'm here for a week, then heading to Paris.** — 여행 일정 소개 `T-SOC-037`
- **I'm a researcher at a radiation health institute.** — 직업 답 `T-SOC-038`
- **I work in medical research.** — 직업 쉽게 설명 `T-SOC-039`

**E13 · I really enjoyed ___ / I loved ___** — 칭찬

- **I love this city. It's so beautiful.** — 도시 칭찬 `T-SOC-040`
- **The food here is fantastic.** — 음식 칭찬 `T-SOC-041`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **No, it's my first time.** — 처음 왔다고 답 `T-SOC-042`
- **Lovely weather today, isn't it?** — 날씨 (좋음) `T-SOC-043`
- **It's colder than I expected.** — 날씨 (예상보다 추움) `T-SOC-044`
- **Well, it was nice chatting with you.** — 대화 마무리 `T-SOC-045`
- **Thank you, that's very kind.** — 칭찬에 답 `T-SOC-046`
- **Thanks — I'm still working on it.** — 영어 칭찬에 겸손 `T-SOC-047`
- **Did I say that right?** — 현지어 발음 확인 `T-SOC-048`
- **I'm not really sure, to be honest.** — 잘 모를 때 `T-SOC-049`
- **That's kind of you, but I have plans tonight.** — 제안 정중히 거절 `T-SOC-050`
- **So, what do you do?** — 직업 묻기 `T-SOC-051`
- **Sorry, I think I missed the joke.** — 농담을 못 알아들음 `T-SOC-052`
- **That's hilarious.** — 웃음 반응 `T-SOC-053`
- **Thanks for the tip!** — 정보 감사 `T-SOC-054`
- **In Korean, we say "kamsahamnida."** — 한국어 알려주기 `T-SOC-055`

### `T-SVC` 우체국·세탁·미용·생활 서비스

*상황 35개 · ★ 2개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get stamps for three postcards to Korea?** — 엽서 우표 `T-SVC-001`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you take a bit more off the sides?** — 옆머리 더 짧게 `T-SVC-002`
- **Could you fix my glasses?** — 안경 수리 `T-SVC-003`
- **Could you print these photos?** — 사진 인화 `T-SVC-004`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- ★ **I'd like to send this package to Korea.** — 한국으로 소포 `T-SVC-005`
- **I'd like to have these clothes washed.** — 세탁 맡기기 `T-SVC-006`
- ★ **I'd like a haircut, please.** — 이발 `T-SVC-007`
- **I'd like just a trim.** — 다듬기만 `T-SVC-008`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Is it possible to get it back today?** — 당일 세탁 `T-SVC-009`

**A14 · I'm looking for ___** — 찾는 물건·장소 설명

- **I'm looking for an optician. My glasses broke.** — 안경원 찾기 `T-SVC-010`
- **I'm looking for somewhere to fix my shoe.** — 구두 수선 `T-SVC-011`
- **I'm looking for a drugstore, like dm or Rossmann.** — 드럭스토어 찾기 `T-SVC-012`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where's the nearest mailbox?** — 가까운 우체통 `T-SVC-013`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How does this washing machine work?** — 세탁기 사용법 `T-SVC-014`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there a faster option?** — 빠른 배송 선택지 `T-SVC-015`
- **Is there a laundromat nearby?** — 셀프 빨래방 `T-SVC-016`
- **Is there somewhere I can get passport photos taken?** — 여권 사진 `T-SVC-017`
- **Is there an internet café around here?** — 인터넷 카페 `T-SVC-018`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have boxes I could buy?** — 포장 상자 `T-SVC-019`
- **Do you have razors?** — 면도기 `T-SVC-020`
- **Do you have sunscreen?** — 선크림 `T-SVC-021`
- **Do you have contact lens solution?** — 렌즈 세척액 `T-SVC-022`
- **Do you sell umbrellas?** — 우산 판매 `T-SVC-023`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time does the post office close?** — 우체국 마감 `T-SVC-024`
- **When will it be ready?** — 세탁 완료 시점 `T-SVC-025`
- **What time do you open tomorrow?** — 내일 영업 시작 `T-SVC-026`

**B06 · How long ___?** — 소요 시간·기간

- **How long will it take to arrive?** — 도착 소요 `T-SVC-027`
- **How long is the wait?** — 미용 대기 `T-SVC-028`

**B07 · How much ___?** — 가격·양

- **How much is it to send this to Korea?** — 한국 우편 요금 `T-SVC-029`
- **How much is dry cleaning for a suit?** — 정장 드라이클리닝 `T-SVC-030`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to fill in a customs form?** — 세관 신고서 작성 `T-SVC-031`
- **Do I need to buy detergent?** — 세제 구매 필요 `T-SVC-032`
- **Do I need an appointment?** — 미용 예약 필요 `T-SVC-033`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- **Does it come with tracking?** — 배송 추적 포함 `T-SVC-034`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Oh, you're closed? Sorry.** — 영업 종료를 몰랐을 때 `T-SVC-035`

---

## Part 3. 학회·연구 활동 영어

### `C-REG` 학회 등록·배지·장소 안내

*상황 60개 · ★ 6개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get a new badge printed?** — 배지 재출력 `C-REG-001`
- ★ **Could I get a receipt for the registration fee?** — 등록비 영수증 `C-REG-002`
- **Could I get a certificate of attendance?** — 참석 증명서 `C-REG-003`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you print this for me? It's my boarding pass.** — 탑승권 인쇄 부탁 `C-REG-004`
- **Could you check that my dietary request is on file?** — 식이 요청 기록 확인 `C-REG-005`
- **Could you send the invoice to my institute?** — 기관으로 인보이스 `C-REG-006`
- **Could you leave a message for Dr. Hoffmann?** — 메시지 남기기 `C-REG-007`

**A04 · I'd like (to) ___** — 원하는 것을 정중히 밝힘

- **I'd like to register an accompanying person.** — 동반자 등록 `C-REG-008`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would it be possible to reissue the invoice with my institute's name?** — 인보이스 재발행 `C-REG-009`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Is it okay to go in now? The session has already started.** — 진행 중 세션 입장 `C-REG-010`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- ★ **Where's Room B?** — 세션장 위치 `C-REG-011`
- **Where's the plenary hall?** — 플레너리 홀 `C-REG-012`
- **Where's the poster area?** — 포스터 구역 `C-REG-013`
- ★ **Where's the speaker ready room?** — 발표자 준비실 `C-REG-014`
- **Where can I leave my coat?** — 코트 보관 `C-REG-015`
- **Where's the coffee break?** — 커피 브레이크 장소 `C-REG-016`
- **Is there an ATM in the building?** — 건물 내 ATM `C-REG-017`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How do I get to the dinner venue?** — 만찬 장소 가는 법 `C-REG-018`

**B03 · Is there ___ (around here)?** — 존재 여부

- ★ **Is there a conference app?** — 학회 앱 `C-REG-019`
- **Is there a cloakroom for luggage?** — 짐 보관 (체크아웃 날) `C-REG-020`
- **Is there a quiet room where I can work?** — 조용한 작업실 `C-REG-021`
- **Is there a charging station?** — 충전 스테이션 `C-REG-022`
- **Is there a printer I could use?** — 프린터 `C-REG-023`
- **Is there a lost and found here?** — 학회장 분실물 `C-REG-024`
- **Is there an information desk?** — 안내 데스크 `C-REG-025`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have any tickets left for the gala dinner?** — 만찬 잔여 티켓 `C-REG-026`
- **Do you have a printed program?** — 인쇄 프로그램북 `C-REG-027`
- **Do you have the program as a PDF?** — 프로그램 PDF `C-REG-028`

**B05 · What time ___? / When ___?** — 시각·시점

- **When can I pick up the certificate of attendance?** — 증명서 수령 시점 `C-REG-029`
- **What time is lunch?** — 점심 시간 `C-REG-030`
- **What time does the registration desk open tomorrow?** — 등록 데스크 운영 `C-REG-031`
- **When will the presentations be posted?** — 슬라이드 공개 시점 `C-REG-032`
- **What time does the shuttle to the dinner leave?** — 만찬 셔틀 시각 `C-REG-033`
- **What time is the keynote?** — 기조강연 시각 `C-REG-034`

**B07 · How much ___?** — 가격·양

- **How much is an extra ticket for the dinner?** — 만찬 추가 티켓 가격 `C-REG-035`

**B08 · Which ___?** — 선택지 중 특정

- **Which room is the AI for dose management session in?** — 특정 세션 장소 `C-REG-036`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Have there been any changes to the program?** — 프로그램 변경 여부 `C-REG-037`
- **Has the session moved to a different room?** — 세션장 변경 여부 `C-REG-038`
- **Will the sessions be recorded?** — 녹화 여부 `C-REG-039`
- **Will the slides be available online?** — 슬라이드 공개 여부 `C-REG-040`
- **Is the welcome reception here or somewhere else?** — 웰컴 리셉션 장소 `C-REG-041`
- **Is there assigned seating for the opening ceremony?** — 첫날 개회식 좌석 `C-REG-042`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to request the invoice separately?** — 인보이스 별도 요청 `C-REG-043`
- **Do I need to wear my badge at all times?** — 배지 착용 필수 `C-REG-044`
- **Do I need to register my poster separately?** — 포스터 별도 등록 `C-REG-045`
- **Do I need to sign up for the city tour?** — 시티 투어 신청 `C-REG-046`

**B11 · Is ___ included? / Does it come with ___?** — 포함 여부

- ★ **Does the registration include the conference dinner?** — 등록비 포함 사항 (만찬) `C-REG-047`
- **Is lunch included?** — 점심 포함 여부 `C-REG-048`

**B13 · Do you know ___? / Do you happen to know ___?** — 정보 보유 여부

- **Do you know if Professor Müller has arrived?** — 연사 도착 여부 `C-REG-049`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's the Wi-Fi network and password?** — 와이파이 정보 `C-REG-050`
- **What's the dress code for the gala dinner?** — 만찬 드레스 코드 `C-REG-051`

**C01 · I have a reservation ___ / I booked ___** — 예약 사실 제시

- **I registered online. My name is Kim.** — 사전 등록 사실 `C-REG-052`

**C02 · I'm here for ___ / I'm here to ___** — 방문 목적

- ★ **Hi, I'm here to pick up my badge.** — 배지 수령 `C-REG-053`

**C05 · I think there's a mistake ___** — 오류 지적 (완곡)

- **I think there's a typo on my badge.** — 배지 오타 `C-REG-054`
- **My affiliation is wrong on the badge.** — 소속 오류 `C-REG-055`

**C06 · I lost ___ / I can't find ___ / I left ___** — 분실

- **I've lost my badge.** — 배지 분실 `C-REG-056`

**C11 · I don't eat ___ / I'm allergic to ___** — 식이 제한

- **I registered a vegetarian meal for the dinner — could you check?** — 만찬 채식 신청 확인 `C-REG-057`

**C13 · I'm running late / I missed ___** — 지연·놓침

- **I just arrived — have I missed the opening?** — 늦게 도착 `C-REG-058`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **So the session's now in Hall C?** — 변경 확인 `C-REG-059`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Here's my registration confirmation.** — 등록 확인서 제시 `C-REG-060`

### `C-NET` 네트워킹 — 첫인사·자기소개

*상황 91개 · ★ 12개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get your card?** — 명함 요청 `C-NET-001`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you introduce me to Professor Weber?** — 소개 부탁 `C-NET-002`

**A07 · I was wondering if ___** — 매우 조심스러운 부탁

- **I was wondering if you could introduce me to someone from the IAEA.** — 조심스러운 소개 부탁 `C-NET-003`

**A10 · Do you mind if I ___?** — 상대를 배려한 허락

- ★ **Do you mind if I join you?** — 대화 합류 `C-NET-004`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- **Are there any sessions you'd recommend this afternoon?** — 오후 세션 추천 `C-NET-005`

**C02 · I'm here for ___ / I'm here to ___** — 방문 목적

- **I'm presenting a poster on Wednesday.** — 포스터 발표 예정 `C-NET-006`
- **I'm giving a talk in the AI session tomorrow.** — 구두 발표 예정 `C-NET-007`

**D01 · Sorry, could you say that again?** — 반복 요청

- **Sorry, it's a bit loud — could you say that again?** — 소음 속 반복 요청 `C-NET-008`

**D02 · Sorry, I didn't catch ___** — 못 들었음

- **Sorry, I didn't catch your name.** — 이름 못 들음 `C-NET-009`

**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- **Sorry, what does "ETP" stand for?** — 약어 질문 `C-NET-010`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **So you're mainly working on the regulatory side?** — 상대 업무 확인 `C-NET-011`

**D08 · How do you say ___? / What do you call ___?** — 어휘·발음 묻기

- **Sorry, how do you pronounce your name?** — 상대 이름 발음 `C-NET-012`

**E01 · Nice to meet you / Good to see you** — 인사

- ★ **Hi, I'm Kim. Nice to meet you.** — 첫인사 `C-NET-013`
- **I'm Dr. Kim, from Korea. Nice to meet you.** — 격식 첫인사 `C-NET-014`

**E02 · What brings you ___? / Are you here for ___?** — 방문 목적 묻기

- ★ **What brings you to the conference?** — 학회 참가 목적 `C-NET-015`
- **Are you presenting this year?** — 발표 여부 `C-NET-016`
- **Are you going to the reception tonight?** — 리셉션 참석 여부 `C-NET-017`

**E03 · How's ___ going? / How was ___?** — 안부·경험

- **How are you finding the conference so far?** — 학회 인상 `C-NET-018`
- **How did your talk go?** — 발표 결과 묻기 `C-NET-019`

**E04 · Where are you ___?** — 출신·소속·숙소

- ★ **Where are you based?** — 상대 근무지 `C-NET-020`
- **Which institute are you with?** — 상대 기관 `C-NET-021`
- **Where did you fly in from?** — 출발지 묻기 `C-NET-022`

**E05 · That sounds ___ / That's ___** — 반응·맞장구

- ★ **That sounds really interesting.** — 관심 표현 `C-NET-023`
- **Oh, that's very relevant to what we're doing.** — 연관성 표현 `C-NET-024`
- **That's actually quite close to my work.** — 가까운 분야 `C-NET-025`
- **Oh, thank you — that's kind of you to say.** — 칭찬에 겸손 `C-NET-026`
- **We should definitely compare notes.** — 노트 비교 제안 `C-NET-027`

**E06 · Have you ___? / Have you been to ___?** — 경험 묻기

- **Have you been to ERPW before?** — 이전 참석 경험 `C-NET-028`

**E07 · Thanks for ___** — 감사

- **Thanks for your time — this was really useful.** — 대화 감사 `C-NET-029`

**E09 · Excuse me, ___** — 말 걸기

- **Hi, mind if I join you?** — 합류 (구어) `C-NET-030`

**E10 · How about ___? / Shall we ___? / Why don't we ___?** — 제안

- ★ **Shall we exchange cards?** — 명함 교환 제안 `C-NET-031`
- **Shall we connect on LinkedIn?** — 링크드인 연결 `C-NET-032`
- **How about a coffee during the next break?** — 커피 제안 `C-NET-033`
- **Why don't we have lunch together tomorrow?** — 점심 제안 `C-NET-034`
- **Shall we walk over together?** — 같이 이동 `C-NET-035`

**E11 · It was great ___ / Have a ___** — 작별

- ★ **It was great talking to you.** — 대화 마무리 `C-NET-036`
- **Hope to see you around this week.** — 다시 보자 `C-NET-037`
- **I should let you go — I'm sure you want to talk to other people.** — 상대를 놓아줄 때 `C-NET-038`
- **Good luck with your talk tomorrow!** — 발표 응원 `C-NET-039`

**E12 · I'm ___ / I work for ___** — 자기소개

- ★ **I'm a researcher at the Radiation Health Institute in Korea.** — 소속 소개 `C-NET-040`
- **It's part of Korea Hydro & Nuclear Power.** — 모기관 설명 `C-NET-041`
- **We're the research arm of Korea's nuclear power utility.** — 기관 쉽게 설명 `C-NET-042`
- **I lead a small data science group.** — 역할 `C-NET-043`
- **I've been in this field for about 25 years.** — 경력 `C-NET-044`
- **I'm a senior researcher, so I do a bit of everything.** — 시니어 역할 설명 `C-NET-045`

**E13 · I really enjoyed ___ / I loved ___** — 칭찬

- **I really enjoyed your talk this morning.** — 발표 칭찬 `C-NET-046`
- **I really liked how you handled the uncertainty analysis.** — 구체적 칭찬 `C-NET-047`

**F01 · I work on ___ / My research focuses on ___** — 연구 분야 소개

- ★ **I work on occupational radiation dosimetry.** — 연구 분야 `C-NET-048`
- **My research focuses on applying machine learning to dosimetry data.** — ML 연구 `C-NET-049`
- **These days I'm mostly working on language models for radiation protection.** — LLM 연구 `C-NET-050`
- **I'm also an endocrinologist by training.** — 임상 배경 `C-NET-051`
- **I work at the intersection of health physics and data science.** — 융합 분야 `C-NET-052`

**F02 · We're currently ___ing** — 진행 상황

- **We're currently building a retrieval system for ICRP documents.** — 현재 진행 연구 `C-NET-053`

**F12 · It would be interesting to ___ / I wonder whether ___** — 제안·호기심

- **I'd be curious to know how that works in practice.** — 실무 궁금 `C-NET-054`

**F13 · How did you ___?** — 방법 질문

- **How are you approaching that?** — 접근법 질문 `C-NET-055`

**F15 · Could you say more about ___?** — 부연 요청

- ★ **Could you tell me a bit more about that?** — 더 듣고 싶을 때 `C-NET-056`

**F16 · In our case, ___** — 자기 맥락 비교

- **In our case, most of the workers are at nuclear power plants.** — 우리 맥락 `C-NET-057`
- **In Korea, things work a bit differently.** — 한국은 다름 `C-NET-058`
- **In Korea, the dose limits basically follow the ICRP recommendations.** — 한국 규제 기준 `C-NET-059`

**J04 · Could we ___? / Can we ___?** — 일정·회의 제안

- **Could we find some time to talk later this week?** — 따로 시간 내기 `C-NET-060`

**J05 · Would you be interested in ___?** — 협력 제안

- ★ **Would you be interested in collaborating on something like this?** — 협업 관심 타진 `C-NET-061`

**J06 · I'll ___ (send / follow up)** — 후속 약속

- ★ **I'll send you an email after the conference.** — 이메일 약속 `C-NET-062`
- **I'll send you the paper.** — 논문 송부 약속 `C-NET-063`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Just call me Kim — it's easier.** — 호칭 편하게 `C-NET-064`
- **What are you working on these days?** — 상대 연구 묻기 `C-NET-065`
- **So, what's your area?** — 상대 분야 묻기 (구어) `C-NET-066`
- **This is my first time at ERPW.** — 첫 참석 `C-NET-067`
- **It's my second time — I came two years ago.** — 두 번째 참석 `C-NET-068`
- **I saw your talk yesterday — it was great.** — 발표 봤다고 언급 `C-NET-069`
- **I read your paper on eye lens dose — it was really helpful.** — 논문 읽었다고 언급 `C-NET-070`
- **Actually, we cited your 2023 paper in our work.** — 인용했다고 언급 `C-NET-071`
- **Here's my card.** — 명함 건넴 `C-NET-072`
- **I'm afraid I've run out of cards. Can I email you?** — 명함 소진 `C-NET-073`
- **Have you met Dr. Lee? She works on internal dosimetry.** — 제3자 소개 `C-NET-074`
- **I think we both know Dr. Park.** — 공통 지인 `C-NET-075`
- **Oh, you know Professor Han? Small world!** — 좁은 세상 `C-NET-076`
- **I need to catch someone before the next session. Excuse me.** — 다른 사람 만나러 갈 때 `C-NET-077`
- **I'm going to grab another coffee. Nice talking to you!** — 자연스럽게 빠지기 `C-NET-078`
- **Thanks, I'm glad you found it useful.** — 칭찬에 답 `C-NET-079`
- **That's a bit outside my field, but it sounds fascinating.** — 분야 밖이지만 관심 `C-NET-080`
- **Sorry, my English is a bit slow today — jet lag.** — 시차 양해 `C-NET-081`
- **How long are you staying?** — 체류 기간 묻기 `C-NET-082`
- **We're a small team — about ten researchers.** — 팀 규모 `C-NET-083`
- **Do you have students working on this?** — 학생 여부 묻기 `C-NET-084`
- **Long line for coffee, huh?** — 커피 줄 아이스브레이킹 `C-NET-085`
- **That was a good session, wasn't it?** — 세션 후 아이스브레이킹 `C-NET-086`
- **Is this your poster?** — 포스터 앞 아이스브레이킹 `C-NET-087`
- **This is my colleague, Dr. Park. She works on our LLM project.** — 동료 소개 `C-NET-088`
- **How long have you been at the BfS?** — 근속 기간 묻기 `C-NET-089`
- **What got you into this field?** — 입문 계기 묻기 `C-NET-090`
- **I started in health physics, and then got into data science about ten years ago.** — 입문 계기 답 `C-NET-091`

### `C-SML` 학회 스몰토크

*상황 61개 · ★ 3개*


**A10 · Do you mind if I ___?** — 상대를 배려한 허락

- **Do you mind if we take a photo together?** — 함께 사진 `C-SML-001`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time does it end tomorrow?** — 폐회 시각 `C-SML-002`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- ★ **Any recommendations for dinner around here?** — 근처 저녁 추천 `C-SML-003`

**B13 · Do you know ___? / Do you happen to know ___?** — 정보 보유 여부

- **Do you know if there's a pharmacy nearby?** — 근처 약국 정보 `C-SML-004`

**D02 · Sorry, I didn't catch ___** — 못 들었음

- **Sorry, I didn't hear the last part.** — 소음 속 놓침 `C-SML-005`

**E01 · Nice to meet you / Good to see you** — 인사

- ★ **Great to see you again!** — 반가운 재회 `C-SML-006`

**E02 · What brings you ___? / Are you here for ___?** — 방문 목적 묻기

- **Are you going to the IRPA congress next year?** — 다음 학회 참석 `C-SML-007`

**E03 · How's ___ going? / How was ___?** — 안부·경험

- ★ **How's your hotel?** — 호텔 안부 `C-SML-008`
- **How was your flight?** — 비행 안부 `C-SML-009`
- **How was the dinner last night?** — 어제 만찬 `C-SML-010`
- **How's work been?** — 요즘 일 `C-SML-011`

**E04 · Where are you ___?** — 출신·소속·숙소

- **Where are you staying?** — 숙소 묻기 `C-SML-012`

**E05 · That sounds ___ / That's ___** — 반응·맞장구

- **It's so much colder than in Seoul.** — 날씨 비교 `C-SML-013`
- **Tell me about it.** — 공감 (구어) `C-SML-014`
- **Oh, nice!** — 가벼운 반응 `C-SML-015`
- **Really? I didn't know that.** — 몰랐던 사실 `C-SML-016`
- **Oh, that's a shame.** — 아쉬움 `C-SML-017`
- **Congratulations! That's great news.** — 축하 `C-SML-018`
- **It's everywhere, isn't it?** — AI 맞장구 `C-SML-019`
- **You'll be fine!** — 격려 `C-SML-020`

**E06 · Have you ___? / Have you been to ___?** — 경험 묻기

- **Have you had a chance to look around the city?** — 도시 구경 여부 `C-SML-021`
- **Have you ever been to Korea?** — 한국 방문 경험 `C-SML-022`
- **Have you started anything new since we last met?** — 새 프로젝트 여부 `C-SML-023`

**E11 · It was great ___ / Have a ___** — 작별

- **See you at the dinner!** — 만찬에서 보자 `C-SML-024`
- **Catch you later!** — 가벼운 작별 `C-SML-025`
- **Safe travels home!** — 마지막 날 작별 `C-SML-026`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- **I think it's useful, but we still need to be careful with validation.** — AI 신중론 `C-SML-027`

**F10 · I agree ___ / That's a good point** — 동의

- **I thought it was really good too.** — 키노트 동의 `C-SML-028`

**F11 · I see what you mean, but ___** — 정중한 반대

- **It was interesting, but I wasn't fully convinced by the second part.** — 키노트 일부 이견 `C-SML-029`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Long, but okay. I'm still a bit jet-lagged.** — 비행 답 `C-SML-030`
- **I'm just around the corner, actually.** — 가까운 숙소 `C-SML-031`
- **Not yet — maybe after the conference.** — 아직 못 봄 `C-SML-032`
- **Beautiful day, isn't it?** — 날씨 인사 `C-SML-033`
- **The coffee here is actually pretty good.** — 커피 평 `C-SML-034`
- **Lunch was great today.** — 점심 평 `C-SML-035`
- **It's been a long day.** — 긴 하루 `C-SML-036`
- **There's so much going on — it's hard to choose.** — 세션 선택 고민 `C-SML-037`
- **You should come to Korea sometime. We'd be happy to host you.** — 한국 초대 `C-SML-038`
- **Did your family come along this time?** — 가족 동행 여부 `C-SML-039`
- **Are you staying on for a few days after?** — 학회 후 일정 `C-SML-040`
- **I'm taking two days off to see Dresden.** — 학회 후 계획 답 `C-SML-041`
- **Busy as always.** — 늘 바쁨 `C-SML-042`
- **I heard you got promoted — congratulations!** — 승진 축하 `C-SML-043`
- **It's been ages! How have you been?** — 오랜만 `C-SML-044`
- **Sorry, remind me — where did we meet?** — 기억이 안 날 때 (정직) `C-SML-045`
- **I think we met in Seoul a couple of years ago?** — 만난 곳 상기 `C-SML-046`
- **By the way, did you see the keynote this morning?** — 화제 전환 (키노트) `C-SML-047`
- **On a different note, how's your project going?** — 화제 전환 (프로젝트) `C-SML-048`
- **What did you think of the keynote?** — 키노트 의견 묻기 `C-SML-049`
- **Everyone seems to be talking about AI this year.** — AI 화제 `C-SML-050`
- **Have you tried the cake? It's really good.** — 음식 권유 `C-SML-051`
- **Please, have a seat.** — 자리 권유 `C-SML-052`
- **I'll send it to you.** — 사진 보내 주겠다 `C-SML-053`
- **Well, I should probably head to the next session.** — 다음 세션 가야 함 `C-SML-054`
- **Hope to see you at the next one.** — 다음 학회에서 보자 `C-SML-055`
- **Sorry, the tram was packed.** — 늦은 이유 `C-SML-056`
- **My body still thinks it's 3 a.m.** — 시차 농담 `C-SML-057`
- **My talk's done, so I can finally relax.** — 발표 끝난 안도 `C-SML-058`
- **I'm a bit nervous about my talk tomorrow.** — 발표 전 긴장 `C-SML-059`
- **This venue is huge — I keep getting lost.** — 넓은 학회장 `C-SML-060`
- **I need another coffee to get through the afternoon.** — 커피 필요 `C-SML-061`

### `C-PRE1` 발표 시작·기술 점검

*상황 57개 · ★ 5개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I have a glass of water at the podium?** — 단상 물 `C-PRE1-001`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- ★ **Could you help me load my slides?** — 슬라이드 업로드 도움 `C-PRE1-002`
- **Could you go back one slide, please?** — 이전 슬라이드 요청 `C-PRE1-003`
- **Could you dim the lights a little?** — 조명 조절 `C-PRE1-004`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would it be possible to use my own laptop?** — 개인 노트북 사용 `C-PRE1-005`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Is it okay if I start now?** — 시작 허락 `C-PRE1-006`

**B02 · How do I get to ___? / How do I ___?** — 경로·사용법 묻기

- **How will I know when I'm running out of time?** — 시간 신호 방식 `C-PRE1-007`

**B04 · Do you have ___?** — 보유·재고 여부

- **Do you have an HDMI adapter?** — HDMI 어댑터 `C-PRE1-008`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time is my slot?** — 발표 시각 `C-PRE1-009`

**B06 · How long ___?** — 소요 시간·기간

- **How long do I have — 12 minutes plus three for questions?** — 발표 시간 확인 `C-PRE1-010`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is this the latest version of my file?** — 최신 파일 확인 `C-PRE1-011`
- **Is this mic on?** — 마이크 켜짐 확인 `C-PRE1-012`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to upload my slides before the session?** — 사전 업로드 필요 `C-PRE1-013`
- **Will you hold up a card when I have two minutes left?** — 시간 카드 신호 확인 `C-PRE1-014`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **The fonts don't look right on this computer.** — 폰트 깨짐 `C-PRE1-015`
- **The video isn't playing.** — 동영상 재생 불가 `C-PRE1-016`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **Just to confirm, I'm after Dr. Novak?** — 순서 확인 `C-PRE1-017`

**E07 · Thanks for ___** — 감사

- **Thanks for the kind introduction.** — 소개 감사 `C-PRE1-018`

**E12 · I'm ___ / I work for ___** — 자기소개

- **I'm Kim, from the Radiation Health Institute in Korea.** — 간단 자기소개 `C-PRE1-019`

**F17 · This is based on ___** — 근거·출처

- **This work is based on the ICRP Publication 103 framework.** — 이론적 근거 `C-PRE1-020`

**G01 · Today I'd like to ___** — 발표 도입

- ★ **Today I'd like to talk about how we use language models in radiation protection.** — 주제 소개 `C-PRE1-021`
- **Today I'd like to share some results from our study on embedding models.** — 결과 공유 `C-PRE1-022`
- **In this talk, I'm going to show you how we reconstructed the dose algorithm.** — 발표 목적 `C-PRE1-023`
- **What I'd like to do today is focus on one practical question.** — 초점 한정 `C-PRE1-024`

**G02 · Let me start with ___ / First, ___** — 시작·순서

- ★ **Let me start with a quick overview.** — 개요 예고 `C-PRE1-025`
- **First, I'll give some background. Then I'll go through our methods and results.** — 발표 순서 `C-PRE1-026`
- **My talk has three parts.** — 세 부분 구성 `C-PRE1-027`
- **Let me start with a bit of background.** — 배경부터 `C-PRE1-028`
- **Let me start with a question.** — 질문으로 시작 `C-PRE1-029`

**G04 · This slide shows ___ / As you can see, ___** — 시각자료 설명

- **This slide shows the outline of the talk.** — 목차 슬라이드 `C-PRE1-030`
- **Here you can see why this problem matters.** — 문제의 중요성 `C-PRE1-031`
- **I'll show you a short video.** — 동영상 예고 `C-PRE1-032`

**G05 · What this means is ___ / The key point here is ___** — 의미 해석

- **The key point I want you to take away is this.** — 핵심 메시지 예고 `C-PRE1-033`
- **The problem is simple: we have a lot of documents, but finding the right paragraph is hard.** — 문제 정의 `C-PRE1-034`

**G08 · Can everyone ___? / Is ___ working?** — 기술 점검

- ★ **Can everyone hear me okay?** — 마이크 점검 `C-PRE1-035`
- **Can you hear me at the back?** — 뒷줄 점검 `C-PRE1-036`
- **Can everyone see the screen?** — 화면 점검 `C-PRE1-037`
- **Is the clicker working?** — 클리커 점검 `C-PRE1-038`
- **Is there a laser pointer?** — 레이저 포인터 `C-PRE1-039`

**G09 · I'm running short on time, so ___** — 시간 관리

- **I have a lot to cover, so I'll move quickly.** — 빠른 진행 예고 `C-PRE1-040`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Hi, I'm Kim — I'm the third speaker.** — 좌장에게 인사 `C-PRE1-041`
- **Okay, I'm ready.** — 준비 완료 `C-PRE1-042`
- ★ **Thank you, Chair, and good morning, everyone.** — 감사로 시작 `C-PRE1-043`
- **Good afternoon, everyone.** — 오후 인사 `C-PRE1-044`
- **This is joint work with my colleagues at KHNP and Seoul National University.** — 공동연구자 언급 `C-PRE1-045`
- **I have no conflicts of interest to declare.** — 이해충돌 없음 `C-PRE1-046`
- **How many of you have worked with TLD data? Just a show of hands.** — 청중 거수 유도 `C-PRE1-047`
- **Okay, quite a few of you. Great.** — 청중 반응 받기 `C-PRE1-048`
- **English isn't my first language, so please bear with me.** — 발표 중 영어 양해 `C-PRE1-049`
- **I'll try to keep this short — I know I'm between you and lunch.** — 가벼운 유머 `C-PRE1-050`
- **I'll take questions at the end.** — 질문은 마지막에 `C-PRE1-051`
- **Feel free to stop me if anything's unclear.** — 중간 질문 허용 `C-PRE1-052`
- **Sorry, just a moment — the slides seem to have frozen.** — 화면 멈춤 `C-PRE1-053`
- **Let me try that again.** — 다시 시도 `C-PRE1-054`
- **Is this better? Can you hear me now?** — 마이크 문제 후 확인 `C-PRE1-055`
- **Next slide, please.** — 슬라이드 넘김 요청 `C-PRE1-056`
- **I'm not sure you can see the pointer — it's the red line here.** — 포인터가 안 보일 때 `C-PRE1-057`

### `C-PRE2` 발표 본론 — 방법·흐름 설명

*상황 84개 · ★ 8개*


**F02 · We're currently ___ing** — 진행 상황

- **We're still collecting more data for the second phase.** — 진행 중 단계 `C-PRE2-001`

**F03 · We used ___ to ___** — 방법 설명

- ★ **We used a retrieval benchmark built from ICRP documents.** — 벤치마크 `C-PRE2-002`
- **We used dose records from about 5,000 workers.** — 선량 기록 데이터 `C-PRE2-003`
- **We used nine small embedding models.** — 비교 모델 `C-PRE2-004`
- **We used a mixed-effects model to account for repeated measurements.** — 혼합효과모형 `C-PRE2-005`
- **We used gradient boosting to predict the dose.** — 그래디언트 부스팅 `C-PRE2-006`
- **We used five-fold cross-validation.** — 교차검증 `C-PRE2-007`
- **We used an independent dataset for external validation.** — 외부 검증 `C-PRE2-008`
- **We used Monte Carlo simulations to estimate the conversion coefficients.** — 몬테카를로 `C-PRE2-009`
- **We used recall at 10 and nDCG as our main metrics.** — 평가 지표 `C-PRE2-010`
- **We used an LLM as a judge, and then checked a sample by hand.** — LLM 평가자 `C-PRE2-011`
- **We used a simple sliding window to split the documents into chunks.** — 청킹 `C-PRE2-012`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- **It seems that the multilingual models handle technical terms better.** — 조심스러운 관찰 `C-PRE2-013`

**F06 · Compared with ___ / ___ performed better than ___** — 비교

- ★ **We compared our method with the standard approach.** — 비교 기준 `C-PRE2-014`
- **Compared with the conventional algorithm, our method is more transparent.** — 기존 방법 대비 `C-PRE2-015`

**F17 · This is based on ___** — 근거·출처

- ★ **Our approach is based on the method described by Smith and colleagues.** — 선행 방법 근거 `C-PRE2-016`
- **The calibration follows the IEC 62387 standard.** — 표준 근거 `C-PRE2-017`
- **The dose limits are based on the current ICRP recommendations.** — 규제 근거 `C-PRE2-018`

**G02 · Let me start with ___ / First, ___** — 시작·순서

- **First, we cleaned the data. Second, we built the model. Finally, we evaluated it.** — 단계 나열 `C-PRE2-019`
- **Let me walk you through the steps.** — 단계별 안내 예고 `C-PRE2-020`

**G03 · Let's move on to ___ / Next, ___** — 전환

- ★ **Let's move on to the methods.** — 방법으로 전환 `C-PRE2-021`
- **Now, let's look at the results.** — 결과로 전환 `C-PRE2-022`
- **Next, I'd like to show you how we validated the model.** — 검증으로 전환 `C-PRE2-023`
- **So that's the background. Now let's turn to our approach.** — 배경에서 본론으로 `C-PRE2-024`
- **I'll skip the details here and move on to the main results.** — 세부 생략 후 전환 `C-PRE2-025`
- **Let's look at a specific case.** — 구체 사례로 전환 `C-PRE2-026`
- **Moving on to the second experiment.** — 두 번째 실험 `C-PRE2-027`

**G04 · This slide shows ___ / As you can see, ___** — 시각자료 설명

- ★ **This figure shows the overall workflow.** — 전체 흐름도 `C-PRE2-028`
- **Here you can see the pipeline from raw data to the final dose estimate.** — 파이프라인 `C-PRE2-029`
- **This diagram shows the architecture of the system.** — 시스템 구조 `C-PRE2-030`
- **On the left, you can see the input. On the right, the output.** — 좌우 설명 `C-PRE2-031`
- **The top panel shows the training data, and the bottom panel shows the test data.** — 상하 패널 `C-PRE2-032`
- **The blue line is the measured dose, and the red line is the prediction.** — 선 색상 `C-PRE2-033`
- **The x-axis shows time, and the y-axis shows the dose in millisieverts.** — 축 설명 `C-PRE2-034`
- **I've highlighted the most important part in red.** — 강조 표시 `C-PRE2-035`
- **Let me zoom in on this part.** — 확대 `C-PRE2-036`
- **This table summarizes the characteristics of the models.** — 표 설명 `C-PRE2-037`
- **The numbers in bold are the best results.** — 굵은 글씨 설명 `C-PRE2-038`
- **This equation shows how we calculate the dose.** — 수식 소개 `C-PRE2-039`
- **Let me walk you through this diagram step by step.** — 그림 단계별 설명 `C-PRE2-040`

**G05 · What this means is ___ / The key point here is ___** — 의미 해석

- ★ **What this means is that the model works well even with limited data.** — 의미 해석 `C-PRE2-041`
- **In other words, we don't need to retrain the model every time.** — 다시 말해 `C-PRE2-042`
- **The key point here is that the two algorithms give very similar results.** — 요점 `C-PRE2-043`
- **To put it simply, smaller models can do the job just as well.** — 쉽게 말해 `C-PRE2-044`
- **To give you an example, a typical query might be, "What's the dose limit for the lens of the eye?"** — 예시 질의 `C-PRE2-045`
- **In practice, this means operators can find the right document much faster.** — 실무적 의미 `C-PRE2-046`
- **Basically, it's a weighted sum of the four element readings.** — 수식 쉽게 설명 `C-PRE2-047`
- **This suggests that language-specific training matters more than model size.** — 함의 `C-PRE2-048`
- **Intuitively, this makes sense.** — 직관적으로 타당 `C-PRE2-049`

**G06 · As I mentioned ___ / Let me go back to ___** — 되돌아가기·연결

- ★ **As I mentioned earlier, the data were collected over ten years.** — 앞 내용 연결 `C-PRE2-050`
- **Let me go back to this figure for a moment.** — 그림으로 돌아가기 `C-PRE2-051`
- **I'll come back to this point later.** — 나중에 다룸 `C-PRE2-052`

**G09 · I'm running short on time, so ___** — 시간 관리

- ★ **I'll go through this quickly.** — 빠르게 넘김 `C-PRE2-053`
- **I don't have time to go into all the details, but they're in the paper.** — 세부는 논문에 `C-PRE2-054`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **By "dose," I mean the personal dose equivalent, Hp(10).** — 용어 정의 `C-PRE2-055`
- **When I say "small models," I mean models with fewer than 500 million parameters.** — 범위 정의 `C-PRE2-056`
- **RAG stands for retrieval-augmented generation.** — 약어 풀이 `C-PRE2-057`
- **We made a few assumptions here.** — 가정 언급 `C-PRE2-058`
- **We assumed that the workers wore their dosimeters correctly.** — 가정 구체 `C-PRE2-059`
- **We chose this model because it's open-source and runs on a single GPU.** — 모델 선택 이유 `C-PRE2-060`
- **The reason we did this is that the original data were very noisy.** — 처리 이유 `C-PRE2-061`
- **One important design choice was to keep everything on-premises.** — 설계 원칙 `C-PRE2-062`
- **For security reasons, we couldn't use any cloud services.** — 보안 제약 `C-PRE2-063`
- **The dataset consists of 1,200 question–answer pairs.** — 데이터셋 구성 `C-PRE2-064`
- **Half of the questions are in Korean, and half are in English.** — 언어 구성 `C-PRE2-065`
- **All the labels were checked by two domain experts.** — 전문가 검증 `C-PRE2-066`
- **The inter-rater agreement was quite high, with a kappa of 0.82.** — 평가자 일치도 `C-PRE2-067`
- **The study was approved by our institutional review board.** — 윤리 승인 `C-PRE2-068`
- **All the data were anonymized before analysis.** — 익명화 `C-PRE2-069`
- **The code and data are available on GitHub.** — 코드 공개 `C-PRE2-070`
- **Let me give you a real example from one of our plants.** — 실제 사례 예고 `C-PRE2-071`
- **Is that clear so far?** — 이해 확인 (청중) `C-PRE2-072`
- **Does that make sense?** — 이해 확인 (구어) `C-PRE2-073`
- **You can find the full details in our paper.** — 논문 참조 `C-PRE2-074`
- **I've put the details in the backup slides.** — 백업 슬라이드 참조 `C-PRE2-075`
- **You can think of it as a kind of search engine for regulations.** — 직관적 설명 `C-PRE2-076`
- **It's a bit like asking a librarian who has read every ICRP report.** — 비유 `C-PRE2-077`
- **You might be wondering why we didn't use a larger model.** — 예상 질문 선제 `C-PRE2-078`
- **The answer is cost — and also data security.** — 선제 답변 `C-PRE2-079`
- **This is important, so I'd like to spend a minute on it.** — 중요 강조 `C-PRE2-080`
- **Interestingly, the smallest model did surprisingly well.** — 흥미로운 점 강조 `C-PRE2-081`
- **What surprised us was how stable the results were.** — 놀라운 점 `C-PRE2-082`
- **There are other ways to do this, but we chose the simplest one.** — 단순한 방법 선택 `C-PRE2-083`
- **I'll show you the numbers on the next slide.** — 다음 슬라이드 예고 `C-PRE2-084`

### `C-PRE3` 결과·데이터·통계 설명

*상황 86개 · ★ 7개*


**F04 · We found that ___ / The main finding is ___** — 결과 제시

- ★ **We found that the small models performed almost as well as the large ones.** — 주요 결과 `C-PRE3-001`
- **The main finding is that domain-specific fine-tuning improved recall by about 15 percent.** — 성능 향상 `C-PRE3-002`
- **We found a statistically significant difference between the two groups.** — 유의한 차이 `C-PRE3-003`
- **We didn't find any significant difference between the two algorithms.** — 유의한 차이 없음 `C-PRE3-004`
- **We found a strong correlation between the two dosimeters.** — 강한 상관 `C-PRE3-005`
- **We found a clear trend over time.** — 시간 경향 `C-PRE3-006`
- **We found something unexpected.** — 예상 밖 결과 `C-PRE3-007`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- ★ **These results suggest that the method could be applied to other plants.** — 적용 가능성 (헤징) `C-PRE3-008`
- **It seems that the difference is mainly due to the energy response.** — 원인 추정 (헤징) `C-PRE3-009`
- **This indicates that the model is fairly robust.** — 견고성 (헤징) `C-PRE3-010`
- **We should be careful not to over-interpret this.** — 과잉 해석 경계 `C-PRE3-011`
- **This could be useful for routine monitoring.** — 유용 가능성 `C-PRE3-012`
- **We think this is because of the calibration differences.** — 추정 표현 `C-PRE3-013`

**F06 · Compared with ___ / ___ performed better than ___** — 비교

- ★ **Compared with the baseline, our model was about 20 percent more accurate.** — 기준선 대비 `C-PRE3-014`
- **Model A performed better than Model B on Korean queries.** — 언어별 우열 `C-PRE3-015`
- **The two methods gave very similar results.** — 유사 `C-PRE3-016`
- **Our model performed slightly worse on long documents.** — 열세 `C-PRE3-017`
- **The error rate was half that of the conventional method.** — 오류율 비교 `C-PRE3-018`
- **This is consistent with previous studies.** — 선행연구 일치 `C-PRE3-019`
- **This is somewhat different from what Smith and colleagues reported.** — 선행연구 불일치 `C-PRE3-020`
- **All the values were well below the regulatory limit.** — 규제 한도 대비 `C-PRE3-021`

**F08 · One possible explanation is ___ / This might be due to ___** — 해석·원인 추정

- ★ **One possible explanation is that the Korean translation uses different terms.** — 원인 해석 `C-PRE3-022`
- **This might be due to the small sample size.** — 표본 크기 탓 `C-PRE3-023`
- **We think this is partly because of the tokenizer.** — 토크나이저 탓 `C-PRE3-024`
- **It's probably a combination of several factors.** — 복합 요인 `C-PRE3-025`
- **We're not entirely sure why this happened.** — 원인 불명 `C-PRE3-026`

**G03 · Let's move on to ___ / Next, ___** — 전환

- **Let's look at the second set of results.** — 두 번째 결과로 `C-PRE3-027`
- **Now let's take a closer look at the Korean queries.** — 세부로 들어가기 `C-PRE3-028`

**G04 · This slide shows ___ / As you can see, ___** — 시각자료 설명

- ★ **As you can see, the two lines are very close.** — 그래프 일치 `C-PRE3-029`
- **Each bar represents one model.** — 막대 설명 `C-PRE3-030`
- **Each dot represents one worker.** — 점 설명 `C-PRE3-031`
- **The box plot shows the distribution for each plant.** — 박스플롯 `C-PRE3-032`
- **The heat map shows the similarity scores between models.** — 히트맵 `C-PRE3-033`
- **The error bars show the 95 percent confidence intervals.** — 오차막대 `C-PRE3-034`
- **The dashed line is the line of identity.** — 대각선 `C-PRE3-035`
- **This is a Bland–Altman plot comparing the two methods.** — Bland–Altman `C-PRE3-036`
- **The arrow marks the point where we changed the algorithm.** — 화살표 표시 `C-PRE3-037`

**G05 · What this means is ___ / The key point here is ___** — 의미 해석

- ★ **What this tells us is that the bias is consistent across the dose range.** — 그림이 말하는 것 `C-PRE3-038`
- **The key point is that most of the error comes from low-dose readings.** — 오차의 출처 `C-PRE3-039`
- **In other words, the model is well calibrated.** — 보정 양호 `C-PRE3-040`
- **Clinically, this difference is probably not meaningful.** — 임상적 의미 `C-PRE3-041`
- **From a practical point of view, this is good news for operators.** — 실무적 의미 `C-PRE3-042`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **The mean dose was 0.8 millisieverts per year.** — 평균 읽기 `C-PRE3-043`
- **The values ranged from 0.1 to 2.4 millisieverts.** — 범위 읽기 `C-PRE3-044`
- **The standard deviation was relatively small.** — 표준편차 `C-PRE3-045`
- **The median was 0.5, with an interquartile range of 0.3 to 0.9.** — 중앙값·사분위 `C-PRE3-046`
- **The 95 percent confidence interval was 1.2 to 1.8.** — 신뢰구간 `C-PRE3-047`
- **The p-value was less than 0.001.** — p값 `C-PRE3-048`
- **The effect size was moderate.** — 효과크기 `C-PRE3-049`
- **The model achieved an accuracy of 92 percent.** — 정확도 `C-PRE3-050`
- **The AUC was 0.89.** — AUC `C-PRE3-051`
- **Sensitivity was 85 percent and specificity was 90 percent.** — 민감도·특이도 `C-PRE3-052`
- **The R-squared was 0.76.** — 결정계수 `C-PRE3-053`
- **The root mean squared error was about 0.05 millisieverts.** — RMSE `C-PRE3-054`
- **The relative error was within plus or minus 10 percent.** — 상대오차 `C-PRE3-055`
- **The top three models were all multilingual.** — 상위 모델 `C-PRE3-056`
- **The dose increased steadily from 2015 to 2020.** — 증가 추세 `C-PRE3-057`
- **After the new procedure was introduced, the dose dropped sharply.** — 급감 `C-PRE3-058`
- **After that, it leveled off.** — 정체 `C-PRE3-059`
- **There's quite a lot of variation between plants.** — 발전소 간 변동 `C-PRE3-060`
- **There are a few outliers here.** — 이상치 언급 `C-PRE3-061`
- **We excluded these outliers after checking the raw data.** — 이상치 처리 `C-PRE3-062`
- **About three percent of the data were missing.** — 결측 비율 `C-PRE3-063`
- **We handled the missing data using multiple imputation.** — 결측 처리 `C-PRE3-064`
- **The distribution is clearly skewed to the right.** — 분포 모양 `C-PRE3-065`
- **So we log-transformed the data before the analysis.** — 로그 변환 `C-PRE3-066`
- **You can see a clear seasonal pattern.** — 계절성 `C-PRE3-067`
- **The peak corresponds to the outage period.** — 피크 해석 (계획예방정비) `C-PRE3-068`
- **Please note that the scale here is logarithmic.** — 로그 스케일 주의 `C-PRE3-069`
- **Note that the y-axis doesn't start at zero.** — 축 시작점 주의 `C-PRE3-070`
- **We also did a subgroup analysis by job type.** — 하위군 분석 `C-PRE3-071`
- **The results were consistent across subgroups.** — 하위군 일관성 `C-PRE3-072`
- **A sensitivity analysis gave similar results.** — 민감도 분석 `C-PRE3-073`
- **In the ablation study, removing the reranker had the biggest effect.** — 절제 실험 `C-PRE3-074`
- **When we looked at the errors, most of them involved tables.** — 오류 분석 `C-PRE3-075`
- **Here's an example where the model got it wrong.** — 실패 사례 `C-PRE3-076`
- **And here's one where it got it right.** — 성공 사례 `C-PRE3-077`
- **It's statistically significant, but the actual difference is very small.** — 통계 vs 실무 차이 `C-PRE3-078`
- **This was the most surprising result for us.** — 가장 놀라운 결과 `C-PRE3-079`
- **This is more or less what we expected.** — 예상과 일치 `C-PRE3-080`
- **So, in short, the method works.** — 짧은 요약 `C-PRE3-081`
- **I'd like to draw your attention to this number.** — 수치 주목 `C-PRE3-082`
- **That's roughly three times higher than the baseline.** — 배수 표현 `C-PRE3-083`
- **About two-thirds of the queries were answered correctly.** — 분수 표현 `C-PRE3-084`
- **That's about one in five.** — 비율 표현 `C-PRE3-085`
- **All the values are in millisieverts.** — 단위 명시 `C-PRE3-086`

### `C-PRE4` 한계·결론·마무리

*상황 48개 · ★ 5개*


**E07 · Thanks for ___** — 감사

- **Thanks, Chair.** — 좌장 감사 `C-PRE4-001`
- **Thanks to the organizers for inviting me.** — 주최 측 감사 `C-PRE4-002`

**F02 · We're currently ___ing** — 진행 상황

- **We're currently working on a larger dataset.** — 후속 데이터 진행 `C-PRE4-003`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- **We think this approach is promising, but more validation is needed.** — 조심스러운 결론 `C-PRE4-004`
- **These are preliminary results, so please take them with a grain of salt.** — 예비 결과 경고 `C-PRE4-005`

**F07 · One limitation is ___** — 한계 인정

- ★ **One limitation is that we only used data from one country.** — 단일 국가 데이터 `C-PRE4-006`
- **One limitation is the relatively small sample size.** — 작은 표본 `C-PRE4-007`
- **We're not sure how well this generalizes to other settings.** — 일반화 불확실 `C-PRE4-008`
- **Another limitation is that some of the Korean texts were machine-translated.** — 기계번역 데이터 `C-PRE4-009`
- **We had only two annotators, so there may be some bias.** — 평가자 수 `C-PRE4-010`
- **The study was retrospective, so we can't prove causality.** — 후향적 설계 `C-PRE4-011`
- **We didn't test the models on different hardware.** — 하드웨어 미검증 `C-PRE4-012`
- **We didn't look at very long documents.** — 장문 미검토 `C-PRE4-013`
- **I should mention that this is still a pilot study.** — 파일럿 연구임 `C-PRE4-014`

**F09 · In future work, we plan to ___ / Next, we'd like to ___** — 향후 계획

- ★ **In future work, we plan to include more languages.** — 언어 확장 `C-PRE4-015`
- **Next, we'd like to test this in a real operational setting.** — 현장 적용 `C-PRE4-016`
- **We also plan to release the benchmark publicly.** — 벤치마크 공개 `C-PRE4-017`
- **We're hoping to validate this with data from other utilities.** — 타 기관 검증 `C-PRE4-018`
- **Next year, we'd like to extend this to internal dosimetry.** — 내부피폭 확장 `C-PRE4-019`

**F12 · It would be interesting to ___ / I wonder whether ___** — 제안·호기심

- **It would be interesting to see whether this holds for other languages.** — 열린 질문 (언어) `C-PRE4-020`
- **I wonder whether the same pattern would show up in medical data.** — 열린 질문 (의료) `C-PRE4-021`

**G05 · What this means is ___ / The key point here is ___** — 의미 해석

- **The bigger picture here is how we make regulatory knowledge easier to access.** — 큰 그림 `C-PRE4-022`

**G06 · As I mentioned ___ / Let me go back to ___** — 되돌아가기·연결

- **Let me go back to the question I asked at the beginning.** — 처음 질문으로 회귀 `C-PRE4-023`

**G07 · To sum up ___ / The take-home message is ___** — 요약·결론

- ★ **To sum up, small embedding models can work well for radiation protection.** — 결론 요약 `C-PRE4-024`
- **So, to summarize, there are three main points.** — 세 가지 요점 `C-PRE4-025`
- **The take-home message is that you don't always need a large model.** — 핵심 메시지 `C-PRE4-026`
- **If you remember one thing from this talk, I hope it's this.** — 하나만 기억한다면 `C-PRE4-027`
- **In conclusion, the method is accurate, transparent, and easy to use.** — 결론 진술 `C-PRE4-028`
- **Just to recap: the data, the model, and the validation.** — 짧은 재정리 `C-PRE4-029`

**G09 · I'm running short on time, so ___** — 시간 관리

- ★ **I'm running short on time, so let me jump to the conclusion.** — 시간 부족으로 결론 `C-PRE4-030`
- **I'll skip this slide in the interest of time.** — 슬라이드 생략 `C-PRE4-031`
- **I see I'm almost out of time, so I'll wrap up.** — 신호 받고 마무리 `C-PRE4-032`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Our recommendation would be to start with a small model and scale up only if needed.** — 실무 권고 `C-PRE4-033`
- **If anyone's interested in collaborating, please come and talk to me.** — 협업 초대 `C-PRE4-034`
- **The slides and code are available at this link.** — 자료 링크 `C-PRE4-035`
- **You can scan this QR code to get the paper.** — QR 코드 `C-PRE4-036`
- **Feel free to email me if you have any questions.** — 연락 환영 `C-PRE4-037`
- **I'd like to thank my colleagues and our funding agency.** — 공동연구자 감사 `C-PRE4-038`
- **This work was supported by a grant from KHNP.** — 연구비 출처 `C-PRE4-039`
- ★ **Thank you for your attention.** — 발표 종료 `C-PRE4-040`
- **Thank you. I'm happy to take any questions.** — 종료 후 질문 초대 `C-PRE4-041`
- **That's all from me. Thank you.** — 간단한 종료 `C-PRE4-042`
- **Sorry, I went a bit over time.** — 시간 초과 사과 `C-PRE4-043`
- **I think I have a couple of minutes left, so let me show one more example.** — 시간 여유 활용 `C-PRE4-044`
- **I'd be very interested to hear your thoughts on this.** — 청중 의견 요청 `C-PRE4-045`
- **I'd love to hear if anyone has had a similar experience.** — 유사 경험 요청 `C-PRE4-046`
- **Thank you all for coming.** — 참석 감사 `C-PRE4-047`
- **Oops, that's a backup slide. Let me go back.** — 백업 슬라이드로 넘어감 `C-PRE4-048`

### `C-QA1` 질문 받기·답변하기

*상황 81개 · ★ 9개*


**D01 · Sorry, could you say that again?** — 반복 요청

- ★ **Sorry, could you repeat the question?** — 질문 반복 요청 `C-QA1-001`
- **Sorry, could you use the microphone? It's a bit hard to hear.** — 마이크 사용 요청 `C-QA1-002`
- **Sorry, what was the second part of your question again?** — 질문 둘째 부분 잊음 `C-QA1-003`

**D02 · Sorry, I didn't catch ___** — 못 들었음

- **Sorry, I didn't catch the last part of your question.** — 질문 끝부분 놓침 `C-QA1-004`

**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- **When you say "uncertainty," do you mean measurement uncertainty or model uncertainty?** — 용어 의미 확인 `C-QA1-005`

**D05 · Could you speak more slowly / write it down?** — 전달 방식 변경 요청

- **Sorry, could you say that a little more slowly?** — 천천히 요청 `C-QA1-006`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **Do you mean the training data or the test data?** — 대상 확인 `C-QA1-007`

**D07 · Let me ___** — 시간 벌기·행동 예고

- **Let me think about that for a moment.** — 생각할 시간 `C-QA1-008`
- **Let me check my notes.** — 노트 확인 `C-QA1-009`

**F03 · We used ___ to ___** — 방법 설명

- **We used the default settings for all the models.** — 기본 설정 사용 `C-QA1-010`
- **We used the same prompts for every model, to keep it fair.** — 공정 비교 `C-QA1-011`

**F04 · We found that ___ / The main finding is ___** — 결과 제시

- **We actually found that the Korean model was better on technical terms.** — 결과로 답 `C-QA1-012`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- **I think it would work, but we haven't tested it yet.** — 미검증 가능성 `C-QA1-013`
- **It's possible, but I wouldn't want to overstate it.** — 과장 경계 `C-QA1-014`

**F06 · Compared with ___ / ___ performed better than ___** — 비교

- **Compared with your approach, ours is simpler but less flexible.** — 질문자 방법과 비교 `C-QA1-015`
- **Compared with the 2019 study, our dataset is about three times larger.** — 선행연구 대비 규모 `C-QA1-016`

**F07 · One limitation is ___** — 한계 인정

- ★ **That's a fair point — it's one of the limitations of the study.** — 한계 인정 `C-QA1-017`
- **You're right, we didn't control for that.** — 통제 못함 인정 `C-QA1-018`

**F08 · One possible explanation is ___ / This might be due to ___** — 해석·원인 추정

- **We think it's mainly because of the training data.** — 원인으로 답 `C-QA1-019`

**F09 · In future work, we plan to ___ / Next, we'd like to ___** — 향후 계획

- **That's something we're planning to look at next.** — 향후 과제로 답 `C-QA1-020`
- **We'd like to do that in the next phase.** — 다음 단계로 답 `C-QA1-021`

**F11 · I see what you mean, but ___** — 정중한 반대

- ★ **I see what you mean, but in our data, the effect was quite small.** — 정중한 이견 `C-QA1-022`
- **I understand your concern, but I think the risk is limited in this case.** — 우려 이해+이견 `C-QA1-023`

**F14 · Did you consider ___? / Have you tried ___?** — 대안 제시형 질문

- **Have you tried something similar in your lab?** — 역질문 `C-QA1-024`

**F16 · In our case, ___** — 자기 맥락 비교

- **In our case, the dosimeters are read every month.** — 판독 주기 `C-QA1-025`
- **In Korea, that's handled by the regulator, not the utility.** — 한국 제도 `C-QA1-026`

**F17 · This is based on ___** — 근거·출처

- **That's based on the IAEA guidance.** — 지침 근거 `C-QA1-027`

**G04 · This slide shows ___ / As you can see, ___** — 시각자료 설명

- **I have a backup slide on that. Here you can see the breakdown.** — 백업 슬라이드로 답 `C-QA1-028`

**G06 · As I mentioned ___ / Let me go back to ___** — 되돌아가기·연결

- **Let me go back to this slide — I think it answers your question.** — 슬라이드로 답 `C-QA1-029`

**H01 · That's a good question / Thanks for the question** — 답변 도입

- ★ **Thank you for the question.** — 질문 감사 `C-QA1-030`
- **That's a really good question.** — 좋은 질문 `C-QA1-031`
- **That's an important point. Thanks for raising it.** — 중요한 지적 `C-QA1-032`
- **That's a question we get quite often.** — 자주 받는 질문 `C-QA1-033`
- **That's an interesting question. Let me think about that for a second.** — 생각할 시간 `C-QA1-034`

**H02 · If I understand correctly, ___** — 질문 재확인

- ★ **If I understand correctly, you're asking about the calibration, right?** — 질문 재확인 `C-QA1-035`
- **So your question is whether the model works for other languages?** — 질문 요약 `C-QA1-036`
- **Just to make sure I understand — you mean the low-dose range?** — 범위 확인 `C-QA1-037`

**H05 · I'd be happy to ___** — 후속 제안

- ★ **I'd be happy to discuss that in more detail after the session.** — 세션 후 논의 `C-QA1-038`
- **I'd be happy to send you the details by email.** — 이메일로 상세 `C-QA1-039`
- **I'd be happy to share the code if you're interested.** — 코드 공유 `C-QA1-040`

**H07 · Does that answer your question?** — 답변 마무리

- ★ **Does that answer your question?** — 답변 확인 `C-QA1-041`
- **I hope that answers your question.** — 답변 마무리 `C-QA1-042`
- **I'm not sure I fully answered that — maybe we can talk more after the session.** — 답변 부족 시 `C-QA1-043`

**H08 · Can I just add ___? / If I may, ___** — 끼어들기·보충

- ★ **Can I just add one thing?** — 답변 보충 `C-QA1-044`
- **If I may, I'd like to add something to my previous answer.** — 이전 답변 보충 `C-QA1-045`
- **Sorry, let me correct what I said earlier — it was 15 percent, not 50.** — 수치 정정 `C-QA1-046`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **I think there are two parts to your question.** — 두 부분 질문 정리 `C-QA1-047`
- **Let me answer the first part first.** — 첫 부분부터 `C-QA1-048`
- **And regarding your second question…** — 두 번째 부분 `C-QA1-049`
- ★ **The short answer is yes.** — 짧은 답 (예) `C-QA1-050`
- **The short answer is no, but there's a reason.** — 짧은 답 (아니오+이유) `C-QA1-051`
- **Yes, but only under certain conditions.** — 조건부 답 `C-QA1-052`
- **Mostly, yes.** — 대체로 그렇다 `C-QA1-053`
- **That's a great suggestion. Thank you.** — 제안 수용 `C-QA1-054`
- **To be honest, we hadn't thought about that.** — 미처 생각 못함 `C-QA1-055`
- **We'll definitely take that into account.** — 반영 약속 `C-QA1-056`
- **I completely agree.** — 전적 동의 `C-QA1-057`
- **I agree to some extent, but…** — 부분 동의 `C-QA1-058`
- **Any other questions?** — 다음 질문 받기 `C-QA1-059`
- **Yes, at the back?** — 뒷줄 지목 `C-QA1-060`
- **Yes, please — go ahead.** — 질문자 지목 `C-QA1-061`
- **If there are no more questions, thank you again.** — 질문 없을 때 종료 `C-QA1-062`
- **Sorry, could you tell me your name? I'd like to follow up.** — 질문자 이름 묻기 `C-QA1-063`
- **Thank you, that's very kind.** — 칭찬에 답 `C-QA1-064`
- **My colleague here might be able to answer that better.** — 공동저자에게 넘김 `C-QA1-065`
- **Min-ji, would you like to add anything?** — 공동저자 부르기 `C-QA1-066`
- **I'll keep it short, since we're running out of time.** — 시간 부족 짧은 답 `C-QA1-067`
- **Let's take that offline.** — 따로 논의 `C-QA1-068`
- **Please feel free to come and find me later.** — 나중에 찾아오라 `C-QA1-069`
- **Let me give you an example.** — 예시로 답 `C-QA1-070`
- **I don't remember the exact number, but it was around ten percent.** — 정확한 수치 기억 안 남 `C-QA1-071`
- **I'd have to check the exact figure.** — 확인 필요 `C-QA1-072`
- **I can see why you'd think that.** — 오해 이유 공감 `C-QA1-073`
- **Actually, that's a common misunderstanding.** — 흔한 오해 정정 `C-QA1-074`
- **Let me clarify — we didn't replace the existing system. We added a layer on top of it.** — 명확화 `C-QA1-075`
- **Without going into too much detail, the main idea is this.** — 깊이 조절 `C-QA1-076`
- **You probably know this better than I do, but here's how we approached it.** — 전문가 질문자 존중 `C-QA1-077`
- **What's your experience with that?** — 질문자 경험 묻기 `C-QA1-078`
- **Yes, I remember that exact case.** — 그 사례 기억 `C-QA1-079`
- **You've put your finger on the main issue.** — 핵심을 짚은 질문 `C-QA1-080`
- **It's not really a yes-or-no question, but let me try.** — 단답 불가 질문 `C-QA1-081`

### `C-QA2` 어려운 질문·비판 대응

*상황 62개 · ★ 4개*


**C10 · I'm afraid ___** — 나쁜 소식·거절의 완곡

- ★ **I'm afraid we can't share the raw data, for confidentiality reasons.** — 원자료 공유 불가 `C-QA2-001`
- **I'm afraid that's restricted information.** — 제한 정보 `C-QA2-002`
- **I'm afraid I can't say much yet — the paper is under review.** — 심사 중 논문 `C-QA2-003`

**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- **Sorry, could you clarify what you mean by "realistic"?** — 모호한 단어 확인 `C-QA2-004`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **Are you asking about the method or the interpretation?** — 방법인지 해석인지 `C-QA2-005`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- **I wouldn't go as far as to say that.** — 과도한 일반화 거부 `C-QA2-006`
- **I think that would be over-interpreting the data.** — 과잉 해석 지적 `C-QA2-007`

**F06 · Compared with ___ / ___ performed better than ___** — 비교

- **Our results differ from that study mainly because of the population.** — 모집단 차이 `C-QA2-008`

**F07 · One limitation is ___** — 한계 인정

- **That's a valid criticism. We should have included a control group.** — 타당한 비판 수용 `C-QA2-009`
- **You're right, the sample size is small. That's why we call it a pilot.** — 표본 약점 인정 `C-QA2-010`

**F08 · One possible explanation is ___ / This might be due to ___** — 해석·원인 추정

- **Another explanation could be the change in reading equipment.** — 대안 설명 `C-QA2-011`

**F11 · I see what you mean, but ___** — 정중한 반대

- ★ **I take your point, but I think the results still hold.** — 지적 수용 후 반박 `C-QA2-012`
- **I see what you mean, but we did check for that in a sensitivity analysis.** — 민감도 분석 근거 `C-QA2-013`
- **I understand the concern, but the bias was less than two percent.** — 편향 크기 근거 `C-QA2-014`
- **I'd respectfully disagree on that point.** — 정중한 반대 `C-QA2-015`
- **I think we're looking at it from slightly different angles.** — 관점 차이 `C-QA2-016`
- **You may be right, but our data suggest otherwise.** — 데이터는 다르게 시사 `C-QA2-017`

**F16 · In our case, ___** — 자기 맥락 비교

- **In our case, the regulator required us to use the existing method.** — 규제기관 요구 `C-QA2-018`

**H02 · If I understand correctly, ___** — 질문 재확인

- **Let me make sure I understand — you're asking whether the bias could explain the whole effect?** — 공격적 질문 재구성 `C-QA2-019`
- **If I understand your concern correctly, it's about the validity of the reference values?** — 우려 재확인 `C-QA2-020`

**H03 · I'm not sure, but ___ / I don't have ___, but ___** — 모를 때

- ★ **I'm not sure, but my guess would be that it's related to the energy spectrum.** — 모를 때 추측 명시 `C-QA2-021`
- **I don't have the data on that, but I can look into it.** — 데이터 없음 `C-QA2-022`
- **I don't know the answer off the top of my head.** — 즉답 불가 `C-QA2-023`
- **Honestly, I don't know. That's a good question for future work.** — 솔직히 모름 `C-QA2-024`
- **I can only speculate, but…** — 추측일 뿐 `C-QA2-025`

**H04 · That's outside the scope of ___** — 범위 밖

- ★ **That's a bit outside the scope of this study.** — 연구 범위 밖 `C-QA2-026`
- **We didn't look at that specifically.** — 따로 보지 않음 `C-QA2-027`
- **That's beyond my area of expertise, I'm afraid.** — 전문 분야 밖 `C-QA2-028`
- **That's actually being covered in a separate project.** — 별도 과제 `C-QA2-029`

**H05 · I'd be happy to ___** — 후속 제안

- **I'd be happy to continue this discussion over coffee.** — 커피하며 계속 `C-QA2-030`

**H07 · Does that answer your question?** — 답변 마무리

- **Does that address your concern?** — 우려 해소 확인 `C-QA2-031`

**J06 · I'll ___ (send / follow up)** — 후속 약속

- **I'll email you the details after the session.** — 이메일 회신 약속 `C-QA2-032`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **So, if I could summarize your question…** — 긴 질문 요약 `C-QA2-033`
- **You've raised several points — let me take them one at a time.** — 여러 지적 정리 `C-QA2-034`
- **That's a tricky one.** — 까다로운 질문 `C-QA2-035`
- **Hmm, let me think about how best to answer that.** — 시간 벌기 `C-QA2-036`
- **To be honest, that's something we struggled with too.** — 같은 고민 고백 `C-QA2-037`
- **Let me check and get back to you.** — 확인 후 회신 `C-QA2-038`
- **Thank you for pointing that out. You're absolutely right.** — 지적 수용 (전적) `C-QA2-039`
- **That's a mistake on the slide. Thanks for catching it.** — 슬라이드 오류 인정 `C-QA2-040`
- **Sorry, that number should be 0.5, not 5.** — 수치 정정 `C-QA2-041`
- **Do you have any data on that yourself?** — 질문자 데이터 묻기 `C-QA2-042`
- **What would you suggest?** — 질문자 제안 묻기 `C-QA2-043`
- **We chose that metric because it's standard in the field.** — 지표 선택 근거 `C-QA2-044`
- **We did consider that, but it wasn't practical with our data.** — 대안 검토했으나 `C-QA2-045`
- **Unfortunately, we didn't have the resources to do that.** — 자원 한계 `C-QA2-046`
- **That's partly a regulatory issue, not just a technical one.** — 규제 문제 `C-QA2-047`
- **That might be specific to the Korean context.** — 한국 특수성 `C-QA2-048`
- **The situation may be different in Europe.** — 유럽은 다를 수 `C-QA2-049`
- **I think we may have to agree to disagree on this one.** — 합의 불가 인정 `C-QA2-050`
- **I'm happy to discuss more, but I'm conscious of time.** — 시간 의식 `C-QA2-051`
- **I appreciate the comment.** — 공격적 어조에 차분히 `C-QA2-052`
- **Thank you for the comment. I agree that's important.** — 코멘트에 답 `C-QA2-053`
- **That's a good point, and we'll mention it in the paper.** — 논문 반영 약속 `C-QA2-054`
- **Yes, and I'd add that cost is also an issue.** — 동의하며 추가 `C-QA2-055`
- **I share your concern.** — 우려 공유 `C-QA2-056`
- **There's definitely some uncertainty there.** — 불확실성 인정 `C-QA2-057`
- **We'd need more data to answer that properly.** — 추가 데이터 필요 `C-QA2-058`
- **Actually, we did look at that — it's in the supplementary material.** — 보충 자료에 있음 `C-QA2-059`
- **Good point. We actually controlled for that in the model.** — 이미 통제함 `C-QA2-060`
- **I think there may be a slight misunderstanding. Let me explain.** — 오해 바로잡기 `C-QA2-061`
- **Just to clarify, the 20 percent was the relative difference, not absolute.** — 상대·절대 차이 명확화 `C-QA2-062`

### `C-ASK` 청중으로서 질문하기

*상황 74개 · ★ 8개*


**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you show the previous slide again?** — 이전 슬라이드 요청 `C-ASK-001`

**A07 · I was wondering if ___** — 매우 조심스러운 부탁

- ★ **I was wondering whether you looked at the seasonal variation.** — 조심스러운 질문 `C-ASK-002`
- **I was wondering how you chose the threshold.** — 임계값 선택 `C-ASK-003`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can I ask a quick question?** — 질문해도 되는지 `C-ASK-004`

**B16 · What if ___? / What happens if ___?** — 조건·예외 상황

- **What happens if the energy is below 30 keV?** — 저에너지 조건 `C-ASK-005`
- **What if the input documents are in a different format?** — 입력 형식 변화 `C-ASK-006`

**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- **Sorry, what do you mean by "hybrid retrieval"?** — 용어 확인 `C-ASK-007`
- **What does "CR" stand for in this table?** — 표 약어 `C-ASK-008`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **So, if I understood correctly, the model was trained only on English data?** — 이해 확인 `C-ASK-009`

**E07 · Thanks for ___** — 감사

- **Thanks for the very interesting presentation.** — 감사로 시작 `C-ASK-010`

**E09 · Excuse me, ___** — 말 걸기

- ★ **Hi, thank you for the great talk. I'm Kim, from Korea.** — 마이크 잡고 시작 `C-ASK-011`

**E13 · I really enjoyed ___ / I loved ___** — 칭찬

- **I really liked your approach to the uncertainty analysis.** — 칭찬 후 질문 `C-ASK-012`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- **It seems to me that the effect might depend on the plant type.** — 조심스러운 코멘트 `C-ASK-013`

**F10 · I agree ___ / That's a good point** — 동의

- **I agree that small models are underrated.** — 동의 코멘트 `C-ASK-014`

**F11 · I see what you mean, but ___** — 정중한 반대

- **I see your point, but in my experience, the calibration drift can be larger.** — 이견 코멘트 `C-ASK-015`

**F12 · It would be interesting to ___ / I wonder whether ___** — 제안·호기심

- ★ **It would be interesting to see this applied to medical staff.** — 의료진 적용 제안 `C-ASK-016`
- **I wonder whether the same approach would work for internal dose.** — 내부피폭 확장 `C-ASK-017`
- **I wonder if you'd see the same effect with real-world data.** — 실제 데이터 `C-ASK-018`

**F13 · How did you ___?** — 방법 질문

- ★ **How did you define the ground truth?** — 정답 정의 `C-ASK-019`
- **How did you handle the missing data?** — 결측 처리 `C-ASK-020`
- **How did you select the documents for the benchmark?** — 문서 선정 `C-ASK-021`
- **How did you deal with the class imbalance?** — 클래스 불균형 `C-ASK-022`
- **How did you calibrate the dosimeters?** — 선량계 교정 `C-ASK-023`
- **How did you split the training and test sets?** — 데이터 분할 `C-ASK-024`
- **How did you prevent data leakage?** — 데이터 누수 방지 `C-ASK-025`
- **How did you evaluate the LLM's answers?** — LLM 답변 평가 `C-ASK-026`
- **How did you decide which language to use for the prompts?** — 프롬프트 언어 선택 `C-ASK-027`

**F14 · Did you consider ___? / Have you tried ___?** — 대안 제시형 질문

- ★ **Did you consider using a larger model?** — 대안 검토 질문 `C-ASK-028`
- **Did you look at the differences between age groups?** — 연령군 차이 `C-ASK-029`
- **Have you tried combining the two methods?** — 두 방법 결합 `C-ASK-030`
- **Did you compare your results with the phantom measurements?** — 팬텀 비교 `C-ASK-031`
- **Did you consider the effect of the dosimeter position?** — 착용 위치 효과 `C-ASK-032`
- **Did you compare the cost of the different models?** — 비용 비교 여부 `C-ASK-033`

**F15 · Could you say more about ___?** — 부연 요청

- ★ **Could you say a bit more about the reranking step?** — 재순위화 부연 `C-ASK-034`
- **Could you elaborate on how the experts reviewed the answers?** — 전문가 검토 부연 `C-ASK-035`
- **Could you explain the difference between the two curves?** — 두 곡선 차이 `C-ASK-036`

**F16 · In our case, ___** — 자기 맥락 비교

- ★ **In our case, we saw a similar pattern with the Korean documents.** — 비슷한 경험 공유 `C-ASK-037`
- **In our institute, we found that table-heavy documents were the hardest.** — 표가 많은 문서 `C-ASK-038`

**G06 · As I mentioned ___ / Let me go back to ___** — 되돌아가기·연결

- **Could you go back to the slide with the results table?** — 결과표 슬라이드 요청 `C-ASK-039`

**H06 · I have a question about ___ / My question is ___** — 질문하기

- ★ **I have a question about your validation method.** — 질문 기본 `C-ASK-040`
- **I have a quick question about slide 12.** — 짧은 질문 `C-ASK-041`
- **I have two short questions.** — 두 가지 질문 `C-ASK-042`
- **My question is about the reference doses.** — 질문 대상 명시 `C-ASK-043`
- **I have a comment and a question.** — 코멘트와 질문 `C-ASK-044`
- **My question is more conceptual.** — 개념적 질문 예고 `C-ASK-045`
- **My question is a practical one.** — 실무적 질문 예고 `C-ASK-046`

**H08 · Can I just add ___? / If I may, ___** — 끼어들기·보충

- **Sorry, can I just add something here?** — 끼어들기 `C-ASK-047`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **How long would it take to implement this in practice?** — 도입 소요 기간 `C-ASK-048`
- **What kind of hardware did you need?** — 하드웨어 요구 `C-ASK-049`
- **Roughly how much did it cost to run?** — 운영 비용 `C-ASK-050`
- **Do you think this could be used in a regulatory context?** — 규제 활용 가능성 `C-ASK-051`
- **Do you think the results would generalize to other countries?** — 타국 일반화 `C-ASK-052`
- **Are you planning to make the dataset available?** — 데이터 공개 계획 `C-ASK-053`
- **Is the code available?** — 코드 공개 여부 `C-ASK-054`
- **Just a quick follow-up, if I may.** — 후속 질문 `C-ASK-055`
- **Thank you.** — 질문 마침 (감사) `C-ASK-056`
- **That's all. Thanks.** — 질문 마침 `C-ASK-057`
- **Okay, that makes sense. Thank you.** — 답변 이해함 `C-ASK-058`
- **Thanks. Maybe I'll catch you after the session to discuss it more.** — 세션 후 더 논의 `C-ASK-059`
- **Actually, I think you've already answered that. Thanks.** — 질문 철회 `C-ASK-060`
- **Please, go ahead.** — 질문 순서 양보 `C-ASK-061`
- **Maybe a question for all the speakers.** — 모든 연사에게 `C-ASK-062`
- **This is for both panelists.** — 패널 둘 다에게 `C-ASK-063`
- **This connects to what the previous speaker said about uncertainty.** — 앞 발표와 연결 `C-ASK-064`
- **I'll come find you after the session.** — 개별적으로 찾아감 `C-ASK-065`
- **What was the sample size for the external validation?** — 외부검증 표본 수 `C-ASK-066`
- **What time period did the data cover?** — 데이터 기간 `C-ASK-067`
- **How many participants were there?** — 참가자 수 `C-ASK-068`
- **How would you explain these results to workers?** — 작업자 설명 방식 `C-ASK-069`
- **How did the users react to the system?** — 사용자 반응 `C-ASK-070`
- **Were there any cases where the system failed?** — 실패 사례 `C-ASK-071`
- **How did you deal with the privacy issues?** — 개인정보 처리 `C-ASK-072`
- **What did the regulator think about this?** — 규제기관 반응 `C-ASK-073`
- **Just a quick clarification question.** — 간단한 확인 질문 `C-ASK-074`

### `C-PST` 포스터 세션

*상황 67개 · ★ 3개*


**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you write your email address here?** — 이메일 적어 달라 `C-PST-001`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Is it possible to print a poster somewhere nearby?** — 근처 인쇄 `C-PST-002`

**A10 · Do you mind if I ___?** — 상대를 배려한 허락

- **Do you mind if I take a picture of your poster?** — 포스터 촬영 허락 요청 `C-PST-003`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where can I get pins for the poster?** — 포스터 핀 `C-PST-004`

**B03 · Is there ___ (around here)?** — 존재 여부

- **Is there any tape?** — 테이프 `C-PST-005`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time do we need to put up the posters?** — 부착 시각 `C-PST-006`
- **When do we have to take them down?** — 철거 시각 `C-PST-007`
- **When will the judges come by?** — 심사 시각 `C-PST-008`

**B08 · Which ___?** — 선택지 중 특정

- **Which board is mine? My number is P-34.** — 보드 번호 `C-PST-009`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is A0 portrait okay?** — 포스터 규격 `C-PST-010`
- **Is there a poster prize?** — 포스터 상 여부 `C-PST-011`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need to stand by the poster the whole time?** — 상주 의무 `C-PST-012`

**C04 · There's a problem with ___ / ___ isn't working** — 고장·문제 신고

- **My poster got a bit damaged in the tube.** — 포스터 손상 `C-PST-013`

**D01 · Sorry, could you say that again?** — 반복 요청

- **Sorry, it's really noisy — could you say that again?** — 소음 속 반복 요청 `C-PST-014`

**D07 · Let me ___** — 시간 벌기·행동 예고

- **Let me show you on the figure.** — 그림에서 보여주기 `C-PST-015`

**E04 · Where are you ___?** — 출신·소속·숙소

- **Where are you from?** — 관람객 출신 `C-PST-016`

**E05 · That sounds ___ / That's ___** — 반응·맞장구

- **Oh, that's really relevant.** — 관심 반응 `C-PST-017`
- **That's a great question — nobody's asked me that yet.** — 처음 받은 질문 `C-PST-018`

**E07 · Thanks for ___** — 감사

- **Thanks for stopping by.** — 들러줘서 감사 `C-PST-019`
- **Thanks for the feedback — that's really helpful.** — 피드백 감사 `C-PST-020`

**E09 · Excuse me, ___** — 말 걸기

- ★ **Hi, would you like me to walk you through the poster?** — 관람객에게 말 걸기 `C-PST-021`

**F01 · I work on ___ / My research focuses on ___** — 연구 분야 소개

- **This poster is about predicting TLD readings with machine learning.** — 포스터 주제 `C-PST-022`

**F03 · We used ___ to ___** — 방법 설명

- **We used about 1,200 query–document pairs.** — 데이터 규모 `C-PST-023`

**F04 · We found that ___ / The main finding is ___** — 결과 제시

- **The main finding is that the smallest models were surprisingly competitive.** — 핵심 결과 `C-PST-024`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- **It seems that the domain vocabulary matters a lot.** — 헤징 설명 `C-PST-025`

**F07 · One limitation is ___** — 한계 인정

- **One limitation is that we only had one annotator per language.** — 평가자 한계 `C-PST-026`

**F08 · One possible explanation is ___ / This might be due to ___** — 해석·원인 추정

- **We think that's because the Korean translations aren't always consistent.** — 원인 설명 `C-PST-027`

**F09 · In future work, we plan to ___ / Next, we'd like to ___** — 향후 계획

- **Next, we're planning to test it with real users.** — 다음 단계 `C-PST-028`

**F12 · It would be interesting to ___ / I wonder whether ___** — 제안·호기심

- **It would be interesting to try this on clinical guidelines too.** — 임상 지침 적용 `C-PST-029`

**F13 · How did you ___?** — 방법 질문

- **How did you build the reference set?** — 기준셋 구축 방법 `C-PST-030`

**F14 · Did you consider ___? / Have you tried ___?** — 대안 제시형 질문

- **Did you try a hybrid approach?** — 하이브리드 시도 `C-PST-031`

**F16 · In our case, ___** — 자기 맥락 비교

- **We're doing something similar in Korea, actually.** — 한국에서 유사 연구 `C-PST-032`

**G01 · Today I'd like to ___** — 발표 도입

- **In short, we compared nine embedding models for radiation protection documents.** — 1분 요약 `C-PST-033`

**G04 · This slide shows ___ / As you can see, ___** — 시각자료 설명

- ★ **This figure here shows the overall results.** — 결과 그림 `C-PST-034`
- **If you start from the top left, you can see the workflow.** — 읽는 순서 `C-PST-035`
- **This table compares the models on Korean and English queries.** — 비교표 `C-PST-036`

**G05 · What this means is ___ / The key point here is ___** — 의미 해석

- **The key point is in this box here.** — 핵심 상자 `C-PST-037`

**H01 · That's a good question / Thanks for the question** — 답변 도입

- **Good question.** — 질문 감사 (짧게) `C-PST-038`

**H02 · If I understand correctly, ___** — 질문 재확인

- **You mean the Korean queries specifically?** — 질문 범위 확인 `C-PST-039`

**H06 · I have a question about ___ / My question is ___** — 질문하기

- **I have a question about this figure.** — 그림 질문 `C-PST-040`

**J05 · Would you be interested in ___?** — 협력 제안

- ★ **Would you be interested in comparing results sometime?** — 결과 비교 협업 `C-PST-041`
- **Would you be interested in sharing your benchmark? We could share ours too.** — 벤치마크 교환 `C-PST-042`

**J06 · I'll ___ (send / follow up)** — 후속 약속

- **I'll email you the PDF.** — PDF 송부 약속 `C-PST-043`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Would you like a quick overview?** — 요약 제안 `C-PST-044`
- **Feel free to have a look, and let me know if you have any questions.** — 자유 관람 권유 `C-PST-045`
- **You can scan the QR code for the full paper.** — QR 안내 `C-PST-046`
- **Would you like a copy of the handout?** — 유인물 제공 `C-PST-047`
- **I'm afraid I've run out of handouts, but I can email it to you.** — 유인물 소진 `C-PST-048`
- **What's your field?** — 관람객 분야 `C-PST-049`
- **Are you working on something similar?** — 비슷한 연구 여부 `C-PST-050`
- **The part I find most interesting is this.** — 가장 흥미로운 부분 `C-PST-051`
- **What surprised us was this result here.** — 놀라운 결과 `C-PST-052`
- **Is this your poster? Could you tell me about it?** — 다른 포스터 저자에게 `C-PST-053`
- **Is the author around?** — 저자 부재 확인 `C-PST-054`
- **Do you know when the author will be back?** — 저자 복귀 시점 `C-PST-055`
- **Here's my card.** — 명함 건넴 `C-PST-056`
- **Thank you for coming. Would you like a two-minute summary?** — 심사위원 맞이 `C-PST-057`
- **In one sentence: smaller, multilingual models are good enough for most radiation protection searches.** — 한 문장 피치 `C-PST-058`
- **Sure, feel free to take a picture.** — 촬영 허락 `C-PST-059`
- **Back in ten minutes — please leave your card.** — 자리 비움 메모 `C-PST-060`
- **Enjoy the rest of the session!** — 관람 끝 인사 `C-PST-061`
- **I know you're busy — just the main point: it works.** — 바쁜 관람객에게 핵심만 `C-PST-062`
- **I'm going to take it down now. Thanks again.** — 철거하며 인사 `C-PST-063`
- **What caught your eye?** — 관심 포인트 묻기 `C-PST-064`
- **Let me start from the beginning for you.** — 새 관람객에게 처음부터 `C-PST-065`
- **Would you like to leave your email so I can send you the full paper?** — 이메일 남기기 제안 `C-PST-066`
- **You should talk to the person at poster 41 — they're doing something very similar.** — 관람객 연결 `C-PST-067`

### `C-CHR` 좌장·세션 진행

*상황 56개 · ★ 6개*


**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is your presentation already loaded?** — 발표 파일 업로드 여부 `C-CHR-001`
- **Is there anything you'd like me to mention in your introduction?** — 소개 시 언급 사항 `C-CHR-002`

**D08 · How do you say ___? / What do you call ___?** — 어휘·발음 묻기

- **How do you pronounce your name? I'd like to get it right.** — 연사 이름 발음 확인 `C-CHR-003`

**E07 · Thanks for ___** — 감사

- **Thank you very much for that excellent talk.** — 발표 감사 `C-CHR-004`

**E12 · I'm ___ / I work for ___** — 자기소개

- **I'm Kim, and I'll be chairing this session with Dr. Novak.** — 좌장 자기소개 `C-CHR-005`

**F12 · It would be interesting to ___ / I wonder whether ___** — 제안·호기심

- **It would be interesting to see how these methods compare on the same dataset.** — 좌장 코멘트 `C-CHR-006`

**G01 · Today I'd like to ___** — 발표 도입

- **This session is on dosimetry and machine learning.** — 세션 주제 소개 `C-CHR-007`

**G07 · To sum up ___ / The take-home message is ___** — 요약·결론

- **To sum up this session, we've seen three very different approaches to the same problem.** — 세션 요약 `C-CHR-008`

**G08 · Can everyone ___? / Is ___ working?** — 기술 점검

- **Can you see your slides?** — 온라인 연사 화면 확인 `C-CHR-009`

**H06 · I have a question about ___ / My question is ___** — 질문하기

- **I have a question myself.** — 좌장 본인 질문 `C-CHR-010`

**J01 · Our next speaker is ___** — 연사 소개

- ★ **Our first speaker is Dr. Anna Weber, from the BfS.** — 첫 연사 소개 `C-CHR-011`
- **Our next speaker is Professor Rossi, who'll talk about eye lens dosimetry.** — 다음 연사 소개 `C-CHR-012`
- **Next up is Dr. Lee, from the Korea Institute of Nuclear Safety.** — 다음 연사 (구어) `C-CHR-013`

**J02 · We have time for ___** — 시간 안내

- ★ **Each speaker has 12 minutes, followed by three minutes for questions.** — 발표 형식 안내 `C-CHR-014`
- **We have time for a couple of questions.** — 질문 두어 개 `C-CHR-015`
- **We have about five minutes for questions.** — 질문 시간 5분 `C-CHR-016`
- **We have time for one more question.** — 마지막 질문 `C-CHR-017`
- **I'm afraid we're out of time.** — 시간 종료 `C-CHR-018`

**J03 · Let's ___ (진행)** — 진행 지시

- **Let's get started — could everyone please take a seat?** — 착석 요청 `C-CHR-019`
- ★ **Let's open the floor for questions.** — 질의 시작 `C-CHR-020`
- ★ **Just a reminder to keep to time.** — 시간 엄수 상기 `C-CHR-021`
- **Let's take a short pause while we fix the projector.** — 기술 문제로 잠시 중단 `C-CHR-022`
- ★ **Let's thank all the speakers once again.** — 세션 마무리 `C-CHR-023`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **Good morning, everyone. Let's get started.** — 세션 시작 `C-CHR-024`
- **The floor is yours.** — 발언권 넘김 `C-CHR-025`
- **Please go ahead.** — 시작 권유 `C-CHR-026`
- **Are there any questions?** — 질문 요청 `C-CHR-027`
- **Yes, the gentleman in the front.** — 앞줄 질문자 지목 `C-CHR-028`
- **Yes, at the back.** — 뒷줄 질문자 지목 `C-CHR-029`
- **Please wait for the microphone.** — 마이크 기다리기 `C-CHR-030`
- **Could you please state your name and affiliation?** — 이름·소속 요청 `C-CHR-031`
- **Please keep your questions short, so we can get to as many as possible.** — 짧은 질문 요청 `C-CHR-032`
- **While people are thinking, I'll start with a question.** — 질문 없을 때 좌장 질문 `C-CHR-033`
- **You have two minutes left.** — 남은 시간 알림 `C-CHR-034`
- **Could you start wrapping up, please?** — 마무리 요청 `C-CHR-035`
- **I'm sorry, but we need to move on.** — 시간 초과 시 정중히 끊기 `C-CHR-036`
- **Maybe you could continue the discussion during the break.** — 휴식 시간에 계속 `C-CHR-037`
- **Let's take two questions together.** — 질문 두 개 묶기 `C-CHR-038`
- **Just to repeat the question for everyone…** — 질문 반복 (전체 청중) `C-CHR-039`
- **Unfortunately, our third speaker couldn't make it.** — 연사 불참 `C-CHR-040`
- **There's a small change in the order of talks.** — 순서 변경 `C-CHR-041`
- **Our next speaker is joining us online. Can you hear us?** — 온라인 연사 `C-CHR-042`
- **Please join me in thanking the speakers.** — 박수 유도 `C-CHR-043`
- **Coffee is now served in the foyer.** — 커피 안내 `C-CHR-044`
- **The next session starts at eleven in this room.** — 다음 세션 안내 `C-CHR-045`
- **Don't forget the poster session after lunch.** — 포스터 세션 안내 `C-CHR-046`
- **Perhaps I could ask the panel a general question.** — 패널 공통 질문 `C-CHR-047`
- **What do you see as the biggest challenge in the next five years?** — 미래 과제 질문 `C-CHR-048`
- **Would anyone on the panel like to respond?** — 패널 응답 요청 `C-CHR-049`
- **Dr. Weber, would you like to add anything?** — 특정 패널 지목 `C-CHR-050`
- **These are both valid points. Maybe we can come back to this in the discussion.** — 논쟁 조정 `C-CHR-051`
- **It's great to see such a lively discussion.** — 활발한 토론 칭찬 `C-CHR-052`
- **Before we start, a few housekeeping notes.** — 공지 예고 `C-CHR-053`
- **Please make sure your phones are on silent.** — 휴대폰 무음 `C-CHR-054`
- **Please note that this session is being recorded.** — 녹화 공지 `C-CHR-055`
- **Hi, I'm chairing your session. Could we quickly go over the timing?** — 연사 사전 미팅 `C-CHR-056`

### `C-DSC` 연구 방법론·전문 토론

*상황 102개 · ★ 7개*


**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- **What exactly do you mean by "domain adaptation" here?** — 도메인 적응 의미 `C-DSC-001`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **So basically, you retrain the model every year?** — 재학습 주기 확인 `C-DSC-002`

**F01 · I work on ___ / My research focuses on ___** — 연구 분야 소개

- **We're working on dose reconstruction for workers with incomplete records.** — 선량 재구성 연구 `C-DSC-003`

**F02 · We're currently ___ing** — 진행 상황

- **We're currently comparing three different algorithms.** — 알고리즘 비교 진행 `C-DSC-004`

**F03 · We used ___ to ___** — 방법 설명

- **We used Bayesian methods to estimate the missing doses.** — 베이지안 `C-DSC-005`
- **We used a transformer-based model for the time-series forecasting.** — 트랜스포머 시계열 `C-DSC-006`
- **We used LoRA to fine-tune the model on our own data.** — LoRA 미세조정 `C-DSC-007`
- **We used a hybrid search — BM25 plus dense embeddings.** — 하이브리드 검색 `C-DSC-008`
- **We used kriging to interpolate the dose rate maps.** — 크리깅 `C-DSC-009`
- **We used SHAP values to interpret the model.** — SHAP 해석 `C-DSC-010`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- **It seems to me that overfitting might be an issue here.** — 과적합 우려 `C-DSC-011`
- **I suspect the performance would drop with real queries.** — 실제 질의 성능 의심 `C-DSC-012`
- **My sense is that the bias is coming from the reference data.** — 기준 데이터 편향 `C-DSC-013`

**F06 · Compared with ___ / ___ performed better than ___** — 비교

- **In our experience, the smaller model was faster and almost as accurate.** — 소형 모델 경험 `C-DSC-014`
- **Compared with traditional statistics, the ML model was harder to explain to the regulator.** — 설명 가능성 비교 `C-DSC-015`

**F07 · One limitation is ___** — 한계 인정

- **The weak point of our approach is the small number of high-dose cases.** — 고선량 사례 부족 `C-DSC-016`
- **One issue we haven't solved yet is how to update the model over time.** — 모델 갱신 미해결 `C-DSC-017`

**F08 · One possible explanation is ___ / This might be due to ___** — 해석·원인 추정

- **One possible explanation is that the test set is too similar to the training set.** — 테스트셋 유사성 `C-DSC-018`
- **That might be due to differences in the reading systems.** — 판독 시스템 차이 `C-DSC-019`

**F09 · In future work, we plan to ___ / Next, we'd like to ___** — 향후 계획

- **Next, we'd like to add a function-calling layer.** — 함수 호출 계층 `C-DSC-020`
- **We plan to test it on a larger corpus next year.** — 대규모 코퍼스 `C-DSC-021`

**F10 · I agree ___ / That's a good point** — 동의

- ★ **I agree, interpretability is crucial in this field.** — 해석 가능성 동의 `C-DSC-022`
- **That's a good point. We've seen the same thing.** — 같은 관찰 `C-DSC-023`
- **Exactly. That's what we found too.** — 같은 결과 `C-DSC-024`

**F11 · I see what you mean, but ___** — 정중한 반대

- ★ **I see what you mean, but I think the sample size is still too small.** — 표본 부족 이견 `C-DSC-025`
- **I'm not sure I agree. In our data, the effect was the opposite.** — 반대 결과 `C-DSC-026`
- **That's true in general, but radiation data are a bit special.** — 방사선 데이터 특수성 `C-DSC-027`

**F12 · It would be interesting to ___ / I wonder whether ___** — 제안·호기심

- ★ **It would be interesting to compare this with the IAEA method.** — IAEA 방법과 비교 `C-DSC-028`
- **It might be worth trying a mixed-effects model here.** — 혼합효과 제안 `C-DSC-029`
- **I wonder whether adding metadata would help the retrieval.** — 메타데이터 추가 `C-DSC-030`
- **I wonder if a time-series approach would capture the trend better.** — 시계열 접근 `C-DSC-031`

**F13 · How did you ___?** — 방법 질문

- ★ **How did you tune the hyperparameters?** — 하이퍼파라미터 `C-DSC-032`
- **How did you choose the chunk size?** — 청크 크기 `C-DSC-033`
- **How did you handle the different units?** — 단위 혼재 `C-DSC-034`
- **How did you validate the Monte Carlo model?** — 몬테카를로 검증 `C-DSC-035`
- **How did you account for the background dose?** — 자연방사선 보정 `C-DSC-036`
- **How did you deal with readings below the detection limit?** — 검출한계 미만 값 `C-DSC-037`
- **How did you handle the temporal autocorrelation?** — 시간 자기상관 `C-DSC-038`
- **How do you keep track of prompt versions?** — 프롬프트 버전 관리 `C-DSC-039`

**F14 · Did you consider ___? / Have you tried ___?** — 대안 제시형 질문

- ★ **Did you consider a non-parametric approach?** — 비모수 대안 `C-DSC-040`
- **Did you try a simpler baseline, like logistic regression?** — 단순 기준선 `C-DSC-041`
- **Have you tried using a reranker?** — 리랭커 `C-DSC-042`
- **Did you look at the calibration curve?** — 보정 곡선 `C-DSC-043`
- **Have you tried quantizing the model?** — 양자화 `C-DSC-044`
- **Did you consider the energy dependence of the dosimeter?** — 에너지 의존성 `C-DSC-045`
- **Have you tried cross-lingual retrieval, like Korean queries on English documents?** — 교차 언어 검색 `C-DSC-046`

**F15 · Could you say more about ___?** — 부연 요청

- **Could you say more about how you built the prompts?** — 프롬프트 설계 부연 `C-DSC-047`
- **Could you tell me more about the annotation guidelines?** — 주석 지침 부연 `C-DSC-048`

**F16 · In our case, ___** — 자기 맥락 비교

- ★ **In our case, we have about 30 years of dose records.** — 장기 선량 기록 `C-DSC-049`
- **In our setting, everything has to run offline.** — 오프라인 제약 `C-DSC-050`
- **In our lab, we usually validate with an independent dataset.** — 독립 검증 관행 `C-DSC-051`
- **In our case, the regulator needs the full calculation to be reproducible.** — 재현성 요구 `C-DSC-052`

**F17 · This is based on ___** — 근거·출처

- **This approach is based on the ISO 4037 reference fields.** — ISO 기준장 `C-DSC-053`
- **Our threshold is based on the recording level in the ICRP recommendations.** — 기록준위 근거 `C-DSC-054`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **What does your data look like?** — 데이터 형태 `C-DSC-055`
- **How big is your dataset?** — 데이터 규모 `C-DSC-056`
- **What format are the records in?** — 기록 형식 `C-DSC-057`
- **How clean is the data?** — 데이터 품질 `C-DSC-058`
- **Who did the labeling?** — 라벨링 주체 `C-DSC-059`
- **Do you have access to individual-level data?** — 개인 단위 접근 `C-DSC-060`
- **What kind of GPU are you using?** — GPU 사양 `C-DSC-061`
- **Which model size worked best for you?** — 최적 모델 크기 `C-DSC-062`
- **Are you running it on-premises or in the cloud?** — 온프레미스 여부 `C-DSC-063`
- **How do you deal with data security?** — 데이터 보안 `C-DSC-064`
- **What metric do you use to evaluate it?** — 평가 지표 `C-DSC-065`
- **Have you done any user testing?** — 사용자 테스트 `C-DSC-066`
- **Is your model open-source?** — 오픈소스 여부 `C-DSC-067`
- **Has the regulator accepted this method?** — 규제 수용 여부 `C-DSC-068`
- **Is it already being used in practice?** — 현장 사용 여부 `C-DSC-069`
- **How reproducible are the results?** — 재현성 질문 `C-DSC-070`
- **How do you quantify the uncertainty?** — 불확실성 정량화 `C-DSC-071`
- **We report the uncertainty at the 95 percent level.** — 불확실성 보고 수준 `C-DSC-072`
- **How often do you calibrate the system?** — 교정 주기 `C-DSC-073`
- **The energy response is flat above 50 keV.** — 에너지 응답 특성 `C-DSC-074`
- **There's a strong angular dependence at low energies.** — 각도 의존성 `C-DSC-075`
- **The real challenge is in the low-dose range.** — 저선량 영역 난제 `C-DSC-076`
- **Most of our readings are close to the detection limit.** — 검출한계 근처 `C-DSC-077`
- **Hallucination is still a big concern for us.** — LLM 환각 우려 `C-DSC-078`
- **That's why we use retrieval — so every answer can be traced back to a source.** — RAG 사용 이유 `C-DSC-079`
- **Each answer comes with a link to the original paragraph.** — 출처 링크 `C-DSC-080`
- **Korean tokenization is a real challenge for some models.** — 한국어 토큰화 `C-DSC-081`
- **The ICRP terminology isn't always translated consistently.** — 용어 번역 불일치 `C-DSC-082`
- **We built a small glossary to standardize the terms.** — 용어집 구축 `C-DSC-083`
- **We were worried about overfitting, so we kept the model simple.** — 과적합 대응 `C-DSC-084`
- **We split the data by worker, not by record, to avoid leakage.** — 누수 방지 분할 `C-DSC-085`
- **For the time series, we used a rolling-origin evaluation.** — 시계열 평가 `C-DSC-086`
- **The baseline is surprisingly hard to beat.** — 기준선의 강함 `C-DSC-087`
- **For regulatory use, we need something we can explain line by line.** — 규제용 설명 가능성 `C-DSC-088`
- **The vendor software is basically a black box.** — 상용 소프트웨어 블랙박스 `C-DSC-089`
- **So we reimplemented the algorithm from scratch to check every step.** — 알고리즘 재구현 `C-DSC-090`
- **Our reimplementation matched the original output to within 0.1 percent.** — 재구현 일치도 `C-DSC-091`
- **From a clinical point of view, this is quite similar to glucose forecasting.** — 임상과의 유사성 `C-DSC-092`
- **In endocrinology, we use similar models to predict blood glucose.** — 혈당 예측 예시 `C-DSC-093`
- **Have you tried applying this to medical records?** — 의료기록 적용 질문 `C-DSC-094`
- **This could be a nice area for collaboration.** — 협업 가능 영역 `C-DSC-095`
- **There's a good paper on that — I'll send you the reference.** — 논문 추천해 주기 `C-DSC-096`
- **Is there a paper you'd recommend on that?** — 논문 추천 받기 `C-DSC-097`
- **Which library are you using for that?** — 라이브러리 묻기 `C-DSC-098`
- **We're using Hugging Face for most of the models.** — 라이브러리 답 `C-DSC-099`
- **The quantized model was almost as good, but much faster.** — 양자화 결과 `C-DSC-100`
- **We fixed the test set before we started tuning anything.** — 테스트셋 선고정 `C-DSC-101`
- **We always check the code against a few hand-calculated reference cases.** — 기준 사례 검증 `C-DSC-102`

### `C-AGR` 동의·반대·의견 표현

*상황 57개 · ★ 4개*


**B16 · What if ___? / What happens if ___?** — 조건·예외 상황

- **What if we tried both and compared?** — 둘 다 해보자 `C-AGR-001`

**E10 · How about ___? / Shall we ___? / Why don't we ___?** — 제안

- **Why don't we start with a small pilot?** — 작은 파일럿 제안 `C-AGR-002`
- **How about sharing a small sample of the data first?** — 샘플 먼저 공유 제안 `C-AGR-003`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- ★ **It seems to me that the problem is the reference data.** — 의견 (헤징) `C-AGR-004`
- **I tend to think that simpler models are better here.** — 경향적 생각 `C-AGR-005`
- **My feeling is that we need more validation first.** — 느낌 `C-AGR-006`
- **I'd say it's probably too early to tell.** — 판단 유보 `C-AGR-007`
- **As far as I know, there's no standard method for this yet.** — 아는 범위에서 `C-AGR-008`
- **From what I've seen, the results are quite consistent.** — 본 바로는 `C-AGR-009`

**F10 · I agree ___ / That's a good point** — 동의

- ★ **I completely agree.** — 완전 동의 `C-AGR-010`
- **I couldn't agree more.** — 강한 동의 `C-AGR-011`
- **That's a good point.** — 좋은 지적 `C-AGR-012`
- **You're absolutely right.** — 전적으로 맞음 `C-AGR-013`
- **That makes sense.** — 일리 있음 `C-AGR-014`
- **I agree up to a point.** — 어느 정도 동의 `C-AGR-015`
- **I agree, and I'd add that cost is also a factor.** — 동의+추가 `C-AGR-016`

**F11 · I see what you mean, but ___** — 정중한 반대

- ★ **I see what you mean, but I'm not sure that's the case here.** — 정중한 반대 `C-AGR-017`
- **I take your point, but I'd see it a bit differently.** — 다르게 봄 `C-AGR-018`
- **I understand where you're coming from, but our data suggest otherwise.** — 데이터 근거 반대 `C-AGR-019`
- **That's true, but on the other hand, it's much cheaper.** — 반면에 `C-AGR-020`
- **I'm not entirely convinced.** — 확신 없음 `C-AGR-021`
- **I'm not sure I'd go that far.** — 그렇게까지는 `C-AGR-022`
- **With respect, I think that's a bit of an oversimplification.** — 과도한 단순화 `C-AGR-023`
- **I'd question that assumption.** — 가정 의문 `C-AGR-024`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **In my view, the main issue is data quality.** — 내 견해 `C-AGR-025`
- **In my experience, users don't trust black-box tools.** — 내 경험상 `C-AGR-026`
- **Personally, I think it's worth trying.** — 개인적으로 `C-AGR-027`
- **To be honest, I'm a bit skeptical.** — 솔직히 회의적 `C-AGR-028`
- **I'm pretty sure that's right.** — 꽤 확신 `C-AGR-029`
- **I might be wrong, but I think it was in the 2007 recommendations.** — 틀릴 수도 `C-AGR-030`
- **I really don't know. What do you think?** — 모르겠다 `C-AGR-031`
- **What's your take on this?** — 상대 견해 묻기 `C-AGR-032`
- **How do you see it?** — 상대 관점 묻기 `C-AGR-033`
- **Do you agree?** — 동의 여부 묻기 `C-AGR-034`
- **Would you say that's typical?** — 일반적인지 묻기 `C-AGR-035`
- **I can see both sides.** — 양쪽 이해 `C-AGR-036`
- **It depends on the situation.** — 상황에 따라 `C-AGR-037`
- **That's true if the energy is high enough.** — 조건부 동의 `C-AGR-038`
- **Fair enough.** — 양보 `C-AGR-039`
- **You've convinced me.** — 설득됨 `C-AGR-040`
- **Actually, you're right. I hadn't thought of it that way.** — 입장 변경 `C-AGR-041`
- **Let me think about that a bit more.** — 좀 더 생각 `C-AGR-042`
- **So, if I've understood, the main disagreement is about the threshold?** — 쟁점 정리 `C-AGR-043`
- **I think we both agree that validation is the key issue.** — 공통점 찾기 `C-AGR-044`
- **So we're on the same page.** — 의견 일치 확인 `C-AGR-045`
- **I think we'll have to agree to disagree.** — 이견 인정 `C-AGR-046`
- **Let's leave that for now and come back to it later.** — 나중으로 미룸 `C-AGR-047`
- **The point I'm trying to make is that context matters.** — 요지 강조 `C-AGR-048`
- **Let me put it another way.** — 다르게 표현 `C-AGR-049`
- **For example, in our plants, the dose distribution is very skewed.** — 예시로 뒷받침 `C-AGR-050`
- **But there are cases where that doesn't work.** — 반례 제시 `C-AGR-051`
- **But wouldn't that increase the uncertainty?** — 질문으로 반박 `C-AGR-052`
- **Isn't it possible that the difference comes from the instruments?** — 가능성으로 반박 `C-AGR-053`
- **My only concern is the cost.** — 우려 (비용) `C-AGR-054`
- **I'm a little worried that it won't scale.** — 우려 (확장성) `C-AGR-055`
- **I think it's a great idea.** — 지지 `C-AGR-056`
- **I'd be happy to support that.** — 지원 의사 `C-AGR-057`

### `C-COL` 공동연구·후속 협력

*상황 63개 · ★ 4개*


**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would it be possible to get a copy of your dataset for validation?** — 검증용 데이터 요청 `C-COL-001`
- **Would it be possible to use your phantom data?** — 팬텀 데이터 사용 `C-COL-002`

**A07 · I was wondering if ___** — 매우 조심스러운 부탁

- ★ **I was wondering if we could explore a collaboration.** — 협력 타진 `C-COL-003`
- **I was wondering if you'd be open to a short call next month.** — 화상 회의 타진 `C-COL-004`
- **I was wondering if you could share the protocol you mentioned.** — 프로토콜 요청 `C-COL-005`
- **I was wondering if the code is available.** — 코드 요청 `C-COL-006`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is the dataset publicly available?** — 공개 데이터 여부 `C-COL-007`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do we need ethics approval for that?** — 윤리 승인 필요 `C-COL-008`

**B13 · Do you know ___? / Do you happen to know ___?** — 정보 보유 여부

- **Do you know who I should contact about that?** — 담당자 문의 `C-COL-009`

**B14 · Could you tell me ___?** — 간접 의문 (정중)

- **Could you tell me who's in charge of the data?** — 데이터 책임자 `C-COL-010`

**C10 · I'm afraid ___** — 나쁜 소식·거절의 완곡

- **I'm afraid we can't share individual dose records.** — 개인 선량기록 공유 불가 `C-COL-011`
- **I'm afraid that's not something I can decide myself.** — 결정 권한 없음 `C-COL-012`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **Just to confirm, you'll send the protocol, and I'll prepare the data summary?** — 역할 합의 확인 `C-COL-013`
- **So we'll aim for a call in early November?** — 일정 합의 확인 `C-COL-014`

**E07 · Thanks for ___** — 감사

- **Thanks for the opportunity.** — 기회 감사 `C-COL-015`
- **Thanks for your interest in our work.** — 관심 감사 `C-COL-016`

**E10 · How about ___? / Shall we ___? / Why don't we ___?** — 제안

- **Why don't we start with something small?** — 작게 시작 제안 `C-COL-017`
- **How about a joint session at the next conference?** — 공동 세션 제안 `C-COL-018`

**E11 · It was great ___ / Have a ___** — 작별

- **It was really great to meet you. Let's keep in touch.** — 만남 마무리 `C-COL-019`

**J04 · Could we ___? / Can we ___?** — 일정·회의 제안

- ★ **Could we set up a video call after the conference?** — 화상 회의 제안 `C-COL-020`
- **Can we talk about it in more detail over lunch?** — 점심 논의 `C-COL-021`
- **Could we follow up by email?** — 이메일로 후속 `C-COL-022`

**J05 · Would you be interested in ___?** — 협력 제안

- ★ **Would you be interested in working together on this?** — 공동 작업 제안 `C-COL-023`
- **Would you be interested in sharing data?** — 데이터 공유 `C-COL-024`
- **Would you be interested in writing a joint paper?** — 공동 논문 `C-COL-025`
- **Would you be interested in applying for a joint grant?** — 공동 과제 신청 `C-COL-026`
- **Would you be interested in visiting our institute?** — 기관 방문 초청 `C-COL-027`
- **Would you be interested in giving a talk at our workshop?** — 워크숍 발표 초청 `C-COL-028`

**J06 · I'll ___ (send / follow up)** — 후속 약속

- ★ **I'll send you a short summary of our project.** — 프로젝트 요약 송부 `C-COL-029`
- **I'll follow up next week.** — 다음 주 후속 `C-COL-030`
- **I'll introduce you to my colleague by email.** — 동료 소개 `C-COL-031`
- **I'll check with my director and get back to you.** — 원장 확인 후 회신 `C-COL-032`

**K05 · Looking forward to ___** — 기대·마무리

- **Looking forward to working with you.** — 협업 기대 `C-COL-033`
- **Looking forward to hearing from you.** — 연락 기대 `C-COL-034`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **I'll need to get approval from my institute first.** — 기관 승인 필요 `C-COL-035`
- **Our data can't leave the institute, but we could share the code.** — 데이터 반출 불가 `C-COL-036`
- **We'd need a data-sharing agreement.** — 데이터 공유 협약 `C-COL-037`
- **We'd probably need to sign an NDA.** — 비밀유지계약 `C-COL-038`
- **Maybe we could take care of the data, and you could handle the modeling?** — 역할 분담 제안 `C-COL-039`
- **What would you like your role to be?** — 상대 역할 묻기 `C-COL-040`
- **What kind of timeline are you thinking?** — 일정 감 묻기 `C-COL-041`
- **Do you have funding for this, or should we apply together?** — 예산 묻기 `C-COL-042`
- **There's an EU call that might fit.** — EU 과제 공모 `C-COL-043`
- **We could also look for funding on the Korean side.** — 한국 측 재원 `C-COL-044`
- **How should we handle authorship?** — 저자권 처리 `C-COL-045`
- **I'd suggest we decide the author order at the start.** — 저자 순서 선결정 `C-COL-046`
- **We might be able to send a student for a few months.** — 학생 파견 `C-COL-047`
- **When would be a good time to visit?** — 방문 적기 `C-COL-048`
- **We'd be happy to invite you to Korea.** — 한국 초청 `C-COL-049`
- **We could cover your travel expenses.** — 여비 지원 `C-COL-050`
- **We could build a shared benchmark for both languages.** — 공동 벤치마크 `C-COL-051`
- **I think it would benefit both sides.** — 상호 이익 `C-COL-052`
- **I'm really excited about this.** — 기대감 `C-COL-053`
- **Let's see how it goes with a small pilot first.** — 신중하게 시작 `C-COL-054`
- **That sounds interesting, but I'm afraid I don't have the capacity right now.** — 여력 없음 (완곡 거절) `C-COL-055`
- **Maybe we could revisit this next year.** — 내년 재검토 `C-COL-056`
- **I think my colleague would be a better fit for this.** — 적임자 추천 `C-COL-057`
- **What's the best way to reach you?** — 연락 방법 `C-COL-058`
- **Is email best, or do you prefer Teams?** — 연락 수단 선호 `C-COL-059`
- **So, the next steps are: I'll draft the proposal, and you'll check the budget.** — 다음 단계 정리 `C-COL-060`
- **Maybe the first step would be to compare our datasets.** — 첫 단계 제안 `C-COL-061`
- **I'll keep you posted.** — 진행 공유 약속 `C-COL-062`
- **Please keep me updated.** — 업데이트 요청 `C-COL-063`

### `C-MTG` 미팅·온라인 회의

*상황 72개 · ★ 9개*


**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you share your screen?** — 화면 공유 요청 `C-MTG-001`
- **Could you make it a bit bigger?** — 화면 확대 `C-MTG-002`
- **Could you put the link in the chat?** — 채팅에 링크 `C-MTG-003`
- **Could you record the meeting?** — 회의 녹화 `C-MTG-004`
- **Could you send the slides after the meeting?** — 슬라이드 송부 `C-MTG-005`

**A10 · Do you mind if I ___?** — 상대를 배려한 허락

- ★ **Do you mind if I go first? I have to leave early.** — 먼저 발언 `C-MTG-006`
- **Do you mind if I drop off a bit early?** — 일찍 나감 `C-MTG-007`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is that Central European Time?** — 시간대 확인 `C-MTG-008`

**D01 · Sorry, could you say that again?** — 반복 요청

- ★ **Sorry, you broke up a little. Could you say that again?** — 온라인 끊김 반복 요청 `C-MTG-009`

**D02 · Sorry, I didn't catch ___** — 못 들었음

- **Sorry, I missed that — the connection dropped.** — 연결 끊겨 놓침 `C-MTG-010`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- ★ **Just to confirm, we're going with option B?** — 결정 확인 `C-MTG-011`
- **Just to make sure — the deadline is the 15th, right?** — 마감일 확인 `C-MTG-012`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **So you're suggesting we postpone the deadline?** — 제안 확인 `C-MTG-013`

**E10 · How about ___? / Shall we ___? / Why don't we ___?** — 제안

- ★ **Shall we get started?** — 회의 시작 `C-MTG-014`

**F02 · We're currently ___ing** — 진행 상황

- **We're currently finalizing the dataset.** — 데이터셋 마무리 중 `C-MTG-015`
- **We're about halfway through the analysis.** — 분석 절반 진행 `C-MTG-016`

**G08 · Can everyone ___? / Is ___ working?** — 기술 점검

- ★ **Can you hear me?** — 소리 확인 `C-MTG-017`
- **Can you see my screen?** — 화면 공유 확인 `C-MTG-018`
- **Is my screen showing?** — 화면 표시 확인 `C-MTG-019`

**H08 · Can I just add ___? / If I may, ___** — 끼어들기·보충

- ★ **Sorry to interrupt, but can I just add something?** — 끼어들기 `C-MTG-020`
- **Can I just jump in here?** — 끼어들기 (구어) `C-MTG-021`

**J03 · Let's ___ (진행)** — 진행 지시

- **Let's go through the agenda.** — 안건 검토 `C-MTG-022`
- **Let's try to finish by three.** — 종료 시각 설정 `C-MTG-023`
- **Let's go around the table and introduce ourselves.** — 돌아가며 소개 `C-MTG-024`
- **Let's quickly recap where we are.** — 현황 요약 `C-MTG-025`
- **Let's move on to the next item.** — 다음 안건 `C-MTG-026`
- **Let's make a decision on this today.** — 오늘 결정 `C-MTG-027`
- **Let's park that for now.** — 보류 `C-MTG-028`
- **Let's wrap up.** — 마무리 `C-MTG-029`

**J04 · Could we ___? / Can we ___?** — 일정·회의 제안

- ★ **Could we move the meeting to Thursday?** — 회의 일정 변경 `C-MTG-030`
- **Can we schedule a follow-up in two weeks?** — 후속 회의 `C-MTG-031`

**J06 · I'll ___ (send / follow up)** — 후속 약속

- **I'll take care of that.** — 내가 맡겠다 `C-MTG-032`
- **I'll send the minutes by tomorrow.** — 회의록 송부 `C-MTG-033`
- **I'll circulate a draft by Friday.** — 초안 회람 `C-MTG-034`

**K08 · Would ___ work for you?** — 일정 제안

- **Would 10 a.m. CET work for you?** — 시간 제안 `C-MTG-035`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **The purpose of today's meeting is to agree on the timeline.** — 회의 목적 `C-MTG-036`
- **We have three items on the agenda.** — 안건 수 `C-MTG-037`
- **Let me give you a quick update.** — 진행 보고 예고 `C-MTG-038`
- **We're a bit behind schedule.** — 일정 지연 `C-MTG-039`
- **The main reason is that the data approval took longer than expected.** — 지연 사유 `C-MTG-040`
- **The first phase is done.** — 1단계 완료 `C-MTG-041`
- **There's one issue I'd like to raise.** — 이슈 제기 `C-MTG-042`
- **I have a quick question before we move on.** — 넘어가기 전 질문 `C-MTG-043`
- **I think you're on mute.** — 상대 음소거 알림 `C-MTG-044`
- **Sorry, I was on mute.** — 내가 음소거였음 `C-MTG-045`
- **Sorry, my camera isn't working today.** — 카메라 고장 `C-MTG-046`
- **My connection's a bit unstable. I might turn off my video.** — 연결 불안정 `C-MTG-047`
- **Sorry, I got disconnected. Did I miss anything?** — 재접속 후 `C-MTG-048`
- **There's a bit of an echo.** — 에코 `C-MTG-049`
- **Sorry, go ahead.** — 발언 양보 `C-MTG-050`
- **Sorry, please finish.** — 끝까지 들음 `C-MTG-051`
- **Oh, sorry — you go first.** — 동시 발언 시 `C-MTG-052`
- **Going back to what you said earlier…** — 앞 발언으로 복귀 `C-MTG-053`
- ★ **So the action items are: Kim will send the data, and Anna will draft the report.** — 실행 항목 정리 `C-MTG-054`
- **Who's going to take care of this?** — 담당자 정하기 `C-MTG-055`
- **When do we need this by?** — 기한 묻기 `C-MTG-056`
- **Is the end of the month realistic?** — 기한 현실성 `C-MTG-057`
- **That's a bit tight for us. Could we say mid-November?** — 기한 조정 요청 `C-MTG-058`
- **That would be 6 p.m. in Korea, so that's fine.** — 시차 괜찮음 `C-MTG-059`
- **That's a bit late for me — it's midnight in Seoul.** — 시차 곤란 `C-MTG-060`
- **Could we do it an hour earlier?** — 대안 시간 `C-MTG-061`
- **I think that's everything. Thanks, everyone.** — 회의 종료 `C-MTG-062`
- **Thanks for your time. Talk soon.** — 회의 종료 (구어) `C-MTG-063`
- **Same time next month?** — 정기 회의 `C-MTG-064`
- **I'll check and let you know.** — 확인 후 알림 `C-MTG-065`
- **I'm not sure — I'll need to ask my team.** — 팀에 확인 필요 `C-MTG-066`
- **What do you all think?** — 전체 의견 요청 `C-MTG-067`
- **Dr. Park, would you like to add anything?** — 조용한 참석자에게 `C-MTG-068`
- **Nothing from my side.** — 추가 의견 없음 `C-MTG-069`
- **No, I think that covers it.** — 다 다룸 `C-MTG-070`
- **I just want to stress one thing.** — 한 가지 강조 `C-MTG-071`
- **What's our top priority right now?** — 우선순위 묻기 `C-MTG-072`

### `C-EML` 이메일·메시지

*상황 90개 · ★ 10개*


**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would it be possible to extend the deadline by a week?** — 기한 연장 요청 `C-EML-001`

**A07 · I was wondering if ___** — 매우 조심스러운 부탁

- **I was wondering if you might be available for a short call next week.** — 짧은 통화 요청 `C-EML-002`
- **I was wondering if you could share your code.** — 코드 공유 요청 `C-EML-003`

**K01 · I'm writing to ___ / I'm following up on ___** — 이메일 목적

- ★ **I'm writing to follow up on our conversation at ERPW.** — 만남 후 후속 `C-EML-004`
- **I'm writing to ask about your dosimetry protocol.** — 프로토콜 문의 `C-EML-005`
- **I'm writing to introduce myself.** — 자기소개 메일 `C-EML-006`
- **I'm following up on my email from last week.** — 이전 메일 후속 `C-EML-007`
- **I'm writing regarding the data-sharing agreement.** — 협약 관련 `C-EML-008`
- **I'm writing on behalf of Dr. Park.** — 대리 발신 `C-EML-009`

**K02 · Please find attached ___ / I've attached ___** — 첨부

- ★ **Please find attached the paper we discussed.** — 논문 첨부 `C-EML-010`
- **I've attached a short summary of our project.** — 요약 첨부 `C-EML-011`
- **Please find attached the revised version.** — 수정본 첨부 `C-EML-012`
- **I've attached the slides from my talk.** — 발표자료 첨부 `C-EML-013`

**K03 · I'd appreciate it if ___** — 정중한 요청 (서면)

- ★ **I'd appreciate it if you could send me the protocol.** — 정중한 자료 요청 `C-EML-014`
- **I'd be grateful if you could review the draft by Friday.** — 기한 내 검토 요청 `C-EML-015`
- **I'd appreciate your feedback on this.** — 피드백 요청 `C-EML-016`

**K04 · Thank you for your ___** — 이메일 감사

- ★ **Thank you for your quick reply.** — 빠른 회신 감사 `C-EML-017`
- **Thank you for your email.** — 메일 감사 `C-EML-018`
- **Thank you for sharing the slides.** — 슬라이드 공유 감사 `C-EML-019`
- **Thank you for your interest in our work.** — 관심 감사 `C-EML-020`
- **Thank you for your feedback on the draft.** — 초안 피드백 감사 `C-EML-021`

**K05 · Looking forward to ___** — 기대·마무리

- ★ **Looking forward to hearing from you.** — 회신 기대 `C-EML-022`
- **Looking forward to our call.** — 통화 기대 `C-EML-023`
- **Looking forward to working together.** — 협업 기대 `C-EML-024`
- **Looking forward to seeing you in Seoul.** — 서울에서 만남 기대 `C-EML-025`

**K06 · Apologies for ___** — 서면 사과

- ★ **Apologies for the late reply.** — 늦은 회신 사과 `C-EML-026`
- **Sorry for the delay in getting back to you.** — 회신 지연 사과 (구어) `C-EML-027`
- **Apologies for any confusion.** — 혼선 사과 `C-EML-028`
- **Apologies for the short notice.** — 촉박한 요청 사과 `C-EML-029`

**K07 · Could you let me know ___? / Please let me know ___** — 회신 요청

- ★ **Could you let me know if this works for you?** — 가능 여부 회신 요청 `C-EML-030`
- **Please let me know if you have any questions.** — 질문 환영 `C-EML-031`
- **Please let me know what you think.** — 의견 요청 `C-EML-032`
- **Could you let me know by the end of the week?** — 기한부 회신 `C-EML-033`
- **Let me know if you need anything else.** — 추가 필요 사항 `C-EML-034`
- **Could you let me know whether travel costs would be covered?** — 여비 지원 문의 `C-EML-035`

**K08 · Would ___ work for you?** — 일정 제안

- ★ **Would Tuesday at 10 a.m. CET work for you?** — 일정 제안 `C-EML-036`
- **Would sometime next week work for a call?** — 다음 주 통화 `C-EML-037`
- **Does Thursday afternoon suit you?** — 목요일 오후 `C-EML-038`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **Dear Dr. Weber,** — 격식 인사 `C-EML-039`
- **Hi Anna,** — 친근한 인사 `C-EML-040`
- **Dear Sir or Madam,** — 수신자 모를 때 `C-EML-041`
- **Dear all,** — 여러 명에게 `C-EML-042`
- **It was a pleasure meeting you in Berlin last week.** — 만남 상기 `C-EML-043`
- **We spoke briefly after your talk on Tuesday.** — 만남 장면 상기 `C-EML-044`
- **Dr. Lee suggested I contact you.** — 소개 경로 `C-EML-045`
- **You can download the dataset here: [link].** — 다운로드 링크 `C-EML-046`
- **I'm available on Monday or Wednesday afternoon.** — 가능 일정 제시 `C-EML-047`
- **I'm flexible, so please choose a time that suits you.** — 일정 유연 `C-EML-048`
- **Tuesday at ten works perfectly. I'll send an invite.** — 일정 확정 `C-EML-049`
- **Here's the Zoom link for our meeting.** — 회의 링크 `C-EML-050`
- **Sorry, I forgot the attachment. Here it is.** — 첨부 누락 `C-EML-051`
- **Please disregard my previous email — the correct date is the 15th.** — 이전 메일 정정 `C-EML-052`
- **Just a gentle reminder about the deadline on Friday.** — 부드러운 리마인더 `C-EML-053`
- **Just checking in on this.** — 진행 확인 `C-EML-054`
- **I just wanted to follow up on my previous message.** — 이전 메시지 후속 `C-EML-055`
- **Could you confirm that you received the files?** — 수신 확인 요청 `C-EML-056`
- **Thanks — got it.** — 수신 확인 (짧게) `C-EML-057`
- **I've received the files. Thank you.** — 수신 확인 (정중) `C-EML-058`
- **I'll take a look and get back to you by Monday.** — 검토 후 회신 약속 `C-EML-059`
- **I'm out of the office until the 20th.** — 부재 안내 `C-EML-060`
- **I have limited access to email this week.** — 메일 확인 제한 `C-EML-061`
- **I'm copying my colleague, Dr. Lee, who's in charge of the data.** — 담당자 참조 `C-EML-062`
- **I've cc'd Min-ji, who can help with the technical details.** — 참조 추가 `C-EML-063`
- **Moving Dr. Kim to bcc to save her inbox.** — 숨은참조로 이동 `C-EML-064`
- ★ **Best regards,** — 맺음 (표준) `C-EML-065`
- **Best,** — 맺음 (친근) `C-EML-066`
- **Many thanks,** — 맺음 (감사) `C-EML-067`
- **Kind regards,** — 맺음 (격식) `C-EML-068`
- **Please don't hesitate to contact me if you need anything else.** — 연락 환영 `C-EML-069`
- **I'd be happy to review the manuscript.** — 심사 수락 `C-EML-070`
- **Unfortunately, I won't be able to review this paper due to time constraints.** — 심사 거절 `C-EML-071`
- **Please find our abstract attached for consideration.** — 초록 제출 `C-EML-072`
- **I'd be delighted to accept your invitation.** — 초청 수락 `C-EML-073`
- **Thank you for the kind invitation. Unfortunately, I'm not able to attend this time.** — 초청 거절 `C-EML-074`
- **Thank you again for organizing such a great conference.** — 학회 후 주최 측 감사 `C-EML-075`
- **I'm sending you the photos from the dinner.** — 사진 공유 `C-EML-076`
- **Congratulations on the best poster award!** — 수상 축하 `C-EML-077`
- **Thank you for a very productive meeting yesterday.** — 회의 감사 `C-EML-078`
- **Please find the minutes below.** — 회의록 본문 `C-EML-079`
- **To summarize what we agreed:** — 합의 요약 도입 `C-EML-080`
- **The next steps are as follows:** — 다음 단계 도입 `C-EML-081`
- **Quick question — do you have the latest version of the file?** — 메신저 짧은 질문 `C-EML-082`
- **Sounds good, thanks!** — 메신저 동의 `C-EML-083`
- **Running five minutes late, sorry!** — 메신저 지각 알림 `C-EML-084`
- **I'm here — at the main entrance.** — 메신저 도착 알림 `C-EML-085`
- **Subject: Follow-up from ERPW 2026 — embedding benchmark** — 제목줄 (후속) `C-EML-086`
- **Subject: Request for your dosimetry protocol** — 제목줄 (요청) `C-EML-087`
- **Happy to set up a call if that would be easier.** — 통화 제안 (열린) `C-EML-088`
- **Thanks, that's very helpful.** — 짧은 감사 회신 `C-EML-089`
- **I'd be grateful for an update when you have a moment.** — 정중한 진행 문의 `C-EML-090`

### `C-DIN` 만찬·리셉션

*상황 58개 · ★ 2개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get a glass of water?** — 물 요청 `C-DIN-001`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you pass the bread, please?** — 빵 건네 달라 `C-DIN-002`

**A10 · Do you mind if I ___?** — 상대를 배려한 허락

- **Do you mind if we join you?** — 합석 양해 `C-DIN-003`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- ★ **Is this seat free?** — 자리 비었는지 `C-DIN-004`
- **Is anyone sitting here?** — 자리 주인 있는지 `C-DIN-005`
- **Does this have pork in it?** — 돼지고기 포함 여부 `C-DIN-006`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- **What would you recommend?** — 메뉴 추천 `C-DIN-007`

**C11 · I don't eat ___ / I'm allergic to ___** — 식이 제한

- **I don't drink, so I'll have sparkling water.** — 술 대신 탄산수 `C-DIN-008`

**D01 · Sorry, could you say that again?** — 반복 요청

- **Sorry, could you say that again? It's so loud.** — 소음 속 반복 요청 `C-DIN-009`

**D04 · What does ___ mean? / What do you mean by ___?** — 의미 확인

- **What's this dish called?** — 요리 이름 `C-DIN-010`

**E01 · Nice to meet you / Good to see you** — 인사

- ★ **Hi, I'm Kim, from Korea. Nice to meet you all.** — 테이블 인사 `C-DIN-011`

**E03 · How's ___ going? / How was ___?** — 안부·경험

- **How was your day?** — 오늘 하루 `C-DIN-012`

**E04 · Where are you ___?** — 출신·소속·숙소

- **Where do you live?** — 사는 곳 묻기 `C-DIN-013`

**E05 · That sounds ___ / That's ___** — 반응·맞장구

- **Wow, that looks amazing.** — 요리 등장 반응 `C-DIN-014`
- **Same here!** — 나도 그렇다 `C-DIN-015`
- **Really? I had no idea.** — 처음 알았음 `C-DIN-016`
- **That's so funny.** — 재밌다 `C-DIN-017`

**E06 · Have you ___? / Have you been to ___?** — 경험 묻기

- **Have you ever had Korean barbecue?** — 한국 바비큐 경험 `C-DIN-018`
- **Have you traveled much in Asia?** — 아시아 여행 경험 `C-DIN-019`

**E10 · How about ___? / Shall we ___? / Why don't we ___?** — 제안

- **Shall we share a taxi back to the hotel?** — 택시 합승 제안 `C-DIN-020`
- **Why don't we grab a drink somewhere nearby?** — 2차 제안 `C-DIN-021`

**E11 · It was great ___ / Have a ___** — 작별

- **It was a lovely evening. Thank you.** — 저녁 감사 작별 `C-DIN-022`
- **Have a safe trip home!** — 귀국길 인사 `C-DIN-023`
- **See you tomorrow!** — 내일 보자 `C-DIN-024`

**E13 · I really enjoyed ___ / I loved ___** — 칭찬

- **I really enjoyed your talk today.** — 발표 칭찬 `C-DIN-025`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Cheers!** — 건배 (짧게) `C-DIN-026`
- **I'd like to propose a toast — to new collaborations!** — 건배 제의 `C-DIN-027`
- **To a great conference!** — 학회 건배 `C-DIN-028`
- **I'm fine, thanks — I've had enough.** — 술 권유 사양 `C-DIN-029`
- **Just a little, please.** — 조금만 `C-DIN-030`
- **Would you like some of this?** — 음식 권하기 `C-DIN-031`
- **This is really delicious.** — 맛 칭찬 `C-DIN-032`
- **It's grilled meat that you wrap in lettuce with a bit of sauce.** — 한국 바비큐 설명 `C-DIN-033`
- **Soju is a bit like vodka, but milder.** — 소주 설명 `C-DIN-034`
- **In Korea, we usually pour drinks for each other.** — 한국 술 문화 `C-DIN-035`
- **In Korea, it's polite to turn your head away when you drink in front of a senior.** — 한국 예절 설명 `C-DIN-036`
- **Is it common to tip here?** — 현지 팁 문화 질문 `C-DIN-037`
- **What do you like to do outside of work?** — 여가 묻기 `C-DIN-038`
- **I enjoy hiking and reading.** — 취미 답 `C-DIN-039`
- **If you come to Korea, you should visit Gyeongju.** — 경주 추천 `C-DIN-040`
- **It's the old capital — full of temples and royal tombs.** — 경주 설명 `C-DIN-041`
- **Autumn is the best time to visit Korea.** — 방문 적기 `C-DIN-042`
- **Let's not talk about work tonight!** — 일 얘기 그만 `C-DIN-043`
- **Didn't you give the talk on eye lens dose?** — 발표 기억 상기 `C-DIN-044`
- **Thank you for organizing such a wonderful evening.** — 만찬 주최 감사 `C-DIN-045`
- **Thank you so much for inviting me.** — 초대 감사 `C-DIN-046`
- **Excuse me for a moment.** — 잠시 자리 비움 `C-DIN-047`
- **I'm going to say hello to some old friends. Excuse me.** — 다른 테이블 인사 `C-DIN-048`
- **It's a bit hard to hear in here!** — 시끄러움 `C-DIN-049`
- **I'm afraid I have to leave early — I have an early flight.** — 일찍 떠남 `C-DIN-050`
- **I'm going to call it a night.** — 그만 들어가 볼게 `C-DIN-051`
- **Let's have dinner again next time you're in Seoul.** — 서울에서 다시 저녁 `C-DIN-052`
- **This is a small gift from Korea.** — 선물 증정 `C-DIN-053`
- **It's traditional Korean tea.** — 선물 설명 `C-DIN-054`
- **Oh, thank you! You shouldn't have.** — 선물 받음 `C-DIN-055`
- **Let me get this one.** — 소규모 식사 계산 `C-DIN-056`
- **Shall we split it?** — 나눠 내자 `C-DIN-057`
- **No, no — I insist.** — 계산 고집 `C-DIN-058`

### `C-VST` 기관 방문·시설 견학

*상황 48개 · ★ 3개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- **Could I get a copy of the brochure?** — 안내 책자 `C-VST-001`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you take a picture of all of us?** — 단체 사진 부탁 `C-VST-002`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would it be possible to see the calibration lab as well?** — 교정실 추가 견학 `C-VST-003`
- **Would it be possible to have someone translate for my colleague?** — 통역 요청 `C-VST-004`

**A09 · Can I ___? / Is it okay if I ___?** — 허락 구하기

- **Can I take a picture of this?** — 장비 촬영 `C-VST-005`

**A10 · Do you mind if I ___?** — 상대를 배려한 허락

- **Do you mind if I take some notes?** — 메모 허락 `C-VST-006`

**B01 · Where is ___? / Where can I ___?** — 위치 묻기

- **Where can I change?** — 탈의실 `C-VST-007`
- **Where's the restroom?** — 화장실 `C-VST-008`

**B05 · What time ___? / When ___?** — 시각·시점

- **When was this facility built?** — 시설 건립 시기 `C-VST-009`

**B06 · How long ___?** — 소요 시간·기간

- **How long will the tour take?** — 견학 소요 시간 `C-VST-010`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is photography allowed inside?** — 내부 촬영 허용 `C-VST-011`
- **Is this in use right now?** — 가동 중 여부 `C-VST-012`
- **Is there guest Wi-Fi?** — 방문자 와이파이 `C-VST-013`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need a visitor's badge?** — 방문증 필요 `C-VST-014`
- **Do I need to sign in?** — 출입 서명 `C-VST-015`
- **Do I need to do a safety briefing first?** — 안전 교육 `C-VST-016`
- **Do I need to wear a dosimeter?** — 선량계 착용 `C-VST-017`
- **Do I need to wear protective clothing?** — 보호복 착용 `C-VST-018`
- **Is there anywhere I shouldn't go?** — 출입 금지 구역 `C-VST-019`

**B14 · Could you tell me ___?** — 간접 의문 (정중)

- **Could you tell us a little about your department?** — 부서 소개 요청 `C-VST-020`

**B15 · What's the ___?** — 정보 항목 묻기

- **How many people work here?** — 직원 수 `C-VST-021`
- **How big is the team?** — 팀 규모 `C-VST-022`
- **What's this instrument used for?** — 장비 용도 `C-VST-023`
- **What's the dose rate in this area?** — 구역 선량률 `C-VST-024`

**C01 · I have a reservation ___ / I booked ___** — 예약 사실 제시

- **I'm on the visitor list. My name is Kim.** — 방문자 명단 `C-VST-025`

**C02 · I'm here for ___ / I'm here to ___** — 방문 목적

- ★ **Hi, I'm here to see Dr. Weber. I have a meeting at ten.** — 방문 도착 `C-VST-026`
- **I'm here for the lab visit.** — 견학 목적 `C-VST-027`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **Just to confirm, I can't touch anything here?** — 접촉 금지 확인 `C-VST-028`

**D06 · So you mean ___? / Do you mean ___?** — 이해 확인 (되묻기)

- **So I should stay behind the yellow line?** — 안전선 지시 확인 `C-VST-029`

**E05 · That sounds ___ / That's ___** — 반응·맞장구

- **This is really impressive.** — 감탄 `C-VST-030`

**E07 · Thanks for ___** — 감사

- ★ **Thank you for having us.** — 방문 수락 감사 `C-VST-031`
- **Thanks for taking the time to show us around.** — 안내 감사 `C-VST-032`

**E11 · It was great ___ / Have a ___** — 작별

- **Thank you again. This was very valuable for us.** — 견학 마무리 `C-VST-033`

**E13 · I really enjoyed ___ / I loved ___** — 칭찬

- **I really like how you've organized the workflow.** — 업무 흐름 칭찬 `C-VST-034`

**F12 · It would be interesting to ___ / I wonder whether ___** — 제안·호기심

- **It would be interesting to try this approach at our plant.** — 우리 발전소 적용 `C-VST-035`

**F13 · How did you ___?** — 방법 질문

- **How do you calibrate the dosimeters here?** — 선량계 교정 방식 `C-VST-036`
- **How do you manage the dose records?** — 선량 기록 관리 `C-VST-037`
- **How do you train new staff?** — 신규 직원 교육 `C-VST-038`

**F16 · In our case, ___** — 자기 맥락 비교

- ★ **In our institute, we use a similar setup.** — 우리 기관과 비교 `C-VST-039`
- **In Korea, we do this every quarter.** — 한국 주기 비교 `C-VST-040`

**J05 · Would you be interested in ___?** — 협력 제안

- **Would you be interested in a return visit next year?** — 답방 제안 `C-VST-041`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Here's my passport.** — 신분증 제시 `C-VST-042`
- **After you.** — 먼저 가시라 `C-VST-043`
- **Our schedule today is quite tight — we need to leave by three.** — 일정 제약 공유 `C-VST-044`
- **Could we take a group photo?** — 단체 사진 제안 `C-VST-045`
- **We brought a small gift from our institute.** — 기관 기념품 `C-VST-046`
- **We'd be happy to host you in Korea next time.** — 답방 초청 `C-VST-047`
- **I'll send a follow-up email with the topics we discussed.** — 후속 메일 약속 `C-VST-048`

### `C-ONL` 온라인·하이브리드 발표

*상황 38개 · ★ 2개*


**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- ★ **Could you advance the slides for me?** — 슬라이드 넘김 부탁 `C-ONL-001`
- **Could you go to the next slide, please?** — 다음 슬라이드 부탁 `C-ONL-002`
- **Could you switch to my screen?** — 화면 전환 부탁 `C-ONL-003`
- **Could you read out the questions from the chat?** — 채팅 질문 읽어 달라 `C-ONL-004`
- **Could you mute your microphone, please?** — 마이크 꺼 달라 `C-ONL-005`
- **Could you turn on your camera when you ask your question?** — 질문 시 카메라 `C-ONL-006`
- **Could you make me a co-host?** — 공동 호스트 `C-ONL-007`

**B05 · What time ___? / When ___?** — 시각·시점

- **What time should I log in for the tech check?** — 기술 점검 접속 시각 `C-ONL-008`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Is this being recorded?** — 녹화 여부 `C-ONL-009`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do you need my slides in advance?** — 슬라이드 사전 제출 `C-ONL-010`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's the link for speakers?** — 연사용 링크 `C-ONL-011`

**D01 · Sorry, could you say that again?** — 반복 요청

- **Sorry, you're breaking up. Could you type your question in the chat?** — 끊김 시 채팅 요청 `C-ONL-012`

**D03 · Just to confirm, ___? / Just to make sure ___** — 확인

- **Just to confirm, that's 9 p.m. in Seoul?** — 서울 시각 확인 `C-ONL-013`

**E07 · Thanks for ___** — 감사

- **Thanks for joining, especially those in different time zones.** — 시차 참석 감사 `C-ONL-014`

**G06 · As I mentioned ___ / Let me go back to ___** — 되돌아가기·연결

- **Let me go back to where we were.** — 중단 지점으로 `C-ONL-015`

**G08 · Can everyone ___? / Is ___ working?** — 기술 점검

- ★ **Can you hear me okay?** — 연결 확인 `C-ONL-016`
- **Can everyone see my slides?** — 슬라이드 보이는지 `C-ONL-017`
- **Is it showing in presenter mode?** — 발표자 모드 확인 `C-ONL-018`
- **Is my video coming through?** — 영상 송출 확인 `C-ONL-019`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **I can see a question in the chat — let me answer that.** — 채팅 질문 확인 `C-ONL-020`
- **Someone in the chat is asking about the dataset size.** — 채팅 질문 인용 `C-ONL-021`
- **Hello to everyone joining online.** — 온라인 청중 인사 `C-ONL-022`
- **There may be a slight delay, so please bear with me.** — 지연 양해 `C-ONL-023`
- **If I drop out, I'll rejoin straight away.** — 끊기면 재접속 `C-ONL-024`
- **Sorry about that — I'm back. Where was I?** — 재접속 후 재개 `C-ONL-025`
- **I think there's a problem with the audio in the room.** — 현장 오디오 문제 `C-ONL-026`
- **Could everyone in the room mute their laptops?** — 에코 해결 요청 `C-ONL-027`
- **I'll start the recording now.** — 녹화 시작 `C-ONL-028`
- **I'm in the waiting room.** — 대기실에 있음 `C-ONL-029`
- **I can't share my screen. Could the host give me permission?** — 화면 공유 권한 `C-ONL-030`
- **Just to check — is that 2 p.m. Berlin time?** — 시간대 확인 (베를린) `C-ONL-031`
- **Let's take a question from the room first, and then one from online.** — 현장·온라인 질문 순서 `C-ONL-032`
- **Please go ahead — you're unmuted.** — 온라인 질문자 발언 `C-ONL-033`
- **Thanks, everyone, both here and online.** — 양쪽 청중 감사 `C-ONL-034`
- **Could the moderator read the online questions?** — 사회자에게 온라인 질문 `C-ONL-035`
- **Sorry about the background noise.** — 배경 소음 사과 `C-ONL-036`
- **Hi everyone, I'm joining from Seoul, where it's almost midnight.** — 온라인 자기소개 `C-ONL-037`
- **I'll drop the link in the chat.** — 채팅에 링크 `C-ONL-038`

### `C-PUB` 논문·심사·출판 관련 대화

*상황 38개 · ★ 1개*


**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you double-check your affiliation for the paper?** — 소속 확인 요청 `C-PUB-001`
- **Could you approve the final version by Friday?** — 최종본 승인 요청 `C-PUB-002`

**B06 · How long ___?** — 소요 시간·기간

- **How long did the review take?** — 심사 기간 `C-PUB-003`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Does the journal require data sharing?** — 데이터 공개 요구 여부 `C-PUB-004`

**B12 · What do you recommend? / Can you recommend ___?** — 추천 요청

- **Which journal would you recommend for this kind of work?** — 저널 추천 `C-PUB-005`

**B13 · Do you know ___? / Do you happen to know ___?** — 정보 보유 여부

- **Do you know which journal would be a good fit for this?** — 적합 저널 `C-PUB-006`

**E03 · How's ___ going? / How was ___?** — 안부·경험

- **How's the paper coming along?** — 논문 진행 묻기 `C-PUB-007`

**E05 · That sounds ___ / That's ___** — 반응·맞장구

- **Congratulations — that's a great journal!** — 게재 축하 `C-PUB-008`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- **We agree with the reviewer and have softened our conclusions.** — 결론 완화 (답변서) `C-PUB-009`

**F07 · One limitation is ___** — 한계 인정

- **We added a paragraph on the limitations.** — 한계 단락 추가 `C-PUB-010`

**J05 · Would you be interested in ___?** — 협력 제안

- **Would you be interested in co-authoring a review paper?** — 리뷰 논문 공저 제안 `C-PUB-011`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **Our paper is currently under review.** — 심사 중 `C-PUB-012`
- **It was just accepted in Radiation Protection Dosimetry.** — 게재 승인 `C-PUB-013`
- **We're working on the revisions now.** — 수정 중 `C-PUB-014`
- **Unfortunately, it was rejected, so we're resubmitting it elsewhere.** — 게재 거절 후 재투고 `C-PUB-015`
- **There's a preprint on arXiv.** — 프리프린트 `C-PUB-016`
- **It should be out next month.** — 출판 예정 `C-PUB-017`
- **The reviewers asked us to add an external validation.** — 심사위원 요구 `C-PUB-018`
- **One of the reviewers was quite critical.** — 비판적 심사위원 `C-PUB-019`
- **We addressed all the reviewers' comments.** — 모든 코멘트 반영 `C-PUB-020`
- **We thank the reviewer for this helpful comment.** — 심사위원 감사 (답변서) `C-PUB-021`
- **We respectfully disagree with the reviewer on this point, for the following reasons.** — 정중한 반박 (답변서) `C-PUB-022`
- **We have revised the manuscript accordingly.** — 수정 반영 (답변서) `C-PUB-023`
- **As suggested, we have performed an additional sensitivity analysis.** — 추가 분석 (답변서) `C-PUB-024`
- **This has been added on page 7, lines 120 to 135.** — 수정 위치 명시 `C-PUB-025`
- **We have clarified this in the Methods section.** — 방법 명확화 (답변서) `C-PUB-026`
- **There's a special issue on AI in radiation protection — you should submit.** — 특별호 권유 `C-PUB-027`
- **Are you on the editorial board?** — 편집위원 여부 `C-PUB-028`
- **I've been asked to review a paper on this topic.** — 심사 요청 받음 `C-PUB-029`
- **Is it open access?** — 오픈 액세스 여부 `C-PUB-030`
- **The publication fee is quite high.** — 게재료 부담 `C-PUB-031`
- **They asked us to make the code available.** — 코드 공개 요구 `C-PUB-032`
- **Our abstract was accepted for an oral presentation.** — 구두 발표 채택 `C-PUB-033`
- **We were assigned to the poster session.** — 포스터 배정 `C-PUB-034`
- **Our student won the best poster award.** — 학생 수상 `C-PUB-035`
- **I'll be the corresponding author, if that's okay.** — 교신저자 `C-PUB-036`
- **We'll include a CRediT statement for each author.** — 기여 진술 `C-PUB-037`
- **Feel free to cite our preprint.** — 프리프린트 인용 허락 `C-PUB-038`

### `C-PNL` 패널 토론 참여

*상황 27개 · ★ 1개*


**D01 · Sorry, could you say that again?** — 반복 요청

- **Sorry, could you repeat the question for the panel?** — 패널 질문 반복 요청 `C-PNL-001`

**E07 · Thanks for ___** — 감사

- **Thanks for inviting me to this panel.** — 패널 초대 감사 `C-PNL-002`

**F05 · The results suggest ___ / It seems that ___** — 헤징 (단정 회피)

- **I think AI will become part of routine dose management, but not overnight.** — AI 도입 전망 `C-PNL-003`
- **My guess is that we'll see the first regulatory use cases within five years.** — 규제 활용 예측 `C-PNL-004`

**F10 · I agree ___ / That's a good point** — 동의

- **I agree with what Dr. Weber said about transparency.** — 다른 패널 동의 `C-PNL-005`

**F11 · I see what you mean, but ___** — 정중한 반대

- **I'd slightly disagree with the previous point.** — 다른 패널 이견 `C-PNL-006`

**F12 · It would be interesting to ___ / I wonder whether ___** — 제안·호기심

- **It would be interesting to run a joint pilot across several countries.** — 다국 공동 파일럿 `C-PNL-007`

**F16 · In our case, ___** — 자기 맥락 비교

- **In Korea, we have more than 20 reactors, so occupational dose management is a big issue.** — 한국 원전 맥락 `C-PNL-008`

**H08 · Can I just add ___? / If I may, ___** — 끼어들기·보충

- **If I may add something to that…** — 발언 보충 `C-PNL-009`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- ★ **Thank you. I'll keep my opening remarks brief.** — 짧은 개회 발언 `C-PNL-010`
- **I'd like to offer a slightly different perspective.** — 다른 관점 제시 `C-PNL-011`
- **Let me add a view from Asia.** — 아시아 관점 `C-PNL-012`
- **Let me give you a concrete example from our institute.** — 구체 사례 제시 `C-PNL-013`
- **For me, the biggest challenge is trust, not technology.** — 최대 난제 `C-PNL-014`
- **My recommendation would be to start with low-risk applications.** — 단계적 권고 `C-PNL-015`
- **That links nicely to the question from the audience.** — 청중 질문과 연결 `C-PNL-016`
- **I'll be brief.** — 짧게 답하겠다 `C-PNL-017`
- **Just to clarify what I said earlier…** — 앞 발언 명확화 `C-PNL-018`
- **If I could leave you with one thought, it would be this.** — 마지막 한마디 `C-PNL-019`
- **We need more international collaboration on shared benchmarks.** — 국제 협력 촉구 `C-PNL-020`
- **I'd encourage everyone to share anonymized data where possible.** — 데이터 공유 촉구 `C-PNL-021`
- **Regulators have an important role to play here.** — 규제기관 역할 `C-PNL-022`
- **I'd like to echo what was just said.** — 앞 발언에 공감 `C-PNL-023`
- **I'll leave it there so others can come in.** — 발언권 양보 `C-PNL-024`
- **I'd reframe the question slightly.** — 질문 재정의 `C-PNL-025`
- **I don't think anyone has a definitive answer yet.** — 확답 없음 인정 `C-PNL-026`
- **I'm cautiously optimistic.** — 조심스러운 낙관 `C-PNL-027`

### `C-ADM` 출장 행정·증빙·정산

*상황 21개 · ★ 1개*


**A01 · Could I get ___? / Can I have ___?** — 물건·서비스 요청 (가장 범용)

- ★ **Could I get a receipt with the VAT shown separately?** — 부가세 분리 영수증 `C-ADM-001`
- **Could I get a letter confirming my participation?** — 참가 확인 서한 `C-ADM-002`
- **Could I get a certificate confirming my presentation?** — 발표 증명서 `C-ADM-003`

**A02 · Could you ___ (for me)?** — 상대에게 행동을 부탁

- **Could you put my institute's name on the invoice?** — 기관명 인보이스 `C-ADM-004`
- **Could you issue the invoice in English?** — 영문 인보이스 `C-ADM-005`
- **Could you send me proof of payment?** — 결제 증빙 송부 `C-ADM-006`
- **Could you transfer the travel grant to my institute's account?** — 여비 지원금 송금 `C-ADM-007`
- **Could you send an official invitation letter for my travel approval?** — 출장 승인용 초청장 `C-ADM-008`
- **Could you write the date and amount on the receipt?** — 수기 영수증 기재 `C-ADM-009`

**A06 · Would it be possible to ___? / Is it possible to ___?** — 규정 밖·예외 요청

- **Would it be possible to split the bill into accommodation and meals?** — 숙박·식비 분리 `C-ADM-010`

**B07 · How much ___?** — 가격·양

- **How much is the bank transfer fee?** — 송금 수수료 `C-ADM-011`

**B09 · Is this ___? / Does this ___?** — 예·아니오 확인

- **Does the receipt include your VAT number?** — 영수증 사업자번호 `C-ADM-012`

**B10 · Do I need to ___? / Do I have to ___?** — 의무·필요 여부

- **Do I need a separate receipt for the deposit?** — 보증금 별도 영수증 `C-ADM-013`
- **Do you need our institute's bank details?** — 기관 계좌 정보 필요 `C-ADM-014`

**B15 · What's the ___?** — 정보 항목 묻기

- **What's the invoice number?** — 인보이스 번호 `C-ADM-015`

**C06 · I lost ___ / I can't find ___ / I left ___** — 분실

- **I lost my receipt. Could you print a copy?** — 영수증 분실 재출력 `C-ADM-016`

**K07 · Could you let me know ___? / Please let me know ___** — 회신 요청

- **Could you let me know how to request a certificate of presentation?** — 발표 증명서 발급 문의 `C-ADM-017`

**Z00 · (고정 표현 · chunk)** — 패턴으로 쪼개지 않고 통째로 외우는 관용 덩어리

- **Our travel policy only covers economy class.** — 출장 규정 (좌석 등급) `C-ADM-018`
- **I need to submit all the receipts within two weeks.** — 정산 기한 `C-ADM-019`
- **I'll take a photo of the receipt just in case.** — 영수증 사진 보관 `C-ADM-020`
- **Please refund it to the same card.** — 같은 카드로 환불 `C-ADM-021`

---

## 부록 A. 핵심(★) 표현 압축 목록

출국 전 최종 점검용이다. 각 카테고리에서 '이것만은 반드시 입에서 나와야 하는' 표현만 추렸다.

### Part 1. 공통 의사소통 기반

**REP 의사소통 수리 — 못 알아들었을 때** — *Sorry, could you say that again?* · *Sorry, could you repeat that a bit more slowly?* · *Sorry, I didn't catch that.* · *Just to confirm, it's platform 7, right?* · *Sorry, what does that word mean?* · *Could you speak a little more slowly, please?* · *Could you write it down for me?* · *So I should go back to the first counter?* · *Let me think for a second.* · *How do you say this in English?* · *My English isn't perfect, so please bear with me.* · *Just a moment, please.*

**BAS 인사·사과·감사·말 걸기** — *Nice to meet you.* · *Thanks so much.* · *Sorry about that.* · *Sorry I'm late.* · *Excuse me, do you have a minute?* · *You're welcome.* · *No, thank you.*

**NUM 숫자·시간·날짜·위치 확인** — *Where's the restroom?* · *Do you know what time it is?* · *How long will it take?* · *How much is this?*

**EXP 선택·허락·상태 표현** — *Could you do me a favor?* · *I'd like this one, please.* · *This one, please.* · *Can I take a photo here?* · *I'd prefer the earlier one.* · *Could you help me with this?* · *It's my first time here.* · *I'm afraid I can't.*

### Part 2. 여행 영어

**AIR1 공항 출국 — 체크인·수하물** — *Could I get a window seat?* · *Hi, I'd like to check in for my flight to Frankfurt.* · *I'd like to change my flight.* · *How do I use this kiosk?* · *What time does boarding start?* · *Which gate is it?* · *Is checked baggage included in my ticket?* · *Here you go.*

**AIR2 보안검색·면세·라운지·탑승** — *Where's gate B22?* · *What time does boarding start?* · *Which group am I in?* · *Is this the line for Group 3?* · *Do I need to take my laptop out?*

**FLT 기내** — *Could I get some water, please?* · *Sorry, can I get out?* · *I'll have the chicken, please.* · *How long until we land?* · *Do I need to fill this out?* · *My screen isn't working.* · *Excuse me, I think I'm in the window seat.*

**ARR 입국심사·세관·수하물 찾기** — *Where's the baggage claim?* · *Where's the exit?* · *How do I get to the city center?* · *Do I need to scan my fingerprints?* · *Do I need to declare this?* · *I'm here for a conference.* · *My bag didn't come out.* · *Here's my passport.*

**TRN 기차·장거리 열차** — *I'd like a ticket to Dresden, please.* · *How do I use this machine?* · *When's the next train to Dresden?* · *How much is a ticket to Prague?* · *Which platform does it leave from?* · *Does this train go to Dresden?* · *Is the train delayed?* · *Do I need to validate this ticket?* · *Excuse me, I think you're in my seat.*

**MET 지하철·S반·버스·트램** — *Can I just tap my card?* · *Where can I buy a ticket?* · *Where's the bus stop for the 100?* · *How do I get to the Reichstag from here?* · *Is there a day pass?* · *Which line goes to Museum Island?* · *Does this go to Alexanderplatz?* · *Does this bus go to the university?* · *Do I need to validate it?* · *Excuse me, I'm getting off.*

**TAX 택시·라이드셰어·공항 이동** — *Could I get a receipt?* · *Could you call a taxi for me?* · *To the Hilton, please.* · *Where's the taxi rank?* · *How much is it to the city center?* · *Keep the change.*

**CAR 렌터카·운전** — *Is insurance included?* · *I have a reservation under Kim.*

**DIR 길 묻기·위치 찾기** — *I'm looking for the conference center — the ICC.* · *How do I get to the Pergamon Museum?* · *Excuse me, could you help me? I'm a bit lost.*

**HTL1 호텔 체크인·체크아웃** — *Could you print this for me?* · *I'd like to check out, please.* · *Would it be possible to check in early?* · *Can I leave my bags here until check-in?* · *What time is checkout?* · *Is the room ready?* · *Is breakfast included?* · *What's the Wi-Fi password?* · *Hi, I have a reservation under Kim.* · *I think there's a mistake on my bill.*

**HTL2 호텔 생활·문제 해결** — *Could I get some extra towels?* · *The air conditioning isn't working.* · *I locked myself out.*

**RST1 레스토랑 예약·입장·주문** — *Could we see the menu, please?* · *Could we get some tap water, please?* · *I'd like to make a reservation for two tonight.* · *I'd like it medium-rare.* · *I'll have the schnitzel, please.* · *Do you have a table for two tonight?* · *What do you recommend?* · *We have a reservation under Kim.* · *What exactly is Eisbein?* · *A table for two, please.* · *Could we have a few more minutes?* · *I'm full, thanks.*

**RST2 계산·문제·식이 제한** — *Could we get the check, please?* · *Could I get a box for this?* · *Can I pay by card?* · *Can we pay separately?* · *Does this have nuts in it?* · *Is service included?* · *Our food hasn't arrived yet.* · *I think there's a mistake on the bill.* · *I'm allergic to nuts.*

**CAF 카페·베이커리·바** — *Could I get a flat white, please?* · *Is this seat taken?* · *To go, please.*

**SHP 쇼핑·면세·환불** — *Could I get a bag?* · *Could I get a receipt?* · *Could you gift-wrap it?* · *I'd like to exchange this.* · *I'd like a refund, please.* · *Can I try this on?* · *Can I get a tax-free form?* · *I'll take it.* · *I'm looking for a gift for my wife.* · *Do you have this in a medium?* · *How much is this?* · *I'm just looking, thanks.* · *Excuse me, could you help me?* · *In euros, please.*

**SGT 관광·박물관·공연·투어** — *Could you take a picture of us?* · *Two adult tickets, please.* · *What time does it close?* · *How much is admission?*

**MON 환전·ATM·결제** — *I'd like to change 300 dollars into euros.* · *Is there an ATM nearby?* · *Do you take cards?* · *What's the exchange rate today?*

**COM 통신·SIM·와이파이·충전** — *I'd like a prepaid SIM card.* · *Is there free Wi-Fi here?* · *Do you have a plug adapter?*

**MED 약국·병원·응급** — *Could you call a doctor, please?* · *I need something for a headache.* · *I need a prescription for this.* · *Where's the nearest emergency room?* · *Is there a pharmacy near here?* · *I have a bad headache.* · *I've had a fever since yesterday.* · *Call an ambulance!* · *Help!*

**TRB 분실·도난·사고·항공 지연** — *Could I get a written confirmation of the delay?* · *Could you call the police?* · *I need to contact the Korean embassy.* · *Where's the nearest police station?* · *What are my options?* · *My flight's been cancelled.* · *I've lost my wallet.* · *I missed my connecting flight.* · *Someone stole my bag.*

**SOC 여행지 스몰토크·현지인 대화** — *What would you recommend I see while I'm here?* · *What brings you here?* · *Where are you from?* · *That sounds amazing.* · *I'm from South Korea.*

**SVC 우체국·세탁·미용·생활 서비스** — *I'd like to send this package to Korea.* · *I'd like a haircut, please.*

### Part 3. 학회·연구 활동 영어

**REG 학회 등록·배지·장소 안내** — *Could I get a receipt for the registration fee?* · *Where's Room B?* · *Where's the speaker ready room?* · *Is there a conference app?* · *Does the registration include the conference dinner?* · *Hi, I'm here to pick up my badge.*

**NET 네트워킹 — 첫인사·자기소개** — *Do you mind if I join you?* · *Hi, I'm Kim. Nice to meet you.* · *What brings you to the conference?* · *Where are you based?* · *That sounds really interesting.* · *Shall we exchange cards?* · *It was great talking to you.* · *I'm a researcher at the Radiation Health Institute in Korea.* · *I work on occupational radiation dosimetry.* · *Could you tell me a bit more about that?* · *Would you be interested in collaborating on something like this?* · *I'll send you an email after the conference.*

**SML 학회 스몰토크** — *Any recommendations for dinner around here?* · *Great to see you again!* · *How's your hotel?*

**PRE1 발표 시작·기술 점검** — *Could you help me load my slides?* · *Today I'd like to talk about how we use language models in radiation protection.* · *Let me start with a quick overview.* · *Can everyone hear me okay?* · *Thank you, Chair, and good morning, everyone.*

**PRE2 발표 본론 — 방법·흐름 설명** — *We used a retrieval benchmark built from ICRP documents.* · *We compared our method with the standard approach.* · *Our approach is based on the method described by Smith and colleagues.* · *Let's move on to the methods.* · *This figure shows the overall workflow.* · *What this means is that the model works well even with limited data.* · *As I mentioned earlier, the data were collected over ten years.* · *I'll go through this quickly.*

**PRE3 결과·데이터·통계 설명** — *We found that the small models performed almost as well as the large ones.* · *These results suggest that the method could be applied to other plants.* · *Compared with the baseline, our model was about 20 percent more accurate.* · *One possible explanation is that the Korean translation uses different terms.* · *As you can see, the two lines are very close.* · *What this tells us is that the bias is consistent across the dose range.* · *The mean dose was 0.8 millisieverts per year.*

**PRE4 한계·결론·마무리** — *One limitation is that we only used data from one country.* · *In future work, we plan to include more languages.* · *To sum up, small embedding models can work well for radiation protection.* · *I'm running short on time, so let me jump to the conclusion.* · *Thank you for your attention.*

**QA1 질문 받기·답변하기** — *Sorry, could you repeat the question?* · *That's a fair point — it's one of the limitations of the study.* · *I see what you mean, but in our data, the effect was quite small.* · *Thank you for the question.* · *If I understand correctly, you're asking about the calibration, right?* · *I'd be happy to discuss that in more detail after the session.* · *Does that answer your question?* · *Can I just add one thing?* · *The short answer is yes.*

**QA2 어려운 질문·비판 대응** — *I'm afraid we can't share the raw data, for confidentiality reasons.* · *I take your point, but I think the results still hold.* · *I'm not sure, but my guess would be that it's related to the energy spectrum.* · *That's a bit outside the scope of this study.*

**ASK 청중으로서 질문하기** — *I was wondering whether you looked at the seasonal variation.* · *Hi, thank you for the great talk. I'm Kim, from Korea.* · *It would be interesting to see this applied to medical staff.* · *How did you define the ground truth?* · *Did you consider using a larger model?* · *Could you say a bit more about the reranking step?* · *In our case, we saw a similar pattern with the Korean documents.* · *I have a question about your validation method.*

**PST 포스터 세션** — *Hi, would you like me to walk you through the poster?* · *This figure here shows the overall results.* · *Would you be interested in comparing results sometime?*

**CHR 좌장·세션 진행** — *Our first speaker is Dr. Anna Weber, from the BfS.* · *Each speaker has 12 minutes, followed by three minutes for questions.* · *Let's open the floor for questions.* · *Just a reminder to keep to time.* · *Let's thank all the speakers once again.* · *Good morning, everyone. Let's get started.*

**DSC 연구 방법론·전문 토론** — *I agree, interpretability is crucial in this field.* · *I see what you mean, but I think the sample size is still too small.* · *It would be interesting to compare this with the IAEA method.* · *How did you tune the hyperparameters?* · *Did you consider a non-parametric approach?* · *In our case, we have about 30 years of dose records.* · *What does your data look like?*

**AGR 동의·반대·의견 표현** — *It seems to me that the problem is the reference data.* · *I completely agree.* · *I see what you mean, but I'm not sure that's the case here.* · *In my view, the main issue is data quality.*

**COL 공동연구·후속 협력** — *I was wondering if we could explore a collaboration.* · *Could we set up a video call after the conference?* · *Would you be interested in working together on this?* · *I'll send you a short summary of our project.*

**MTG 미팅·온라인 회의** — *Do you mind if I go first? I have to leave early.* · *Sorry, you broke up a little. Could you say that again?* · *Just to confirm, we're going with option B?* · *Shall we get started?* · *Can you hear me?* · *Sorry to interrupt, but can I just add something?* · *Could we move the meeting to Thursday?* · *The purpose of today's meeting is to agree on the timeline.* · *So the action items are: Kim will send the data, and Anna will draft the report.*

**EML 이메일·메시지** — *I'm writing to follow up on our conversation at ERPW.* · *Please find attached the paper we discussed.* · *I'd appreciate it if you could send me the protocol.* · *Thank you for your quick reply.* · *Looking forward to hearing from you.* · *Apologies for the late reply.* · *Could you let me know if this works for you?* · *Would Tuesday at 10 a.m. CET work for you?* · *Dear Dr. Weber,* · *Best regards,*

**DIN 만찬·리셉션** — *Is this seat free?* · *Hi, I'm Kim, from Korea. Nice to meet you all.*

**VST 기관 방문·시설 견학** — *Hi, I'm here to see Dr. Weber. I have a meeting at ten.* · *Thank you for having us.* · *In our institute, we use a similar setup.*

**ONL 온라인·하이브리드 발표** — *Could you advance the slides for me?* · *Can you hear me okay?*

**PUB 논문·심사·출판 관련 대화** — *Our paper is currently under review.*

**PNL 패널 토론 참여** — *Thank you. I'll keep my opening remarks brief.*

**ADM 출장 행정·증빙·정산** — *Could I get a receipt with the VAT shown separately?*

---

## 부록 B. 패턴 × 카테고리 교차 색인

한 패턴이 어떤 상황들에서 재사용되는지를 보여준다. 재사용 범위가 넓은 패턴일수록 학습 효율이 높다.

| 패턴 | 틀 | 등장 카테고리 (상황 수) |
|---|---|---|
| A01 | Could I get ___? / Can I have ___? | RST1(13), HTL2(11), FLT(10), CAF(10), AIR1(6), HTL1(6), RST2(6), AIR2(3), SHP(3), MON(3), REG(3), ADM(3), ARR(2), MED(2), TRB(2), TRN(1), TAX(1), NET(1), PRE1(1), DIN(1), VST(1), SVC(1) |
| A02 | Could you ___ (for me)? | TAX(17), HTL2(10), RST2(8), HTL1(7), ONL(7), ADM(6), AIR1(5), FLT(5), RST1(5), TRB(5), MTG(5), SHP(4), MON(4), COM(4), REG(4), DIR(3), SGT(3), PRE1(3), SVC(3), EXP(2), AIR2(2), TRN(2), CAF(2), PUB(2), ARR(1), MET(1), CAR(1), MED(1), NET(1), ASK(1), PST(1), DIN(1), VST(1) |
| A03 | Would you mind ___ing? | EXP(2), FLT(1) |
| A04 | I'd like (to) ___ | RST1(6), AIR1(4), SGT(4), SVC(4), TRN(3), HTL1(3), SHP(3), EXP(2), ARR(2), TAX(2), MON(2), TRB(2), CAR(1), HTL2(1), RST2(1), CAF(1), COM(1), MED(1), REG(1) |
| A05 | ___, please. | TRN(3), EXP(2), MET(2), TAX(2), CAR(1), CAF(1), SGT(1) |
| A06 | Would it be possible to ___? / Is it possible to ___? | HTL1(6), AIR1(5), AIR2(3), TRB(3), FLT(2), HTL2(2), RST1(2), RST2(2), COL(2), VST(2), EXP(1), TRN(1), SHP(1), REG(1), PRE1(1), PST(1), EML(1), SVC(1), ADM(1) |
| A07 | I was wondering if ___ | COL(4), ASK(2), EML(2), EXP(1), NET(1) |
| A08 | I need (to) ___ | MED(15), EXP(3), TRB(2), FLT(1), CAR(1) |
| A09 | Can I ___? / Is it okay if I ___? | EXP(5), MET(4), RST1(4), MON(4), FLT(3), TRN(3), CAR(3), HTL1(3), CAF(3), SHP(3), AIR1(2), AIR2(2), RST2(2), ARR(1), TAX(1), SGT(1), COM(1), REG(1), PRE1(1), ASK(1), VST(1) |
| A10 | Do you mind if I ___? | EXP(3), FLT(2), MTG(2), MET(1), CAF(1), NET(1), SML(1), PST(1), DIN(1), VST(1) |
| A11 | I'll have ___ / I'll take ___ | RST1(9), CAF(3), FLT(2), SHP(2), AIR2(1), TRN(1), HTL2(1) |
| A12 | I'd prefer ___ / I'd rather ___ | EXP(4), TRN(3), CAR(1), HTL1(1), RST1(1), SHP(1), SOC(1) |
| A13 | Could you help me with ___? | EXP(3), TRN(1) |
| A14 | I'm looking for ___ | SHP(3), SVC(3), DIR(2) |
| B01 | Where is ___? / Where can I ___? | ARR(11), TRN(9), AIR2(8), DIR(7), REG(7), MET(6), SGT(5), SHP(4), AIR1(3), TAX(3), CAR(3), TRB(3), NUM(2), HTL1(2), CAF(2), VST(2), RST1(1), COM(1), MED(1), PST(1), SVC(1) |
| B02 | How do I get to ___? / How do I ___? | HTL2(5), CAR(4), COM(3), FLT(2), ARR(2), MET(2), SHP(2), AIR1(1), AIR2(1), TRN(1), DIR(1), TRB(1), REG(1), PRE1(1), SVC(1) |
| B03 | Is there ___ (around here)? | SGT(12), DIR(10), REG(7), AIR2(6), MET(6), AIR1(5), TRN(5), HTL1(5), HTL2(5), RST1(4), MED(4), SVC(4), COM(3), FLT(2), ARR(2), CAR(2), SHP(2), MON(2), TRB(2), NUM(1), TAX(1), PST(1) |
| B04 | Do you have ___? | RST1(8), SHP(6), HTL1(5), CAF(5), SVC(5), FLT(4), COM(4), REG(3), MET(2), SGT(2), AIR2(1), TRN(1), RST2(1), MED(1), PRE1(1) |
| B05 | What time ___? / When ___? | SGT(6), REG(6), NUM(5), HTL1(5), MET(4), TRN(3), TAX(3), PST(3), SVC(3), AIR1(2), FLT(2), HTL2(2), RST1(2), CAF(2), AIR2(1), CAR(1), DIR(1), SHP(1), MON(1), TRB(1), SML(1), PRE1(1), VST(1), ONL(1) |
| B06 | How long ___? | NUM(5), TRN(5), AIR2(4), MET(3), SGT(3), TRB(3), AIR1(2), ARR(2), TAX(2), HTL2(2), RST1(2), SHP(2), SVC(2), FLT(1), DIR(1), RST2(1), COM(1), MED(1), PRE1(1), VST(1), PUB(1) |
| B07 | How much ___? | HTL1(7), NUM(6), AIR1(4), TRN(4), TAX(4), SHP(4), CAR(3), MON(3), MET(2), SGT(2), COM(2), SVC(2), AIR2(1), FLT(1), ARR(1), HTL2(1), MED(1), REG(1), ADM(1) |
| B08 | Which ___? | MET(4), DIR(4), ARR(3), TRN(3), NUM(2), AIR2(2), AIR1(1), SHP(1), TRB(1), REG(1), PST(1) |
| B09 | Is this ___? / Does this ___? | TRN(16), MET(14), AIR1(10), AIR2(9), DIR(8), SGT(8), TAX(7), CAF(7), SHP(7), MED(7), RST1(6), MON(6), REG(6), HTL2(5), RST2(5), NUM(4), CAR(4), TRB(4), FLT(3), ARR(3), COM(3), DIN(3), VST(3), HTL1(2), PRE1(2), PST(2), CHR(2), SOC(1), COL(1), MTG(1), ONL(1), PUB(1), ADM(1) |
| B10 | Do I need to ___? / Do I have to ___? | MET(7), SGT(7), AIR2(6), ARR(6), VST(6), TRN(5), TRB(5), AIR1(4), CAR(4), SHP(4), MED(4), REG(4), HTL1(3), MON(3), SVC(3), EXP(2), FLT(2), RST1(2), RST2(2), CAF(2), COM(2), PRE1(2), ADM(2), TAX(1), DIR(1), HTL2(1), PST(1), COL(1), ONL(1) |
| B11 | Is ___ included? / Does it come with ___? | HTL1(4), SGT(4), TRN(3), CAR(3), RST1(3), AIR1(2), AIR2(2), TAX(2), HTL2(2), SHP(2), COM(2), TRB(2), REG(2), FLT(1), ARR(1), MET(1), RST2(1), MON(1), SVC(1) |
| B12 | What do you recommend? / Can you recommend ___? | SGT(5), RST1(4), SHP(3), SOC(3), DIR(2), CAF(2), MET(1), TAX(1), HTL1(1), NET(1), SML(1), DIN(1), PUB(1) |
| B13 | Do you know ___? / Do you happen to know ___? | DIR(3), SOC(2), REP(1), FLT(1), MET(1), RST1(1), MON(1), REG(1), SML(1), COL(1), PUB(1) |
| B14 | Could you tell me ___? | FLT(1), DIR(1), SGT(1), COM(1), COL(1), VST(1) |
| B15 | What's the ___? | MED(5), RST1(4), MON(4), VST(4), FLT(3), TRN(3), CAF(3), AIR2(2), MET(2), CAR(2), HTL1(2), SHP(2), COM(2), REG(2), AIR1(1), ARR(1), TAX(1), DIR(1), RST2(1), SGT(1), TRB(1), ONL(1), ADM(1) |
| B16 | What if ___? / What happens if ___? | TRN(2), ASK(2), EXP(1), AIR1(1), AIR2(1), SGT(1), TRB(1), AGR(1) |
| C01 | I have a reservation ___ / I booked ___ | HTL1(2), AIR1(1), FLT(1), ARR(1), CAR(1), RST1(1), REG(1), VST(1) |
| C02 | I'm here for ___ / I'm here to ___ | ARR(4), NET(2), VST(2), TAX(1), REG(1) |
| C03 | I'm heading to ___ | DIR(2) |
| C04 | There's a problem with ___ / ___ isn't working | HTL2(17), RST2(6), COM(5), FLT(4), CAR(4), AIR1(3), SHP(3), MON(3), ARR(2), MET(2), TRB(2), PRE1(2), AIR2(1), TRN(1), CAF(1), PST(1) |
| C05 | I think there's a mistake ___ | RST2(5), TAX(2), HTL1(2), MON(2), REG(2), AIR1(1), AIR2(1), FLT(1), TRN(1), MET(1), CAR(1), CAF(1), SHP(1), TRB(1) |
| C06 | I lost ___ / I can't find ___ / I left ___ | TRB(6), HTL2(3), AIR2(2), ARR(2), MED(2), TAX(1), DIR(1), MON(1), REG(1), ADM(1) |
| C07 | I have ___ / I feel ___ | MED(20), FLT(5), EXP(3), DIR(1), HTL2(1), RST2(1), COM(1) |
| C08 | I've been ___ since / for ___ | MED(4) |
| C09 | It's my first time ___ | EXP(1), ARR(1) |
| C10 | I'm afraid ___ | EXP(3), QA2(3), RST2(2), COL(2), HTL2(1), TRB(1) |
| C11 | I don't eat ___ / I'm allergic to ___ | RST2(6), AIR1(1), FLT(1), MED(1), REG(1), DIN(1) |
| C12 | I'm just ___ | EXP(3), SHP(2), MET(1) |
| C13 | I'm running late / I missed ___ | TRB(3), EXP(1), AIR1(1), AIR2(1), FLT(1), TRN(1), MET(1), TAX(1), HTL1(1), RST1(1), REG(1) |
| C14 | I was told ___ | AIR1(1), TAX(1), HTL1(1), HTL2(1), TRB(1) |
| D01 | Sorry, could you say that again? | REP(8), QA1(3), ARR(1), DIR(1), HTL1(1), SGT(1), COM(1), NET(1), PST(1), MTG(1), DIN(1), ONL(1), PNL(1) |
| D02 | Sorry, I didn't catch ___ | REP(6), AIR2(1), TRN(1), MET(1), DIR(1), NET(1), SML(1), QA1(1), MTG(1) |
| D03 | Just to confirm, ___? / Just to make sure ___ | REP(5), NUM(2), AIR1(2), COL(2), MTG(2), TRN(1), TAX(1), DIR(1), MON(1), COM(1), MED(1), TRB(1), PRE1(1), VST(1), ONL(1) |
| D04 | What does ___ mean? / What do you mean by ___? | REP(6), TRN(2), ASK(2), ARR(1), RST1(1), RST2(1), SOC(1), NET(1), QA1(1), QA2(1), DSC(1), DIN(1) |
| D05 | Could you speak more slowly / write it down? | REP(8), MED(1), QA1(1) |
| D06 | So you mean ___? / Do you mean ___? | REP(7), NUM(4), DIR(3), AIR2(2), TRN(1), MET(1), TAX(1), SHP(1), REG(1), NET(1), QA1(1), QA2(1), ASK(1), DSC(1), MTG(1), VST(1) |
| D07 | Let me ___ | REP(5), AIR1(2), QA1(2), FLT(1), CAR(1), PST(1) |
| D08 | How do you say ___? / What do you call ___? | REP(4), CAF(1), SOC(1), NET(1), CHR(1) |
| E01 | Nice to meet you / Good to see you | BAS(3), NET(2), SML(1), DIN(1) |
| E02 | What brings you ___? / Are you here for ___? | NET(3), SOC(2), FLT(1), TRN(1), SML(1) |
| E03 | How's ___ going? / How was ___? | SML(4), SOC(3), BAS(2), NET(2), DIN(1), PUB(1) |
| E04 | Where are you ___? | NET(3), SOC(2), FLT(1), TAX(1), SML(1), PST(1), DIN(1) |
| E05 | That sounds ___ / That's ___ | SOC(8), SML(8), NET(5), DIN(4), SGT(2), PST(2), RST1(1), CAF(1), VST(1), PUB(1) |
| E06 | Have you ___? / Have you been to ___? | SOC(5), SML(3), DIN(2), NET(1) |
| E07 | Thanks for ___ | BAS(6), PRE4(2), PST(2), COL(2), VST(2), DIR(1), HTL1(1), HTL2(1), NET(1), PRE1(1), ASK(1), CHR(1), ONL(1), PNL(1) |
| E08 | Sorry about ___ / Sorry to ___ | BAS(8), HTL2(1), TRB(1) |
| E09 | Excuse me, ___ | BAS(5), FLT(2), AIR2(1), TRN(1), MET(1), DIR(1), SHP(1), NET(1), ASK(1), PST(1) |
| E10 | How about ___? / Shall we ___? / Why don't we ___? | NET(5), SOC(3), AGR(2), COL(2), DIN(2), MTG(1) |
| E11 | It was great ___ / Have a ___ | BAS(4), NET(4), SML(3), DIN(3), SOC(2), COL(1), VST(1) |
| E12 | I'm ___ / I work for ___ | NET(6), SOC(5), ARR(2), PRE1(1), CHR(1) |
| E13 | I really enjoyed ___ / I loved ___ | SOC(2), NET(2), RST1(1), SGT(1), ASK(1), DIN(1), VST(1) |
| F01 | I work on ___ / My research focuses on ___ | NET(5), PST(1), DSC(1) |
| F02 | We're currently ___ing | MTG(2), NET(1), PRE2(1), PRE4(1), DSC(1) |
| F03 | We used ___ to ___ | PRE2(11), DSC(6), QA1(2), PST(1) |
| F04 | We found that ___ / The main finding is ___ | PRE3(7), QA1(1), PST(1) |
| F05 | The results suggest ___ / It seems that ___ | PRE3(6), AGR(6), DSC(3), PRE4(2), QA1(2), QA2(2), PNL(2), SML(1), PRE2(1), ASK(1), PST(1), PUB(1) |
| F06 | Compared with ___ / ___ performed better than ___ | PRE3(8), PRE2(2), QA1(2), DSC(2), QA2(1) |
| F07 | One limitation is ___ | PRE4(9), QA1(2), QA2(2), DSC(2), PST(1), PUB(1) |
| F08 | One possible explanation is ___ / This might be due to ___ | PRE3(5), DSC(2), QA1(1), QA2(1), PST(1) |
| F09 | In future work, we plan to ___ / Next, we'd like to ___ | PRE4(5), QA1(2), DSC(2), PST(1) |
| F10 | I agree ___ / That's a good point | AGR(7), DSC(3), SML(1), ASK(1), PNL(1) |
| F11 | I see what you mean, but ___ | AGR(8), QA2(6), DSC(3), QA1(2), SML(1), ASK(1), PNL(1) |
| F12 | It would be interesting to ___ / I wonder whether ___ | DSC(4), ASK(3), PRE4(2), NET(1), PST(1), CHR(1), VST(1), PNL(1) |
| F13 | How did you ___? | ASK(9), DSC(8), VST(3), NET(1), PST(1) |
| F14 | Did you consider ___? / Have you tried ___? | DSC(7), ASK(6), QA1(1), PST(1) |
| F15 | Could you say more about ___? | ASK(3), DSC(2), NET(1) |
| F16 | In our case, ___ | DSC(4), NET(3), QA1(2), ASK(2), VST(2), QA2(1), PST(1), PNL(1) |
| F17 | This is based on ___ | PRE2(3), DSC(2), PRE1(1), QA1(1) |
| G01 | Today I'd like to ___ | PRE1(4), PST(1), CHR(1) |
| G02 | Let me start with ___ / First, ___ | PRE1(5), PRE2(2) |
| G03 | Let's move on to ___ / Next, ___ | PRE2(7), PRE3(2) |
| G04 | This slide shows ___ / As you can see, ___ | PRE2(13), PRE3(9), PRE1(3), PST(3), QA1(1) |
| G05 | What this means is ___ / The key point here is ___ | PRE2(9), PRE3(5), PRE1(2), PRE4(1), PST(1) |
| G06 | As I mentioned ___ / Let me go back to ___ | PRE2(3), PRE4(1), QA1(1), ASK(1), ONL(1) |
| G07 | To sum up ___ / The take-home message is ___ | PRE4(6), CHR(1) |
| G08 | Can everyone ___? / Is ___ working? | PRE1(5), ONL(4), MTG(3), CHR(1) |
| G09 | I'm running short on time, so ___ | PRE4(3), PRE2(2), PRE1(1) |
| H01 | That's a good question / Thanks for the question | QA1(5), PST(1) |
| H02 | If I understand correctly, ___ | QA1(3), QA2(2), PST(1) |
| H03 | I'm not sure, but ___ / I don't have ___, but ___ | QA2(5) |
| H04 | That's outside the scope of ___ | QA2(4) |
| H05 | I'd be happy to ___ | QA1(3), QA2(1) |
| H06 | I have a question about ___ / My question is ___ | ASK(7), PST(1), CHR(1) |
| H07 | Does that answer your question? | QA1(3), QA2(1) |
| H08 | Can I just add ___? / If I may, ___ | QA1(3), MTG(2), ASK(1), PNL(1) |
| J01 | Our next speaker is ___ | CHR(3) |
| J02 | We have time for ___ | CHR(5) |
| J03 | Let's ___ (진행) | MTG(8), CHR(5) |
| J04 | Could we ___? / Can we ___? | COL(3), MTG(2), NET(1) |
| J05 | Would you be interested in ___? | COL(6), PST(2), NET(1), VST(1), PUB(1) |
| J06 | I'll ___ (send / follow up) | COL(4), MTG(3), NET(2), QA2(1), PST(1) |
| K01 | I'm writing to ___ / I'm following up on ___ | EML(6) |
| K02 | Please find attached ___ / I've attached ___ | EML(4) |
| K03 | I'd appreciate it if ___ | EML(3) |
| K04 | Thank you for your ___ | EML(5) |
| K05 | Looking forward to ___ | EML(4), COL(2) |
| K06 | Apologies for ___ | EML(4) |
| K07 | Could you let me know ___? / Please let me know ___ | EML(6), ADM(1) |
| K08 | Would ___ work for you? | EML(3), MTG(1) |
| Z00 | (고정 표현 · chunk) | EML(52), DSC(48), PRE3(44), MTG(37), QA1(35), CHR(33), AGR(33), DIN(33), SML(32), PRE2(30), QA2(30), COL(29), NET(28), ASK(27), PUB(27), ARR(25), PST(24), ONL(19), PNL(18), PRE1(17), PRE4(16), BAS(15), SOC(14), RST1(13), TRB(13), AIR1(10), REP(9), TAX(9), RST2(9), SHP(9), MED(9), EXP(8), VST(7), FLT(6), CAF(6), AIR2(5), MET(4), DIR(4), HTL1(4), ADM(4), NUM(3), TRN(3), MON(3), COM(3), CAR(2), HTL2(2), SGT(2), REG(1), SVC(1) |

---

## 부록 C. 데이터 스키마와 검증 기록

### C.1 파일 구성

이 문서는 사람이 읽는 학습용 뷰이며, 원본 데이터는 함께 제공되는 세 파일에 있다. `speak_pattern_situations.csv`는 상황 단위 원장(行 = 상황 1개)이고, `speak_pattern_patterns.csv`는 패턴 사전, `speak_pattern_data.json`은 두 표와 카테고리 메타데이터를 묶은 HTML 사이트 직결용 번들이다. CSV는 UTF-8 BOM으로 저장되어 엑셀에서 한글이 깨지지 않는다. 표현을 수정·추가할 때는 CSV를 고치거나 원천 텍스트 레이어(`data/*.txt`)를 고친 뒤 재빌드하면 마크다운·JSON이 동시에 갱신된다.

### C.2 상황 원장 스키마 (`speak_pattern_situations.csv`)

| 열 | 형식 | 설명 |
|---|---|---|
| id | `영역-카테고리-NNN` | 불변 기본키. HTML 사이트의 진도·즐겨찾기·간격반복 기록 키 |
| domain | U / T / C | 공통 기반 / 여행 / 학회·연구 |
| category | 문자열 코드 | 예: AIR1, PRE3, PNL |
| category_title | 한국어 | 카테고리 제목 |
| pattern_id | A01 … K08, Z00 | 패턴 사전의 외래키 |
| pattern_template | 영어 | 패턴 틀 (조회 편의를 위한 비정규화 열) |
| situation_ko | 한국어 | 상황 설명 (인출 연습의 '문제' 면) |
| english | 영어 | 목표 표현 (인출 연습의 '정답' 면) |
| core | 0 / 1 | ★ 핵심 표현 여부 |

ID의 일련번호는 카테고리 내부에서 패턴 계열 순(A→K, Z00 마지막)으로 정렬한 뒤 부여된다. 따라서 데이터를 추가하고 재빌드하면 같은 카테고리의 번호가 밀릴 수 있다. 사이트에서 학습 기록을 장기 보존하려면 v1.0의 ID를 동결하고, 이후 추가분에는 별도 접미사(예: `T-AIR1-S01`)를 부여하는 방식을 권한다.

### C.3 HTML 학습 사이트 구현 권고

단일 HTML 파일로 구현할 경우 JSON 번들을 `<script>` 내부에 인라인으로 포함하면 외부 의존성 없이 동작한다. 기능 구성은 영역·카테고리·패턴 3중 필터와 ★ 토글을 갖춘 탐색 뷰, 한국어 상황을 먼저 보이고 영어를 가린 플래시카드 뷰(인출 연습), 브라우저 내장 Web Speech API(`speechSynthesis`, 언어 `en-GB`·`en-US` 선택)를 이용한 발음 듣기, 그리고 '틀림' 표시 항목을 1·3·7일 간격으로 다시 제시하는 간격반복 큐가 핵심이다. 간격반복 상태는 `localStorage`에 ID 기준으로 저장하되, 저장소가 비어 있어도 정상 동작하도록 예외 처리를 둔다. 패턴 뷰에서는 하나의 패턴을 선택했을 때 부록 B처럼 여러 카테고리의 예문이 한꺼번에 나열되도록 하면 '하나의 틀로 여러 장면을 해결한다'는 설계 의도가 화면에서 직접 드러난다.

### C.4 빌드 검증 기록

| 검증 항목 | 결과 |
|---|---|
| 총 상황 수 | 3092 (목표 ≥ 3,000 충족) |
| 고유 영어 표현 수 | 3029 (대소문자 무시 기준; 차이는 '카드로 결제할 수 있나요'처럼 여러 장소에서 같은 문장을 쓰는 정상 재사용) |
| 영역별 분포 | U 186 · T 1465 · C 1441 |
| 카테고리 / 패턴 | 49 / 114 |
| 핵심(★) 표현 | 296 |
| 레코드 필드 수 (3필드) | 전 레코드 통과 |
| 미정의 패턴 참조 | 0건 |
| 카테고리 내 중복 표현 | 0건 |
| 미사용 패턴 | 0건 |
| 빈 표현·구분자 혼입 | 0건 |

### C.5 근사·한계 고지

`[ADD]` 모든 영어 표현은 모델이 생성한 것으로, 원어민 검수를 거치지 않았다. 문법적 정확성과 구어적 자연성을 기준으로 선별했으나, 지역 변이(영국·미국·국제 영어)와 격식 수준에 따라 더 자연스러운 대안이 존재할 수 있다. 학회 발표용 문장은 실제 사용 전 원어민 동료의 확인을 권한다.

`[ADD]` Part 3 결과 설명 문장의 수치(kappa 0.82, AUC 0.89, 정확도 92 % 등)와 인명(Dr. Weber, Professor Rossi 등), 기관 예시는 **문형 학습을 위한 가상 예시**이며 어떤 실제 연구 결과도 지칭하지 않는다. 실전에서는 본인 연구의 값과 실명으로 교체해야 한다.

`[DOC]` 현지 제도 관련 상황(베를린 BER 공항의 C구역, 독일 빈병 보증금 Pfand, 오스트리아 고속도로 비넷, EU 항공 지연 보상, ETIAS)은 질문 문장의 소재로만 사용했다. 실제 요금·규정·시행 시점은 출발 전 공식 출처에서 확인해야 한다.

`[ADD]` ★ 지정은 출장 빈도와 실패 비용(못 했을 때의 불이익)을 기준으로 한 저자 판단이며, 빈도 코퍼스에 근거한 정량 순위는 아니다.
