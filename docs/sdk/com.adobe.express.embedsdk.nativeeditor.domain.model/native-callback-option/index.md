//[sdk](../../../index.md)/[com.adobe.express.embedsdk.nativeeditor.domain.model](../index.md)/[NativeCallbackOption](index.md)

# NativeCallbackOption

\
data class [NativeCallbackOption](index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val style: [NativeButtonStyle](../native-button-style/index.md) = NativeButtonStyle(), val actionTarget: [NativeExportActionTarget](../native-export-action-target/index.md) = NativeExportActionTarget.CALLBACK, val publishFileType: [NativeExportFileType](../native-export-file-type/index.md) = NativeExportFileType.PNG, val closeOnPublish: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true, val enableByDefault: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true) : [NativeExportOption](../native-export-option/index.md)

Invokes a host-defined callback identified by [id](id.md). No export is performed automatically; the host handles the action from com.adobe.express.embedsdk.Callbacks.onEvent.

Routed by [actionTarget](action-target.md); callback targets dispatch com.adobe.express.embedsdk.shared.messenger.HostCallbackRequestEvent.

## Constructors

| | |
|---|---|
| [NativeCallbackOption](native-callback-option.md) | <br>constructor(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), style: [NativeButtonStyle](../native-button-style/index.md) = NativeButtonStyle(), actionTarget: [NativeExportActionTarget](../native-export-action-target/index.md) = NativeExportActionTarget.CALLBACK, publishFileType: [NativeExportFileType](../native-export-file-type/index.md) = NativeExportFileType.PNG, closeOnPublish: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true, enableByDefault: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true) |

## Properties

| Name | Summary |
|---|---|
| [actionTarget](action-target.md) | <br>open override val [actionTarget](action-target.md): [NativeExportActionTarget](../native-export-action-target/index.md) |
| [closeOnPublish](close-on-publish.md) | <br>val [closeOnPublish](close-on-publish.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true<br>Whether the editor dismisses itself after the callback's publish flow completes. Defaults to `true`. Host-defined callback ids are responsible for dismissing themselves. |
| [enableByDefault](enable-by-default.md) | <br>val [enableByDefault](enable-by-default.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true<br>Whether the button starts enabled. Defaults to `true` since callbacks usually drive host-side actions that are valid at any time. |
| [id](id.md) | <br>open override val [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [label](label.md) | <br>open override val [label](label.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [publishFileType](publish-file-type.md) | <br>val [publishFileType](publish-file-type.md): [NativeExportFileType](../native-export-file-type/index.md)<br>Format hint for hosts that want to publish the edited image from their callback. |
| [style](style.md) | <br>open override val [style](style.md): [NativeButtonStyle](../native-button-style/index.md) |
