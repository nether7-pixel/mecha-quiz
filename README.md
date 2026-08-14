# メカ・カテゴリクイズ

GitHub Pages 用ファイルです。

## 公開方法
1. `index.html` をリポジトリのルートにアップロードしてください。
2. Settings → Pages → Deploy from a branch
3. Branch: `main` / Folder: `/ (root)`
4. 保存後、GitHub Pages のURLを開きます。

`index.html` 単体で動作します。`questions.json` は問題データの編集・保管用です。

## 実装済み
- 10 / 20 / 30 / 全66問
- ランダム出題・重複なし
- 自由入力
- 大文字小文字・全角半角・空白・中黒・ハイフン等を吸収する正規化
- 略称・正式名称・英語・カタカナ表記の acceptedAnswers
- 「わからない」
- 正誤・自分の回答・正解・別表記・一言解説
- 連続正解数
- 問題ID
- 結果画面
- 間違えた問題だけ再挑戦
- iPhone向けレスポンシブ表示
