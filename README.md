# Orange Seitai Mock (Cocoon child theme style)

これは GitHub Pages や任意のホスティングで動く **スタティックなモック** です。

## 使い方

1. このリポジトリに `index.html` を置くだけでOKです（追加ビルド不要）。
2. GitHub Pages を使う場合：  
   - Settings > Pages > Build and deployment で `Deploy from a branch`  
   - Branch を `main`、Folder を `/root` に設定して保存
   - 数分後に公開URLが発行されます

## カスタマイズのヒント

- 電話番号とLINEリンクは `index.html` のCTA部分を編集してください。
- 画像は現在HPのもの（`orange-seitai.com`）を直接参照しています。自前でホストする場合は画像を `/assets/images/` などに置いてパスを変更してください。
- WordPress に組み込む場合は、このHTMLを `front-page.php` の骨格に流用し、各ブロックをループやACFに置き換えてください。
