//[sdk](../../../index.md)/[com.adobe.express.embedsdk.nativeeditor.domain.model](../index.md)/[NativeCancelOption](index.md)

# NativeCancelOption

\
data class [NativeCancelOption](index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = NativeEditorExportOptionId.CANCEL.value, val label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, val style: [NativeButtonStyle](../native-button-style/index.md) = NativeButtonStyle(), val actionTarget: [NativeExportActionTarget](../native-export-action-target/index.md) = NativeExportActionTarget.CANCEL, val enableByDefault: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true) : [NativeExportOption](../native-export-option/index.md)

Customises the editor's back/cancel button (always rendered on the leading edge of the top bar). At most one of these is honoured per config; any extras are ignored.

## Constructors

| | |
|---|---|
| [NativeCancelOption](native-cancel-option.md) | <br>constructor(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = NativeEditorExportOptionId.CANCEL.value, label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, style: [NativeButtonStyle](../native-button-style/index.md) = NativeButtonStyle(), actionTarget: [NativeExportActionTarget](../native-export-action-target/index.md) = NativeExportActionTarget.CANCEL, enableByDefault: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true) |

## Properties

| Name | Summary |
|---|---|
| [actionTarget](action-target.md) | <br>open override val [actionTarget](action-target.md): [NativeExportActionTarget](../native-export-action-target/index.md) |
| [enableByDefault](enable-by-default.md) | <br>val [enableByDefault](enable-by-default.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = true<br>Whether the visible back button is enabled. Defaults to `true`. When `false`, the button is rendered disabled — the user can still dismiss via the system back gesture / button (those are governed by the host's lifecycle, not by this flag). |
| [id](id.md) | <br>open override val [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [label](label.md) | <br>open override val [label](label.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [style](style.md) | <br>open override val [style](style.md): [NativeButtonStyle](../native-button-style/index.md) |
