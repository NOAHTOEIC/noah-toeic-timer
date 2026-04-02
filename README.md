# 📝 노아토익 타이머 (Noah TOEIC RC Timer)

토익 RC(Reading Comprehension) 시험에 최적화된 웹 타이머입니다.  
Part 5 → Part 6 → Part 7 → 마킹 순서로 자동 진행되며, 실전 감각을 키울 수 있습니다.

<br>

## ✨ 주요 기능

- **자동 순차 진행** — Part 5 → Part 6 → Part 7 → 마킹이 원 클릭으로 순서대로 진행
- **전체 시간 타이머** — 메인 화면에 전체 남은 시간 표시, 파트별 남은 시간도 동시 확인
- **맞춤 시간 설정** — 파트별 시간을 0분부터 자유롭게 설정 가능
- **초과시간 표시** — 설정 시간이 끝나면 빨간색 초과시간(+00:00)으로 전환
- **일시정지 / 다음 파트 스킵** — 상황에 맞게 유연하게 사용
- **파트별 TIP 표시** — 각 파트에 맞는 풀이 페이스 가이드 제공
- **종료 알림** — 파트 종료 시 알림음 + 진동
- **완료 분석** — 풀이 완료 후 파트별 소요 시간 분석 리포트
- **화면 꺼짐 방지** — Wake Lock API + 영상 재생 방식으로 모바일 화면 유지
- **PWA 지원** — 홈 화면에 추가하여 앱처럼 사용 가능

<br>

## 🕐 기본 시간 배분

| 파트 | 시간 | 문항 수 |
|------|------|---------|
| Part 5 | 10분 | 30문항 |
| Part 6 | 8분 | 16문항 |
| Part 7 | 52분 | 54문항 |
| 마킹 | 5분 | OMR 마킹 |
| **합계** | **75분** | **100문항** |

<br>

## 🚀 사용 방법

### 웹에서 바로 사용
GitHub Pages로 배포된 경우:
```
https://[사용자명].github.io/noah-toeic-timer/
```

### 로컬에서 실행
```bash
git clone https://github.com/[사용자명]/noah-toeic-timer.git
cd noah-toeic-timer
```
`index.html` 파일을 브라우저에서 열면 바로 사용할 수 있습니다.

### 모바일 앱처럼 사용 (PWA)
1. 모바일 브라우저(Chrome/Safari)에서 접속
2. **"홈 화면에 추가"** 선택
3. 앱 아이콘으로 바로 실행 가능

<br>

## 📁 프로젝트 구조

```
noah-toeic-timer/
├── index.html          # 메인 타이머 (HTML/CSS/JS 단일 파일)
├── manifest.json       # PWA 매니페스트
├── sw.js               # Service Worker (오프라인 지원)
├── icons/              # PWA 아이콘
│   ├── icon-192.png
│   └── icon-512.png
├── README.md
└── LICENSE
```

<br>

## 🛠 기술 스택

- **HTML / CSS / JavaScript** — 프레임워크 없이 순수 웹 기술로 구현
- **Web Audio API** — 알림 사운드 생성
- **Wake Lock API + Video Keep-alive** — 모바일 화면 꺼짐 방지
- **PWA (Progressive Web App)** — 오프라인 사용 및 홈 화면 설치 지원
- **Google Fonts** — Plus Jakarta Sans, Space Mono

<br>

## 📱 지원 브라우저

| 브라우저 | 지원 |
|---------|------|
| Chrome (모바일/데스크톱) | ✅ |
| Samsung Internet | ✅ |
| Safari (iOS 16.4+) | ✅ |
| Firefox | ✅ |
| Edge | ✅ |

<br>

## 📄 라이선스

MIT License — 자유롭게 사용, 수정, 배포할 수 있습니다.

<br>

## 🙋 기여

이슈나 개선 아이디어가 있다면 [Issues](../../issues) 탭에서 제안해주세요!

<br>

---

Made with ☕ for TOEIC 고득점을 향해 달리는 모든 분들
