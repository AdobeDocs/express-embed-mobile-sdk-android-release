//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[PublishButtonGroup](index.md)

# PublishButtonGroup

\
data class [PublishButtonGroup](index.md)(val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = ExportGroupType.PUBLISH_BUTTON_GROUP.type, val style: [ButtonStyle](../button-style/index.md), val label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, val options: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[PublishExportOption](../publish-export-option/index.md)&lt;[ButtonStyle](../button-style/index.md)&gt;&gt;? = null) : [ExportGroup](../export-group/index.md)

## Constructors

| | |
|---|---|
| [PublishButtonGroup](publish-button-group.md) | <br>constructor(type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = ExportGroupType.PUBLISH_BUTTON_GROUP.type, style: [ButtonStyle](../button-style/index.md), label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, options: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[PublishExportOption](../publish-export-option/index.md)&lt;[ButtonStyle](../button-style/index.md)&gt;&gt;? = null) |

## Properties

| Name | Summary |
|---|---|
| [label](label.md) | <br>val [label](label.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null |
| [options](options.md) | <br>val [options](options.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[PublishExportOption](../publish-export-option/index.md)&lt;[ButtonStyle](../button-style/index.md)&gt;&gt;? = null |
| [style](style.md) | <br>open override val [style](style.md): [ButtonStyle](../button-style/index.md) |
| [type](type.md) | <br>open override val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
