# 또롱 & 슝

**우주에서 가장 느린 곰과 우주에서 가장 빠른 토끼의 이야기.**

---

또롱은 오늘도 하늘을 바라봅니다.  
슝은 오늘도 어딘가로 달려갑니다.  
둘은 정반대지만, 함께라서 완벽합니다.

---

## 또롱 (TTORONG)

> *"또롱?"*

우주 전체를 상징하는 행성곰.  
크림 화이트 몸, 보라와 파랑의 행성 귀, 가슴의 별 목걸이, 초승달 꼬리.

호기심이 많고 관찰을 좋아합니다.  
생각이 많아서 행동이 느리지만, 궁금한 건 절대 그냥 지나치지 않습니다.  
우주의 고요함을 닮은 탐험가입니다.

→ [`bible/ttorong.md`](bible/ttorong.md)

---

## 슝 (SHOONG)

> *"슝! 일단 가보자!"*

수성에서 온 토끼.  
순백의 몸, 민트 스카프, 고글, 번개 꼬리, 유성처럼 흐르는 귀.

생각보다 몸이 먼저 움직입니다.  
또롱이 "또롱?" 하면 슝은 이미 달려가고 있습니다.  
우주에서 가장 빠른 존재입니다.

→ [`bible/shoong.md`](bible/shoong.md)

---

## 세계관

또롱과 슝은 **우주마을**에 삽니다.  
별이 늘 보이고, 빠른 것과 느린 것이 공존하는 작은 우주 공동체.

> *"또롱이 없으면 궁금한 걸 놓칠지도 몰라!"* — 슝  
> *"슝이 없으면 새로운 걸 발견할 수 없어!"* — 또롱

→ [`bible/world.md`](bible/world.md)

---

## 로드맵

| Phase | 목표 | 상태 |
|-------|------|------|
| 1 | 캐릭터 바이블 & 저장소 구축 | ✅ 완료 |
| 2 | 카카오 이모티콘 출시 (또롱 단독) | 진행 중 |
| 3 | 굿즈 출시 (키링, 스티커, 인형) | 예정 |
| 4 | 숏폼 애니메이션 & 웹툰 | 예정 |

---

## 저장소 구조

```
ttorong-ip/
├── bible/                        # 캐릭터 & 세계관 바이블
│   ├── ttorong.md                # 또롱 캐릭터 바이블
│   ├── shoong.md                 # 슝 캐릭터 바이블
│   ├── world.md                  # 세계관 설정
│   └── design_rules.md           # 디자인 원칙 (필독)
│
├── reference/                    # 공식 레퍼런스 이미지
│   ├── README.md                 # 레퍼런스 관리 정책
│   ├── ttorong_character_sheet.png
│   ├── shoong_character_sheet.png
│   └── duo_sheet.png
│
├── assets/                       # 캐릭터 일러스트 에셋
│   ├── ttorong/
│   │   ├── concepts/             # 작업 중인 시안
│   │   ├── approved/             # 최종 승인
│   │   └── archive/              # 기각 / 보류
│   ├── shoong/
│   └── duo/
│
├── emoticon/                     # 이모티콘
│   ├── expressions.md            # 감정 표현 기준표 (필독)
│   ├── ideas.md                  # 아이디어 목록
│   ├── kakao_submission.md       # 카카오 제출 체크리스트
│   └── assets/
│       ├── ttorong/
│       │   ├── concepts/
│       │   └── approved/
│       ├── shoong/
│       └── duo/
│
├── goods/                        # 굿즈 기획
│   ├── keyring.md
│   ├── sticker.md
│   ├── plush.md
│   └── assets/
│       ├── keyring/
│       ├── sticker/
│       └── plush/
│
└── lore/
    └── stories.md                # 단편 에피소드
```

---

## 운영 원칙

- **모든 제작 전** `bible/design_rules.md` 확인 필수
- **캐릭터는 또롱과 슝, 2명으로 고정** — 추가는 Phase 3 이후 검토
- 작업 중 이미지 → `concepts/` | 승인된 이미지 → `approved/` | 기각 → `archive/`
- 레퍼런스 이미지는 `reference/` 에만 보관, 수정 금지

---

*우주는 우리의 놀이터. 또롱? 슝! 오늘도 출발~*
