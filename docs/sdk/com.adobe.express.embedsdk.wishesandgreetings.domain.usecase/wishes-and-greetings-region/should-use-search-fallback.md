//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.usecase](../index.md)/[WishesAndGreetingsRegion](index.md)/[shouldUseSearchFallback](should-use-search-fallback.md)

# shouldUseSearchFallback

\
fun [shouldUseSearchFallback](should-use-search-fallback.md)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?, searchTerm: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)

Mirrors web `TemplatesService._shouldUseSearchFallback`: a non-IN user with a [searchTerm](should-use-search-fallback.md) bypasses the category's `collectionId` and does a free-text search instead.
