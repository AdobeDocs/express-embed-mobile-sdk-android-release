//[sdk](../../../../index.md)/[com.adobe.express.embedsdk](../../index.md)/[Container](../index.md)/[Companion](index.md)

# Companion

[androidJvm]\
object [Companion](index.md)

## Properties

| Name | Summary |
|---|---|
| [CONTAINER_TAG](-c-o-n-t-a-i-n-e-r_-t-a-g.md) | [androidJvm]<br>const val [CONTAINER_TAG](-c-o-n-t-a-i-n-e-r_-t-a-g.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html) |

## Functions

| Name | Summary |
|---|---|
| [loadContentInExistingWebView](load-content-in-existing-web-view.md) | [androidJvm]<br>fun [loadContentInExistingWebView](load-content-in-existing-web-view.md)(targetInfo: [TargetInfo](../../-target-info/index.md), targetEndpoint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), actionRequestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?)<br>Loads content into an existing webview that was created in loading state. This is used for the early loading flow where we create the webview first, then load the actual content once the URL is available. |
| [open](open.md) | [androidJvm]<br>fun [open](open.md)(fragmentOrContext: [FragmentOrContext](../../-fragment-or-context/index.md)?, targetEndpoint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), targetInfo: [TargetInfo](../../-target-info/index.md), containerProperties: [ContainerProperties](../../-container-properties/index.md)?, actionRequestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)): [Container](../index.md)? |
| [openWithLoadingState](open-with-loading-state.md) | [androidJvm]<br>fun [openWithLoadingState](open-with-loading-state.md)(fragmentOrContext: [FragmentOrContext](../../-fragment-or-context/index.md)?, targetInfo: [TargetInfo](../../-target-info/index.md), containerProperties: [ContainerProperties](../../-container-properties/index.md)?, actionRequestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)): [Container](../index.md)? |
