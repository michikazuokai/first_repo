# VS Code インストール（Windows 10/11）

> 目的：授業で使う「VS Code」を入れて、起動できる状態にする  
> ✅ だいたい 10〜15分

## 目次
- [0. PCが x64 / ARM64 か確認](#0-pcが-x64--arm64-か確認)
- [1. ダウンロード](#1-ダウンロード)
- [2. インストール](#2-インストール)
- [3. 日本語にする（推奨）](#3-日本語にする推奨)
- [4. 動作確認（ここまでできたらOK）](#4-動作確認ここまでできたらok)
- [困ったとき](#困ったとき)

---

## 0. PCが x64 / ARM64 か確認
1. Windowsの「設定」を開く  
2. **システム → バージョン情報（About）**  
3. **システムの種類（System type）** を見る  
- ほとんどのPC：**x64**
- 一部のPC：**ARM64**

✅ 確認できたらOK（次へ）

---

## 1. ダウンロード
1. 公式ページを開く： https://code.visualstudio.com/download  
2. Windows のところで選ぶ  
- ふつうは **User Installer x64**（授業PCで管理者権限が無い場合に向く）
- ARM64 の人は **User Installer Arm64**

✅ ダウンロードフォルダに `VSCodeUserSetup-...exe` があればOK

（参考：公式ダウンロードと対応OS）  
Windows 10/11 向けのインストーラが用意されています。  
https://code.visualstudio.com/download

---

## 2. インストール
1. ダウンロードした `VSCodeUserSetup-...exe` をダブルクリック  
2. 「同意する」→「次へ」  
3. **Select Additional Tasks（追加タスク）** の画面で、次はチェック推奨：
- ✅ Add to PATH（ターミナルで `code` が使える）
- ✅ Add "Open with Code"（右クリックで開ける）
- ✅ Register Code as an editor（関連付け）

4. 「インストール」→「完了」

✅ VS Code が起動できたらOK

> 補足：VS Code のWindowsインストール手順（公式）  
> https://code.visualstudio.com/docs/setup/windows

---

## 3. 日本語にする（推奨）
1. VS Code を開く  
2. 左の「拡張機能（Extensions）」を開く（ショートカット：Ctrl+Shift+X）
3. 検索欄に `Japanese Language Pack`  
4. **Japanese Language Pack for Visual Studio Code（Microsoft）** を Install  
5. 右下の **Change Language and Restart** を押す

✅ メニューが日本語になったらOK

---

## 4. 動作確認（ここまでできたらOK）
### A. フォルダを開ける
- 「ファイル → フォルダを開く」→ 任意の場所を選ぶ  
✅ 左にファイル一覧が出ればOK

### B. ファイルを作って保存できる
- 新規ファイルを作る → `test.txt` で保存  
✅ 保存できればOK

### C. ターミナルを開ける
- 「ターミナル → 新しいターミナル」  
✅ 画面下に黒い画面（ターミナル）が出ればOK

---

## 困ったとき
### Q1. 右クリックの「Open with Code」が出ない
- もう一度インストーラを実行して、追加タスクのチェックを入れて修復/再インストールすると直ることがあります。

### Q2. 起動できない / エラーが出る
- いったんアンインストール → 公式から入れ直し  
- 公式：ダウンロード https://code.visualstudio.com/download
