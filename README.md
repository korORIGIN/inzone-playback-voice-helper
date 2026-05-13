# INZONE Playback Voice Helper

Unofficial local voice playback helper for Windows.

This project is not affiliated with Sony Corporation. INZONE and related trademarks are the property of their respective owners.

## Commands

- `play`: Play
- `pause`: Pause
- `previous`: Previous track
- `next`: Next track

## 사용법

1. `INZONE Playback Voice Helper.exe`를 실행합니다.
2. 사용할 마이크를 선택합니다.
3. `듣기 시작`을 누릅니다.
4. 영어 명령어 `play`, `pause`, `previous`, `next` 중 하나를 말합니다.
5. 오인식이 있으면 매칭 기준을 올리고, 반응이 느리면 중복 방지 시간을 줄여보세요.

## How To Use

1. Run `INZONE Playback Voice Helper.exe`.
2. Select the microphone you want to use.
3. Press `Start Listening`.
4. Say one English command: `play`, `pause`, `previous`, or `next`.
5. If false triggers happen, raise the match threshold. If response feels slow, lower the cooldown time.

## 使い方

1. `INZONE Playback Voice Helper.exe`を実行します。
2. 使用するマイクを選択します。
3. `聞き取り開始`を押します。
4. 英語コマンド `play`, `pause`, `previous`, `next` のいずれかを話します。
5. 誤認識がある場合はマッチ基準を上げ、反応が遅い場合は重複防止時間を短くしてください。

## 개인정보 주의

- 음성 인식은 PC 안에서 로컬로 처리됩니다.
- 이 앱은 마이크 음성을 외부 서버로 업로드하지 않습니다.
- 이 앱은 녹음 파일을 저장하지 않습니다.
- 앱 화면의 실시간 로그에는 인식된 텍스트가 표시될 수 있습니다.
- 선택한 마이크는 `듣기 시작`이 켜져 있는 동안에만 사용됩니다.
- Voicemod, Wave Link, Discord, OBS 같은 다른 오디오 앱은 이 앱과 별도로 마이크를 사용할 수 있습니다.

자세한 내용은 `PRIVACY.md`를 확인하세요.

## Privacy Notice

- Speech recognition is processed locally on your Windows PC.
- This app does not upload microphone audio to an external server.
- This app does not save recording files.
- Recognized text may appear in the real-time log inside the app window.
- The selected microphone is used only while listening is active.
- Other audio apps such as Voicemod, Wave Link, Discord, or OBS may use microphones independently of this app.

See `PRIVACY.md` for details.

## 個人情報に関する注意

- 音声認識はWindows PC内でローカル処理されます。
- このアプリはマイク音声を外部サーバーへアップロードしません。
- このアプリは録音ファイルを保存しません。
- アプリ画面のリアルタイムログに認識されたテキストが表示される場合があります。
- 選択したマイクは聞き取り中のみ使用されます。
- Voicemod、Wave Link、Discord、OBSなどの他の音声アプリは、このアプリとは別にマイクを使用する場合があります。

詳細は `PRIVACY.md` を確認してください。

## Notes

Windows, the browser, or the music app must support media session controls for `previous` and `next` to work. Some apps may only support `play` and `pause`.
