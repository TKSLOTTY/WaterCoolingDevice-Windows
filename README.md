# Water Cooling Device for Windows

Water Cooling DeviceをWindowsから監視・設定するための公式アプリ配布ページです。

## ダウンロード

GitHub Releasesから用途に合うZIPをダウンロードしてください。

- **Windows App v3.0.2 Beta**: 通常画面を使用する標準版です。
- **WCD-01 LUNE Edition v1.0.0**: 通常画面とLUNE画面を切り替えて使用できる特別版です。

- **Full**: .NET 8同梱版です。通常はこちらを選んでください。
- **Minimal**: 小容量版です。別途.NET 8 Desktop Runtimeが必要です。

ZIPを展開し、`WaterCoolingDevice.exe`を実行します。

## 主な機能

- 水温、FAN/PUMP Duty、RPMの表示
- ファンカーブ、警告温度、ARGB LED構成の設定
- OLED表示画面と切替時間の設定
- CPU・メモリ使用率のOLED表示
- CPU・GPU温度の取得とOLED表示（任意）
- Windows起動時の自動起動と通知領域表示

LUNE Editionでは、本体から取得した水温に合わせてLUNE画面の数値、表情、動き、背景色が
変化します。通常画面とはアプリ内で相互に切り替えでき、HID接続と水温監視も継続します。

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

最新の標準版v3.0.2-betaでは、バージョン表示、自動起動登録先の自動修復、
高水温フェイルセーフの警告表示とWindows標準警告音を追加しました。
v3.0.1-betaまでの温度取得安定化修正も含まれます。
不具合はGitHub Issuesへお知らせください。

---

This repository distributes the official Windows companion app for Water Cooling Device.

- **Full** includes .NET 8 and is recommended for most users.
- **Minimal** is smaller and requires the .NET 8 Desktop Runtime.
- Windows 11 x64 and compatible device firmware are required.
- CPU/GPU temperature acquisition is optional. Some CPUs may not expose a supported temperature sensor.
- WCD-01 LUNE Edition synchronizes its display, motion, and background color with coolant temperature.
- WinRing0 is not included or used.
