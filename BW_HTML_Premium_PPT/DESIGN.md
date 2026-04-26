---
version: alpha
name: "AI Graphic HTML PPT — Lunar Ivory"
description: "한국어 대학 1학년 수업용 15장 HTML PPT 슬라이드 덱을 한 번에 다시 만들기 위한 Design.md. 검은 배경, 아이보리 글자, 세리프 제목, 필기체 강조, 산세리프 본문, 배경 뒤 3D 오브와 궤도 애니메이션을 포함한다."
colors:
  primary: "#050505"
  secondary: "#121212"
  tertiary: "#F6F4EF"
  neutral: "#FFFFFF"
  surface: "#080808"
  surface-deep: "#020202"
  panel: "#111112"
  panel-strong: "#141415"
  panel-soft: "#1A1A1B"
  on-primary: "#F6F4EF"
  on-tertiary: "#080808"
  muted: "#A8A49C"
  quiet: "#6F6C66"
  faint: "#3C3A37"
  line: "#2A2A2E"
  line-strong: "#44413C"
  grid-line: "#1D1D1D"
  glow-soft: "#E8E0D2"
  orb-core: "#090909"
  orb-rim: "#F6F4EF"
  warning: "#C8BBA0"
typography:
  display-xl:
    fontFamily: "Noto Serif KR"
    fontSize: "96px"
    fontWeight: 700
    lineHeight: 0.98
    letterSpacing: "-0.073em"
  headline-lg:
    fontFamily: "Noto Serif KR"
    fontSize: "76px"
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: "-0.064em"
  headline-md:
    fontFamily: "Noto Serif KR"
    fontSize: "56px"
    fontWeight: 700
    lineHeight: 1.08
    letterSpacing: "-0.05em"
  headline-card:
    fontFamily: "Noto Serif KR"
    fontSize: "30px"
    fontWeight: 700
    lineHeight: 1.18
    letterSpacing: "-0.045em"
  script-accent:
    fontFamily: "Nanum Pen Script"
    fontSize: "46px"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  body-lg:
    fontFamily: "Noto Sans KR"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1.8
    letterSpacing: "-0.01em"
  body-md:
    fontFamily: "Noto Sans KR"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: "-0.01em"
  body-sm:
    fontFamily: "Noto Sans KR"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "-0.005em"
  label-caps:
    fontFamily: "Noto Sans KR"
    fontSize: "12px"
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.10em"
  ui-strong:
    fontFamily: "Noto Sans KR"
    fontSize: "17px"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "-0.01em"
  code-md:
    fontFamily: "ui-monospace"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.72
    letterSpacing: "0em"
rounded:
  none: "0px"
  sm: "10px"
  md: "14px"
  lg: "18px"
  xl: "30px"
  full: "9999px"
spacing:
  none: "0px"
  base: "8px"
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "34px"
  xxl: "48px"
  xxxl: "64px"
  slide-width: "1600px"
  slide-height: "900px"
  aspect-ratio: 1.7777778
  slide-padding-x: "74px"
  slide-padding-y: "58px"
  mobile-padding: "28px"
  card-gap: "18px"
  card-padding: "24px"
  panel-padding: "26px"
  nav-height: "46px"
  footer-height: "42px"
  icon-size: "38px"
  grid-columns: 12
  grid-gutter: "24px"
  safe-area: "64px"
components:
  slide-frame:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xl}"
    padding: "{spacing.slide-padding-x}"
    width: "{spacing.slide-width}"
    height: "{spacing.slide-height}"
  topbar:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label-caps}"
    rounded: "{rounded.none}"
    padding: "{spacing.md}"
    height: "{spacing.nav-height}"
  footer:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.muted}"
    typography: "{typography.label-caps}"
    rounded: "{rounded.none}"
    padding: "{spacing.md}"
    height: "{spacing.footer-height}"
  hero-title:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.tertiary}"
    typography: "{typography.display-xl}"
    rounded: "{rounded.none}"
    padding: "{spacing.none}"
  section-title:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.tertiary}"
    typography: "{typography.headline-lg}"
    rounded: "{rounded.none}"
    padding: "{spacing.none}"
  script-line:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.tertiary}"
    typography: "{typography.script-accent}"
    rounded: "{rounded.none}"
    padding: "{spacing.none}"
  card:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: "{spacing.card-padding}"
  card-highlight:
    backgroundColor: "{colors.panel-strong}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: "{spacing.card-padding}"
  button-primary:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.on-tertiary}"
    typography: "{typography.ui-strong}"
    rounded: "{rounded.sm}"
    padding: "{spacing.lg}"
    height: "56px"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.tertiary}"
    typography: "{typography.ui-strong}"
    rounded: "{rounded.sm}"
    padding: "{spacing.lg}"
    height: "56px"
  chip:
    backgroundColor: "{colors.panel-soft}"
    textColor: "{colors.muted}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.full}"
    padding: "{spacing.md}"
    height: "40px"
  icon-box:
    backgroundColor: "{colors.panel-soft}"
    textColor: "{colors.tertiary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: "{spacing.sm}"
    size: "38px"
  codebox:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.on-primary}"
    typography: "{typography.code-md}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  navigation-control:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.tertiary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.full}"
    padding: "{spacing.sm}"
    size: "44px"
  speaker-notes-panel:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
    width: "420px"
  orb-3d:
    backgroundColor: "{colors.orb-core}"
    textColor: "{colors.orb-rim}"
    rounded: "{rounded.full}"
    padding: "{spacing.none}"
    size: "660px"
