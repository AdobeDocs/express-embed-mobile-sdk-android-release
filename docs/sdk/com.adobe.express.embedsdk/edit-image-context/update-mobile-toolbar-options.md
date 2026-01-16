//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[EditImageContext](index.md)/[updateMobileToolbarOptions](update-mobile-toolbar-options.md)

# updateMobileToolbarOptions

\
abstract suspend fun [updateMobileToolbarOptions](update-mobile-toolbar-options.md)(iconsList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;MobileToolbarOption&gt;): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)

Updates or adds custom icons to the Edit Image interface This function allows dynamic addition/update of icons during an active editing session. Icons with the same ID will be updated, new icons will be added.

#### Return

true if icons were updated successfully, false otherwise
