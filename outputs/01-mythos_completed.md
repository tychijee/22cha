# Anthropic 사이버 방어 프론티어 모델 확대 발표 정리

> ⚠️ 저작권 정책상 영어 원문 전체를 그대로 옮길 수 없어, 아래 "영어 원문" 섹션은 원문 링크와 핵심 포인트 개조식 정리로 대체했습니다. 한글 섹션 역시 문장 단위 직역이 아닌, 원문의 모든 내용을 빠짐없이 반영한 상세 정리본입니다.

---

## 1. 핵심 내용 요약

Anthropic이 최상위 모델 **Claude Mythos 5**를 사이버 방어 영역에 단계적으로 확대합니다. 핵심 전략은 "모델 직접 접근"이 아닌 "결과물만 제공"하는 방식으로 위험을 낮추는 것입니다.

- **파트너 도구 통합**: 방어자들이 이미 쓰는 보안 제품·서비스에 Mythos 5 임베드
- **Claude Security + Mythos 5**: Enterprise 고객 대상, 코드베이스 취약점 스캔 및 패치 제안 (기존 플랜 내 표준 과금, 별도 add-on 없음)
- **Defender Advantage Fund (0xDAF)**: 오픈소스 보안 지원용 3,500만 달러 규모 크레딧 펀드 신설
- **Cyber Verification Program 확대**: 검증된 보안팀 대상, Opus/Sonnet 완화 안전장치 → Mythos급까지 단계적 확대
- 4월 시작된 **Project Glasswing**(정부·핵심 인프라 방어 조직 대상 조기 제공 프로그램)의 후속 조치

---

## 2. SNS 포스팅 초안 (3가지 유형)

### ① 실무 밀착형 (보안/개발 실무자 대상)

Anthropic이 Claude Security 스캔에 최상위 모델 Mythos 5를 적용했습니다.

- 코드베이스 취약점 자동 스캔
- CWE 분류·심각도·신뢰도 등급 제공
- 패치 제안 → Claude Code에서 반영
- 별도 과금 없이 Enterprise 플랜 내 포함
- 최종 반영은 반드시 사람 승인 필요

보안팀 워크플로우에 실질적으로 편입되는 사례라 주목할 만합니다.

[원문 URL]

---

### ② 산업 특화형 (오픈소스/보안 생태계 대상)

오픈소스 보안 지원을 위한 3,500만 달러 규모 펀드가 신설됐습니다.

- 명칭: Defender Advantage Fund(0xDAF)
- 형태: 현금이 아닌 Claude 크레딧 지원
- 목적: 취약점 패치, 스캔·패치 자동화, 신규 보안 접근법 실험
- 우선 소수 파일럿 지원부터 시작

자원 부족한 오픈소스 메인테이너들에게 실질적 도움이 될지 지켜볼 지점입니다.

[원문 URL]

---

### ③ 트렌드 큐레이션형 (AI 산업 전반 관심자 대상)

프론티어 AI를 안전하게 푸는 방식이 눈에 띕니다.

- 모델 직접 접근 대신 결과물만 제공
- 파트너 보안 툴에 임베드하는 간접 배포
- 검증된 조직부터 단계적 접근 확대
- 정부·핵심 인프라 대상 Project Glasswing 연계

'더 강력한 모델 = 더 정교한 안전장치'라는 흐름을 보여주는 사례입니다.

[원문 URL]

---

## 3. 한글 번역본 (전체 상세 정리)

**Anthropic, 사이버 방어를 위한 프론티어 모델 확대 발표**

Anthropic이 더 많은 팀이 사이버 방어에 프론티어급 AI 능력을 활용할 수 있도록 하는 노력을 소개합니다. Claude Mythos 5가 Claude Security에 도입되었으며, 곧 파트너사의 사이버 방어 도구에도 적용될 예정입니다. 또한 오픈소스 소프트웨어 보안을 지원하기 위한 3,500만 달러 규모의 펀드를 신설하고, Cyber Verification Program 확장 계획도 공유합니다.

