//[sdk](../../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.ui](../../index.md)/[WishesAndGreetingsStockAssetsState](../index.md)/[Assets](index.md)

# Assets

\
data class [Assets](index.md)(val results: Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-asset/index.md)&gt;&gt;, val currentCollection: [ContentCollection](../../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md)) : [WishesAndGreetingsStockAssetsState](../index.md)

Flat grid of template assets (search results or a leaf collection's assets).

## Constructors

| | |
|---|---|
| [Assets](assets.md) | <br>constructor(results: Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-asset/index.md)&gt;&gt;, currentCollection: [ContentCollection](../../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [currentCollection](current-collection.md) | <br>val [currentCollection](current-collection.md): [ContentCollection](../../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md) |
| [results](results.md) | <br>val [results](results.md): Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-asset/index.md)&gt;&gt; |
