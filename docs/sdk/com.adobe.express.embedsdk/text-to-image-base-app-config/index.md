//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[TextToImageBaseAppConfig](index.md)

# TextToImageBaseAppConfig

\
interface [TextToImageBaseAppConfig](index.md) : AppConfig

## Properties

| Name | Summary |
|---|---|
| [appVersion](app-version.md) | <br>abstract val [appVersion](app-version.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>Specifies the version of the Generate Image experience to be enabled. This setting allows the selection between the older and the newer interface version. |
| [callbacks](callbacks.md) | <br>abstract override var [callbacks](callbacks.md): [Callbacks](../callbacks/index.md)?<br>Callbacks for handling various events. |
| [createTempDoc](create-temp-doc.md) | <br>abstract override val [createTempDoc](create-temp-doc.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)?<br>Flag to determine whether to create a temporary document. |
| [editDropdownOptions](edit-dropdown-options.md) | <br>open val [editDropdownOptions](edit-dropdown-options.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[EditDropdownOptionConfig](../edit-dropdown-option-config/index.md)&gt;?<br>Options to be passed for Edit dropdown. |
| [editorTitle](editor-title.md) | <br>abstract override var [editorTitle](editor-title.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>Property to configure the title |
| [fastModeConfig](fast-mode-config.md) | <br>abstract val [fastModeConfig](fast-mode-config.md): [FastModeConfig](../fast-mode-config/index.md)?<br>Configuration for enabling or disabling fast mode in the Text to Image module. NOTE: This property is supported only in the new Generate Image experience and when FAST_MODE is set to true in featureConfig. |
| [featureConfig](feature-config.md) | <br>open val [featureConfig](feature-config.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)&gt;?<br>Configuration for enabling or disabling specific features. |
| [headerBarColorTheme](header-bar-color-theme.md) | <br>abstract val [headerBarColorTheme](header-bar-color-theme.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>Theming options for the TextToImage Editor header bar. |
| [metaData](meta-data.md) | <br>abstract override val [metaData](meta-data.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;?<br>Metadata information. |
| [promptText](prompt-text.md) | <br>abstract val [promptText](prompt-text.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>Text prompt used for generating images. |
| [publishConfig](publish-config.md) | <br>abstract val [publishConfig](publish-config.md): [PublishConfig](../publish-config/index.md)?<br>Config to be set for Publish action. NOTE: This property is supported only in the new Generate Image experience. |
| [thumbnailOptions](thumbnail-options.md) | <br>open val [thumbnailOptions](thumbnail-options.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;?<br>Options passed to be displayed on the thumbnail. |
| [useClientAuth](use-client-auth.md) | <br>open val [useClientAuth](use-client-auth.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)?<br>Flag to explicitly opt-in to use client authentication. When true, client access token will be fetched from the partner and used in the module. |
