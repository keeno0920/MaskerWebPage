# 個人情報マスカー プロモーションサイト

App Store 審査・公開で必要な **サポートURL** と **プライバシーポリシーURL**、および紹介用の
**マーケティングURL** をまかなう静的サイト。外部依存なし（HTML + CSSのみ）。

## ファイル構成
- `index.html` … 紹介ページ（マーケティング用）
- `support.html` … サポート・よくある質問・お問い合わせ
- `privacy.html` … プライバシーポリシー
- `styles.css` … 共有スタイル

お問い合わせ先メール：**appjiajibu@gmail.com**

## 公開方法（GitHub Pages 例）
1. GitHubで新規リポジトリを作成（例：`privacymasker-site`）
2. このフォルダ内の4ファイルをアップロード（リポジトリ直下）
3. Settings → Pages → Branch を `main` / `/(root)` にして保存
4. 数分後、`https://<ユーザー名>.github.io/privacymasker-site/` で公開

※ Netlify / Cloudflare Pages / 自前サーバーでも、4ファイルをそのまま置くだけで動きます。

## App Store Connect に入力するURL
| 項目 | 入れるURL |
|---|---|
| マーケティングURL（任意） | `…/index.html`（またはサイトのトップ） |
| **サポートURL（必須）** | `…/support.html` |
| **プライバシーポリシーURL（必須）** | `…/privacy.html` |

## ローカル確認
ブラウザで `index.html` を直接開けば表示を確認できます（サーバー不要）。

## 文言の方針
- AEOの検索意図（PDF黒塗り・スクショ・本人確認書類・領収書・EXIF・QR）を自然な日本語で反映。
- 禁止文言（100%安全／完全削除を保証／法的に有効／提出先で必ず通る）は不使用。
- 「自動検出は補助機能・出力前に要確認」の注意文を各ページに掲載。
