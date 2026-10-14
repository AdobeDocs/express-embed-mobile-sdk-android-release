//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[AcpAsset](index.md)

# AcpAsset

\
@Serializable

data class [AcpAsset](index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val contentType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, val licensingCategory: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, val path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, val task: [AcpPageTask](../acp-page-task/index.md)? = null, val pages: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[AcpPage](../acp-page/index.md)&gt;? = null, val names: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? = null, val links: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [Link](../link/index.md)&gt; = emptyMap(), val behaviors: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? = null, var assetJson: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, val totalAssetCount: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/long/index.html) = 0) : [ContentAsset](../content-asset/index.md)

## Constructors

| | |
|---|---|
| [AcpAsset](acp-asset.md) | <br>constructor(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), contentType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, licensingCategory: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, task: [AcpPageTask](../acp-page-task/index.md)? = null, pages: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[AcpPage](../acp-page/index.md)&gt;? = null, names: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? = null, links: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [Link](../link/index.md)&gt; = emptyMap(), behaviors: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? = null, assetJson: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, totalAssetCount: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/long/index.html) = 0) |

## Types

| Name | Summary |
|---|---|
| [Companion](companion/index.md) | <br>object [Companion](companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [aspectRatio](aspect-ratio.md) | <br>open override val [aspectRatio](aspect-ratio.md): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/float/index.html)? |
| [assetJson](asset-json.md) | <br>open override var [assetJson](asset-json.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? |
| [assetType](asset-type.md) | <br>open override val [assetType](asset-type.md): [ContentAssetType](../content-asset-type/index.md) |
| [behaviors](behaviors.md) | <br>@SerialName(value = &quot;behaviors&quot;)<br>val [behaviors](behaviors.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? = null |
| [compUrl](comp-url.md) | <br>open override val [compUrl](comp-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null |
| [contentType](content-type.md) | <br>@SerialName(value = &quot;contentType&quot;)<br>val [contentType](content-type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [downloadUrl](download-url.md) | <br>open override val [downloadUrl](download-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null |
| [duration](duration.md) | <br>open override val [duration](duration.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/double/index.html) = 0.0 |
| [id](id.md) | <br>@SerialName(value = &quot;id&quot;)<br>open override val [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [isAnimated](is-animated.md) | <br>open override val [isAnimated](is-animated.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [isGentech](is-gentech.md) | <br>open override val [isGentech](is-gentech.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false |
| [isMultiPage](is-multi-page.md) | <br>open override val [isMultiPage](is-multi-page.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [isPremium](is-premium.md) | <br>open override val [isPremium](is-premium.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [isVideo](is-video.md) | <br>open override val [isVideo](is-video.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [keywords](keywords.md) | <br>open override val [keywords](keywords.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt; |
| [licensingCategory](licensing-category.md) | <br>@SerialName(value = &quot;licensingCategory&quot;)<br>val [licensingCategory](licensing-category.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [links](links.md) | <br>@SerialName(value = &quot;_links&quot;)<br>val [links](links.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [Link](../link/index.md)&gt; |
| [names](names.md) | <br>@SerialName(value = &quot;dc:title&quot;)<br>open override val [names](names.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? = null |
| [pages](pages.md) | <br>@SerialName(value = &quot;pages&quot;)<br>open override val [pages](pages.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[AcpPage](../acp-page/index.md)&gt;? = null |
| [path](path.md) | <br>@SerialName(value = &quot;path&quot;)<br>val [path](path.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [source](source.md) | <br>open override val [source](source.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [task](task.md) | <br>@SerialName(value = &quot;task&quot;)<br>open override val [task](task.md): [AcpPageTask](../acp-page-task/index.md)? = null |
| [thumbnails](thumbnails.md) | <br>open override val [thumbnails](thumbnails.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt; |
| [title](title.md) | <br>open override val [title](title.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null |
| [totalAssetCount](total-asset-count.md) | <br>open override val [totalAssetCount](total-asset-count.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/long/index.html) = 0 |
| [type](type.md) | <br>@SerialName(value = &quot;assetType&quot;)<br>val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [videoPreviewUrl](video-preview-url.md) | <br>open override val [videoPreviewUrl](video-preview-url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null |
