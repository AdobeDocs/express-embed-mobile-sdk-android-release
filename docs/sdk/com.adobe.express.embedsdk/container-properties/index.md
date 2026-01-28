//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ContainerProperties](index.md)

# ContainerProperties

\
data class [ContainerProperties](index.md)(val size: [ContainerSize](../container-size/index.md)? = null, val targetDomain: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, val keepTargetHidden: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = null, val colorTheme: ColorTheme? = null, val containerConfig: ContainerConfig? = null) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)

## Constructors

| | |
|---|---|
| [ContainerProperties](container-properties.md) | <br>constructor(size: [ContainerSize](../container-size/index.md)? = null, targetDomain: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, keepTargetHidden: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = null, colorTheme: ColorTheme? = null, containerConfig: ContainerConfig? = null) |

## Properties

| Name | Summary |
|---|---|
| [colorTheme](color-theme.md) | <br>val [colorTheme](color-theme.md): ColorTheme? = null<br>Color theme used for Quick Action workflow |
| [containerConfig](container-config.md) | <br>val [containerConfig](container-config.md): ContainerConfig? = null |
| [keepTargetHidden](keep-target-hidden.md) | <br>val [keepTargetHidden](keep-target-hidden.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = null<br>Default is false for Editor workflows and true for pre-cache. |
| [size](size.md) | <br>val [size](size.md): [ContainerSize](../container-size/index.md)? = null |
| [targetDomain](target-domain.md) | <br>val [targetDomain](target-domain.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null |
