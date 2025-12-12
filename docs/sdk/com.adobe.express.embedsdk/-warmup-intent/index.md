//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WarmupIntent](index.md)

# WarmupIntent

[androidJvm]\
internal enum [WarmupIntent](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-enum/index.html)&lt;[WarmupIntent](index.md)&gt; , [ActionIntent](../-action-intent/index.md)

Internal warmup intent for performance optimization. Used internally to preload resources and improve launch performance.

## Entries

| | |
|---|---|
| [WARMUP](-w-a-r-m-u-p/index.md) | [androidJvm]<br>[WARMUP](-w-a-r-m-u-p/index.md)<br>Warmup session for resource preloading |

## Properties

| Name | Summary |
|---|---|
| [entries](entries.md) | [androidJvm]<br>val [entries](entries.md): [EnumEntries](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.enums/-enum-entries/index.html)&lt;[WarmupIntent](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |
| [value](value.md) | [androidJvm]<br>open override val [value](value.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)<br>String identifier for the action intent |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | [androidJvm]<br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)): [WarmupIntent](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | [androidJvm]<br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[WarmupIntent](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
