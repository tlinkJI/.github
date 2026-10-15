# 🏢 tlinkJI

통화 녹취, CRM, 메신저 솔루션을 개발하는 조직입니다.

---

## 📊 프로젝트 현황

### CRM 솔루션

| 프로젝트 | 설명 | 상태 |
|---------|------|:----:|
| **VoiceCRM** | 인바운드 CRM (로컬 Whisper STT) | ✅ 운영중 |
| **OSIS CRM** | 아웃바운드 보험영업 CRM | ✅ 운영중 |
| **TlinkNote** | 클라우드 CRM | ✅ 운영중 |

### 녹취 모듈

| 구분 | 프로젝트 | 상태 |
|------|---------|:----:|
| **엔진** | New_voice, New_voice_NCP, New_voice_pbx, All_CRM, All_CRM_STT | ✅ 운영중 |
| **웹서버** | new_voice_web, new_voice_web_ncp, Moidacar_voice | ✅ 운영중 |
| **클라이언트** | NewCallNote, CallNote_V2 | ✅ 운영중 |
| **모바일** | tlinkmobile | ✅ 운영중 |

### 통신/인프라

| 구분 | 프로젝트 | 상태 |
|------|---------|:----:|
| **PBX** | pbx_ami | ✅ 운영중 |
| **소프트폰** | tlinkpbx-phone | ✅ 운영중 |
| **메신저** | TlinkTalk / TlinkTalkWeb / electron_tlinktalk | 🔄 개발중 |
| **티링크온** | TlinkOn / TlinkOnApp | ✅ 운영중 |
| **알림** | CloudNote | ✅ 운영중 |

### 관리

| 프로젝트 | 설명 | 상태 |
|---------|------|:----:|
| **billing** | 과금관리 웹서버 | ✅ 운영중 |

### AI/협력 (봄소프트)

| 프로젝트 | 설명 | 상태 |
|---------|------|:----:|
| **Walkie** | 실시간 STT 서버 | 🔄 개발중 |
| **WhisperTrain** | Whisper 모델 학습 | 🔄 개발중 |

---

## 📦 저장소 구조

### 📞 VoiceCRM (운영중)

| 저장소 | 역할 | 기술스택 |
|-------|------|---------|
| `VoiceCrm` | 백엔드 API | Java (Spring Boot) |
| `VoiceCrm_front` | 프론트엔드 | JavaScript |
| `CallNote_V2` | 데스크톱 클라이언트 | Java (Spring Boot) |
| `NewCallNote` | 콜노트 신버전 | Java |

### 📊 OSIS CRM (운영중)

| 저장소 | 역할 | 기술스택 |
|-------|------|---------|
| `osis` | 백엔드 API | Java (Spring Boot) |
| `osis_front` | 프론트엔드 | JavaScript |
| `OsisClient` | 데스크톱 클라이언트 | Kotlin (Compose Multiplatform) |
| `OsisRelay` | 중계서버 | - |

### 📱 TlinkNote (운영중)

| 저장소 | 역할 | 기술스택 |
|-------|------|---------|
| `TlinkNoteApi` | 백엔드 API | Java (Spring Boot) |
| `TlinkNote` | 프론트엔드 | JavaScript |
| `TlinkNoteClient` | 데스크톱 클라이언트 | Electron |

### 🎙️ 녹취 모듈 (운영중)

| 구분 | 저장소 | 역할 |
|------|-------|------|
| 엔진 | `New_voice` | 녹취 엔진 (온프레미스) |
| 엔진 | `New_voice_NCP` | 녹취 엔진 (클라우드) |
| 엔진 | `New_voice_pbx` | 녹취 엔진 (클라우드 PBX) |
| 엔진 | `All_CRM` | 녹취 엔진 (화자분리X) |
| 엔진 | `All_CRM_STT` | 녹취 엔진 (화자분리O) |
| 웹서버 | `new_voice_web` | 웹서버 (온프레미스) |
| 웹서버 | `new_voice_web_ncp` | 웹서버 (클라우드) |
| 웹서버 | `Moidacar_voice` | 웹서버 (모이다카) |
| 클라이언트 | `NewCallNote` | 콜노트 신버전 |
| 클라이언트 | `CallNote_V2` | 콜노트 V2 |
| 모바일 | `tlinkmobile` | 모바일 앱 |

### 📡 통신/인프라

| 구분 | 저장소 | 역할 | 상태 |
|------|-------|------|:----:|
| PBX | `pbx_ami` | PBX API 서버 | ✅ 운영중 |
| 소프트폰 | `tlinkpbx-phone` | TlinkPBX 소프트폰 | ✅ 운영중 |
| 메신저 | `TlinkTalk` | 메신저 백엔드 | 🔄 개발중 |
| 메신저 | `TlinkTalkWeb` | 메신저 웹 | 🔄 개발중 |
| 메신저 | `electron_tlinktalk` | 메신저 데스크톱 | 🔄 개발중 |
| 티링크온 | `TlinkOn` | 티링크온 백엔드 | ✅ 운영중 |
| 티링크온 | `TlinkOnApp` | 티링크온 안드로이드 | ✅ 운영중 |
| 알림 | `CloudNote` | 웹소켓 통지 클라이언트 | ✅ 운영중 |
| 관리 | `billing` | 과금관리 웹서버 | ✅ 운영중 |

### 🎙️ AI/협력 (봄소프트)

| 저장소 | 역할 | 기술스택 |
|-------|------|---------|
| `Walkie` | STT 웹서버 | Java (Spring Boot) |
| `WhisperTrain` | Whisper 모델 학습 | Python |

### 🛠️ 문서/설정

| 저장소 | 역할 |
|-------|------|
| `doc` | 프로젝트 문서 및 가이드 |
| `.github` | 조직 프로필 및 설정 |

---

## 🔗 문서

자세한 프로젝트 정보는 [doc 저장소](https://github.com/tlinkJI/doc)를 참고하세요.

- [프로젝트 목표](https://github.com/tlinkJI/doc/blob/main/프로젝트목표.md)
- [로드맵](https://github.com/tlinkJI/doc/blob/main/로드맵.md)
- [릴리즈 이력](https://github.com/tlinkJI/doc/blob/main/릴리즈이력.md)
- [테크트리](https://github.com/tlinkJI/doc/blob/main/테크트리.md)

---

📅 *최종 업데이트: 2026-10-15*
