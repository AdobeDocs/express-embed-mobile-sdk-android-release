//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[EditImageContextImpl](index.md)

# EditImageContextImpl

[androidJvm]\
internal class [EditImageContextImpl](index.md)(ccEverywhereInstance: [CCEverywhereBase](../-c-c-everywhere-base/index.md)) : [WorkflowContext](../-workflow-context/index.md), [EditImageContext](../-edit-image-context/index.md)

Implementation of EditImageContext for Edit Image workflow operations

## Constructors

| | |
|---|---|
| [EditImageContextImpl](-edit-image-context-impl.md) | [androidJvm]<br>constructor(ccEverywhereInstance: [CCEverywhereBase](../-c-c-everywhere-base/index.md)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [getAsset](get-asset.md) | [androidJvm]<br>open suspend override fun [getAsset](get-asset.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;[OutputAsset](../-output-asset/index.md)&gt;<br>Gets the published assets from the current editing session |
| [hasUnsavedChanges](has-unsaved-changes.md) | [androidJvm]<br>open suspend override fun [hasUnsavedChanges](has-unsaved-changes.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Checks if there are any unsaved changes in the current editing session |
