//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[WishesAndGreetingsCategory](index.md)

# WishesAndGreetingsCategory

\
data class [WishesAndGreetingsCategory](index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, @[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)val labelRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)? = null, val collectionId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, val searchTerm: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null)

A Wishes & greetings category pill. Remote catalog entries carry a display [label](label.md); the bundled fallback catalog sets [labelRes](label-res.md) instead so its labels resolve through Android string resources.

## Constructors

| | |
|---|---|
| [WishesAndGreetingsCategory](wishes-and-greetings-category.md) | <br>constructor(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, @[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)labelRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)? = null, collectionId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, searchTerm: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [collectionId](collection-id.md) | <br>val [collectionId](collection-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null |
| [id](id.md) | <br>val [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [label](label.md) | <br>val [label](label.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [labelRes](label-res.md) | <br>val [labelRes](label-res.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)? = null |
| [searchTerm](search-term.md) | <br>val [searchTerm](search-term.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null |
