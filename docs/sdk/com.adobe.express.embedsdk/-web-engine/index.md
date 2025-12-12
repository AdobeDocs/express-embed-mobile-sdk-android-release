//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WebEngine](index.md)

# WebEngine

internal interface [WebEngine](index.md)

#### Inheritors

| |
|---|
| [WebViewEngine](../-web-view-engine/index.md) |

## Functions

| Name | Summary |
|---|---|
| [addJavascriptInterface](add-javascript-interface.md) | [androidJvm]<br>abstract fun [addJavascriptInterface](add-javascript-interface.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-any/index.html), interfaceName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html))<br>Add a JavaScript interface to the web engine. |
| [addWebEngineToLayout](add-web-engine-to-layout.md) | [androidJvm]<br>abstract fun [addWebEngineToLayout](add-web-engine-to-layout.md)(keepTargetHidden: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)?, viewGroup: [ViewGroup](https://developer.android.com/reference/kotlin/android/view/ViewGroup.html), isRestoringState: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html))<br>Add the web engine to the specified layout. |
| [closeWebView](close-web-view.md) | [androidJvm]<br>abstract fun [closeWebView](close-web-view.md)()<br>Unloads the current page and closes the web engine. |
| [destroyWebEngine](destroy-web-engine.md) | [androidJvm]<br>abstract fun [destroyWebEngine](destroy-web-engine.md)()<br>Clear any ongoing WebView calls. |
| [handleMainViewTargetLoad](handle-main-view-target-load.md) | [androidJvm]<br>abstract fun [handleMainViewTargetLoad](handle-main-view-target-load.md)()<br>Provides an option to the Webview to handle any main view target load event |
| [handleOnBackPress](handle-on-back-press.md) | [androidJvm]<br>abstract fun [handleOnBackPress](handle-on-back-press.md)()<br>Handle back press event. |
| [hide](hide.md) | [androidJvm]<br>abstract fun [hide](hide.md)()<br>Hide the web engine to make it invisible. |
| [hideLoaderWebView](hide-loader-web-view.md) | [androidJvm]<br>abstract fun [hideLoaderWebView](hide-loader-web-view.md)()<br>Hide the loader webView to make it invisible. |
| [loadUrl](load-url.md) | [androidJvm]<br>abstract fun [loadUrl](load-url.md)(url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html))<br>Load a URL in the web engine. |
| [loadUrlWithReferrer](load-url-with-referrer.md) | [androidJvm]<br>abstract fun [loadUrlWithReferrer](load-url-with-referrer.md)(url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), referrer: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html))<br>Load a URL in the web engine with a referrer. |
| [performLayoutMeasurement](perform-layout-measurement.md) | [androidJvm]<br>abstract fun [performLayoutMeasurement](perform-layout-measurement.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html))<br>Forces the WebView to measure and layout itself with explicit dimensions. |
| [runOnUiThread](run-on-ui-thread.md) | [androidJvm]<br>abstract fun [runOnUiThread](run-on-ui-thread.md)(jsFunction: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), callback: [ValueCallback](https://developer.android.com/reference/kotlin/android/webkit/ValueCallback.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;?)<br>Run a JavaScript function on the UI thread. |
| [show](show.md) | [androidJvm]<br>abstract fun [show](show.md)()<br>Show the web engine to make it visible. |
| [updateFragmentContext](update-fragment-context.md) | [androidJvm]<br>abstract fun [updateFragmentContext](update-fragment-context.md)(newFragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?)<br>Updates the fragment context associated with this WebEngine. This is called during container adoption to ensure the WebView uses the correct fragment context. |
