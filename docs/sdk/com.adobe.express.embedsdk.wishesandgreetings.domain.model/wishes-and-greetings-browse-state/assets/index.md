//[sdk](../../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../../index.md)/[WishesAndGreetingsBrowseState](../index.md)/[Assets](index.md)

# Assets

\
data class [Assets](index.md)(val params: [WishesAndGreetingsStockAssetsParams](../../wishes-and-greetings-stock-assets-params/index.md), val results: Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../../wishes-and-greetings-asset/index.md)&gt;&gt;, val currentCollection: [ContentCollection](../../content-collection/index.md)) : [WishesAndGreetingsBrowseState](../index.md)

A flat grid of template assets (search results or a leaf collection's assets).

## Constructors

| | |
|---|---|
| [Assets](assets.md) | <br>constructor(params: [WishesAndGreetingsStockAssetsParams](../../wishes-and-greetings-stock-assets-params/index.md), results: Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../../wishes-and-greetings-asset/index.md)&gt;&gt;, currentCollection: [ContentCollection](../../content-collection/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [currentCollection](current-collection.md) | <br>val [currentCollection](current-collection.md): [ContentCollection](../../content-collection/index.md) |
| [params](params.md) | <br>open override val [params](params.md): [WishesAndGreetingsStockAssetsParams](../../wishes-and-greetings-stock-assets-params/index.md) |
| [results](results.md) | <br>val [results](results.md): Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../../wishes-and-greetings-asset/index.md)&gt;&gt; |
