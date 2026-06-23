# 🏢 tlinkJI

통화 녹취, CRM, 메신저 솔루션을 개발하는 조직입니다.

---

## 📊 프로젝트 현황

### CRM 솔루션

| 프로젝트 | 설명 | 상태 |
|---------|------|:----:|
| **VoiceCRM** | 인바운드 CRM (로컬 Whisper STT) | ✅ 운영중 |
| **OSIS CRM** | 아웃바운드 보험영업 CRM | ✅ 운영중 |

### 녹취 모듈

| 프로젝트 | 설명 | 상태 |
|---------|------|:----:|
| **녹취 모듈 (신버전)** | New_voice / new_voice_web / tlinkmobile | ✅ 운영중 |
| **녹취 모듈 (클라우드)** | NCP 클라우드형 | ✅ 운영중 |
| **녹취 모듈 (모이다카)** | 모이다카 커스텀 | ✅ 운영중 |

### 통신/인프라

| 프로젝트 | 설명 | 상태 |
|---------|------|:----:|
| **TlinkTalk** | 메신저 | 🔄 개발중 |
| **TlinkOn** | 티링크온 | 🔄 개발중 |
| **CloudNote** | 클라우드 웹소켓 통지 | 🔄 개발중 |

### AI 음성 (협력 - 봄소프트)

| 프로젝트 | 설명 | 상태 |
|---------|------|:----:|
| **Walkie** | 실시간 STT 서버 | 🔄 개발중 |
| **WhisperTrain** | Whisper 모델 학습 | 🔄 개발중 |
| **SoftPhone** | VoIP 소프트폰 | 🤝 협력중 |

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

### 🎙️ 녹취 모듈 (운영중)

| 저장소 | 역할 | 버전 |
|-------|------|------|
| `New_voice` | 녹취 엔진 (신버전) | v4.0.5 |
| `new_voice_web` | 웹서버 (신버전) | v2026.05.30 |
| `tlinkmobile` | 모바일 앱 | v14.0 |
| `All_CRM_STT` | 녹취 엔진 (화자분리) | v4.3.92 |
| `All_CRM` | 녹취 엔진 (레거시) | - |
| `New_voice_NCP` | 녹취 엔진 (NCP 클라우드) | - |
| `new_voice_web_ncp` | 웹서버 (NCP 클라우드) | - |
| `New_voice_moidacar` | 녹취 엔진 (모이다카) | v3.0.11 |
| `Moidacar_voice` | 웹서버 (모이다카) | - |

### 📡 통신/인프라

| 저장소 | 역할 | 기술스택 | 상태 |
|-------|------|---------|:----:|
| `pbx_ami` | PBX API 서버 | - | ✅ 운영중 |
| `TlinkTalk` | 메신저 백엔드 | Express, WebSocket | 🔄 개발중 |
| `electron_tlinktalk` | 메신저 데스크톱 | Electron | 🔄 개발중 |
| `TlinkOn` | 티링크온 백엔드 | - | 🔄 개발중 |
| `TlinkOnApp` | 티링크온 안드로이드 | Android | 🔄 개발중 |
| `CloudNote` | 웹소켓 통지 클라이언트 | - | 🔄 개발중 |

### 🎙️ AI 음성 (협력 - 봄소프트)

| 저장소 | 역할 | 기술스택 |
|-------|------|---------|
| `Walkie` | STT 웹서버 | Java (Spring Boot) |
| `WhisperTrain` | Whisper 모델 학습 | Python |
| `SoftPhone` | VoIP 소프트폰 | JavaScript (Electron) |

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

📅 *최종 업데이트: 2026-06-23*
