<!-- pre-align:aligned sig=265591c02f39 -->

<a id="container-nhn-container-registry-ncr-release-notes"></a>
## Container > NHN Container Registry(NCR)  > リリースノート { #container-nhn-container-registry-ncr-release-notes }

<a id="august-26-2025"></a>
### 2025. 08. 26. { #august-26-2025 }

<a id="august-26-2025-feature-updates"></a>
#### 機能改善

* 複製対象NCRでソースレジストリに存在するイメージと同じイメージを識別して削除できる機能を追加しました。

<a id="november-26-2024"></a>
### 2024. 11. 26. { #november-26-2024 }

<a id="november-26-2024-feature-updates"></a>
#### 機能改善

* NCRコンソールでマルチプラットフォームイメージを使用できます。

<a id="august-27-2024"></a>
### 2024. 08. 27. { #august-27-2024 }

<a id="august-27-2024-added-features"></a>
#### 機能追加

* NCRサービスのためのPublic APIが公開されました。
  * Public APIの詳細は[APIガイド](./public-api/)を参照してください。
* Resource Watcherサービスを通じて、レジストリで発生するイベントに関する通知を受けることができます。
  * 詳細は[Resource Watcher](/Governance%20&%20Audit/Resource%20Watcher/ja/overview)を参照してください。
* イメージ署名リストを照会できます。

<a id="august-27-2024-feature-updates"></a>
#### 機能改善

* プロジェクト間の複製機能が追加されました。

<a id="may-28-2024"></a>
### 2024. 05. 28. { #may-28-2024 }

<a id="may-28-2024-added-features"></a>
#### 機能追加
* 未署名イメージ配布ブロック機能が追加されました。

<a id="may-28-2024-feature-updates"></a>
#### 機能改善
* イメージ整理/保護ポリシーで`/`が含まれたイメージも識別できるように修正しました。
* アーティファクト照会項目を拡張しました。
* イメージ整理ポリシーの数制限がなくなりました。

<a id="february-27-2024"></a>
### 2024. 02. 27. { #february-27-2024 }

<a id="february-27-2024-added-features"></a>
#### 機能追加

* NCR コンソールで発生したイベントを CloudTrail で確認できます。
* イメージ複製機能に上書きオプションを追加しました。

<a id="february-27-2024-feature-updates"></a>
#### 機能改善

* イメージのキーワード検索ができるように修正しました。

<a id="november-28-2023"></a>
### 2023. 11. 28. { #november-28-2023 }

<a id="november-28-2023-added-features"></a>
#### 機能追加
* Public URIを使用するかどうかを設定する機能を追加しました。
* イメージアップロードのみ可能な`Image Uploader`権限が追加されました。

<a id="august-29-2023"></a>
### 2023. 08. 29. { #august-29-2023 }

<a id="august-29-2023-feature-updates"></a>
#### 機能改善

* OCIアーティファクトを管理できる機能が追加されました。
* Quota機能が追加されました。

<a id="may-30-2023"></a>
### 2023. 05. 30. { #may-30-2023 }

<a id="may-30-2023-feature-updates"></a>
#### 機能改善

* リージョン間Pull複製機能を追加しました。

<a id="march-28-2023"></a>
### 2023. 03. 28. { #march-28-2023 }

<a id="march-28-2023-added-features"></a>
#### 機能追加

* イメージの信頼機能を追加しました。

<a id="january-31-2023"></a>
### 2023. 01. 31. { #january-31-2023 }

<a id="january-31-2023-added-features"></a>
#### 機能追加

* イメージの脆弱性スキャン機能を追加しました。

<a id="november-29-2022"></a>
### 2022. 11. 29. { #november-29-2022 }

<a id="november-29-2022-added-features"></a>
#### 機能追加

* イメージキャッシュ機能を追加しました。

<a id="september-27-2022"></a>
### 2022. 09. 27. { #september-27-2022 }

<a id="september-27-2022-added-features"></a>
#### 機能追加

* Private URI機能追加
  * インターネットゲートウェイに接続されていないインスタンスでNCRサービスを利用できるPrivate URI機能を追加しました。
  * 詳細については[Private URI使用ガイド](./user-guide/#use-private-uri)を参照してください。

<a id="july-26-2022"></a>
### 2022. 07. 26. { #july-26-2022 }

<a id="july-26-2022-added-features"></a>
#### 機能追加

* イメージ整理、イメージ保護機能を追加しました。

<a id="may-24-2022"></a>
### 2022. 05. 24. { #may-24-2022 }

<a id="may-24-2022-feature-updates"></a>
#### 機能改善

* レジストリドメインにnhncloud.comを使用するように修正しました。

<a id="april-26-2022"></a>
### 2022. 04. 26. { #april-26-2022 }

<a id="april-26-2022-feature-updates"></a>
#### 機能改善

* Garbage Collection機能をユーザーに表示しないように修正しました。

<a id="march-29-2022"></a>
### 2022. 03. 29. { #march-29-2022 }

<a id="march-29-2022-added-features"></a>
#### 機能追加

* リージョン間の複製機能を追加しました。

<a id="march-29-2022-feature-updates"></a>
#### 機能改善

* Container Registryサービスの名前がNHN Container Registry(NCR)に変更されました。

<a id="january-25-2022"></a>
### 2022. 01. 25. { #january-25-2022 }
<a id="january-25-2022-bug-fixes"></a>
#### バグ修正
* サービスの有効に失敗することがある問題を修正しました。
* トークンの有効時間が意図したものより短く設定されていた問題を修正しました。
* Webフック作成時、無効なエンドポイントによるエラーメッセージを細分化しました。

<a id="november-23-2021"></a>
### 2021. 11. 23. { #november-23-2021 }
<a id="november-23-2021-new-service-release"></a>
#### 新規サービスリリース
* 既存のContainer Registryサービスを改善し、より快適で安定した環境を提供します。
* 既存Container Registryサービスで不足していた点を補完し、さまざまな機能を提供します。サポートする機能は継続的にアップデートする予定です。
