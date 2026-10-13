//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.ui](../index.md)/[WishesAndGreetingsStockAssetsState](index.md)

# WishesAndGreetingsStockAssetsState

sealed interface [WishesAndGreetingsStockAssetsState](index.md)

UI-facing content state for the paged template area, mapped from the Phase 3 domain [com.adobe.express.embedsdk.wishesandgreetings.domain.model.WishesAndGreetingsBrowseState](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-browse-state/index.md) by WishesAndGreetingsListingViewModel.

#### Inheritors

| |
|---|
| [Loading](loading/index.md) |
| [Error](error/index.md) |
| [Collections](collections/index.md) |
| [Assets](assets/index.md) |

## Types

| Name | Summary |
|---|---|
| [Assets](assets/index.md) | <br>data class [Assets](assets/index.md)(val results: Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsAsset](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-asset/index.md)&gt;&gt;, val currentCollection: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md)) : [WishesAndGreetingsStockAssetsState](index.md)<br>Flat grid of template assets (search results or a leaf collection's assets). |
| [Collections](collections/index.md) | <br>data class [Collections](collections/index.md)(val results: Flow&lt;[PagingData](https://developer.android.com/reference/kotlin/androidx/paging/PagingData.html)&lt;[WishesAndGreetingsCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-collection/index.md)&gt;&gt;, val currentCollection: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md)) : [WishesAndGreetingsStockAssetsState](index.md)<br>Sub-collections browse view (a vertical list of hero rows). |
| [Error](error/index.md) | <br>data class [Error](error/index.md)(val error: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/exception/index.html)) : [WishesAndGreetingsStockAssetsState](index.md)<br>The content root / collection could not be resolved. |
| [Loading](loading/index.md) | <br>data object [Loading](loading/index.md) : [WishesAndGreetingsStockAssetsState](index.md)<br>No stream resolved yet — the grid area shows a shimmer. |