**배경 — Project Glasswing**

지난 4월, Anthropic은 Project Glasswing을 통해 가장 강력한 프론티어 모델인 Claude Mythos Preview(및 후속 모델 Claude Mythos 5)를 세계에서 가장 중요한 소프트웨어를 보호하는 소수의 조직에 제공했습니다. 이는 유사한 능력을 가진 모델이 일반에 공개되거나 악의적 행위자의 손에 들어가기 전에, 방어자들이 취약점을 찾아 수정할 수 있는 시간을 벌어주기 위함이었습니다.

목표는 항상 Mythos급 방어 능력을 안전하게 제공할 수 있는 만큼 최대한 많은 방어자에게 확대하는 것이었습니다. 이를 위해 Mythos급 모델의 공격적 사이버 능력이 악용되지 않도록 하면서도 접근성을 넓힐 수 있는 안전장치와 분류기를 개발해왔습니다. Claude Fable 5는 그 첫 단계로, 이중용도(dual-use) 사이버 작업을 차단하면서 모델을 광범위하게 사용할 수 있게 했습니다.

**이번 발표의 핵심 내용**

가장 위험한 상황은 사용자가 모델에 직접 접근할 수 있어 악의적 행위자가 모델을 유해한 방향으로 유도하려 시도할 때 발생합니다. 반면 사용자가 취약점 패치나 보안 경고 같은 특정 결과물만 받을 수 있다면 위험은 훨씬 낮아집니다. 이번 발표는 모델에 대한 직접 접근에는 적절한 가드레일을 유지하면서, 방어 관련 결과물에 대한 접근성은 넓히는 데 초점을 둡니다.

1. **파트너 도구에 Claude Mythos 5 통합**: 방어자들이 이미 사용 중인 제품·서비스에 Claude Mythos 5를 통합하기 위해 사이버보안 기술·서비스 파트너들과 협력 중입니다.
2. **Claude Security 스캔에 Mythos 5 적용**: Claude Enterprise 고객은 이제 Claude Security에서 최상위 모델을 실행해 코드베이스의 보안 취약점을 스캔하고 패치를 제안받을 수 있습니다.
3. **오픈소스 보안을 위한 3,500만 달러 크레딧**: 신설된 Defender Advantage Fund(0xDAF)는 오픈소스 프로젝트의 취약점 패치, 스캔·패치 프로세스 자동화, 새로운 보안 접근법 실험 등을 수행하는 조직에 3,500만 달러 규모의 크레딧을 제공합니다.
4. **Cyber Verification Program 확대**: 이 프로그램은 이미 검증된 방어자들에게 Opus 및 Sonnet 모델에서 완화된 안전장치를 제공하고 있습니다. 앞으로 몇 주 내에 Opus·Sonnet에서의 이중용도 능력을 더 넓히고, 이후 Mythos급 접근도 뒤따를 예정입니다.

Anthropic은 AI 모델이 점점 강력해지는 속도와 요구에 조직들이 적응할 수 있도록 계속해서 안전장치, 접근 프로그램, 커뮤니티 지원을 발전시켜 나갈 계획입니다.

---

**기존 사이버 방어 도구에 Mythos 통합하기**

병원, 유틸리티, 금융 시스템, 소프트웨어 공급망을 방어하는 팀들은 이미 보안 운영, 사고 대응, 위협 인텔리전스, 탐지 엔지니어링을 위한 다양한 제품·서비스를 활용하고 있습니다. 프론티어 능력을 방어자들에게 가장 빠르게 제공하는 방법은 Mythos급 모델을 그들이 이미 쓰고 있는 도구에 통합하는 것입니다.

