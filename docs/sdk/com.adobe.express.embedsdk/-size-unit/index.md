//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[SizeUnit](index.md)

# SizeUnit

\
enum [SizeUnit](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/enum/index.html)&lt;[SizeUnit](index.md)&gt; 

Units of measurement for asset dimensions and sizing. Defines the measurement system used for width and height values.

## Entries

| | |
|---|---|
| [PIXELS](p-i-x-e-l-s/index.md) | <br>[PIXELS](p-i-x-e-l-s/index.md)<br>Pixels (screen/digital measurement) |
| [MILLIMETERS](m-i-l-l-i-m-e-t-e-r-s/index.md) | <br>[MILLIMETERS](m-i-l-l-i-m-e-t-e-r-s/index.md)<br>Millimeters (metric measurement) |
| [INCHES](i-n-c-h-e-s/index.md) | <br>[INCHES](i-n-c-h-e-s/index.md)<br>Inches (imperial measurement) |
| [CENTIMETERS](c-e-n-t-i-m-e-t-e-r-s/index.md) | <br>[CENTIMETERS](c-e-n-t-i-m-e-t-e-r-s/index.md)<br>Centimeters (metric measurement) |

## Properties

| Name | Summary |
|---|---|
| [entries](entries.md) | <br>val [entries](entries.md): [EnumEntries](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.enums/enum-entries/index.html)&lt;[SizeUnit](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |
| [unit](unit.md) | <br>val [unit](unit.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>String identifier for the measurement unit |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | <br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [SizeUnit](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | <br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/array/index.html)&lt;[SizeUnit](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
