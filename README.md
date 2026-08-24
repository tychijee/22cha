# 22cha

![Last Commit](https://img.shields.io/github/last-commit/tychijee/22cha)
![Repo Size](https://img.shields.io/github/repo-size/tychijee/22cha)
![Top Language](https://img.shields.io/github/languages/top/tychijee/22cha)
![License](https://img.shields.io/badge/license-unspecified-lightgrey)

특허 due-diligence 및 영문 아티클 한글 정리를 위한 작업 저장소입니다.

## 폴더 구조

```
.
├── Inputs/                  # 처리 대상 원문(영문 아티클 등)
├── outputs/                 # 정리/분석 완료 결과물
└── docs/                    # 통합 정리 문서
```

## 주요 내용

### 1. 특허 Due-Diligence
- `outputs/특허예시.pdf` — 분석 원본(KIPRIS 국내 특허·실용신안 상세 인쇄 화면, 공개 정보)
- `outputs/KR1020227016657_analysis.md` — 위 원본에 대한 특허 분석 예시 결과물
- 특허 due-diligence 스킬 및 작업 지침서는 별도 저장소
  [tychijee/my-agent](https://github.com/tychijee/my-agent)로 분리되어 관리됩니다.

### 2. 영문 아티클 한글 정리
- `Inputs/01-mythos.md` — 처리 대상 영문 원문
- `outputs/01-mythos_completed.md`, `outputs/02-startups_completed.md` — 번역 + 핵심요약 +
  SNS 포스팅 초안으로 구성된 한글 통합 정리 결과물
- `docs/작업지침서_영문아티클_통합정리.md` — 정리 작업 지침

## 작업 로그
특허 스킬 관련 작업 이력은 [tychijee/my-agent](https://github.com/tychijee/my-agent) 저장소의
`docs/작업로그.md`에 기록됩니다.

## 참고
- 그 외 PDF 원본 파일(`test.pdf` 등)은 `.gitignore`에 의해 저장소에서 제외되어 있습니다.
