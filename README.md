# Mimicam Legal Pages

Mimicam（写真構図ガイドアプリ）の法的情報・サポートページ。

## ホスティング
GitHub Pages で公開予定。

- 公開URL: `https://code-and-chord.github.io/mimicam-legal/`
- privacy.html: プライバシーポリシー
- terms.html: 利用規約
- support.html: お問い合わせ・FAQ
- index.html: ランディング

## GitHub Pages の有効化手順
1. GitHub で `code-and-chord/mimicam-legal` リポジトリを作成（Public）
2. このフォルダの中身を push:
   ```
   cd mimicam_legal_pages
   git init
   git add .
   git commit -m "Initial pages"
   git branch -M main
   git remote add origin https://github.com/code-and-chord/mimicam-legal.git
   git push -u origin main
   ```
3. リポジトリの Settings → Pages → Source = main / root → Save
4. 数分後 `https://code-and-chord.github.io/mimicam-legal/` でアクセス可能に

## メンテナンス
本文の更新は `/Users/kippo/Desktop/777_company/mimicam_app/mimicam/legal/` の md ファイルが正本。HTMLは git push 用のコピー。
