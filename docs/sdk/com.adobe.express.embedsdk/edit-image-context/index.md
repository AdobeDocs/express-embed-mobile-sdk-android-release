//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[EditImageContext](index.md)

# EditImageContext

\
interface [EditImageContext](index.md)

Interface for Edit Image workflow context operations This context provides access to workflow-specific functionality for the Edit Image workflow, allowing clients to interact with the active editing session.

## Functions

| Name | Summary |
|---|---|
| [getAsset](get-asset.md) | <br>abstract suspend fun [getAsset](get-asset.md)(assetConfig: AssetConfig): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[OutputAsset](../output-asset/index.md)&gt;<br>Gets the published assets from the current editing session |
| [hasUnsavedChanges](has-unsaved-changes.md) | <br>abstract suspend fun [hasUnsavedChanges](has-unsaved-changes.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)<br>Checks if there are any unsaved changes in the current editing session |
| [updateMobileToolbarOptions](update-mobile-toolbar-options.md) | <br>abstract suspend fun [updateMobileToolbarOptions](update-mobile-toolbar-options.md)(iconsList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;MobileToolbarOption&gt;): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)<br>Updates or adds custom icons to the Edit Image interface This function allows dynamic addition/update of icons during an active editing session. Icons with the same ID will be updated, new icons will be added. |
