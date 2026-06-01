# 레퍼런스 관리 정책

> 최종 수정: 2026-06-01

---

## 이 폴더의 역할

`reference/` 폴더는 캐릭터의 **공식 레퍼런스 이미지**만 보관합니다.  
이 폴더의 이미지는 모든 제작 작업의 기준이 되는 원본입니다.

---

## 현재 보관 이미지

| 파일명 | 내용 | 용도 |
|--------|------|------|
| `ttorong_character_sheet.png` | 또롱 캐릭터 시트 | 또롱의 공식 비주얼 기준 |
| `shoong_character_sheet.png` | 슝 캐릭터 시트 | 슝의 공식 비주얼 기준 |
| `duo_sheet.png` | 또롱 & 슝 듀오 시트 | 두 캐릭터의 관계 및 크기 기준 |

---

## reference vs assets — 차이점

| 구분 | reference/ | assets/ |
|------|-----------|---------|
| 목적 | 공식 기준 원본 보관 | 작업물 관리 |
| 수정 여부 | **절대 수정 금지** | 자유롭게 추가/이동 가능 |
| 내용 | 캐릭터 시트, 공식 승인 원본 | 시안, 완성본, 기각본 |
| 누가 관리 | 아트 디렉터만 | 누구나 |

---

## assets/ 하위 폴더 안내

작업 중인 이미지는 `assets/` 폴더를 사용합니다.

```
assets/
├── ttorong/
│   ├── concepts/     # 작업 중, 검토 전 이미지
│   ├── approved/     # 검수 통과, 공식 사용 가능
│   └── archive/      # 기각 또는 장기 보류
├── shoong/
│   ├── concepts/
│   ├── approved/
│   └── archive/
└── duo/
    ├── concepts/
    ├── approved/
    └── archive/
```

### concepts/ — 작업 중

- 아직 검수를 받지 않은 시안
- AI 생성 이미지, 초안 스케치 등
- 누구나 자유롭게 추가 가능
- 파일명 예시: `ttorong_happy_v1.png`, `ttorong_sitting_01.png`

### approved/ — 최종 승인

- 비주얼 DNA 검수를 통과한 이미지
- `bible/design_rules.md`의 체크리스트를 모두 통과한 것
- 공식 사용 가능 (이모티콘, 굿즈, SNS 등)
- `concepts/`에서 검수 후 이동
- 파일명 예시: `ttorong_happy_approved.png`

### archive/ — 기각 / 보류

- 비주얼 DNA 검수 불합격 이미지
- 방향성이 맞지 않아 보류된 이미지
- **삭제하지 않고 보관** — 나중에 참고하거나 수정의 기반이 될 수 있음
- 파일명 예시: `ttorong_wrong_ears_archived.png`

---

## 이모티콘 이미지 관리

이모티콘 이미지는 별도로 관리합니다.

```
emoticon/assets/
├── ttorong/
│   ├── concepts/   # 작업 중인 이모티콘 시안
│   └── approved/   # 카카오 제출 준비 완료
├── shoong/
└── duo/
```

---

## 굿즈 시안 관리

굿즈 시안 이미지는 별도로 관리합니다.

```
goods/assets/
├── keyring/    # 키링 시안
├── sticker/    # 스티커 시안
└── plush/      # 인형 시안
```

---

## 파일명 규칙

일관된 파일명을 사용합니다.

```
{캐릭터}_{감정/포즈/설명}_{버전}.{확장자}

예시:
ttorong_happy_v1.png
ttorong_waving_approved.png
shoong_running_v3.png
duo_together_concepts.png
```

- 한글 파일명 금지 (경로 오류 방지)
- 공백 금지, 언더스코어(_) 사용
- 버전 관리: v1, v2, v3 또는 날짜(20260601) 사용
