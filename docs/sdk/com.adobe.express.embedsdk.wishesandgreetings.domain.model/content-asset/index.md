//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[ContentAsset](index.md)

# ContentAsset

interface [ContentAsset](index.md)

Source-agnostic asset contract consumed by convertToAsset and the paging sources.

#### Inheritors

| |
|---|
| [AcpAsset](../acp-asset/index.md) |

## Properties

| Name | Summary |
|---|---|
| [aspectRatio](aspect-ratio.md) | <br>abstract val [aspectRatio](aspect-ratio.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/float/index.html)? |
| [assetJson](asset-json.md) | <br>abstract var [assetJson](asset-json.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? |
| [assetType](asset-type.md) | <br>abstract val [assetType](asset-type.md): [ContentAssetType](../content-asset-type/index.md) |
| [compUrl](comp-url.md) | <br>abstract val [compUrl](comp-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? |
| [downloadUrl](download-url.md) | <br>abstract val [downloadUrl](download-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? |
| [duration](duration.md) | <br>abstract val [duration](duration.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/double/index.html) |
| [id](id.md) | <br>abstract val [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [isAnimated](is-animated.md) | <br>abstract val [isAnimated](is-animated.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [isGentech](is-gentech.md) | <br>abstract val [isGentech](is-gentech.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [isMultiPage](is-multi-page.md) | <br>abstract val [isMultiPage](is-multi-page.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [isPremium](is-premium.md) | <br>abstract val [isPremium](is-premium.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [isVideo](is-video.md) | <br>abstract val [isVideo](is-video.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [keywords](keywords.md) | <br>abstract val [keywords](keywords.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? |
| [names](names.md) | <br>abstract val [names](names.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? |
| [pages](pages.md) | <br>abstract val [pages](pages.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[AcpPage](../acp-page/index.md)&gt;? |
| [source](source.md) | <br>abstract val [source](source.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [task](task.md) | <br>abstract val [task](task.md): [AcpPageTask](../acp-page-task/index.md)? |
| [thumbnails](thumbnails.md) | <br>abstract val [thumbnails](thumbnails.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt; |
| [title](title.md) | <br>abstract val [title](title.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? |
| [totalAssetCount](total-asset-count.md) | <br>abstract val [totalAssetCount](total-asset-count.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/long/index.html) |
| [videoPreviewUrl](video-preview-url.md) | <br>abstract val [videoPreviewUrl](video-preview-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? |
