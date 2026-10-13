//[sdk](../../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../../index.md)/[WishesAndGreetingsBrowseState](../index.md)/[Collections](index.md)

# Collections

\
data class [Collections](index.md)(val params: [WishesAndGreetingsStockAssetsParams](../../wishes-and-greetings-stock-assets-params/index.md), val results: Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsCollection](../../wishes-and-greetings-collection/index.md)&gt;&gt;, val currentCollection: [ContentCollection](../../content-collection/index.md)) : [WishesAndGreetingsBrowseState](../index.md)

The resolved collection exposes child sub-collections (a row-of-rows browse view).

## Constructors

| | |
|---|---|
| [Collections](collections.md) | <br>constructor(params: [WishesAndGreetingsStockAssetsParams](../../wishes-and-greetings-stock-assets-params/index.md), results: Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsCollection](../../wishes-and-greetings-collection/index.md)&gt;&gt;, currentCollection: [ContentCollection](../../content-collection/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [currentCollection](current-collection.md) | <br>val [currentCollection](current-collection.md): [ContentCollection](../../content-collection/index.md) |
| [params](params.md) | <br>open override val [params](params.md): [WishesAndGreetingsStockAssetsParams](../../wishes-and-greetings-stock-assets-params/index.md) |
| [results](results.md) | <br>val [results](results.md): Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsCollection](../../wishes-and-greetings-collection/index.md)&gt;&gt; |
