# 🏢 tlinkJI 조직 가이드

## 📦 저장소 (Repositories) 구조

### 🎙️ 음성/AI
- **`Walkie`** - STT 웹서버
  - 기술스택: Java (Spring Boot)
  - 역할: STT 데이터 수신 및 실시간 조회 API 서버

- **`WhisperTrain`** - Whisper 학습
  - 기술스택: Python
  - 역할: Whisper 모델 학습 및 Fine-tuning

- **`voice_ai`** - 음성 AI
  - 기술스택: Python
  - 역할: 음성 인식 및 AI 처리 모듈

### 📞 VoiceCRM
- **`VoiceCrm`** - 백엔드
  - 기술스택: Java (Spring Boot)
  - 역할: 음성 CRM API 서버

- **`VoiceCrm_front`** - 프론트엔드
  - 기술스택: JavaScript
  - 역할: 음성 CRM 사용자 인터페이스

### 📱 모바일 애플리케이션
- **`tlinkmobile`** - 모바일 CRM V2
  - 기술스택: Kotlin (Android)
  - 역할: 콜노트 모바일 어플리케이션 V2

- **`MobileCRM`** - 모바일 CRM V1
  - 기술스택: Java (Android)
  - 역할: 콜노트 모바일 어플리케이션 V1

### 💬 메신저
- **`TlinkTalk`** - 백엔드 서버
  - 기술스택: JavaScript (Express, WebSocket)
  - 역할: 메신저 API 서버 및 실시간 통신

- **`electron_tlinktalk`** - 데스크톱 클라이언트
  - 기술스택: JavaScript (Electron)
  - 역할: 데스크톱 메신저 클라이언트

### 📊 OSIS CRM
- **`osis`** - 백엔드
  - 기술스택: Java (Spring Boot)
  - 역할: 보험 영업 CRM API 서버

- **`osis_front`** - 프론트엔드
  - 기술스택: JavaScript
  - 역할: 보험 영업 CRM 사용자 인터페이스

### 💼 콜노트
- **`CallNote_V1`** - 통화 노트 V1
  - 기술스택: Java (Spring Boot)
  - 역할: 통화 기록 및 메모 관리

- **`CallNote_V2`** - 통화 노트 V2
  - 기술스택: Java (Spring Boot)
  - 역할: 통화 기록 및 메모 관리 (개선 버전)

### 🔄 녹취 모듈
- **`All_CRM_V1`** - 녹취 솔루션 V1
  - 기술스택: Java
  - 역할: RTP/SIP 패킷 처리, FTP 백업, 음성 파일 복구

- **`All_CRM_V2`** - 녹취 솔루션 V2
  - 기술스택: Java
  - 역할: 성능 최적화된 통화 복구 시스템

### 📞 소프트폰
- **`SoftPhone`** - 소프트폰 클라이언트
  - 기술스택: JavaScript (Electron)
  - 역할: VoIP 소프트폰 데스크톱 애플리케이션

### 🛠️ 조직/문서
- **`doc`** - 문서 저장소
  - 역할: 프로젝트 문서 및 가이드

- **`.github`** - 조직 설정
  - 역할: 조직 프로필, 이슈 템플릿, 워크플로우

---
