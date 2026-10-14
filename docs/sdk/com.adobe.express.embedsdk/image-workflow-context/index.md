//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ImageWorkflowContext](index.md)

# ImageWorkflowContext

interface [ImageWorkflowContext](index.md)

Public surface shared by every image-module workflow context (e.g. EditImage, AnnotateImage). Workflow-specific contexts extend this interface and add their own operations on top.

#### Inheritors

| |
|---|
| [AnnotateImageContext](../annotate-image-context/index.md) |
| [EditImageContext](../edit-image-context/index.md) |

## Functions

| Name | Summary |
|---|---|
| [getAsset](get-asset.md) | <br>abstract suspend fun [getAsset](get-asset.md)(assetConfig: AssetConfig): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;OutputAsset&gt;<br>Gets the published assets from the current session. |
| [hasUnsavedChanges](has-unsaved-changes.md) | <br>abstract suspend fun [hasUnsavedChanges](has-unsaved-changes.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)<br>Checks if there are any unsaved changes in the current session. |
| [updateMobileToolbarOptions](update-mobile-toolbar-options.md) | <br>open suspend fun &lt;[T](update-mobile-toolbar-options.md)&gt; [updateMobileToolbarOptions](update-mobile-toolbar-options.md)(iconsList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[T](update-mobile-toolbar-options.md)&gt;): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)<br>Updates or adds custom icons to a workflow's mobile toolbar. Icons with the same ID are updated in place, unmatched ids are added. |
