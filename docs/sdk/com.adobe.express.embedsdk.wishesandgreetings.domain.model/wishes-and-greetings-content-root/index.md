//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[WishesAndGreetingsContentRoot](index.md)

# WishesAndGreetingsContentRoot

\
enum [WishesAndGreetingsContentRoot](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/enum/index.html)&lt;[WishesAndGreetingsContentRoot](index.md)&gt; 

The Adobe Content Service root URNs the Wishes & greetings surface browses.

## Entries

| | |
|---|---|
| [TEMPLATES](t-e-m-p-l-a-t-e-s/index.md) | <br>[TEMPLATES](t-e-m-p-l-a-t-e-s/index.md) |

## Properties

| Name | Summary |
|---|---|
| [analyticsName](analytics-name.md) | <br>val [analyticsName](analytics-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [entries](entries.md) | <br>val [entries](entries.md): [EnumEntries](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.enums/enum-entries/index.html)&lt;[WishesAndGreetingsContentRoot](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |
| [pageLimit](page-limit.md) | <br>val [pageLimit](page-limit.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html) |

## Functions

| Name | Summary |
|---|---|
| [root](root.md) | <br>fun [root](root.md)(isProd: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>Resolves the root URN for the current environment. |
| [valueOf](value-of.md) | <br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [WishesAndGreetingsContentRoot](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | <br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/array/index.html)&lt;[WishesAndGreetingsContentRoot](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