이미 많은 파트너가 Claude Opus 기반으로 보안팀의 알림 분류, 위협 식별, 취약점 대응 속도를 높이는 사이버 제품을 구축했습니다. Anthropic은 이들 파트너 및 추가 파트너와 함께 Claude Mythos 5를 제품·서비스에 통합해 Mythos급 방어 성과를 고객에게 제공하려 하고 있습니다.

최종 사용자가 이러한 제품을 이용할 때는 Mythos와 직접 상호작용하지 않습니다. 대신 특정 작업을 위해 백그라운드에서 Mythos를 실행하는 맞춤형 인터페이스를 통해 작업하며, 해당 제품이 제공하도록 설계된 특정 결과물만 받습니다. 예를 들어 취약점 대응 도구는 결과물로 제안된 패치 목록을 제공할 수 있습니다. 이 결과물은 Mythos가 생성하지만, 사용자가 모델에게 취약점 익스플로잇 개발 등을 요청할 방법은 없습니다. Anthropic과 파트너들은 모델이 의도된 범위 내에서 작동하도록 남용 방지 조치도 마련해두고 있습니다.

이 작업은 아직 초기 단계이며 시간이 지나며 확대될 예정입니다. 보안 제품·서비스를 개발하며 고객에게 Claude Mythos 5를 제공하고자 하는 경우, 관심 등록이 가능합니다.

---

**Enterprise 고객 대상 Claude Security와 Mythos 5 연동**

오늘부터 Claude Security 스캔은 Claude Mythos 5로 실행됩니다. Claude Security는 코드베이스를 스캔해 취약점을 찾고 사람이 검토할 패치를 제안하며, 현재 Claude Enterprise 고객 대상 퍼블릭 베타로 운영 중입니다. Mythos 5를 활용한 스캔은 별도 부가 상품 없이 기존 플랜의 표준 토큰 사용량으로 청구됩니다.

Enterprise 관리자는 admin console에서 Claude Security를 활성화할 수 있습니다. claude.ai/security에서 사용자는 저장소를 선택해 Claude Mythos 5로 스캔할 수 있으며, Claude는 코드베이스를 스캔한 뒤 각 발견 사항에 대해 CWE(Common Weakness Enumeration) 분류, 신뢰도·심각도 등급, 제안된 수정안을 함께 제공합니다.

이후 사용자는 웹에서 Claude Code를 열어 수정 사항을 반영할 수 있습니다. 대화형 패치 작업은 조직이 Claude Code에서 접근 권한을 가진 모델을 사용합니다. Mythos 스캔 자체가 다른 플랫폼으로 Mythos 접근 권한을 확장하는 것은 아닙니다. 모든 패치는 적용 전 반드시 사람의 검토와 승인을 거쳐야 합니다.

Claude Security는 Mythos 5를 사용해 사용자가 소유한 코드를 스캔하고, 원본(raw) 출력이 아닌 상세한 결과만 반환함으로써 모델 자체를 노출하지 않습니다. 이를 통해 방어자들은 모델이 악용될 걱정 없이 Claude Mythos 5의 능력을 활용할 수 있습니다.

Claude Security에 대한 자세한 내용은 시작 가이드를 참고할 수 있습니다.

---

**오픈소스 소프트웨어 보안을 위한 Defender Advantage Fund 출범**

세계에서 가장 널리 쓰이는 프로그램 중 상당수는 오픈소스 소프트웨어로 운영됩니다. 하지만 이런 프로젝트들은 종종 자원봉사자나 비영리 재단이 관리하며, 공격으로부터 프로젝트를 종합적으로 방어할 자원이나 인력이 부족한 경우가 많습니다. Project Glasswing을 통해 Anthropic은 오픈소스 보안 단체에 400만 달러를 직접 기부했고, 프로그램에 참여한 오픈소스 보안 재단들에 크레딧을 제공했으며, 널리 쓰이는 프로젝트의 스캔·패치를 지원하고 Akrites, Gold Eagle 같은 협업 취약점 대응 노력을 지원했습니다.

