# 自分で使う用の Slidev テンプレート

このままでは GitHub Pages にデプロイされないので以下の手順が必要。

- Settings > Pages > Build and deployment の「Source」を GitHub Actions に
- `pnpm install` を実行して、生成された `pnpm-lock.yaml` をコミットしてプッシュ
