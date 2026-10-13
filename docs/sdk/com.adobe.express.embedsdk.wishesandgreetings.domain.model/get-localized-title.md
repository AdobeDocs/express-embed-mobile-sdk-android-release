//[sdk](../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](index.md)/[getLocalizedTitle](get-localized-title.md)

# getLocalizedTitle

\
fun [getLocalizedTitle](get-localized-title.md)(names: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;, locale: [Locale](https://developer.android.com/reference/kotlin/java/util/Locale.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)

Picks the [names](get-localized-title.md) entry for [locale](get-localized-title.md) (pass the SDK-configured UI locale), else the ACP `i-default` title, else &quot;&quot;.
