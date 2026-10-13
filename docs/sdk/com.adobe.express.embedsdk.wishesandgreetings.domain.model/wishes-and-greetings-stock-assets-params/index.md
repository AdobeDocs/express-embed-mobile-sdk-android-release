//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[WishesAndGreetingsStockAssetsParams](index.md)

# WishesAndGreetingsStockAssetsParams

\
data class [WishesAndGreetingsStockAssetsParams](index.md)(val dataSource: [WishesAndGreetingsContentRoot](../wishes-and-greetings-content-root/index.md), val searchTerms: [SearchTerms](../search-terms/index.md), val breadcrumbs: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[WishesAndGreetingsCollection](../wishes-and-greetings-collection/index.md)&gt; = emptyList(), val collectionId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, val shuffle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false)

The one-per-category browse request consumed by [com.adobe.express.embedsdk.wishesandgreetings.domain.usecase.WishesAndGreetingsBrowseCollectionsUseCase](../../com.adobe.express.embedsdk.wishesandgreetings.domain.usecase/wishes-and-greetings-browse-collections-use-case/index.md).

## Constructors

| | |
|---|---|
| [WishesAndGreetingsStockAssetsParams](wishes-and-greetings-stock-assets-params.md) | <br>constructor(dataSource: [WishesAndGreetingsContentRoot](../wishes-and-greetings-content-root/index.md), searchTerms: [SearchTerms](../search-terms/index.md), breadcrumbs: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[WishesAndGreetingsCollection](../wishes-and-greetings-collection/index.md)&gt; = emptyList(), collectionId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, shuffle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false) |

## Properties

| Name | Summary |
|---|---|
| [breadcrumbs](breadcrumbs.md) | <br>val [breadcrumbs](breadcrumbs.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[WishesAndGreetingsCollection](../wishes-and-greetings-collection/index.md)&gt; |
| [collectionId](collection-id.md) | <br>val [collectionId](collection-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null |
| [dataSource](data-source.md) | <br>val [dataSource](data-source.md): [WishesAndGreetingsContentRoot](../wishes-and-greetings-content-root/index.md) |
| [searchTerms](search-terms.md) | <br>val [searchTerms](search-terms.md): [SearchTerms](../search-terms/index.md) |
| [shuffle](shuffle.md) | <br>val [shuffle](shuffle.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false |
