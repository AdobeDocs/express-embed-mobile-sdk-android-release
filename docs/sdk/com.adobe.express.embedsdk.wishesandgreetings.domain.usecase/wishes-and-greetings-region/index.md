//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.usecase](../index.md)/[WishesAndGreetingsRegion](index.md)

# WishesAndGreetingsRegion

\
object [WishesAndGreetingsRegion](index.md)

Pure, framework-free region logic for the Wishes & greetings browse.

## Properties

| Name | Summary |
|---|---|
| [INDIA_REGION](i-n-d-i-a_-r-e-g-i-o-n.md) | <br>const val [INDIA_REGION](i-n-d-i-a_-r-e-g-i-o-n.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |

## Functions

| Name | Summary |
|---|---|
| [currentCountryCode](current-country-code.md) | <br>fun [currentCountryCode](current-country-code.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>Device country (uppercased ISO code) from the SDK/JVM locale, or null when unavailable. |
| [shouldUseSearchFallback](should-use-search-fallback.md) | <br>fun [shouldUseSearchFallback](should-use-search-fallback.md)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?, searchTerm: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)<br>Mirrors web `TemplatesService._shouldUseSearchFallback`: a non-IN user with a [searchTerm](should-use-search-fallback.md) bypasses the category's `collectionId` and does a free-text search instead. |
