//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ExportOptionGroup](index.md)

# ExportOptionGroup

\
data class [ExportOptionGroup](index.md)(val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = ExportGroupType.BUTTON_GROUP.type, val style: [ButtonStyle](../button-style/index.md), val label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val options: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[DropdownExportOption](../dropdown-export-option/index.md)&gt;) : [ExportGroup](../export-group/index.md)

## Constructors

| | |
|---|---|
| [ExportOptionGroup](export-option-group.md) | <br>constructor(type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = ExportGroupType.BUTTON_GROUP.type, style: [ButtonStyle](../button-style/index.md), label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), options: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[DropdownExportOption](../dropdown-export-option/index.md)&gt;) |

## Properties

| Name | Summary |
|---|---|
| [label](label.md) | <br>val [label](label.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [options](options.md) | <br>val [options](options.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[DropdownExportOption](../dropdown-export-option/index.md)&gt; |
| [style](style.md) | <br>open override val [style](style.md): [ButtonStyle](../button-style/index.md) |
| [type](type.md) | <br>open override val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
