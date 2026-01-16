//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WarmupMode](index.md)

# WarmupMode

\
enum [WarmupMode](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/enum/index.html)&lt;[WarmupMode](index.md)&gt;

## Entries

| | |
|---|---|
| [PRE_CACHE](p-r-e_-c-a-c-h-e/index.md) | <br>[PRE_CACHE](p-r-e_-c-a-c-h-e/index.md)<br>The mode in which resources are fetched from the CDN via service worker and cached e.g., /preload route. |
| [PRE_LOAD](p-r-e_-l-o-a-d/index.md) | <br>[PRE_LOAD](p-r-e_-l-o-a-d/index.md)<br>The application will be preloaded upto certain point in the workflow. e.g., /edit-image-preload?preload=true |

## Properties

| Name | Summary |
|---|---|
| [entries](entries.md) | <br>val [entries](entries.md): [EnumEntries](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.enums/enum-entries/index.html)&lt;[WarmupMode](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | <br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [WarmupMode](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | <br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/array/index.html)&lt;[WarmupMode](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
