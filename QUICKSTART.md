# クイックスタートガイド

このガイドでは、システムをすぐに使い始めるための最小限の手順を説明します。詳細は `MANUAL.md` を参照してください。

## 5分で始める

### 1. 文体サンプルを配置（2分）

`knowledge/style-samples/` ディレクトリに、あなたの過去の記事を3〜5本配置します。

```bash
# 例：あなたの記事をコピーして配置
cp ~/過去の記事1.md knowledge/style-samples/article_1.md
cp ~/過去の記事2.md knowledge/style-samples/article_2.md
cp ~/過去の記事3.md knowledge/style-samples/article_3.md
```

### 2. ルールをカスタマイズ（3分）

`.cursor/rules/10_writing-style/RULE.md` を開き、あなたの文体に合わせて編集します。

最低限、以下のセクションを確認・編集してください：
- **基本的な考え方**: あなたが文章を書く上で大切にしている価値観
- **避けるべき表現**: AIが使いがちな、あなたが使いたくない表現

### 3. 最初の記事を生成

`README.md` を開き、以下のプロンプトをCursorに入力します：

```markdown
すべての.cursor/rules/内のルールを厳格に遵守し、以下の条件でnote記事のドラフトを作成してください。

- **テーマ**: [あなたのテーマ]
- **読者ターゲット**: [想定する読者層]
- **記事のゴール**: [読者が得られるもの]
- **参考情報**: @knowledge/inputs/2025-01-15_テーマ名.md
- **参考文体**: @knowledge/style-samples/

生成された記事は、`articles/2025-01-15_テーマ名/draft.md` に保存してください。
```

## 次のステップ

1. 生成された `draft.md` をレビューし、修正します
2. 修正した内容を `final.md` として保存します
3. noteに投稿します
4. レビューで気づいたことを `.cursor/rules/10_writing-style/RULE.md` に追加します

## 困ったときは

- 詳細な使い方: `MANUAL.md` を参照
- トラブルシューティング: `MANUAL.md` の「トラブルシューティング」セクションを参照

