//[sdk](../../../../index.md)/[com.adobe.express.embedsdk.nativeeditor.domain.model](../../index.md)/[RemoveOrReplaceBackgroundState](../index.md)/[Error](index.md)

# Error

\
data class [Error](index.md)(val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val cause: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/throwable/index.html)? = null) : [RemoveOrReplaceBackgroundState](../index.md), [FeatureState.Error](../../feature-state/-error/index.md)

## Constructors

| | |
|---|---|
| [Error](error.md) | <br>constructor(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), cause: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/throwable/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [cause](cause.md) | <br>open override val [cause](cause.md): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/throwable/index.html)? = null |
| [message](message.md) | <br>open override val [message](message.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
