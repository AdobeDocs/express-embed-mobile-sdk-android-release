//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[WishesAndGreetingsBrowseState](index.md)

# WishesAndGreetingsBrowseState

sealed interface [WishesAndGreetingsBrowseState](index.md)

The domain-level result emitted by [com.adobe.express.embedsdk.wishesandgreetings.domain.usecase.WishesAndGreetingsBrowseCollectionsUseCase](../../com.adobe.express.embedsdk.wishesandgreetings.domain.usecase/wishes-and-greetings-browse-collections-use-case/index.md) for a single [WishesAndGreetingsStockAssetsParams](../wishes-and-greetings-stock-assets-params/index.md) request.

#### Inheritors

| |
|---|
| [Collections](collections/index.md) |
| [Assets](assets/index.md) |
| [Error](error/index.md) |

## Types

| Name | Summary |
|---|---|
| [Assets](assets/index.md) | <br>data class [Assets](assets/index.md)(val params: [WishesAndGreetingsStockAssetsParams](../wishes-and-greetings-stock-assets-params/index.md), val results: Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../wishes-and-greetings-asset/index.md)&gt;&gt;, val currentCollection: [ContentCollection](../content-collection/index.md)) : [WishesAndGreetingsBrowseState](index.md)<br>A flat grid of template assets (search results or a leaf collection's assets). |
| [Collections](collections/index.md) | <br>data class [Collections](collections/index.md)(val params: [WishesAndGreetingsStockAssetsParams](../wishes-and-greetings-stock-assets-params/index.md), val results: Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsCollection](../wishes-and-greetings-collection/index.md)&gt;&gt;, val currentCollection: [ContentCollection](../content-collection/index.md)) : [WishesAndGreetingsBrowseState](index.md)<br>The resolved collection exposes child sub-collections (a row-of-rows browse view). |
| [Error](error/index.md) | <br>data class [Error](error/index.md)(val params: [WishesAndGreetingsStockAssetsParams](../wishes-and-greetings-stock-assets-params/index.md), val error: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/exception/index.html)) : [WishesAndGreetingsBrowseState](index.md)<br>The content root / collection could not be resolved. |

## Properties

| Name | Summary |
|---|---|
| [params](params.md) | <br>abstract val [params](params.md): [WishesAndGreetingsStockAssetsParams](../wishes-and-greetings-stock-assets-params/index.md) |
