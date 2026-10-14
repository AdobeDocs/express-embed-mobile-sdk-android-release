//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.usecase](../index.md)/[WishesAndGreetingsBrowseCollectionsUseCase](index.md)

# WishesAndGreetingsBrowseCollectionsUseCase

\
class [WishesAndGreetingsBrowseCollectionsUseCase](index.md)

Resolves a [WishesAndGreetingsStockAssetsParams](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-stock-assets-params/index.md) request into a [WishesAndGreetingsBrowseState](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-browse-state/index.md) flow.

## Constructors

| | |
|---|---|
| [WishesAndGreetingsBrowseCollectionsUseCase](wishes-and-greetings-browse-collections-use-case.md) | <br>constructor() |

## Types

| Name | Summary |
|---|---|
| [Companion](companion/index.md) | <br>object [Companion](companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [execute](execute.md) | <br>fun [execute](execute.md)(params: [WishesAndGreetingsStockAssetsParams](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-stock-assets-params/index.md), contentRepository: [WishesAndGreetingsContentRepository](../../com.adobe.express.embedsdk.wishesandgreetings.domain.repository/wishes-and-greetings-content-repository/index.md), countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = WishesAndGreetingsRegion.currentCountryCode()): Flow&lt;[WishesAndGreetingsBrowseState](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-browse-state/index.md)&gt; |
