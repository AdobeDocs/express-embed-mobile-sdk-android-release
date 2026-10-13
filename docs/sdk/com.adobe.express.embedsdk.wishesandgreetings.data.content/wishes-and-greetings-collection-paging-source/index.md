//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.data.content](../index.md)/[WishesAndGreetingsCollectionPagingSource](index.md)

# WishesAndGreetingsCollectionPagingSource

\
class [WishesAndGreetingsCollectionPagingSource](index.md)(api: [WishesAndGreetingsContentServiceApi](../wishes-and-greetings-content-service-api/index.md), source: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)?, templatesRoot: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), locale: [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html), orderedAllowlist: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? = null, maxConcurrentTasks: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html) = 5) : [PagingSource](https://developer.android.com/reference/kotlin/androidx/paging/PagingSource.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [WishesAndGreetingsCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-collection/index.md)&gt; 

Paging source over a collection's child collections, hydrating each with a row of hero assets (the browse carousels).

## Constructors

| | |
|---|---|
| [WishesAndGreetingsCollectionPagingSource](wishes-and-greetings-collection-paging-source.md) | <br>constructor(api: [WishesAndGreetingsContentServiceApi](../wishes-and-greetings-content-service-api/index.md), source: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)?, templatesRoot: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), locale: [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html), orderedAllowlist: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? = null, maxConcurrentTasks: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html) = 5) |

## Functions

| Name | Summary |
|---|---|
| [getRefreshKey](get-refresh-key.md) | <br>open override fun [getRefreshKey](get-refresh-key.md)(state: [PagingState](https://developer.android.com/reference/kotlin/androidx/paging/PagingState.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [WishesAndGreetingsCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-collection/index.md)&gt;): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? |
| [load](load.md) | <br>open suspend override fun [load](load.md)(params: [PagingSource.LoadParams](https://developer.android.com/reference/kotlin/androidx/paging/PagingSource.LoadParams.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;): [PagingSource.LoadResult](https://developer.android.com/reference/kotlin/androidx/paging/PagingSource.LoadResult.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [WishesAndGreetingsCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-collection/index.md)&gt; |