새롭게 출범한 Defender Advantage Fund(0xDAF)는 이 작업을 이어받아, 오픈소스 유지관리자들이 소프트웨어를 보호하도록 돕는 조직들에 3,500만 달러 규모의 Claude 크레딧을 제공합니다. 지원금은 세 가지 영역에 집중됩니다: 널리 쓰이는 프로젝트의 활성 취약점 패치, 다른 프로젝트도 복제할 수 있는 방식의 스캔·패치 자동화, 그리고 프로젝트가 특정 유형의 공격 전반에 강해지도록 하는 더 야심 찬 보안 접근법 지원입니다.

우선 소수의 대규모 파일럿 지원금부터 시작해 무엇이 효과적이고 확장 가능한지 파악할 계획이며, 초기 수혜 대상에 대한 세부 내용은 향후 몇 주 내에 공유할 예정입니다.

---

**Cyber Verification Program 확대**

현재까지 Cyber Verification Program은 Claude Opus 및 Sonnet 모델 사용 시 조직들에 이중용도 능력에 대한 접근을 제공해왔습니다. 프로그램에 참여한 조직들은 완화된 안전장치를 경험하며, 자신들이 권한을 가진 시스템에서 정당한 사이버보안 작업을 수행하는 승인된 팀의 업무 방해를 최소화합니다.

앞으로 몇 주에 걸쳐 이 프로그램은 Claude Mythos에 대한 안전장치가 적용된 접근으로 확대될 예정입니다. 이에 따라 취약점 분류·검증 같은 방어적 능력은 Mythos급 모델까지 확대되고, 사이버 방어자들은 Claude Opus 및 Sonnet급 모델에서 차단이 줄어드는 것을 경험하게 됩니다. 또한 미국 정부 파트너들과의 협력을 통한 Project Glasswing을 통해 Claude Mythos 접근을 계속 확대하고 있으며, 이는 엄격한 보안 통제 요건을 충족하는 핵심 인프라 보호 기관들을 대상으로 합니다.

Cyber Verification Program 확대에 대한 자세한 내용은 향후 몇 주 내에 추가로 공유할 예정입니다. 그동안 정당한 사이버보안 업무를 수행하는 모든 보안팀은 Claude Opus 및 Sonnet 모델에서 완화된 안전장치를 위해 프로그램에 지원하는 것을 권장합니다. 이미 등록되어 승인받은 경우 별도 조치는 필요 없으며, 업데이트 사항이 있을 시 연락드릴 예정입니다.

---

## 4. 영어 원문 안내

> 저작권 정책상 원문 전체를 그대로 게재할 수 없습니다. 아래에 SNS 포스팅 시 첨부할 **원문 URL 자리**와, 원문의 섹션별 핵심 포인트만 개조식으로 남겨둡니다. 실제 게시 시 원문 링크를 채워 넣어 주세요.

- 원문 URL: `[여기에 원문 링크 입력]`

**Section-by-section key points (for reference only, not verbatim):**
- Intro: Claude Mythos 5 rollout to Claude Security; upcoming partner integrations; $35M open-source security fund; Cyber Verification Program expansion
- Background: Project Glasswing (April launch); Claude Fable 5 as broad-access dual-use-blocked model
- Core changes: (1) partner tool integration, (2) Claude Security + Mythos 5, (3) Defender Advantage Fund (0xDAF), (4) Cyber Verification Program expansion
- Partner integration details: purpose-built interfaces, output-only access, abuse prevention measures
- Claude Security details: admin console setup, CWE categorization, human review requirement, standard token billing
- 0xDAF details: $4M prior direct donations via Glasswing, new $35M in credits, three grant focus areas, pilot-first approach
- Cyber Verification Program details: existing reduced safeguards on Opus/Sonnet, planned Mythos-class expansion, Glasswing/government collaboration continuation

---

*본 문서는 대화 중 제공된 원문 문서를 바탕으로 정리한 요약·번역·SNS 콘텐츠 초안입니다.*
