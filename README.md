# Otomata

UTAU 보이스뱅크 **자동 원음설정(oto.ini)** 프로그램 — AI 기반 경계 검출로 oto.ini를 자동 생성합니다.

AI-powered automatic oto.ini generator for UTAU voicebanks.

> 🧪 **베타 버전입니다.** 오류가 있을 수 있으며, 피드백은 앱 내 *도움말 → 의견 보내기 / 버그 신고*로 보내주세요.

## 다운로드 / Download

👉 **[Releases](../../releases)** 페이지에서 최신 설치파일을 받으세요.

| 파일 | 대상 |
|---|---|
| `Otomata-x.x.x-Setup-GPU.exe` | **NVIDIA GPU** 사용자 (CUDA 가속, 용량 큼) |
| `Otomata-x.x.x-Setup-CPU.exe` | GPU가 없거나 NVIDIA가 아닌 경우 (용량 작음) |

어느 것을 받을지 모르겠다면 → **CPU 버전**을 받으세요. 어느 버전이든 기능은 동일하며, GPU 버전은 추론 속도만 빠릅니다.

### ⚠ Windows SmartScreen 경고가 뜨는 경우

베타 버전은 코드 서명이 없어 설치 시 파란색 SmartScreen 경고가 뜰 수 있습니다.
**「추가 정보」 → 「실행」** 을 누르면 설치가 진행됩니다.

If Windows SmartScreen appears, click **"More info" → "Run anyway"**.

## 시스템 요구사항 / Requirements

- Windows 10 / 11 (64-bit)
- GPU 버전: NVIDIA GPU (CUDA 12 지원 드라이버)

## 주요 기능 / Features

- 한국어(CV·VC / 연속음 VCV) · 일본어(단독음 / 연속음) 보이스뱅크 자동 원음설정
- 스펙트로그램 + 경계 시각 편집, 재생 미리듣기
- BPM 기반 / BPM 없는 녹음 모두 지원
- oto.ini 내보내기 · 자동저장 · 편집 상태(oto.omt) 보존

## 크레딧 / Credits

- 제작: [@matax2bi](https://x.com/matax2bi)
- 데이터 기여: 혜성 [@comet_UTAU](https://x.com/comet_UTAU)
- Built with PySide6 · librosa · matplotlib · ONNX Runtime