---

# DESIGN.md — AI Graphic HTML PPT Slide System

이 문서는 새 세션에서도 같은 방향의 HTML PPT를 한 번에 만들 수 있도록 적어 둔 디자인 시스템이다. 최종 산출물은 **단일 HTML 파일**이어야 하며, 16:9 가로형 발표 슬라이드 15장, 한국어 본문, 발표자 메모, 키보드 이동, 전체화면, 인쇄/PDF 저장, 배경 뒤 3D 오브 애니메이션을 포함한다.

## Overview

이 디자인 시스템의 이름은 **AI Graphic HTML PPT — Lunar Ivory**다. 분위기는 “조용한 우주, 고급 발표 자료, 차분한 선생님의 설명”에 가깝다. 보는 사람은 대학교 1학년이며, 주제는 **AI 시대 Design.md를 활용한 그래픽 디자인의 활용 방법 및 가능성**이다.

발표 자료는 장식으로 감탄을 얻기보다, 학생이 내용을 잘 따라오게 만드는 것을 우선한다. 화면은 매우 어둡고, 글자는 아이보리 톤으로 또렷하게 보인다. 큰 제목은 세리프 글자로 무게감 있게 읽히고, 본문은 산세리프 글자로 쉽게 읽힌다. 필기체는 수업 선생님이 옆에서 짧게 덧붙이는 메모처럼 사용한다.

### Experience Goals

- 학생이 “AI 디자인은 어렵다”가 아니라 “기준을 적으면 나도 할 수 있다”고 느끼게 한다.
- Design.md를 어려운 개발 문서가 아니라 **AI에게 보여주는 디자인 약속장**으로 이해하게 한다.
- 매 슬라이드는 발표용 본문으로 바로 쓰일 수 있어야 하며, 슬라이드 안에 디자인 의도 설명이나 제작 안내 문구를 넣지 않는다.
- 그래픽 디자인 예시는 포스터, 카드뉴스, 발표 슬라이드, 개인/팀 프로젝트 브랜드, 썸네일, 행사 홍보물처럼 학생이 바로 떠올릴 수 있는 것으로 구성한다.
- 발표자는 친절한 선생님처럼 말한다. 어려운 단어를 쓰면 바로 쉬운 뜻을 붙인다.

### Product Format

- Output: one self-contained `html` file.
- Aspect ratio: 16:9.
- Target viewport: desktop projector first, mobile fallback second.
- Slide count: 15 slides.
- Language: Korean-first, with English labels only for short UI metadata.
- Tone: 친절한 선생님, 차분한 설명, 학생을 겁주지 않는 말투.
- Interaction: `←`, `→`, `Space`, `Home`, `End`, `N`, `F`, `P` keyboard controls.
- Print: `@page { size: 16in 9in; margin: 0; }` style PDF export.
- Notes: each slide has hidden speaker notes, opened with `N`.

## Colors

색은 거의 모두 검정, 차콜, 아이보리, 회색 계열로 유지한다. 강조색을 따로 많이 쓰지 않는다. 색으로 튀게 만들기보다, 크기·여백·구분선·빛으로 위계를 만든다.

- **Primary / Matte Black (`#050505`)**: 전체 발표의 가장 깊은 배경색이다. 화면의 중심이 되는 어둠이다.
- **Secondary / Charcoal (`#121212`)**: 카드, 패널, 배경 레이어에 쓴다. 완전한 검정과 구분되지만 튀지 않는다.
- **Tertiary / Ivory White (`#F6F4EF`)**: 제목, 주요 글자, 버튼 배경에 쓴다. 순백보다 부드럽다.
- **Neutral / Soft White (`#FFFFFF`)**: 아주 작은 하이라이트, 빛 가장자리, 3D 오브의 림 라이트에 제한적으로 쓴다.
- **Muted Gray (`#A8A49C`)**: 본문, 보조 설명, 발표자용 작은 메타 정보에 쓴다.
- **Quiet Gray (`#6F6C66`)**: 덜 중요한 라벨, 비활성 네비게이션, 설명 텍스트에 쓴다.
- **Line (`#2A2A2E`)**: 얇은 구분선과 카드 테두리에 쓴다.
- **Glow Soft (`#E8E0D2`)**: 오브 주변의 아주 약한 빛에 쓴다. 넓게 쓰면 안 된다.

