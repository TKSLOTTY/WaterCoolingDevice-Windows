# Windows App v3.0.2-beta

Water Cooling Device Windowsアプリ標準版のベータ更新です。

## 配布ファイル

- `WaterCoolingDevice-Windows-v3.0.2-beta-full.zip`
  - .NET 8同梱。通常はこちらを推奨します。
- `WaterCoolingDevice-Windows-v3.0.2-beta-minimal.zip`
  - 小容量版。.NET 8 Desktop Runtimeの事前インストールが必要です。
- `SHA256SUMS.txt`
  - ダウンロードファイルのSHA-256確認用です。

## 更新内容

- タイトルバーと設定画面にアプリのバージョンを表示
- アプリを別フォルダへ展開・移動した場合、Windows自動起動の登録先を現在の実行ファイルへ自動修復
- 高水温フェイルセーフ作動中、警告帯に100%出力保護の状態を表示
- 高水温警告時、設定に応じてWindows標準の重大な警告音を1回再生
- v3.0.1-betaまでのCPU・GPU温度取得安定化修正を収録

ファームウェアはこの公開リリースに含まれず、製造固定版v2.0.0にも変更はありません。
