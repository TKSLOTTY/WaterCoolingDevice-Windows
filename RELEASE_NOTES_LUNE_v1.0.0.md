# WCD-01 LUNE Edition v1.0.0

Water Cooling Device WindowsアプリのLUNE Edition初回リリースです。
標準版v3.0.2の機能を土台に、LUNE表示を統合しています。

## 配布ファイル

- `WaterCoolingDevice-Windows-LUNE-v1.0.0-full.zip`
  - .NET 8同梱。通常はこちらを推奨します。
- `WaterCoolingDevice-Windows-LUNE-v1.0.0-minimal.zip`
  - 小容量版。.NET 8 Desktop Runtimeの事前インストールが必要です。
- `SHA256SUMS.txt`
  - ダウンロードファイルのSHA-256確認用です。

## LUNE Editionの機能

- 状態表示画面からLUNE画面へ切り替え、画面内ボタン・Escキー・右上の×で通常画面へ復帰
- 通常画面とLUNE画面で同じHID接続を共有し、切り替え中も本体通信と水温監視を継続
- 本体から取得した水温に数値、表情、動き、背景色を同期
- 高水温、センサー異常、USB切断の状態をLUNE画面へ反映
- 標準版v3.0.2のバージョン表示、自動起動修復、温度取得安定化、フェイルセーフ警告を収録

ファームウェアはこの公開リリースに含まれません。標準版と同じ対応ファームウェアを使用します。
