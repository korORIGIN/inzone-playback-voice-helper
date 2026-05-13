# Release Upload Guide

## 최종 배포 파일

업로드할 파일은 아래 ZIP 하나입니다.

```text
dist/INZONE Playback Voice Helper.zip
```

ZIP 안에는 실행 파일, 영어 Vosk 모델, 설정 파일, 개인정보 안내, 제3자 고지, 라이선스가 포함되어 있습니다.

## 권장 업로드 위치

가장 깔끔한 방식은 GitHub 공개 저장소 + Releases입니다.

1. GitHub에서 새 저장소를 만듭니다.
2. 저장소 이름 예시:
   - `inzone-playback-voice-helper`
   - `playback-voice-helper`
3. 설명 문구:

```text
Unofficial local voice playback helper for Windows. Supports play, pause, previous, and next.
```

4. `README_RELEASE.md` 내용을 GitHub 저장소의 `README.md`로 올립니다.
5. `LICENSE`, `PRIVACY.md`, `THIRD_PARTY_NOTICES.md`도 같이 올립니다.
6. GitHub의 Releases에서 `v1.0.0` 릴리스를 만듭니다.
7. `INZONE Playback Voice Helper.zip`을 첨부합니다.

## 릴리스 제목 예시

```text
INZONE Playback Voice Helper v1.0.0
```

## 릴리스 설명 예시

```text
Initial public release.

Features:
- Local offline voice recognition
- English commands: play, pause, previous, next
- Korean, English, and Japanese interface
- No external audio upload

Notes:
- This is an unofficial personal project and is not affiliated with Sony Corporation.
- Windows SmartScreen may show a warning because the executable is not code-signed.
- Unzip the file first, then run INZONE Playback Voice Helper.exe.
```

## 법적/상표 문구

README와 릴리스 설명에 아래 문구를 유지하는 것을 권장합니다.

```text
This is an unofficial personal project and is not affiliated with Sony Corporation.
INZONE and related trademarks are the property of their respective owners.
```

한국어:

```text
이 프로그램은 Sony Corporation과 관련이 없는 비공식 개인 프로젝트입니다.
INZONE 및 관련 상표는 각 소유자의 자산입니다.
```

## 업로드 전 체크리스트

- ZIP 파일 이름이 `INZONE Playback Voice Helper.zip`인지 확인
- ZIP을 풀었을 때 `.exe`가 바로 보이는지 확인
- `_internal/models/vosk-model-small-en-us-0.15`가 포함되어 있는지 확인
- `README.md`, `PRIVACY.md`, `THIRD_PARTY_NOTICES.md`, `LICENSE`가 포함되어 있는지 확인
- 릴리스 설명에 비공식 프로젝트 문구가 있는지 확인
- Windows SmartScreen 경고 가능성을 안내했는지 확인

## 현재 ZIP SHA256

```text
16FC8A4245A79CB4FCA760E15804DD73634F2CB0253A18A94F8044DDBF56FAD1
```
