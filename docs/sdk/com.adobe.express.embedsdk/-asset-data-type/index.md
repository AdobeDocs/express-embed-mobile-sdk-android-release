//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[AssetDataType](index.md)

# AssetDataType

\
enum [AssetDataType](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/enum/index.html)&lt;[AssetDataType](index.md)&gt; 

Supported data formats for asset content representation. Defines how the asset data is encoded or accessed.

## Entries

| | |
|---|---|
| [BASE64](b-a-s-e64/index.md) | <br>[BASE64](b-a-s-e64/index.md)<br>Base64 encoded string data |
| [URL](u-r-l/index.md) | <br>[URL](u-r-l/index.md)<br>URL reference to asset location |
| [BLOB](b-l-o-b/index.md) | <br>[BLOB](b-l-o-b/index.md)<br>Binary blob data |

## Types

| Name | Summary |
|---|---|
| [Companion](companion/index.md) | <br>object [Companion](companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [entries](entries.md) | <br>val [entries](entries.md): [EnumEntries](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.enums/enum-entries/index.html)&lt;[AssetDataType](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |
| [value](value.md) | <br>val [value](value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>String identifier for the data type |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | <br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [AssetDataType](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | <br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/array/index.html)&lt;[AssetDataType](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
