//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ValidateTokenError](index.md)

# ValidateTokenError

\
enum [ValidateTokenError](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/enum/index.html)&lt;[ValidateTokenError](index.md)&gt; 

Token validation error types for authentication failures.

## Entries

| | |
|---|---|
| [UNKNOWN](u-n-k-n-o-w-n/index.md) | <br>[UNKNOWN](u-n-k-n-o-w-n/index.md)<br>Unknown validation error |
| [BAD_SIGNATURE](b-a-d_-s-i-g-n-a-t-u-r-e/index.md) | <br>[BAD_SIGNATURE](b-a-d_-s-i-g-n-a-t-u-r-e/index.md)<br>Token signature validation failed |
| [INVALID_TOKEN](i-n-v-a-l-i-d_-t-o-k-e-n/index.md) | <br>[INVALID_TOKEN](i-n-v-a-l-i-d_-t-o-k-e-n/index.md)<br>Token format or content is invalid |
| [TIMEOUT](t-i-m-e-o-u-t/index.md) | <br>[TIMEOUT](t-i-m-e-o-u-t/index.md)<br>Token validation request timed out |

## Properties

| Name | Summary |
|---|---|
| [entries](entries.md) | <br>val [entries](entries.md): [EnumEntries](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.enums/enum-entries/index.html)&lt;[ValidateTokenError](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |
| [value](value.md) | <br>val [value](value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>String identifier for the validation error |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | <br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [ValidateTokenError](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | <br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/array/index.html)&lt;[ValidateTokenError](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
