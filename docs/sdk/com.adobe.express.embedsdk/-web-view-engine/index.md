//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WebViewEngine](index.md)

# WebViewEngine

[androidJvm]\
internal class [WebViewEngine](index.md)(_webView: [WebView](https://developer.android.com/reference/kotlin/android/webkit/WebView.html)?, _fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?) : [WebEngine](../-web-engine/index.md), [ActionStateListener](../-action-state-listener/index.md)

## Constructors

| | |
|---|---|
| [WebViewEngine](-web-view-engine.md) | [androidJvm]<br>constructor(_webView: [WebView](https://developer.android.com/reference/kotlin/android/webkit/WebView.html)?, _fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [kBackgroundColor](k-background-color.md) | [androidJvm]<br>val [kBackgroundColor](k-background-color.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html) |

## Functions

| Name | Summary |
|---|---|
| [addJavascriptInterface](add-javascript-interface.md) | [androidJvm]<br>open override fun [addJavascriptInterface](add-javascript-interface.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-any/index.html), interfaceName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html))<br>Add a JavaScript interface to the web engine. |
| [addLoaderWebView](add-loader-web-view.md) | [androidJvm]<br>fun [addLoaderWebView](add-loader-web-view.md)(viewGroup: [ViewGroup](https://developer.android.com/reference/kotlin/android/view/ViewGroup.html)) |
| [addWebEngineToLayout](add-web-engine-to-layout.md) | [androidJvm]<br>open override fun [addWebEngineToLayout](add-web-engine-to-layout.md)(keepTargetHidden: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)?, viewGroup: [ViewGroup](https://developer.android.com/reference/kotlin/android/view/ViewGroup.html), isRestoringState: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html))<br>Add the web engine to the specified layout. |
| [closeWebView](close-web-view.md) | [androidJvm]<br>open override fun [closeWebView](close-web-view.md)()<br>Unloads the current page and closes the web engine. |
| [destroyWebEngine](destroy-web-engine.md) | [androidJvm]<br>open override fun [destroyWebEngine](destroy-web-engine.md)()<br>Clear any ongoing WebView calls. |
| [handleMainViewTargetLoad](handle-main-view-target-load.md) | [androidJvm]<br>open override fun [handleMainViewTargetLoad](handle-main-view-target-load.md)()<br>Hint the compositor that the main WebView should be considered visible by clipping a small strip from the loader so the main is not fully occluded. Call this when the target reports DID_TARGET_LOAD. |
| [handleOnBackPress](handle-on-back-press.md) | [androidJvm]<br>open override fun [handleOnBackPress](handle-on-back-press.md)()<br>Handle back press event. |
| [hide](hide.md) | [androidJvm]<br>open override fun [hide](hide.md)()<br>Hide the web engine to make it invisible. |
| [hideLoaderWebView](hide-loader-web-view.md) | [androidJvm]<br>open override fun [hideLoaderWebView](hide-loader-web-view.md)()<br>Hide the loader webView to make it invisible. |
| [isValidUrl](is-valid-url.md) | [androidJvm]<br>fun [isValidUrl](is-valid-url.md)(url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [loadUrl](load-url.md) | [androidJvm]<br>open override fun [loadUrl](load-url.md)(url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html))<br>Load a URL in the web engine. |
| [loadUrlWithReferrer](load-url-with-referrer.md) | [androidJvm]<br>open override fun [loadUrlWithReferrer](load-url-with-referrer.md)(url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), referrer: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html))<br>Load a URL in the web engine with a referrer. |
| [onActionClosed](on-action-closed.md) | [androidJvm]<br>open override fun [onActionClosed](on-action-closed.md)(actionIntent: [ActionIntent](../-action-intent/index.md)?, closeReason: [ContainerCloseReason](../-container-close-reason/index.md))<br>Called when an action is closed for any reason |
| [onActionLaunched](on-action-launched.md) | [androidJvm]<br>open override fun [onActionLaunched](on-action-launched.md)(actionIntent: [ActionIntent](../-action-intent/index.md))<br>Called when an action is successfully launched |
| [onActionTimeout](on-action-timeout.md) | [androidJvm]<br>open override fun [onActionTimeout](on-action-timeout.md)(actionIntent: [ActionIntent](../-action-intent/index.md)?)<br>Called when an action times out during launch |
| [performLayoutMeasurement](perform-layout-measurement.md) | [androidJvm]<br>open override fun [performLayoutMeasurement](perform-layout-measurement.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html))<br>Forces the WebView to measure and layout itself with explicit dimensions. This is needed for cases when the WebView is running in Headless mode (for eg: preload scenarios). |
| [runOnUiThread](run-on-ui-thread.md) | [androidJvm]<br>open override fun [runOnUiThread](run-on-ui-thread.md)(jsFunction: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), callback: [ValueCallback](https://developer.android.com/reference/kotlin/android/webkit/ValueCallback.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;?)<br>Run a JavaScript function on the UI thread. |
| [show](show.md) | [androidJvm]<br>open override fun [show](show.md)()<br>Show the web engine to make it visible. |
| [updateFragmentContext](update-fragment-context.md) | [androidJvm]<br>open override fun [updateFragmentContext](update-fragment-context.md)(newFragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?)<br>Updates the fragment context for this WebViewEngine instance (for container adoption workflow). |