### Color Application Rules

1. 한 슬라이드에서 배경 면적의 85% 이상은 검정 또는 차콜이어야 한다.
2. 흰색은 정보 전달을 위한 글자와 핵심 버튼에 먼저 배정한다.
3. 회색 본문은 너무 흐려지면 안 된다. 발표장 스크린에서 읽히는 밝기를 유지한다.
4. 색으로 장식하지 않는다. 필요한 경우 빛, 선, 여백으로만 분위기를 만든다.
5. 경고, 오류, 주의 같은 색상도 강한 빨강 대신 절제된 베이지 계열을 쓴다.

## Typography

글자 조합은 이 시스템의 중심이다. 세리프 제목, 산세리프 본문, 필기체 강조의 세 층으로 구성한다.

### Type Roles

- **Display / 큰 제목**: `Noto Serif KR`, 700 weight. 슬라이드의 주장을 크게 보여준다. 줄 수는 2~4줄 안에서 끝낸다.
- **Headline / 섹션 제목**: `Noto Serif KR`, 700 weight. 큰 제목보다 작지만 여전히 발표의 중심이다.
- **Body / 본문**: `Noto Sans KR`, 400 weight. 학생이 바로 이해할 수 있도록 문장을 너무 길게 만들지 않는다.
- **Label / 라벨**: `Noto Sans KR`, 700 weight, uppercase, letter spacing. 슬라이드 번호, 섹션명, 작은 UI 정보에 쓴다.
- **Script / 필기체 강조**: `Nanum Pen Script`. 한 슬라이드에 0~1회만 쓴다. 감성적인 보조 문장, 짧은 기억 문장에 쓴다.
- **Code / 예시 코드**: `ui-monospace`. Design.md 예시, 프롬프트 예시, YAML 조각에 쓴다.

### Korean Writing Rules

- 학생에게 처음 설명하는 말투로 쓴다.
- 어려운 용어는 바로 쉬운 뜻을 붙인다. 예: “디자인 토큰(색·글자·여백 같은 작은 기준값)”
- 한 문장에 개념을 너무 많이 넣지 않는다.
- 부정적인 경고보다 “이렇게 하면 더 잘 됩니다”라는 식으로 말한다.
- 발표용 슬라이드 본문에는 제작 과정 설명을 넣지 않는다. 슬라이드 자체가 수업 내용이어야 한다.

### Type Scale Guidance

- 표지 제목: 86–108px.
- 큰 내용 제목: 62–80px.
- 중간 제목: 44–62px.
- 카드 제목: 24–34px.
- 본문: 16–22px.
- 라벨: 10–13px.
- 필기체: 32–58px.

## Layout

슬라이드는 16:9 가로형 발표 화면에 맞춘다. 중앙의 큰 슬라이드 프레임 안에 모든 내용을 넣고, 바깥쪽 UI는 실제 발표에서는 최소화한다. 기존 HTML PPT의 구조처럼 각 장은 `section.slide`이며, 내부는 `topbar`, `content`, `footer`의 세 줄 구조를 유지한다.

### Slide Frame

- Width: `min(96vw, calc(96vh * 16 / 9))`.
- Aspect ratio: `16 / 9`.
- Desktop padding: 58px top, 74px left/right, 48px bottom을 기준으로 한다.
- Border radius: 30px.
- Border: 1px solid, 낮은 투명도의 아이보리 계열.
- Content rows: header / main / footer.
- Main content는 슬라이드마다 `two`, `two-wide-left`, `two-narrow`, `stack`, `center` 중 하나를 쓴다.

### Grid Rules

- 기본은 12컬럼 감각을 유지한다.
- 실제 CSS에서는 슬라이드마다 2컬럼, 3컬럼, 5컬럼, bento grid를 쓴다.
- 모든 정보 카드는 같은 패딩, 같은 테두리, 같은 모서리 둥글기를 공유한다.
- 한 슬라이드의 핵심 주장은 왼쪽 큰 제목에 두고, 오른쪽은 카드·예시·표로 풀어낸다.
- 3D 오브는 항상 내용 뒤에 있어야 한다. 글자와 겹치더라도 글자 읽힘을 방해하면 안 된다.

### Responsive Rules

