# トータルフットケア GRACE - 公式サイト

## 公開前に直す箇所

1. **LINEリンク**（3箇所）
   `index.html` 内の `https://lin.ee/xxxxxxx` を、実際のLINE公式アカウントの友だち追加URLに置き換えてください。
   （LINE Official Account Manager → 設定 → 友だち追加ガイド から取得できます）

2. **Instagramリンク**（1箇所）
   `https://www.instagram.com/` を実際のアカウントURL（例: `https://www.instagram.com/grace_footcare`）に置き換えてください。

## GitHub Pagesでの公開手順

1. このフォルダの中身（`index.html`, `README.md`, `logo.png`, `IMG_xxxx.jpeg` 全ファイル）を **すべて同じ階層（リポジトリ直下）** にアップロード
   ※ iPadではフォルダ構造を保ったままアップロードするのが難しいため、あえてサブフォルダを使わずすべて同じ階層に置く構成にしています。
2. リポジトリの Settings → Pages → Branch を `main`（ルート）に設定
3. 数分後、`https://ユーザー名.github.io/リポジトリ名/` で公開されます

## 構成

- `index.html` … トップページ
- `therapist.html` … セラピスト紹介ページ（別ページ）
- `cancel-policy.html` … キャンセルポリシーページ（別ページ）
- `style.css` … 全ページ共通のスタイル
- `logo.png` … ロゴ画像（ヘッダー・フッター用）
- `therapist-face.jpg` … セラピスト紹介用の顔写真（丸型トリミング）
- `IMG_4882.jpeg` 〜 `IMG_4897.jpeg` … トップのスライドショー用写真（10枚）

ページを追加・編集する場合も、見た目を統一するために `style.css` を共通で読み込む形にしています。

## 住所について

自宅サロンのため、詳細住所はサイトには掲載せず「岡山県岡山市北区」までの表示とし、予約確定後に個別にご案内する導線にしています。掲載方針を変更したい場合は `index.html` の `id="access"` セクションを編集してください。
