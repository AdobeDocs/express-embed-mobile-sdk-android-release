//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[AuthMode](index.md)

# AuthMode

\
enum [AuthMode](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/enum/index.html)&lt;[AuthMode](index.md)&gt; 

Authentication modes determining when and how users are authenticated.

## Entries

| | |
|---|---|
| [UPFRONT](u-p-f-r-o-n-t/index.md) | <br>[UPFRONT](u-p-f-r-o-n-t/index.md)<br>User authentication is upfront. |
| [DELAYED](d-e-l-a-y-e-d/index.md) | <br>[DELAYED](d-e-l-a-y-e-d/index.md)<br>Authentication is delayed. |
| [PRE_SIGNED_IN](p-r-e_-s-i-g-n-e-d_-i-n/index.md) | <br>[PRE_SIGNED_IN](p-r-e_-s-i-g-n-e-d_-i-n/index.md)<br>User is pre-signed in. |
| [IMS_JUMP](i-m-s_-j-u-m-p/index.md) | <br>[IMS_JUMP](i-m-s_-j-u-m-p/index.md)<br>Authentication is through IMS jump. |

## Properties

| Name | Summary |
|---|---|
| [entries](entries.md) | <br>val [entries](entries.md): [EnumEntries](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.enums/enum-entries/index.html)&lt;[AuthMode](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |
| [value](value.md) | <br>val [value](value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>String identifier for the authentication mode |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | <br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [AuthMode](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | <br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/array/index.html)&lt;[AuthMode](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
