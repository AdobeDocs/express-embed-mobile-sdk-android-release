//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ModuleWorkflowInterface](index.md)/[annotateImage](annotate-image.md)

# annotateImage

\
abstract fun [annotateImage](annotate-image.md)(annotateImageDocConfig: AnnotateImageDocConfig, annotateImageAppConfig: AnnotateImageAppConfig? = null, exportConfig: ExportConfig? = null, containerConfig: ContainerConfig? = null, fragment: [Fragment](https://developer.android.com/reference/kotlin/androidx/fragment/app/Fragment.html), onAnnotateImageContextReady: ([AnnotateImageContext](../annotate-image-context/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/unit/index.html)? = null)

Annotate images by drawing, adding shapes and text over the input image.

#### Parameters

androidJvm

| | |
|---|---|
| annotateImageDocConfig | Input asset and document payload for the annotate-image module |
| annotateImageAppConfig | Optional module UI and behavior configuration |
| exportConfig | Export options |
| containerConfig | SDK container options |
| onAnnotateImageContextReady | Invoked with the [AnnotateImageContext](../annotate-image-context/index.md) once the annotate session actually launches — after the preview's Markup tap, or immediately when no preview is shown. It is NOT invoked if the user dismisses the preview without starting markup, since no annotate session exists in that case. |
