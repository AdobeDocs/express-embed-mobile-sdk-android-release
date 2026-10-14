//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[AcpAssetList](index.md)

# AcpAssetList

\
@Serializable

data class [AcpAssetList](index.md)(val items: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[AcpAsset](../acp-asset/index.md)&gt; = emptyList(), val links: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [Link](../link/index.md)&gt; = emptyMap())

## Constructors

| | |
|---|---|
| [AcpAssetList](acp-asset-list.md) | <br>constructor(items: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[AcpAsset](../acp-asset/index.md)&gt; = emptyList(), links: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [Link](../link/index.md)&gt; = emptyMap()) |

## Properties

| Name | Summary |
|---|---|
| [items](items.md) | <br>@SerialName(value = &quot;items&quot;)<br>val [items](items.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[AcpAsset](../acp-asset/index.md)&gt; |
| [links](links.md) | <br>@SerialName(value = &quot;_links&quot;)<br>val [links](links.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [Link](../link/index.md)&gt; |
| [nextLink](next-link.md) | <br>val [nextLink](next-link.md): [Link](../link/index.md)? |
