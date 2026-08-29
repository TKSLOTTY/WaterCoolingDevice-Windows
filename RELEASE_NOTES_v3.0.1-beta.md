# Windows App v3.0.1-beta

Water Cooling Device Windowsアプリのベータ版更新です。

## 配布ファイル

- `WaterCoolingDevice-Windows-v3.0.1-beta-full.zip`
  - .NET 8同梱。通常はこちらを推奨します。
- `WaterCoolingDevice-Windows-v3.0.1-beta-minimal.zip`
  - 小容量版。.NET 8 Desktop Runtimeの事前インストールが必要です。
- `SHA256SUMS.txt`
  - ダウンロードファイルのSHA-256確認用です。

## 修正内容

- アプリ再起動後、CPU・GPU温度が最初の数秒だけ表示され、その後消える場合がある問題を修正
- 正常に動作中の管理者温度取得エージェントを、画面アプリの再起動時にそのまま再利用
- 温度取得エージェントの再起動が必要な場合、旧処理の終了完了を待ってから起動
- Windowsがタスク起動要求を無視した場合に自動再試行

CPU・GPU温度の取得はユーザー環境で継続表示とアプリ再起動後の復旧を確認済みです。
ファームウェアはこの公開リリースに含まれず、製造固定版v2.0.0にも変更はありません。
