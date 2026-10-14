//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[ContentCollection](index.md)

# ContentCollection

\
@Serializable

data class [ContentCollection](index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val parentDirectoryId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, val ancestorAssetIds: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt; = emptyList(), val contentType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, val path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, val names: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt; = emptyMap(), val links: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [Link](../link/index.md)&gt; = emptyMap(), val collectionSpec: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [CollectionSpec](../collection-spec/index.md)&gt; = emptyMap())

## Constructors

| | |
|---|---|
| [ContentCollection](content-collection.md) | <br>constructor(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), parentDirectoryId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, ancestorAssetIds: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt; = emptyList(), contentType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, names: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt; = emptyMap(), links: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [Link](../link/index.md)&gt; = emptyMap(), collectionSpec: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [CollectionSpec](../collection-spec/index.md)&gt; = emptyMap()) |

## Types

| Name | Summary |
|---|---|
| [Companion](companion/index.md) | <br>object [Companion](companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [ancestorAssetIds](ancestor-asset-ids.md) | <br>@SerialName(value = &quot;ancestorAssetIds&quot;)<br>val [ancestorAssetIds](ancestor-asset-ids.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt; |
| [assetsLink](assets-link.md) | <br>val [assetsLink](assets-link.md): [Link](../link/index.md)? |
| [assetType](asset-type.md) | <br>val [assetType](asset-type.md): [ContentAssetType](../content-asset-type/index.md) |
| [collectionsLink](collections-link.md) | <br>val [collectionsLink](collections-link.md): [Link](../link/index.md)? |
| [collectionSpec](collection-spec.md) | <br>@SerialName(value = &quot;collectionSpecifications&quot;)<br>val [collectionSpec](collection-spec.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [CollectionSpec](../collection-spec/index.md)&gt; |
| [contentType](content-type.md) | <br>@SerialName(value = &quot;contentType&quot;)<br>val [contentType](content-type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [id](id.md) | <br>@SerialName(value = &quot;id&quot;)<br>val [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [links](links.md) | <br>@SerialName(value = &quot;_links&quot;)<br>val [links](links.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [Link](../link/index.md)&gt; |
| [names](names.md) | <br>@SerialName(value = &quot;dc:title&quot;)<br>val [names](names.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt; |
| [parentDirectoryId](parent-directory-id.md) | <br>@SerialName(value = &quot;parentDirectoryId&quot;)<br>val [parentDirectoryId](parent-directory-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [path](path.md) | <br>@SerialName(value = &quot;path&quot;)<br>val [path](path.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [searchLink](search-link.md) | <br>val [searchLink](search-link.md): [Link](../link/index.md)? |

## Functions

| Name | Summary |
|---|---|
| [localizedName](localized-name.md) | <br>fun [localizedName](localized-name.md)(locale: [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>Title for [locale](localized-name.md) (the SDK-configured UI locale), falling back to the ACP default title. |
