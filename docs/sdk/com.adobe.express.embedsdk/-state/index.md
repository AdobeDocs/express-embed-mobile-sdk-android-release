//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[State](index.md)

# State

\
enum [State](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/enum/index.html)&lt;[State](index.md)&gt; 

Current initialization state of the Adobe Express Embed SDK.

## Entries

| | |
|---|---|
| [NOT_INITIALIZED](n-o-t_-i-n-i-t-i-a-l-i-z-e-d/index.md) | <br>[NOT_INITIALIZED](n-o-t_-i-n-i-t-i-a-l-i-z-e-d/index.md)<br>SDK is not initialized and no operations are available |
| [INITIALIZING](i-n-i-t-i-a-l-i-z-i-n-g/index.md) | <br>[INITIALIZING](i-n-i-t-i-a-l-i-z-i-n-g/index.md)<br>SDK initialization is in progress (transient state) |
| [INITIALIZED](i-n-i-t-i-a-l-i-z-e-d/index.md) | <br>[INITIALIZED](i-n-i-t-i-a-l-i-z-e-d/index.md)<br>SDK is fully initialized and ready for use |

## Properties

| Name | Summary |
|---|---|
| [entries](entries.md) | <br>val [entries](entries.md): [EnumEntries](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.enums/enum-entries/index.html)&lt;[State](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |
| [value](value.md) | <br>val [value](value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>String identifier for the state |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | <br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [State](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | <br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/array/index.html)&lt;[State](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
