# SRT → FCPXML Converter & Subtitle Editor

Final Cut Proに日本語字幕を読み込むためのブラウザツールです。

## ツール

### 🔄 SRT → FCPXML コンバータ (`srt-to-fcpxml.html`)
SRTファイルをFCPXML形式に変換します。
- 複数SRTファイルの一括変換
- フレームレート・解像度・縦位置の設定
- フレームオフセット調整
- 句読点の自動削除
- 文字エンコーディング対応（UTF-8 / Shift-JIS / EUC-JP）

### ✏️ 字幕エディタ (`srt-editor.html`)
動画を見ながら字幕を編集できます。
- 動画プレーヤー内蔵（MP4 / WebM / MOV対応）
- 字幕テキスト・タイムコードの直接編集
- 字幕の分割・結合・削除・追加
- 動画と字幕の同期再生
- 自動保存 & プロジェクトファイル保存
- 編集完了後にFCPXML書き出し

## 使い方

1. HTMLファイルをブラウザで開く
2. SRTファイル（と動画）をドラッグ＆ドロップ
3. 設定を調整
4. FCPXMLを書き出し → Final Cut Proに読み込み

## 特徴

- **完全ブラウザ動作** — サーバー不要、ファイルのアップロードなし
- **オフライン対応** — ネット接続不要で動作
- **プライバシー安全** — すべての処理はブラウザ内で完結

## 対応環境

- Chrome / Safari / Firefox / Edge
- macOS / Windows / Linux

## ライセンス

MIT