- 980px 이하에서는 모든 그리드를 1컬럼으로 바꾼다.
- 모바일에서는 슬라이드가 `100vw × 100vh`로 꽉 차도 된다.
- 상단 네비게이션의 긴 항목은 숨기고, 로고와 햄버거만 남긴다.
- 카드가 많으면 세로로 쌓고, 오브는 오른쪽 뒤로 작게 밀어 넣는다.

## Elevation & Depth

이 시스템의 깊이는 강한 그림자가 아니라 **어둠 속에서 살짝 떠 있는 층**으로 만든다. 각 슬라이드는 배경, 프레임, 카드, 글자, 3D 오브의 순서로 깊이를 갖는다.

### Depth Layers

1. **Page Background**: 거의 검정에 가까운 전체 배경, 은은한 방사형 빛.
2. **Slide Frame**: 얇은 테두리와 내부 그림자로 살짝 떠 있는 느낌.
3. **Card Layer**: 반투명 차콜 패널, 얇은 테두리, 아주 약한 상단 하이라이트.
4. **Text Layer**: 제목은 가장 앞에 있고, 본문은 한 단계 뒤에 있다.
5. **3D Orb Layer**: 내용 뒤에 배치한다. 시각적 분위기를 만들지만, 본문보다 앞서면 안 된다.

### 3D Background Element

3D 요소는 사진이나 외부 이미지를 쓰지 않고 CSS 또는 `canvas`로 생성한다. 기본은 CSS 기반 오브를 권장한다.

Required elements:

- `.orb`: 커다란 원형 구체. `radial-gradient`, `conic-gradient`, `box-shadow`, `filter`, `transform-style`을 사용한다.
- `.orb::before`: 구체 가장자리의 림 라이트. 천천히 회전한다.
- `.orb::after`: 표면 질감. SVG noise data URI 또는 CSS noise를 사용한다.
- `.orbit`: 얇은 타원 궤도선. 작은 점 하나가 궤도 위에 있는 느낌을 만든다.
- `.grain`: 전체 슬라이드에 깔리는 아주 약한 입자 질감.

Motion rules:

- 오브는 8–14초 사이로 천천히 떠 있는 움직임을 가진다.
- 궤도선은 18–24초 정도로 아주 느리게 회전한다.
- 움직임은 수업 내용을 방해하면 안 된다.
- `prefers-reduced-motion: reduce`에서는 모든 애니메이션을 멈춘다.
- 3D 요소는 `z-index`를 낮게 두고, 글자를 가리지 않게 `opacity`와 `mask`를 조절한다.

Suggested CSS behavior:

```css
.orb {
  position: absolute;
  width: clamp(310px, 34vw, 660px);
  height: clamp(310px, 34vw, 660px);
  border-radius: 50%;
  background:
    radial-gradient(circle at 28% 22%, rgba(255,255,255,.42), rgba(255,255,255,.10) 12%, transparent 31%),
    radial-gradient(circle at 58% 52%, rgba(255,255,255,.045), transparent 54%),
    radial-gradient(circle at 35% 45%, #171717 0 28%, #090909 58%, #020202 76%);
  box-shadow:
    -10px -8px 18px rgba(255,255,255,.18),
    -36px 0 80px rgba(255,255,255,.06),
    inset -70px -50px 100px rgba(0,0,0,.88),
    inset 28px 12px 50px rgba(255,255,255,.05);
  animation: orbFloat 10s cubic-bezier(.22,1,.36,1) infinite alternate;
}
```

## Shapes

형태는 부드럽지만 과하게 둥글지 않다. 모든 사각형 요소는 조용한 라운드 코너를 갖는다.

- Slide frame: 30px.
- Card / panel: 18px.
- Mini card: 14–18px.
- Button: 10px.
- Chip: 9999px.
- Navigation circle: 50% / 9999px.
- Icon box: 12px.
- Orb: full circle.

형태 규칙:

1. 한 슬라이드 안에서 둥근 정도가 너무 다양하면 안 된다.
2. 카드와 패널은 같은 선 두께를 사용한다.
3. 버튼만 더 또렷한 대비를 가져도 된다.
4. 원형 요소는 오브, 궤도 점, 네비게이션 버튼처럼 제한된 곳에서만 쓴다.

## Components

### Slide Frame

슬라이드 전체를 감싸는 프레임이다. `border`, `box-shadow`, `inset shadow`, `grain`으로 깊이를 만든다. 배경은 완전한 단색이 아니라 아주 약한 빛과 질감이 있는 차콜이어야 한다.

### Topbar

상단에는 왼쪽 로고, 가운데 섹션 네비게이션, 오른쪽 시스템 라벨과 햄버거 아이콘을 둔다. 실제 발표 중에는 장식보다 현재 위치를 알려주는 역할이 중요하다.

Recommended items:

