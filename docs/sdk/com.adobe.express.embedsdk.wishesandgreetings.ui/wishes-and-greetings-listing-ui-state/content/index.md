//[sdk](../../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.ui](../../index.md)/[WishesAndGreetingsListingUiState](../index.md)/[Content](index.md)

# Content

\
data class [Content](index.md)(val categories: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[WishesAndGreetingsCategory](../../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-category/index.md)&gt;, val selectedCategoryId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val assetsState: [WishesAndGreetingsStockAssetsState](../../wishes-and-greetings-stock-assets-state/index.md), val expandedTitle: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null) : [WishesAndGreetingsListingUiState](../index.md)

Categories loaded; [assetsState](assets-state.md) carries the paged content for [selectedCategoryId](selected-category-id.md).

## Constructors

| | |
|---|---|
| [Content](content.md) | <br>constructor(categories: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[WishesAndGreetingsCategory](../../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-category/index.md)&gt;, selectedCategoryId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), assetsState: [WishesAndGreetingsStockAssetsState](../../wishes-and-greetings-stock-assets-state/index.md), expandedTitle: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [assetsState](assets-state.md) | <br>val [assetsState](assets-state.md): [WishesAndGreetingsStockAssetsState](../../wishes-and-greetings-stock-assets-state/index.md) |
| [categories](categories.md) | <br>val [categories](categories.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[WishesAndGreetingsCategory](../../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-category/index.md)&gt; |
| [expandedTitle](expanded-title.md) | <br>val [expandedTitle](expanded-title.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null<br>Non-null when drilled into a sub-collection (&quot;View all&quot;); the pill row is hidden. |
| [selectedCategoryId](selected-category-id.md) | <br>val [selectedCategoryId](selected-category-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
