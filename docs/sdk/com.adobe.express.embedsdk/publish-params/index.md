//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[PublishParams](index.md)

# PublishParams

open class [PublishParams](index.md)

Asset related information received with onPublish callback.

#### Inheritors

| |
|---|
| [QuickActionPublishParams](../quick-action-publish-params/index.md) |
| [EditorPublishParams](../editor-publish-params/index.md) |
| [TextToImagePublishParams](../text-to-image-publish-params/index.md) |

## Constructors

| | |
|---|---|
| [PublishParams](publish-params.md) | <br>constructor() |

## Properties

| Name | Summary |
|---|---|
| [asset](asset.md) | <br>var [asset](asset.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[OutputAsset](../output-asset/index.md)&gt;?<br>Asset which is exported |
| [documentId](document-id.md) | <br>var [documentId](document-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>Unique identifier for the assets created/edited. |
| [exportButtonId](export-button-id.md) | <br>var [exportButtonId](export-button-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>id of the export option clicked |