- Left: `Design.md` wordmark + `Graphic Design Class`
- Center: `01 시작`, `02 이해`, `03 실습`, `04 가능성`, `05 정리`
- Right: short English label such as `AI × GRAPHIC DESIGN`, `EXAMPLE 01`, `CHECKLIST`

### Footer

하단에는 왼쪽 슬라이드 성격, 가운데 짧은 기억 문장, 오른쪽 현재 장 번호를 둔다. 번호는 `01 / 15` 형식으로 쓴다.

### Cards

카드는 설명을 작은 단위로 나누는 기본 요소다. 카드 안에는 번호, 아이콘, 제목, 짧은 설명, 체크리스트가 들어갈 수 있다. 카드는 너무 밝으면 안 되며, 테두리와 내부 하이라이트만으로 구분한다.

### Buttons

발표 자료에서는 실제 클릭보다 “행동 제안”을 보여주는 역할이다. 표지와 마지막 장에서만 강하게 사용한다.

- Primary: 아이보리 배경, 검은 글자.
- Secondary: 투명 배경, 아이보리 테두리.
- Linkish: 밑줄만 있는 조용한 텍스트 링크.

### Codebox

Design.md 예시, 프롬프트 예시를 보여주는 상자다. 실제 코드처럼 보이지만 너무 기술적으로 어렵게 느껴지지 않도록 주석과 핵심어에만 차이를 준다.

### Speaker Notes

각 슬라이드에는 발표자가 볼 수 있는 메모를 넣는다. 슬라이드에는 짧게 쓰고, 메모에는 친절한 설명과 수업 진행 팁을 적는다.

### Deck Controls

브라우저 하단 오른쪽에 작은 조작 바를 둔다.

- Previous: `←`
- Next: `→`
- Indicator: `1 / 15`
- Notes: 발표자 메모 토글
- Full: 전체화면
- PDF: 인쇄/PDF 저장

## Do's and Don'ts

### Do

- Do keep every slide presentation-ready. 슬라이드 안에는 제작 설명이 아니라 발표 내용이 들어가야 한다.
- Do use one main idea per slide.
- Do write Korean body text in a friendly first-year student level.
- Do explain hard terms immediately with a short parenthetical meaning.
- Do use many examples: poster, card news, slide deck, team project, personal portfolio, event promotion, YouTube thumbnail.
- Do keep text readable on a projector.
- Do use the script font sparingly, ideally once per slide.
- Do make 3D effects slow, soft, and behind content.
- Do include speaker notes for every slide.
- Do make the deck usable without external image assets.
- Do preserve keyboard navigation and print/PDF support.

### Don't

- Don't put meta design commentary inside the presentation, such as “검은 배경과 흰 글자로 고급스럽게 구성했습니다.”
- Don't use bright gradients, neon colors, rainbow accents, emoji-heavy decoration, or busy backgrounds.
- Don't crowd a slide with long paragraphs.
- Don't use more than three type families.
- Don't let the 3D orb cover important text.
- Don't use English-heavy copy for the student-facing explanation.
- Don't make the deck a mockup. It must be ready for real lecture use.
- Don't make AI sound like magic. Explain that people set the direction and check the result.
- Don't skip responsibility topics: facts, copyright, readability, accessibility, respect.

## Slide Deck Content Blueprint

Create exactly 15 slides. Use the following Korean titles, intent, and layout direction. The copy should be friendly and detailed enough for a first-year university audience.

### Slide 01 — 시작

Title: `AI 시대, Design.md로 그래픽 디자인하기`

Purpose: 수업의 전체 주제를 연다. AI에게 바로 “예쁘게 해줘”라고 맡기지 않고, 먼저 기준을 적는다는 핵심을 알려준다.

Layout: two-wide-left. 왼쪽에는 큰 제목과 필기체 보조 문장, 오른쪽에는 “오늘의 핵심 문장” 패널을 둔다. 배경에는 큰 3D 오브를 둔다.

Key points:

- Design.md는 AI에게 보여주는 디자인 약속장이다.
- 오늘은 AI 도구를 완벽히 다루는 법보다, AI에게 생각을 잘 전달하는 법을 배운다.
- 결과물은 나만의 Design.md다.

Speaker note direction: 학생들이 어렵게 느끼지 않도록 “작은 노트도 Design.md가 될 수 있다”고 말한다.

### Slide 02 — AI와 사람의 역할

Title: `AI는 손이 빠르고, 우리는 방향을 정합니다.`

Purpose: AI와 사람의 역할을 나눈다.

Layout: stack + three cards.

Cards:

1. 사람이 잘하는 일: 대상, 인상, 우선순위, 책임.
2. AI가 잘하는 일: 빠른 시안, 변주, 반복, 형식 변환.
3. Design.md가 하는 일: 사람이 정한 방향을 AI가 계속 참고하게 한다.

