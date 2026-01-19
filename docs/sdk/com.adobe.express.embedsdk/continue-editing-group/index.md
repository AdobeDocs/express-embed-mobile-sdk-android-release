//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ContinueEditingGroup](index.md)

# ContinueEditingGroup

\
data class [ContinueEditingGroup](index.md)(val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = ExportGroupType.CONTINUE_EDITING.type, val style: [ButtonStyle](../button-style/index.md), val label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, val options: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[ContinueEditingDropdownOption](../continue-editing-dropdown-option/index.md)&gt;? = null) : [ExportGroup](../export-group/index.md)

## Constructors

| | |
|---|---|
| [ContinueEditingGroup](continue-editing-group.md) | <br>constructor(type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = ExportGroupType.CONTINUE_EDITING.type, style: [ButtonStyle](../button-style/index.md), label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, options: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[ContinueEditingDropdownOption](../continue-editing-dropdown-option/index.md)&gt;? = null) |

## Properties

| Name | Summary |
|---|---|
| [label](label.md) | <br>val [label](label.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null |
| [options](options.md) | <br>val [options](options.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[ContinueEditingDropdownOption](../continue-editing-dropdown-option/index.md)&gt;? = null |
| [style](style.md) | <br>open override val [style](style.md): [ButtonStyle](../button-style/index.md) |
| [type](type.md) | <br>open override val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
