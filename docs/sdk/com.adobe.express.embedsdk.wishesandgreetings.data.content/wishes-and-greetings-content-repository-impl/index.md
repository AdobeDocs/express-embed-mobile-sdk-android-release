//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.data.content](../index.md)/[WishesAndGreetingsContentRepositoryImpl](index.md)

# WishesAndGreetingsContentRepositoryImpl

\
class [WishesAndGreetingsContentRepositoryImpl](index.md)(api: [WishesAndGreetingsContentServiceApi](../wishes-and-greetings-content-service-api/index.md), isProd: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html), localeProvider: () -&gt; [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html)) : [WishesAndGreetingsContentRepository](../../com.adobe.express.embedsdk.wishesandgreetings.domain.repository/wishes-and-greetings-content-repository/index.md)

ACP content-service repository for the Wishes & greetings browse.

## Constructors

| | |
|---|---|
| [WishesAndGreetingsContentRepositoryImpl](wishes-and-greetings-content-repository-impl.md) | <br>constructor(api: [WishesAndGreetingsContentServiceApi](../wishes-and-greetings-content-service-api/index.md), isProd: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html), localeProvider: () -&gt; [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html)) |

## Functions

| Name | Summary |
|---|---|
| [isChildCollectionListEffectivelyEmpty](is-child-collection-list-effectively-empty.md) | <br>open suspend override fun [isChildCollectionListEffectivelyEmpty](is-child-collection-list-effectively-empty.md)(parent: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [loadAssets](load-assets.md) | <br>open override fun [loadAssets](load-assets.md)(source: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)?, shuffle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)): Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-asset/index.md)&gt;&gt; |
| [loadCollections](load-collections.md) | <br>open override fun [loadCollections](load-collections.md)(source: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), orderedAllowlist: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;?, searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)?): Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-collection/index.md)&gt;&gt; |
| [loadSearchAssets](load-search-assets.md) | <br>open override fun [loadSearchAssets](load-search-assets.md)(source: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md), shuffle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)): Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-asset/index.md)&gt;&gt; |
| [resolve](resolve.md) | <br>open suspend override fun [resolve](resolve.md)(dataSource: [WishesAndGreetingsContentRoot](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-content-root/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)?, collectionId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?): [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md)? |