Speaker note direction: “AI는 제작 조수, 사람은 감독”이라는 비유를 쓴다.

### Slide 03 — Design.md 정의

Title: `Design.md는 AI에게 보여주는 디자인 설명서입니다.`

Purpose: Design.md를 쉽게 정의한다.

Layout: left title + right codebox.

Codebox should show a short Korean DESIGN.md example:

```md
# DESIGN.md

## 1. 분위기
차분함, 신뢰감, 넓은 여백

## 2. 색
배경: #050505 / 글자: #F6F4EF

## 3. 글자
제목: 세리프 / 본문: 산세리프 / 강조: 필기체 한 줄

## 4. 금지 규칙
무지개 그라데이션 금지, 장식 과다 금지
```

Speaker note direction: `md`는 Markdown, 즉 글로 쓰는 간단한 문서 형식이라고 설명한다.

### Slide 04 — 프롬프트만 쓸 때의 문제

Title: `프롬프트만 쓰면 결과가 쉽게 흔들립니다.`

Purpose: “예쁘게 해줘”가 왜 부족한지 비교한다.

Layout: stack + compare panels.

Compare:

- Bad: `신입생 환영 포스터를 예쁘게 만들어줘.`
- Good: `@Design.md를 지키고, A4 포스터 3안을 만들어줘.`

Speaker note direction: “고급스럽게”라는 말이 사람마다 다르게 이해된다는 예시를 든다.

### Slide 05 — Design.md의 재료

Title: `Design.md의 7가지 재료`

Purpose: 학생이 바로 채울 수 있는 7칸을 알려준다.

Layout: bento grid.

Items:

1. 분위기 / 컨셉
2. 색
3. 글자
4. 여백 / 그리드
5. 이미지 스타일
6. 반복 요소
7. 금지 규칙

Speaker note direction: 처음에는 10줄짜리 규칙도 충분하다고 말한다.

### Slide 06 — UI 규칙을 그래픽 디자인으로 바꾸기

Title: `웹 화면의 규칙을 포스터와 카드뉴스에도 쓸 수 있습니다.`

Purpose: Design.md가 그래픽 디자인에도 유용하다는 점을 설명한다.

Layout: two-wide-left + table.

Table examples:

- 버튼 규칙 → 신청 안내, QR, 행사 링크
- 카드 컴포넌트 → 일정, 장소, 준비물 정보 박스
- 타이포그래피 → 제목·부제·본문·캡션 구분
- 레이아웃 그리드 → 포스터 안의 자리표
- 모션 원칙 → 릴스, 발표 전환, 영상 썸네일

Speaker note direction: 포스터도 색, 글자, 여백, 이미지, 정보 순서로 만들어진다고 말한다.

### Slide 07 — 예시 1: 동아리 모집 포스터

Title: `동아리 신입 모집 포스터 만들기`

Purpose: Design.md를 실제 포스터 작업에 쓰는 방법을 보여준다.

Layout: two-column, left explanation, right codebox + prompt panel.

Example request:

```text
@Design.md를 지켜서 대학 사진동아리 신입 모집 포스터 3안을 만들어줘.
A안은 차분하게, B안은 더 젊게, C안은 가장 미니멀하게.
모든 안에는 모집 기간, 장소, QR 위치가 분명히 보여야 해.
```

Check questions:

- 정보가 5초 안에 보이나?
- 동아리 분위기가 잘 느껴지나?
- QR과 날짜가 장식에 묻히지 않나?

Speaker note direction: 포스터는 예쁜 그림이 아니라 정보를 사람에게 도착시키는 물건이라고 말한다.

### Slide 08 — 예시 2: 카드뉴스 5장

Title: `카드뉴스는 “한 장 한 메시지”로 나눕니다.`

Purpose: 5장 카드뉴스의 구조를 보여준다.

Layout: mock-slide grid + three mini cards.

Five cards:

1. 표지: AI로 디자인할 때 가장 흔한 실수
2. 문제: “예쁘게”만 쓰면 결과가 흔들림
3. 해결: Design.md로 색·글자·여백 고정
4. 비교: 프롬프트만 쓴 결과와 기준이 있는 결과 비교
5. 행동: 내 프로젝트용 Design.md 7칸 채우기

Speaker note direction: 카드뉴스는 장마다 새로 디자인하지 않고, 공통 구조를 유지한다고 설명한다.

### Slide 09 — 예시 3: 발표 슬라이드

Title: `발표 슬라이드를 하나의 브랜드처럼 관리하기`

Purpose: 슬라이드 덱에도 Design.md가 적용된다는 점을 설명한다.

Layout: two-wide-left + 4 mini cards.

Rules:

