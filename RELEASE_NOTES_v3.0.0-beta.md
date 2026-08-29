# Windows App v3.0.0-beta

Water Cooling Device Windowsアプリの公開ベータ版です。

## 配布ファイル

- `WaterCoolingDevice-Windows-v3.0.0-beta-full.zip`
  - .NET 8同梱。通常はこちらを推奨します。
- `WaterCoolingDevice-Windows-v3.0.0-beta-minimal.zip`
  - 小容量版。.NET 8 Desktop Runtimeの事前インストールが必要です。
- `SHA256SUMS.txt`
  - ダウンロードファイルのSHA-256確認用です。

## 主な内容

- 実画面に近い青色OLEDプレビューから表示画面を選択
- 総合表示、FAN1カーブ、FAN2/PUMPカーブ、CPU/メモリ使用率、CPU/GPU温度表示
- USB通信がない場合、OLED自動表示は本体情報の画面1～3へ復帰
- CPU/GPU温度取得をチェックボックスでON/OFF可能
- LibreHardwareMonitor 0.9.6と署名済みPawnIOを採用し、WinRing0を廃止
- 温度取得処理だけを管理者権限の非表示タスクとして実行

ファームウェアはこの公開リリースに含まれません。
