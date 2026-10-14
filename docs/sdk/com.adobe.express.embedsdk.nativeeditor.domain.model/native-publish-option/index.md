//[sdk](../../../index.md)/[com.adobe.express.embedsdk.nativeeditor.domain.model](../index.md)/[NativePublishOption](index.md)

# NativePublishOption

\
data class [NativePublishOption](index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val style: [NativeButtonStyle](../native-button-style/index.md) = NativeButtonStyle(), val actionTarget: [NativeExportActionTarget](../native-export-action-target/index.md) = NativeExportActionTarget.PUBLISH, val publishFileType: [NativeExportFileType](../native-export-file-type/index.md) = NativeExportFileType.PNG, val closeOnPublish: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true, val enableByDefault: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false, val outputType: AssetDataType? = null) : [NativeExportOption](../native-export-option/index.md)

Triggers an export of the current edit and reports the result through com.adobe.express.embedsdk.Callbacks.onPublish.

## Constructors

| | |
|---|---|
| [NativePublishOption](native-publish-option.md) | <br>constructor(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), style: [NativeButtonStyle](../native-button-style/index.md) = NativeButtonStyle(), actionTarget: [NativeExportActionTarget](../native-export-action-target/index.md) = NativeExportActionTarget.PUBLISH, publishFileType: [NativeExportFileType](../native-export-file-type/index.md) = NativeExportFileType.PNG, closeOnPublish: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true, enableByDefault: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false, outputType: AssetDataType? = null) |

## Properties

| Name | Summary |
|---|---|
| [actionTarget](action-target.md) | <br>open override val [actionTarget](action-target.md): [NativeExportActionTarget](../native-export-action-target/index.md) |
| [closeOnPublish](close-on-publish.md) | <br>val [closeOnPublish](close-on-publish.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true<br>Whether the editor dismisses itself after publish. Defaults to `false` so the host can chain follow-up actions in com.adobe.express.embedsdk.Callbacks.onPublish before closing. |
| [enableByDefault](enable-by-default.md) | <br>val [enableByDefault](enable-by-default.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false<br>Host gate for the button: when `false`, the button is always disabled. When `true` (default), the button is enabled only after the user has made an edit (i.e. when undo is available). Set `false` to suppress a configured publish option. |
| [id](id.md) | <br>open override val [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [label](label.md) | <br>open override val [label](label.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [outputType](output-type.md) | <br>val [outputType](output-type.md): AssetDataType? = null<br>Asset data format the exported OutputAsset should be built with. AssetDataType.URL provides only a URL asset; AssetDataType.BASE64 or `null` (default) provides only a base64 asset. |
| [publishFileType](publish-file-type.md) | <br>val [publishFileType](publish-file-type.md): [NativeExportFileType](../native-export-file-type/index.md)<br>Output format the editor writes when this option is invoked. The host's com.adobe.express.embedsdk.Callbacks.onPublish receives the file with this MIME type. |
| [style](style.md) | <br>open override val [style](style.md): [NativeButtonStyle](../native-button-style/index.md) |
