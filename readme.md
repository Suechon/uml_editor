# Mermaid UML Editor（オフライン対応）

このツールは、インストール不要・オフラインで動作する Mermaid.js ベースの UML エディタです。  
HTML ファイルを開くだけで、リアルタイムに Mermaid 記法の UML を描画できます。

## 🔧 特徴

- ✅ オフライン対応（`mermaid.min.js` があればネット不要）
- ✅ シンタックスハイライト付きリアルタイムエディタ
- ✅ UMLテキスト＋PNG画像を1ボタンで保存可能
- ✅ テキストファイルの読み込み機能あり
- ✅ Mermaid構文エラー時には明示的にエラーメッセージを表示
- ✅ 残留DOMの自動クリーンアップ処理あり

---

## 💻 使用方法

### 1. 構成ファイル


```
uml_viewer/
├── index.html ← メインファイル（このファイルを開く）
└── mermaid.min.js ← Mermaid本体（ローカル保存推奨、なければCDN fallback）
```


### 2. `index.html` の開き方

- ファイルをダブルクリック or Edge/Chrome で開いてください
- `mermaid.min.js` がある場合ネット接続なしでも動作します

### 3. Mermaid 記法を入力

左ペインのエディタに Mermaid 記法（例: `sequenceDiagram`, `classDiagram`）を記述すると、右ペインにリアルタイムで描画されます。

### 4. 保存・読み込み

- **保存**：`保存（テキスト＋PNG）` ボタンで `.txt`（記法）と `.png`（画像）を同時保存
- **読み込み**：手元の `.txt` ファイルをインポートして編集・再描画

---

## 📌 対応バージョン・動作環境

| 項目 | 内容 |
|------|------|
| Mermaid.js バージョン | `v11.9.0`（UMDビルド） |
| 対応図種類 | `flowchart`, `sequenceDiagram`, `classDiagram`, `stateDiagram-v2`, `erDiagram` など |
| ブラウザ | Edge / Chrome（最新版推奨） |
| OS | Windows 10/11 標準環境でも動作確認済み |

---

## 📥 Mermaid.js のローカル保存方法

1. 以下にアクセス：  
   https://cdn.jsdelivr.net/npm/mermaid@11.9.0/dist/mermaid.min.js

2. 右クリック → 「名前を付けて保存」  
   → `index.html` と同じフォルダに保存してください。

---


## ライセンス

このツールは MIT ライセンスのもと提供されます。  
Mermaid.js 自体も [MIT License](https://github.com/mermaid-js/mermaid/blob/develop/LICENSE) に準拠しています。

---

##  クレジット

- Mermaid.js: https://mermaid.js.org/
- jsDelivr CDN: https://cdn.jsdelivr.net/

