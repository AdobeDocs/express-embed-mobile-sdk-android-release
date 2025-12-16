//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[AdoptionStrategy](index.md)

# AdoptionStrategy

[androidJvm]\
enum [AdoptionStrategy](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-enum/index.html)&lt;[AdoptionStrategy](index.md)&gt; 

Defines the strategy for performing the adoption.

## Entries

| | |
|---|---|
| [NO_ADOPTION](-n-o_-a-d-o-p-t-i-o-n/index.md) | [androidJvm]<br>[NO_ADOPTION](-n-o_-a-d-o-p-t-i-o-n/index.md)<br>Actions are incompatible, create separate containers. Example: preload route to edit-image route (old warmup mechanism for caching resources). |
| [MESSAGE_ADOPTION](-m-e-s-s-a-g-e_-a-d-o-p-t-i-o-n/index.md) | [androidJvm]<br>[MESSAGE_ADOPTION](-m-e-s-s-a-g-e_-a-d-o-p-t-i-o-n/index.md)<br>Message based adoption strategy, wherein we send a message to existing WebView to continue loading from current state. E.g., Send SWITCH_EMBED_ACTION message to existing WebView to continue loading from current state. |

## Properties

| Name | Summary |
|---|---|
| [entries](entries.md) | [androidJvm]<br>val [entries](entries.md): [EnumEntries](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.enums/-enum-entries/index.html)&lt;[AdoptionStrategy](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | [androidJvm]<br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)): [AdoptionStrategy](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | [androidJvm]<br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[AdoptionStrategy](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
