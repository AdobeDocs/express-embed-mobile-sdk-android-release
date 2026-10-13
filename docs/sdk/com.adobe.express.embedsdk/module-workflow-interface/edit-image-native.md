//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ModuleWorkflowInterface](index.md)/[editImageNative](edit-image-native.md)

# editImageNative

\
open fun [editImageNative](edit-image-native.md)(editImageNativeDocConfig: EditImageNativeDocConfig, editImageNativeAppConfig: EditImageNativeAppConfig, exportConfig: [NativeExportConfig](../../com.adobe.express.embedsdk.nativeeditor.domain.model/native-export-config/index.md)? = null): [EmbedSdkEditImageNativeFragment](../../com.adobe.express.embedsdk.nativeeditor.ui.editor/embed-sdk-edit-image-native-fragment/index.md)

Launches the native image editing workflow. Available to 1P clients only. 3P callers receive [UnsupportedOperationException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/unsupported-operation-exception/index.html) at runtime.

#### Parameters

androidJvm

| | |
|---|---|
| editImageNativeDocConfig | Input image asset configuration. |
| editImageNativeAppConfig | Callbacks, dismiss handler, and behavior configuration. |
| exportConfig | Optional export options for the top bar. |
