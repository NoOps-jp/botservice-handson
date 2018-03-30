# チャレンジしてみましょう

時間が余った方は、以下の内容にチャレンジして、よりインテリジェントなチャットボットを構築してみましょう。

## FAQデータの更新

FAQ データの更新、つまり Cosmos DB の更新があった場合、Azure Search のインデックスの更新が必要となります。

そして、Cosmos DB には、データの更新をトリガーとしてイベントを実行する  Change Feed 機能が備わっています。この機能を使って Cosmos DB のデータが更新された時に、自動で Azure Search のインデックスが更新される NoOps な世界を作ってみましょう。

- [](https://docs.microsoft.com/ja-jp/azure/cosmos-db/change-feed)

## Azure Search のログを Power BI で可視化し、分析に役立てる

Azure Search でどんな検索ワードが入力されたかをロギングし、[Power BI](https://powerbi.microsoft.com/ja-jp/) などの可視化ツールを使って分析をすることでアプリケーションの改善に役立ることが可能です。

- [Azure Search サービスの監視](https://docs.microsoft.com/ja-jp/azure/search/search-monitor-usage)
- [Power BI](https://powerbi.microsoft.com/ja-jp/)

## Azure Search の検索エクスペリエンスの向上

Azure Search は機能が豊富なので、データに応じて検索を最適化することができます。

- [Azure Search のフルテキスト検索のしくみ](https://docs.microsoft.com/ja-jp/azure/search/search-lucene-query-architecture)
- [Azure Search のクエリ](https://docs.microsoft.com/ja-jp/azure/search/search-query-overview)

## LUIS を使った返答

Cognitive Serices のひとつ、Language Understanding (旧称LUIS) を使って会話の幅を増やすことも可能です。

- [Language Understanding (LUIS)](https://docs.microsoft.com/ja-jp/azure/cognitive-services/luis/home)

## QnA Maker での FAQ 回答実装

[QnA Maker](https://qnamaker.ai/) を利用しても簡単にFAQチャットボットを実装することができます。ぜひ試してみましょう。

- [QnA Maker](https://qnamaker.ai/)
