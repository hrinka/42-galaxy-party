# 42 Galaxy Party III — 特設サイト

42スクールのイベント「42 Galaxy Party III」の特設ページ。
アクセスすると銀河アニメ＋サイバー演出が再生され、`MEMBERS ONLY` に
合言葉（`42`）を入力すると参加確認（調整さん）へ遷移します。

- 開催: 2026-07-03 (FRI) OPEN 18:00 / CLOSE 21:30
- 会場: WPÜ GALLERY SHINJUKU（ホテル2F）

## ファイル
- `index.html` … 公開用（中身は `42-galaxy-party.html` と同一）
- `42-galaxy-party.html` … 作業用オリジナル
- `flyer.PNG` … 元フライヤー画像（現在サイトでは未使用）

## 設定（`index.html` 内 `<script>` 冒頭）
- `CHOSEISAN_URL` … 調整さんのURL
- `ACCESS_CODE` … members only の合言葉（既定: `42`）
- `USE_FLYER` … `true` でフライヤー画像を背景に使用（既定: `false`）

## デプロイ（Vercel・無料 Hobby プラン）
1. このリポジトリを GitHub にプッシュ
2. https://vercel.com/new でリポジトリを Import
3. Framework Preset: **Other**（静的サイト）のまま Deploy
4. 発行された URL を配布

> 7/3 以降に閉鎖する場合は、Vercel ダッシュボードで該当プロジェクトを Delete すれば公開停止できます。
