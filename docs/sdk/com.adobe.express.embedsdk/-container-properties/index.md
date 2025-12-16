//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ContainerProperties](index.md)

# ContainerProperties

[androidJvm]\
data class [ContainerProperties](index.md)(val size: [ContainerSize](../-container-size/index.md)? = null, val targetDomain: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, val keepTargetHidden: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)? = null, val colorTheme: [ColorTheme](../-color-theme/index.md)? = null, val containerConfig: [ContainerConfig](../-container-config/index.md)? = null) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)

## Constructors

| | |
|---|---|
| [ContainerProperties](-container-properties.md) | [androidJvm]<br>constructor(size: [ContainerSize](../-container-size/index.md)? = null, targetDomain: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, keepTargetHidden: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)? = null, colorTheme: [ColorTheme](../-color-theme/index.md)? = null, containerConfig: [ContainerConfig](../-container-config/index.md)? = null) |

## Properties

| Name | Summary |
|---|---|
| [colorTheme](color-theme.md) | [androidJvm]<br>val [colorTheme](color-theme.md): [ColorTheme](../-color-theme/index.md)? = null<br>Color theme used for Quick Action workflow |
| [containerConfig](container-config.md) | [androidJvm]<br>val [containerConfig](container-config.md): [ContainerConfig](../-container-config/index.md)? = null |
| [keepTargetHidden](keep-target-hidden.md) | [androidJvm]<br>val [keepTargetHidden](keep-target-hidden.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)? = null<br>Default is false for Editor workflows and true for pre-cache. |
| [size](size.md) | [androidJvm]<br>val [size](size.md): [ContainerSize](../-container-size/index.md)? = null |
| [targetDomain](target-domain.md) | [androidJvm]<br>val [targetDomain](target-domain.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null |
