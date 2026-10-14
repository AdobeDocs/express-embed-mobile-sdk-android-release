//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ImageWorkflowContext](index.md)/[updateMobileToolbarOptions](update-mobile-toolbar-options.md)

# updateMobileToolbarOptions

\
open suspend fun &lt;[T](update-mobile-toolbar-options.md)&gt; [updateMobileToolbarOptions](update-mobile-toolbar-options.md)(iconsList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[T](update-mobile-toolbar-options.md)&gt;): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)

Updates or adds custom icons to a workflow's mobile toolbar. Icons with the same ID are updated in place, unmatched ids are added.

Each workflow accepts only its own toolbar-option type: MobileToolbarOption for the WebView-based workflows (e.g. EditImage), and `NativeMobileToolbarOption` for the native editor. Passing entries of any other type is a programming error and throws (see `@throws`) rather than failing silently. The base implementation is a no-op for workflows that do not support toolbar updates.

#### Return

true if icons were updated successfully, false otherwise (default: false).

#### Parameters

androidJvm

| | |
|---|---|
| iconsList | Toolbar options for this workflow (e.g. MobileToolbarOption or [com.adobe.express.embedsdk.nativeeditor.domain.model.NativeMobileToolbarOption](../../com.adobe.express.embedsdk.nativeeditor.domain.model/native-mobile-toolbar-option/index.md)). |

#### Throws

| | |
|---|---|
| [CCEverywhereError](../c-c-everywhere-error/index.md) | with [ErrorCode.UNSUPPORTED_MOBILE_TOOLBAR_OPTION](../error-code/-u-n-s-u-p-p-o-r-t-e-d_-m-o-b-i-l-e_-t-o-o-l-b-a-r_-o-p-t-i-o-n/index.md) when [iconsList](update-mobile-toolbar-options.md) contains entries whose type is not supported by the receiving workflow. |
