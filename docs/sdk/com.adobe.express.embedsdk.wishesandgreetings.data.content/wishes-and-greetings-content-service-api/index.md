//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.data.content](../index.md)/[WishesAndGreetingsContentServiceApi](index.md)

# WishesAndGreetingsContentServiceApi

\
class [WishesAndGreetingsContentServiceApi](index.md)(contentEndpoint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), apiKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), httpClient: HttpClient, json: Json = Json { ignoreUnknownKeys = true })

Anonymous Adobe Content Service (ACP) HTTP surface for the Wishes & greetings templates browse: requests carry only the `x-api-key`, never a user token.

## Constructors

| | |
|---|---|
| [WishesAndGreetingsContentServiceApi](wishes-and-greetings-content-service-api.md) | <br>constructor(contentEndpoint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), apiKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), httpClient: HttpClient, json: Json = Json { ignoreUnknownKeys = true }) |

## Types

| Name | Summary |
|---|---|
| [Companion](companion/index.md) | <br>object [Companion](companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [getChildAssetsWithLink](get-child-assets-with-link.md) | <br>suspend fun [getChildAssetsWithLink](get-child-assets-with-link.md)(href: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [ContentAssetList](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-asset-list/index.md)<br>Fetches one ACP asset page from [href](get-child-assets-with-link.md). Callers pass a link from [getInitialAssetsLink](get-initial-assets-link.md) or [getInitialSearchAssetsLink](get-initial-search-assets-link.md) (both already require an ACP link) or an ACP page's `next` link. |
| [getChildCollectionsWithLink](get-child-collections-with-link.md) | <br>suspend fun [getChildCollectionsWithLink](get-child-collections-with-link.md)(href: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [ContentCollectionList](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection-list/index.md) |
| [getInitialAssetsLink](get-initial-assets-link.md) | <br>fun [getInitialAssetsLink](get-initial-assets-link.md)(collection: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)? = null): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>Builds the ACP browse-assets link for [collection](get-initial-assets-link.md). |
| [getInitialCollectionsLink](get-initial-collections-link.md) | <br>fun [getInitialCollectionsLink](get-initial-collections-link.md)(collection: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)? = null): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>Builds the ACP collections link for [collection](get-initial-collections-link.md) (adds only the region filter, if present). |
| [getInitialSearchAssetsLink](get-initial-search-assets-link.md) | <br>fun [getInitialSearchAssetsLink](get-initial-search-assets-link.md)(collection: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>Builds the ACP search-assets link for [collection](get-initial-search-assets-link.md). |
| [resolve](resolve.md) | <br>suspend fun [resolve](resolve.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md)? |