- 표지: 큰 제목 1개, 필기체 부제 1개, 배경 비주얼 오른쪽.
- 설명: 왼쪽 큰 주장, 오른쪽 카드 2~3개.
- 예시: 문제 → 기준 → 요청 → 확인.
- 정리: 핵심 3개와 마지막 행동.

Speaker note direction: 슬라이드는 대본이 아니라 안내판이라고 설명한다.

### Slide 10 — 예시 4: 작은 브랜드 만들기

Title: `작은 프로젝트도 하나의 브랜드처럼 보이게 할 수 있습니다.`

Purpose: 팀 프로젝트, 개인 포트폴리오, 행사 홍보, 콘텐츠 채널을 예시로 든다.

Layout: two-narrow + formula panel.

Formula:

`핵심 문장 → 시각 규칙 → 여러 결과물`

Examples:

- 팀 프로젝트
- 개인 포트폴리오
- 행사 홍보
- 콘텐츠 채널

Speaker note direction: 브랜드는 큰 회사에만 있는 것이 아니라, 작은 프로젝트도 보는 사람에게 인상을 남긴다고 말한다.

### Slide 11 — 좋은 문장 쓰는 법

Title: `좋은 Design.md는 “느낌”보다 “판단 기준”이 많습니다.`

Purpose: 애매한 표현을 확인 가능한 문장으로 바꾸는 법을 알려준다.

Layout: compare panels + formula + four mini cards.

Bad sentence: `깔끔하고 예쁘게.`

Good sentence: `장식은 1개 이하, 제목은 2줄 이하, 정보는 카드 3개로 나눈다.`

Formula:

`[대상]에게 [남기고 싶은 인상]을 주기 위해 [구체적 규칙]을 쓴다.`

Speaker note direction: 감각을 규칙으로 바꾸는 훈련이 중요하다고 말한다.

### Slide 12 — AI에게 맡길 일 / 사람이 볼 일

Title: `AI에게 맡기기 좋은 일과 사람이 꼭 봐야 하는 일을 나눕니다.`

Purpose: AI 사용의 균형을 잡는다.

Layout: two large cards.

AI tasks:

- 같은 기준으로 시안 여러 개 만들기
- 포스터를 카드뉴스·배너·썸네일로 바꾸기
- 제목 후보, 문구 후보 뽑기
- 배치 변주 실험하기

Human tasks:

- 사실 정보 확인
- 편견과 무례함 확인
- 날짜, 장소, 가격, QR 확인
- 저작권, 상표권, 초상권 확인
- 최종 선택 이유 설명

Speaker note direction: AI는 조수이고 사람은 감독이라고 다시 강조한다.

### Slide 13 — 가능성

Title: `디자인을 공부하는 방식이 조금 달라집니다.`

Purpose: AI 시대 디자인 공부의 가능성을 정리한다.

Layout: two-wide-left + 4 mini cards.

Possibilities:

1. 취향을 언어로 바꾸기
2. 실패 비용 낮추기
3. 작은 디자인 시스템 만들기
4. 협업 언어 만들기

Speaker note direction: 도구를 잘 누르는 것보다 좋은 결과를 알아보는 눈과 설명하는 말이 중요하다고 말한다.

### Slide 14 — 주의할 점

Title: `멋있어 보여도, 발표 전에 한 번 더 확인합니다.`

Purpose: 책임 있는 AI 디자인 사용을 말한다.

Layout: five cards + small rubric.

Cards:

1. 저작권
2. 읽힘
3. 사실성
4. 접근성
5. 존중

Rubric:

- 목적
- 읽힘
- 일관성
- 윤리
- 수정성

Speaker note direction: 좋은 디자인은 보기 좋은 결과물과 책임 있는 확인이 함께 있어야 한다고 설명한다.

### Slide 15 — 20분 실습

Title: `오늘 바로 해보는 20분 Design.md 실습`

Purpose: 학생이 바로 해볼 수 있는 실습으로 마무리한다.

Layout: two-wide-left + step rows + large background orb.

Steps:

1. 3분: 만들 결과물 하나 정하기
2. 2분: 관객과 목적 쓰기
3. 2분: 디자인 키워드 3개 고르기
4. 7분: Design.md 7칸 채우기
5. 6분: AI 시안 3개 만들고 고치기

Speaker note direction: 완벽하게 만들려고 하지 말고, 다음 과제나 동아리 홍보물 하나로 작게 시작하라고 말한다.

## HTML PPT Build Contract

새 세션의 코딩 에이전트는 이 규칙을 지켜서 산출물을 만든다.

### File Requirements

- Produce one HTML file.
- Use inline CSS and inline JS.
- Load Google Fonts when possible:
  - `Noto Serif KR`
  - `Noto Sans KR`
  - `Nanum Pen Script`
