# FALCON Choir Analyzer — PWA

SATB 실시간 음향 분석 · Midas M32 페이더 가이드  
핸드폰 홈화면 설치형 앱 (PWA)

---

## 📦 파일 구성

```
index.html      ← 메인 앱
manifest.json   ← PWA 설정
sw.js           ← 서비스워커 (오프라인 지원)
icon-192.svg    ← 앱 아이콘
icon-512.svg    ← 앱 아이콘 (대형)
```

---

## 🚀 GitHub Pages 배포 (5분)

1. **github.com** 로그인 → **New repository**
2. Repository name 입력 (예: `choir-analyzer`) → **Create**
3. 파일 5개 모두 업로드 (Add file → Upload files)
4. **Settings** → **Pages** → Branch: `main` / `/(root)` → **Save**
5. 잠시 후 아래 주소로 접속:
   ```
   https://[내아이디].github.io/choir-analyzer/
   ```

---

## 📱 핸드폰에 설치

### Android (Chrome)
1. 위 주소 접속
2. 주소창 우측 ⋮ → **홈 화면에 추가**
3. 앱처럼 실행됨

### iPhone (Safari)
1. Safari로 위 주소 접속
2. 하단 공유 버튼 → **홈 화면에 추가**
3. 앱처럼 실행됨

---

## 🎙 기능

| 탭 | 내용 |
|----|------|
| 채널 | S/A/T/B 개별 dBFS, VU미터, 음정, 파트 상태 배지 |
| 스펙트럼 | 4파트 주파수 오버레이 + 밸런스 비율 |
| 가이드 | M32 페이더 조정 수치 실시간 안내 |
| 녹음 | 전체 녹음 → 재생 → 저장 |

---

## ⚠️ 주의

- **HTTPS 필수** — 마이크는 보안 출처에서만 동작 (GitHub Pages는 자동 HTTPS)
- 현재 마이크 1개를 4파트 공유 분석 (실제 4마이크 환경으로 확장 가능)
