# 命軸｜三軸命式占い

生年月日から、本質・行動パターン・今年の流れを読む自己理解ツールです。

## 構成

- `index.html`: GitHub Pages 公開用の単一HTMLアプリ
- `san_axis_fortune.py`: Python版の計算ロジック検証コード
- `reading_generator.py`: Python版の説明文合成コード
- `data/reading_parts.json`: 説明文パーツ
- `data/pillar_overrides.json`: 特徴的な干支の上書き文

## 検証済み

- JS版とPython版の5件サンプル一致
- 立春境界日の切り替え確認
- 共鳴型判定の確認

## 公開

GitHub Pagesでは、このディレクトリの `index.html` を公開対象にします。
