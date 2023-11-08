# 国土数値情報をPMTilesに変換するリポジトリ ()

> GitHub Actionsで自動的にPMTilesに変換

## 何をしているか

GitHub Actionsで以下のことを行なっています。

1. 国土数値情報のダウンロード
2. [tippecanoe]でPMTilesに変換
3. GitHub Pagesにデプロイ

## 注意

国土数値情報は正規のWeb APIサービスを提供していましたが、2020年に廃止されています。したがって、このリポジトリで実行する国土数値情報のダウンロードはダウンロードURLをハック的な方法で取得しています。

## 使い方

### 設定

### リポジトリの設定

### Actions

Workflow permissions:  
  **Read and write permissions**

### Pages

Build and deployment Source:  
  **GitHub Actions**

[tippecanoe]: https://github.com/felt/tippecanoe
