//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WebViewEngine](index.md)/[performLayoutMeasurement](perform-layout-measurement.md)

# performLayoutMeasurement

[androidJvm]\
open override fun [performLayoutMeasurement](perform-layout-measurement.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html))

Forces the WebView to measure and layout itself with explicit dimensions. This is needed for cases when the WebView is running in Headless mode (for eg: preload scenarios).

#### Parameters

androidJvm

| | |
|---|---|
| context | The context to get display metrics from |
