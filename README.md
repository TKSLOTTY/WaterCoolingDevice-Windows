# Water Cooling Device for Windows

Water Cooling DeviceをWindowsから監視・設定するための公式アプリ配布ページです。

## ダウンロード

GitHub Releasesから用途に合うZIPをダウンロードしてください。

- **Full**: .NET 8同梱版です。通常はこちらを選んでください。
- **Minimal**: 小容量版です。別途.NET 8 Desktop Runtimeが必要です。

ZIPを展開し、`Windows_App\WaterCoolingDevice.exe`を実行します。

## 主な機能

- 水温、FAN/PUMP Duty、RPMの表示
- ファンカーブ、警告温度、ARGB LED構成の設定
- OLED表示画面と切替時間の設定
- CPU・メモリ使用率のOLED表示
- CPU・GPU温度の取得とOLED表示（任意）
- Windows起動時の自動起動と通知領域表示

## CPU・GPU温度について

CPU・GPU温度取得は設定画面のチェックボックスでON/OFFできます。
CPU温度取得には、同梱の署名済みPawnIOセットアップが必要です。
CPUやマザーボードによっては、PawnIOを使用してもCPU温度を取得できない場合があります。
取得できない温度は表示されません。

この配布版はWinRing0を同梱・使用しません。

## 動作環境

- Windows 11 x64
- 対応するWater Cooling Device本体・ファームウェア
- Minimal版のみ [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0)

## Beta

最新のv3.0.1-betaでは、アプリ再起動後にCPU・GPU温度が数秒で消える場合がある問題を
修正しました。v3.0.0-betaを使用中の場合は更新してください。
不具合はGitHub Issuesへお知らせください。

---

This repository distributes the official Windows companion app for Water Cooling Device.

- **Full** includes .NET 8 and is recommended for most users.
- **Minimal** is smaller and requires the .NET 8 Desktop Runtime.
- Windows 11 x64 and compatible device firmware are required.
- CPU/GPU temperature acquisition is optional. Some CPUs may not expose a supported temperature sensor.
- WinRing0 is not included or used.
