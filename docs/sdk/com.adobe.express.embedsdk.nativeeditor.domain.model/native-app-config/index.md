//[sdk](../../../index.md)/[com.adobe.express.embedsdk.nativeeditor.domain.model](../index.md)/[NativeAppConfig](index.md)

# NativeAppConfig

\
interface [NativeAppConfig](index.md)

Application configuration for the native workflows.

## Properties

| Name | Summary |
|---|---|
| [analyticsData](analytics-data.md) | <br>open val [analyticsData](analytics-data.md): BaseAnalyticsData? |
| [appVersion](app-version.md) | <br>open val [appVersion](app-version.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? |
| [callbacks](callbacks.md) | <br>abstract val [callbacks](callbacks.md): Callbacks<br>Callbacks for publish, cancel, and error events. |
| [colorTheme](color-theme.md) | <br>open val [colorTheme](color-theme.md): ColorTheme? |
| [metaData](meta-data.md) | <br>open val [metaData](meta-data.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? |
| [mobileToolbarOptions](mobile-toolbar-options.md) | <br>open val [mobileToolbarOptions](mobile-toolbar-options.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[NativeMobileToolbarOption](../native-mobile-toolbar-option/index.md)&gt;?<br>Optional list of host-provided toolbar entries to merge into the editor toolbar. |
| [onDismiss](on-dismiss.md) | <br>abstract val [onDismiss](on-dismiss.md): () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/unit/index.html)<br>Called when the editor should be removed from the view hierarchy. |
| [publishModalTitle](publish-modal-title.md) | <br>open val [publishModalTitle](publish-modal-title.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>Optional title shown on the progress overlay while the editor exports an image (e.g. on Save / Share). Falls back to a built-in localized string when null. |
