//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ModuleWorkflowInterface](index.md)

# ModuleWorkflowInterface

\
interface [ModuleWorkflowInterface](index.md)

## Functions

| Name | Summary |
|---|---|
| [activePreloadIntent](active-preload-intent.md) | <br>abstract fun [activePreloadIntent](active-preload-intent.md)(): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/set/index.html)&lt;ActionIntent&gt;? |
| [createImageFromText](create-image-from-text.md) | <br>abstract fun [createImageFromText](create-image-from-text.md)(textToImageAppConfig: TextToImageAppConfig? = null, exportConfig: ExportConfig? = null, containerConfig: ContainerConfig? = null, fragment: [Fragment](https://developer.android.com/reference/kotlin/androidx/fragment/app/Fragment.html))<br>Launches the text-to-image generation workflow. |
| [editImage](edit-image.md) | <br>abstract fun [editImage](edit-image.md)(editImageDocConfig: EditImageDocConfig, editImageAppConfig: EditImageAppConfig? = null, exportConfig: ExportConfig? = null, containerConfig: ContainerConfig? = null, fragment: [Fragment](https://developer.android.com/reference/kotlin/androidx/fragment/app/Fragment.html)): [EditImageContext](../edit-image-context/index.md)<br>Launches the comprehensive image editing workflow. |
| [purgeWarmupSession](purge-warmup-session.md) | <br>abstract fun [purgeWarmupSession](purge-warmup-session.md)(intent: ActionIntent? = null): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)<br>Purge the background warmup session for the given intent. This closes any preload/precache WebView and ends the warmup action. |
| [warmup](warmup.md) | <br>abstract fun [warmup](warmup.md)(intent: ActionIntent, context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), mode: WarmupMode, moduleWarmupConfig: [ModuleWarmupConfig](../module-warmup-config/index.md)? = null) |
