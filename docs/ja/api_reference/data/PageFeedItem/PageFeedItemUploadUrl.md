# PageFeedItemUploadUrl

PageFeedItemUploadUrlオブジェクトは、アップロードURLを取得するための処理の内容を表します。

## Service

- [PageFeedItemService](../../services/PageFeedItemService.md)

## Namespace

[PageFeedItemService#Namespace](../../services/PageFeedItemService.md#namespace)

| フィールド        | データ型                                                       | response | getUploadUrl | 説明             |
|--------------|------------------------------------------------------------|----------|--------------|----------------|
| accountId    | xsd:long                                                   | ○        | Ignore       | アカウント       |
| uploadType   | enum [PageFeedItemUploadType](./PageFeedItemUploadType.md) | ○        | Requirement  | アップロード方法の種類 |
| feedFolderId | xsd:long                                                   | ○        | Requirement  | フィードフォルダID  |
| url          | xsd:string                                                 | ○        | Ignore       | アップロードURL   |

[![クリエイティブ・コモンズ・ライセンス](https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png)](http://creativecommons.org/licenses/by-nd/2.1/jp/)<br>
この 作品 は [クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。](http://creativecommons.org/licenses/by-nd/2.1/jp/)
