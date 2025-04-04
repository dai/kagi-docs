# Kagi Inc. ドキュメント

このリポジトリには、Kagi Inc. が開発した製品のオープンソース ドキュメントが含まれています。

## コンテンツ

- [ナレッジベースマップ](#knowledgebase-map)
- [サポート](#support)
  - [ディスカッション](#discussions)
  - [コミュニティ](#community)
- [コントリビューション](#contributing)
  - [課題 (Issues)](#issues)
  - [プルリクエスト](#pull-requests)
  - [プルリクエストの作成](##creating-a-pull-request)
- [ビルド](#building)

## ナレッジベースマップ

このリポジトリは、Kagi が開発した複数の製品に関するドキュメントを提供します。

製品 | ドキュメント         | リポ ディレクトリ
--------|-----------------------|----------------
[Kagi Search](https://kagi.com) | https://help.kagi.com/kagi | [kagi](https://github.com/kagisearch/kagi-docs/tree/main/docs/kagi)
[Orion Browser](https://browser.kagi.com) | https://help.kagi.com/orion | [orion](https://github.com/kagisearch/kagi-docs/tree/main/docs/orion)

私たちのドキュメント作成は進行中です！フィードバックやコントリビューションを歓迎します。詳細は以下をご覧ください！

## サポート

### ディスカッション

[ディスカッション](https://github.com/kagisearch/kagi-docs/discussions)ページでは、以下のカテゴリをご覧いただけます：

- **お知らせ**: このリポジトリのドキュメントに関連する重要な更新情報を投稿します。
- **Q&A**: ドキュメントや提供されているAPIについて議論したり質問したりできます。どこから始めればよいかわからない場合は、ここが最適です！

ドキュメントやAPI以外のトピックについては、[コミュニティ](#community)セクションに記載されている各製品の公式サポートをご参照ください。

### コミュニティ

各製品には専用のフォーラムがあり、ぜひご参加ください。また、すべての製品について議論できる共有のDiscordサーバーもあります。

Discord招待リンク: https://kagi.com/discord

製品 | フィードバック & バグ報告
--------|-----------------------
Kagi Search | [kagifeedback.org](https://kagifeedback.org)
Orion Browser | [orionfeedback.org](https://orionfeedback.org)

## コントリビューション

### 課題 (Issues)

バグ報告、説明のリクエスト、その他の問い合わせは、[Issues](https://github.com/kagisearch/kagi-docs/issues)タブからお寄せください。

課題を作成すると、必要な情報を提供するためのテンプレートが表示されます。これにより、適切なラベルで課題を分類できます。

スタッフが課題を確認し、最適な対応方法を検討します。

### プルリクエスト

コントリビューションに時間を割いていただき、ありがとうございます！

以下のようなコントリビューションを歓迎します：

- ドキュメント内の誤った記述や不正確な情報の修正
- 詳細の追加や、複雑な説明をより理解しやすい表現に変更
- 現在のドキュメントに不足している部分の補完
- ドキュメント内のスペルミスや文法エラーの修正
- スタッフがコミュニティに新しいセクションの作成を呼びかけた場合の新しいドキュメントの追加

以下のような変更は控えてください：

- 空白やフォーマットの変更
- 主観的な表現の変更
- ドキュメント全体の構造やフォーマットの変更
- 現在のドキュメントを不必要に再構成する追加
- 未リリースの製品機能を記載する追加

不明な点がある場合は、まず[課題を作成](https://github.com/kagisearch/kagi-docs/issues/new/choose)してください。スタッフがガイドします！

### プルリクエストの作成

1. このリポジトリを[フォーク](https://github.com/kagisearch/kagi-docs/fork)します
2. ブランチを作成します: `git checkout -b username/my-cool-change`
3. [ビルド](#building)手順に従って、変更したいドキュメントをコンパイルします
4. 変更を加えます
5. 変更をコミットします: `git -am 'Update documentation'`
6. フォークにブランチをプッシュします: `git push origin username/my-cool-change`
7. 新しいプルリクエストを作成します

プルリクエストフォームのテンプレートが、変更を受け入れるために必要な追加情報の提供をガイドします。

## ビルド

Kagiのドキュメントは[Vitepress](https://vitepress.dev/)で生成されています。

### ローカル環境での開発

    npm install
    npm run docs:dev