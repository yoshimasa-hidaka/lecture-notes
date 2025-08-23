# Template: Portal + Subbooks (Quarto)

## 使い方
1. ルートでローカルプレビュー
   ```bash
   quarto preview
   ```
2. サブ本（例：QCD）だけPDF化
   ```bash
   cd qcd
   quarto render --to pdf
   ```
3. GitHub Pages で公開するなら Settings → Pages で `main` / `/docs` を指定。
