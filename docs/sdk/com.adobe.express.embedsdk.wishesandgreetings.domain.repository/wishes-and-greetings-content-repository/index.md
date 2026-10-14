//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.repository](../index.md)/[WishesAndGreetingsContentRepository](index.md)

# WishesAndGreetingsContentRepository

interface [WishesAndGreetingsContentRepository](index.md)

Content-service data contract for the Wishes & greetings browse experience (anonymous ACP access only).

#### Inheritors

| |
|---|
| [WishesAndGreetingsContentRepositoryImpl](../../com.adobe.express.embedsdk.wishesandgreetings.data.content/wishes-and-greetings-content-repository-impl/index.md) |

## Functions

| Name | Summary |
|---|---|
| [isChildCollectionListEffectivelyEmpty](is-child-collection-list-effectively-empty.md) | <br>abstract suspend fun [isChildCollectionListEffectivelyEmpty](is-child-collection-list-effectively-empty.md)(parent: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)? = null): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [loadAssets](load-assets.md) | <br>abstract fun [loadAssets](load-assets.md)(source: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)? = null, shuffle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false): Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-asset/index.md)&gt;&gt; |
| [loadCollections](load-collections.md) | <br>abstract fun [loadCollections](load-collections.md)(source: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), orderedAllowlist: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? = null, searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)? = null): Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-collection/index.md)&gt;&gt; |
| [loadSearchAssets](load-search-assets.md) | <br>abstract fun [loadSearchAssets](load-search-assets.md)(source: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md), shuffle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false): Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-asset/index.md)&gt;&gt; |
| [resolve](resolve.md) | <br>abstract suspend fun [resolve](resolve.md)(dataSource: [WishesAndGreetingsContentRoot](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-content-root/index.md), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)? = null, collectionId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null): [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md)? |