- Provide font fallbacks so the deck remains usable without fonts loaded.
- Do not depend on image files.
- Do not depend on external JavaScript libraries.
- Use CSS-generated 3D orb, orbit, and grain. Canvas is allowed only if self-contained.
- Include `meta viewport`, Korean `lang="ko"`, and sensible `title`.

### Required DOM Structure

```html
<main id="stage">
  <section class="slide active" data-section="시작" data-title="...">
    <div class="grain"></div>
    <div class="orb"></div>
    <div class="orbit"></div>
    <header class="topbar">...</header>
    <div class="content ...">...</div>
    <footer class="footer">...</footer>
    <aside class="speaker-notes">...</aside>
  </section>
</main>
```

### Required JavaScript Behavior

- Store all slides in an array.
- Track `index`.
- `setSlide(i)` toggles `.active`.
- Update slide indicator and progress bar.
- Update notes panel from the active slide’s `.speaker-notes`.
- Keyboard:
  - `ArrowRight`, `PageDown`, `Space`: next slide.
  - `ArrowLeft`, `PageUp`: previous slide.
  - `Home`: first slide.
  - `End`: last slide.
  - `N`: notes panel.
  - `F`: fullscreen.
  - `P`: print/PDF.
- Hash navigation: `#1`, `#2`, ... `#15` should open the matching slide.

### Required CSS Behavior

- `html, body` should be `overflow: hidden` for presentation mode.
- `#stage` should center the active slide.
- `.slide.active` should use a subtle entrance animation.
- Use `@media print` to print every slide, not only active slide.
- Use `@media (max-width: 980px)` for mobile fallback.
- Use `@media (prefers-reduced-motion: reduce)` to stop animations.

### Accessibility

- Ensure high contrast between text and background.
- Keep body text large enough for classroom projection.
- Avoid important content in low-opacity text.
- Do not rely only on animation to communicate meaning.
- Speaker notes should not be printed.

## One-shot Build Prompt

아래 문장을 새 세션 첫 메시지로 그대로 사용할 수 있다.

```text
첨부한 DESIGN.md를 기준으로 “AI 시대 Design.md를 활용한 그래픽 디자인의 활용 방법 및 가능성”을 주제로 15장짜리 한국어 HTML PPT 슬라이드 덱을 만들어줘.

대상은 대학교 1학년이야. 굉장히 친절한 선생님처럼 설명해줘. 어려운 말은 쉬운 뜻을 바로 붙이고, 포스터·카드뉴스·발표 슬라이드·동아리 모집·개인 포트폴리오·팀 프로젝트 같은 예시를 적극적으로 넣어줘.

결과물은 목업이 아니라 발표에 바로 쓸 수 있는 단일 HTML 파일이어야 해. 각 슬라이드에는 실제 발표용 내용만 넣고, 디자인 의도를 설명하는 안내 문구는 슬라이드 본문에 넣지 마. 

기능은 다음을 반드시 포함해줘:
- 16:9 가로형 슬라이드 15장
- 검은 배경과 아이보리 글자 중심의 고급스러운 발표 디자인
- 세리프 제목, 산세리프 본문, 섬세한 필기체 강조
- 배경 뒤 3D 오브/행성 느낌의 CSS 애니메이션
- 키보드 이동: ← → Space Home End
- N: 발표자 메모
- F: 전체화면
- P 또는 PDF 버튼: 인쇄/PDF 저장
- 각 슬라이드별 발표자 메모
- 모바일 fallback
- print CSS

DESIGN.md의 토큰과 본문 지침을 우선 적용해서 만들어줘.
```

## Quality Checklist

완성된 HTML PPT는 다음 기준으로 확인한다.

- [ ] 15장이 모두 있다.
- [ ] 슬라이드 내용이 모두 한국어 중심이다.
- [ ] 대학 1학년이 처음 들어도 따라올 수 있다.
- [ ] Design.md를 “AI에게 보여주는 디자인 약속장”으로 쉽게 설명한다.
- [ ] 포스터, 카드뉴스, 발표 슬라이드, 작은 브랜드, 책임 있는 사용 예시가 들어 있다.
- [ ] 슬라이드 안에 디자인 시스템 안내 문구가 섞여 있지 않다.
- [ ] 모든 슬라이드에 발표자 메모가 있다.
- [ ] 3D 오브가 내용 뒤에 있고 글자 읽힘을 방해하지 않는다.
- [ ] 키보드 이동, 노트, 전체화면, PDF 인쇄가 작동한다.
- [ ] 인쇄하면 모든 슬라이드가 16:9 페이지로 나온다.
- [ ] 모바일 화면에서도 내용이 깨지지 않는다.
- [ ] `prefers-reduced-motion`에서 애니메이션이 멈춘다.
