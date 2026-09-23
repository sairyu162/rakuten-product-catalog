# 統合候補選択ページ

このページは既存のGitHub Pages商品カタログと同じ公開ルートに配置するサブページです。既存のルート`index.html`、`products.json`、canvas2way、公開URLを変更しません。

公開後の想定URLは、既存のGitHub Pages URLを`https://既存URL/candidate-selection/`へ置き換えた形です。

「採用候補にする」ボタンは商品採用を確定しません。ブラウザ内に`SELECTED_PENDING_HUMAN_REVIEW`を記録し、確認用JSONをダウンロードします。サーバー側の採用状態、商品カタログ、動画入力、アフィリエイトリンクは変更しません。

次の工程は、人間による楽天アフィリエイトリンク確認、画像確認、人間承認です。承認前は`IMAGE_OK`に変更せず、動画生成もしません。
