# 00. 環境準備

## Azure

#### Azure サブスクリプション

このハンズオンで利用できるMicrosoft Azureのサブスクリプションを用意して下さい。

* サブスクリプションをお持ちでない方: [Azure無料アカウントの作成](https://azure.microsoft.com/ja-jp/free/)

サブスクリプションを用意したら、 https://portal.azure.com にサインインできることを確認して下さい。

#### リソースグループの作成

今回のハンズオンで作成する各種Azureリソースをまとめて管理・削除できるようにリソースグループを新規に作成します。

* 参考手順: [ポータルを使用した Azure リソースの管理 - リソース グループの管理](https://docs.microsoft.com/ja-jp/azure/azure-resource-manager/resource-group-portal#manage-resource-groups)

## Azure Storage Explorer

Azure の Storage の情報を確認することができるツールです。
今回は、Table Storage に出力された情報を確認するために利用します。

[こちら](https://azure.microsoft.com/ja-jp/features/storage-explorer/)を参考にセットアップしましょう。

## CosmosDB - データ移行ツール

様々なデータソースを Cosmos DB へインポート、またはエクスポートできるツールです。
今回使うデータは、jsonファイルで用意しています。Cosmos DB へのデータをインポートするために利用します。

[こちら](https://docs.microsoft.com/ja-jp/azure/cosmos-db/import-data)を参考に、ツールをセットアップします。

## Bot Emulator

開発したチャットボットにアクセスする（話しかける）際に利用するエミュレーターです。

[こちら](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-debug-emulator)を参考に、ツールをセットアップします。

> ツールのダウンロードページでは、Windows の場合　botframework-emulator-Setup-{version}.exe をダウンロードしてインストールします。

## Visual Studio 2017

開発のベースとなるIDEです。エディションは不問です。最新の状態に更新しておきましょう。

---

[Back](README.md) | [Next](01_Create_CosmosDb.md)