//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[PublishAction](index.md)

# PublishAction

\
data class [PublishAction](index.md)(val target: [ExportTarget](../export-target/index.md), val publishFileType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, val closeTargetOnExport: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = null, val outputType: [AssetDataType](../asset-data-type/index.md)? = null, val enableByDefault: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = null) : [BaseActionInterface](../base-action-interface/index.md)

## Constructors

| | |
|---|---|
| [PublishAction](publish-action.md) | <br>constructor(target: [ExportTarget](../export-target/index.md), publishFileType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, closeTargetOnExport: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = null, outputType: [AssetDataType](../asset-data-type/index.md)? = null, enableByDefault: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [closeTargetOnExport](close-target-on-export.md) | <br>val [closeTargetOnExport](close-target-on-export.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = null |
| [enableByDefault](enable-by-default.md) | <br>val [enableByDefault](enable-by-default.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = null |
| [outputType](output-type.md) | <br>val [outputType](output-type.md): [AssetDataType](../asset-data-type/index.md)? = null |
| [publishFileType](publish-file-type.md) | <br>val [publishFileType](publish-file-type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null |
| [target](target.md) | <br>open override val [target](target.md): [ExportTarget](../export-target/index.md) |
