//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[LogLevel](index.md)

# LogLevel

\
enum [LogLevel](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/enum/index.html)&lt;[LogLevel](index.md)&gt; 

Log level enumeration for controlling SDK logging verbosity. Higher numeric values indicate more restrictive logging.

## Entries

| | |
|---|---|
| [INFO](i-n-f-o/index.md) | <br>[INFO](i-n-f-o/index.md)<br>Informational messages |
| [WARN](w-a-r-n/index.md) | <br>[WARN](w-a-r-n/index.md)<br>Warning messages |
| [ERROR](e-r-r-o-r/index.md) | <br>[ERROR](e-r-r-o-r/index.md)<br>Error messages only |
| [NONE](n-o-n-e/index.md) | <br>[NONE](n-o-n-e/index.md)<br>No logging |

## Properties

| Name | Summary |
|---|---|
| [entries](entries.md) | <br>val [entries](entries.md): [EnumEntries](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.enums/enum-entries/index.html)&lt;[LogLevel](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |
| [level](level.md) | <br>val [level](level.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)<br>Numeric level for log filtering |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | <br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [LogLevel](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | <br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/array/index.html)&lt;[LogLevel](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
