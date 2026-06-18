# codedazur-line — LINE/LIFF 静的アセット

コートダジュール生産管理システムの **LINE/LIFF 用 静的ファイル**（GitHub Pages 配信）。

- `form.html` … LIFF 入力フォーム。`?mode=inventory|production|delivery|adjust`
- `products_by_store.json` … 店舗別 取扱商品データ（フォームのピッカー用）
- `d-5f2d9a3431267e8c97d4.html` … 管理者向けダッシュボード（推測困難ファイル名）
- `index.html` … 各モードへの入口

バックエンド（POS取込・Prophet予測・LINE送信・SQLite）はローカル/別環境で稼働。
このリポジトリは入力/閲覧 UI のみ（秘匿情報・DBは含めない）。

## 配信URL（GitHub Pages）
- フォーム: `https://ntomotaka.github.io/codedazur-line/form.html`
- LINE Developers の LIFF エンドポイントをこの URL に設定して使う。
