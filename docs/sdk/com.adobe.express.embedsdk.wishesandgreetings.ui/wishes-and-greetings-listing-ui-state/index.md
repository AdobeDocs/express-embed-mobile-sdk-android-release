//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.ui](../index.md)/[WishesAndGreetingsListingUiState](index.md)

# WishesAndGreetingsListingUiState

sealed interface [WishesAndGreetingsListingUiState](index.md)

Screen state for the Wishes & greetings listing, ported from theo-android `NativeHSWishesListingUiState`.

#### Inheritors

| |
|---|
| [Loading](loading/index.md) |
| [Content](content/index.md) |
| [Error](error/index.md) |

## Types

| Name | Summary |
|---|---|
| [Content](content/index.md) | <br>data class [Content](content/index.md)(val categories: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[WishesAndGreetingsCategory](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-category/index.md)&gt;, val selectedCategoryId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val assetsState: [WishesAndGreetingsStockAssetsState](../wishes-and-greetings-stock-assets-state/index.md), val expandedTitle: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null) : [WishesAndGreetingsListingUiState](index.md)<br>Categories loaded; [assetsState](content/assets-state.md) carries the paged content for [selectedCategoryId](content/selected-category-id.md). |
| [Error](error/index.md) | <br>data class [Error](error/index.md)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)val messageRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)) : [WishesAndGreetingsListingUiState](index.md)<br>Category catalog failed to load (the load-bearing fallback also failed). |
| [Loading](loading/index.md) | <br>data object [Loading](loading/index.md) : [WishesAndGreetingsListingUiState](index.md)<br>Categories / first stream not resolved yet. |
