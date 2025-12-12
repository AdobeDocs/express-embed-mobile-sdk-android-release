//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ModuleWorkflowInterface](index.md)

# ModuleWorkflowInterface

[androidJvm]\
interface [ModuleWorkflowInterface](index.md)

## Functions

| Name | Summary |
|---|---|
| [activePreloadIntent](active-preload-intent.md) | [androidJvm]<br>abstract fun [activePreloadIntent](active-preload-intent.md)(): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-set/index.html)&lt;[ActionIntent](../-action-intent/index.md)&gt;? |
| [createImageFromText](create-image-from-text.md) | [androidJvm]<br>abstract fun [createImageFromText](create-image-from-text.md)(textToImageAppConfig: TextToImageAppConfig? = null, exportConfig: [ExportConfig](../-export-config/index.md)? = null, containerConfig: [ContainerConfig](../-container-config/index.md)? = null, fragment: [Fragment](https://developer.android.com/reference/kotlin/androidx/fragment/app/Fragment.html))<br>Launches the text-to-image generation workflow. |
| [editImage](edit-image.md) | [androidJvm]<br>abstract fun [editImage](edit-image.md)(editImageDocConfig: [EditImageDocConfig](../-edit-image-doc-config/index.md), editImageAppConfig: EditImageAppConfig? = null, exportConfig: [ExportConfig](../-export-config/index.md)? = null, containerConfig: [ContainerConfig](../-container-config/index.md)? = null, fragment: [Fragment](https://developer.android.com/reference/kotlin/androidx/fragment/app/Fragment.html)): [EditImageContext](../-edit-image-context/index.md)<br>Launches the comprehensive image editing workflow. |
| [purgeWarmupSession](purge-warmup-session.md) | [androidJvm]<br>abstract fun [purgeWarmupSession](purge-warmup-session.md)(intent: [ActionIntent](../-action-intent/index.md)? = null): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Purge the background warmup session for the given intent. This closes any preload/precache WebView and ends the warmup action. |
| [warmup](warmup.md) | [androidJvm]<br>abstract fun [warmup](warmup.md)(intent: [ActionIntent](../-action-intent/index.md), context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), mode: [WarmupMode](../-warmup-mode/index.md), moduleWarmupConfig: [ModuleWarmupConfig](../-module-warmup-config/index.md)? = null) |
