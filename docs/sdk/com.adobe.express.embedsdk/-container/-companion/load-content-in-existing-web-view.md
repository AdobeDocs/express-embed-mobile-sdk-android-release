//[sdk](../../../../index.md)/[com.adobe.express.embedsdk](../../index.md)/[Container](../index.md)/[Companion](index.md)/[loadContentInExistingWebView](load-content-in-existing-web-view.md)

# loadContentInExistingWebView

[androidJvm]\
fun [loadContentInExistingWebView](load-content-in-existing-web-view.md)(targetInfo: [TargetInfo](../../-target-info/index.md), targetEndpoint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), actionRequestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?)

Loads content into an existing webview that was created in loading state. This is used for the early loading flow where we create the webview first, then load the actual content once the URL is available.
