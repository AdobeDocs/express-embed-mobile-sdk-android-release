//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.data.content](../index.md)/[WishesAndGreetingsAssetPagingSource](index.md)

# WishesAndGreetingsAssetPagingSource

\
class [WishesAndGreetingsAssetPagingSource](index.md)(api: [WishesAndGreetingsContentServiceApi](../wishes-and-greetings-content-service-api/index.md), source: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)?, templatesRoot: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), locale: [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html), shuffle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false) : [PagingSource](https://developer.android.com/reference/kotlin/androidx/paging/PagingSource.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [WishesAndGreetingsAsset](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-asset/index.md)&gt; 

Paging source over a single ACP collection's assets (the flat template grid).

## Constructors

| | |
|---|---|
| [WishesAndGreetingsAssetPagingSource](wishes-and-greetings-asset-paging-source.md) | <br>constructor(api: [WishesAndGreetingsContentServiceApi](../wishes-and-greetings-content-service-api/index.md), source: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)?, templatesRoot: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), locale: [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html), shuffle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false) |

## Functions

| Name | Summary |
|---|---|
| [getRefreshKey](get-refresh-key.md) | <br>open override fun [getRefreshKey](get-refresh-key.md)(state: [PagingState](https://developer.android.com/reference/kotlin/androidx/paging/PagingState.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [WishesAndGreetingsAsset](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-asset/index.md)&gt;): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? |
| [load](load.md) | <br>open suspend override fun [load](load.md)(params: [PagingSource.LoadParams](https://developer.android.com/reference/kotlin/androidx/paging/PagingSource.LoadParams.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;): [PagingSource.LoadResult](https://developer.android.com/reference/kotlin/androidx/paging/PagingSource.LoadResult.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [WishesAndGreetingsAsset](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-asset/index.md)&gt; |
