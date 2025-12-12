//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WebViewEngineProvider](index.md)

# WebViewEngineProvider

[androidJvm]\
internal class [WebViewEngineProvider](index.md)(var fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)) : [WebEngineProvider](../-web-engine-provider/index.md)

## Constructors

| | |
|---|---|
| [WebViewEngineProvider](-web-view-engine-provider.md) | [androidJvm]<br>constructor(fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [engine](engine.md) | [androidJvm]<br>lateinit var [engine](engine.md): [WebEngine](../-web-engine/index.md) |
| [fragmentOrContext](fragment-or-context.md) | [androidJvm]<br>var [fragmentOrContext](fragment-or-context.md): [FragmentOrContext](../-fragment-or-context/index.md) |

## Functions

| Name | Summary |
|---|---|
| [createWebEngine](create-web-engine.md) | [androidJvm]<br>open override fun [createWebEngine](create-web-engine.md)(): [WebEngine](../-web-engine/index.md)<br>Create a new WebEngine instance and return it. |
| [initializeWebViewSettings](initialize-web-view-settings.md) | [androidJvm]<br>internal fun [initializeWebViewSettings](initialize-web-view-settings.md)(webView: [WebView](https://developer.android.com/reference/kotlin/android/webkit/WebView.html)) |
| [updateFragmentContext](update-fragment-context.md) | [androidJvm]<br>open override fun [updateFragmentContext](update-fragment-context.md)(fragmentWrapper: [FragmentOrContext.FragmentWrapper](../-fragment-or-context/-fragment-wrapper/index.md))<br>Updates the fragment context associated with this WebEngineProvider. |
