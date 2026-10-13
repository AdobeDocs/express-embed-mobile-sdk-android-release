//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.data.content](../index.md)/[WishesAndGreetingsContentServiceApi](index.md)/[getInitialCollectionsLink](get-initial-collections-link.md)

# getInitialCollectionsLink

\
fun [getInitialCollectionsLink](get-initial-collections-link.md)(collection: [ContentCollection](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/content-collection/index.md), limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html), searchTerms: [SearchTerms](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/search-terms/index.md)? = null): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?

Builds the ACP collections link for [collection](get-initial-collections-link.md) (adds only the region filter, if present).
