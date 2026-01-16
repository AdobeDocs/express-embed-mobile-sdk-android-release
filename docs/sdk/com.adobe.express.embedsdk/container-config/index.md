//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ContainerConfig](index.md)

# ContainerConfig

\
data class [ContainerConfig](index.md)(var showLoader: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = true, var loadTimeout: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)? = null, var hideCloseButton: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = null, var containerId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)? = null, var size: [PixelSize](../pixel-size/index.md)? = null, var minSize: [PixelSize](../pixel-size/index.md)? = null, var padding: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)? = null) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)

Configuration options for the SDK webview container display and behavior.

## Constructors

| | |
|---|---|
| [ContainerConfig](container-config.md) | <br>constructor(showLoader: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = true, loadTimeout: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)? = null, hideCloseButton: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = null, containerId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)? = null, size: [PixelSize](../pixel-size/index.md)? = null, minSize: [PixelSize](../pixel-size/index.md)? = null, padding: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [containerId](container-id.md) | <br>var [containerId](container-id.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)?<br>Container ID for fragment placement. Defaults to android.R.id.content if not specified |
| [hideCloseButton](hide-close-button.md) | <br>var [hideCloseButton](hide-close-button.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)?<br>Don't show close button for container and header bars |
| [loadTimeout](load-timeout.md) | <br>var [loadTimeout](load-timeout.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)?<br>If target app doesn't open within this time (in ms, same as of setTimeout), the error callback is invoked with error code TARGET_LOAD_TIMED_OUT. |
| [minSize](min-size.md) | <br>var [minSize](min-size.md): [PixelSize](../pixel-size/index.md)?<br>Minimum size boundary of the webview. |
| [padding](padding.md) | <br>var [padding](padding.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)?<br>Padding applied to the webview in pixels. |
| [showLoader](show-loader.md) | <br>var [showLoader](show-loader.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)?<br>Show spinner while loading target app. Default is true. |
| [size](size.md) | <br>var [size](size.md): [PixelSize](../pixel-size/index.md)?<br>Maximum size boundary of the webview. |
