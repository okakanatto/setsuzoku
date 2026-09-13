# Setsuzoku

Windows用のネットワーク観測・診断アプリです。PC・接続相手・サイトの関係と測定結果を図から調べられます。

## ダウンロード

ビルド済みのWindows用ポータブル版は[Releases](https://github.com/okakanatto/setsuzoku/releases)からダウンロードできます。

- **Windows x64 ポータブル版** (`.zip`): インストール不要です。

## 動作環境

- Windows 10 / 11 x64
- Microsoft Edge WebView2 Runtime

## 使い方

1. ZIPを、書き込み可能な任意のフォルダーへ展開します。
2. 同梱の`portable.flag`はそのままにして、`Setsuzoku.exe`を起動します。
3. 設定・履歴・一時ブラウザデータ・書き出した資料は、展開先の`Setsuzoku-data`に保存されます。

このバイナリは未署名の開発版です。初回起動時にWindowsの警告が出る場合があります。

## プライバシー

この配布ZIPには、設定・履歴・測定値・操作記録などの利用者データは含まれていません。アプリが取得する診断・記録データはローカルに保存されます。

## ライセンス

[MIT](LICENSE)