//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[AcpPage](index.md)

# AcpPage

\
@Serializable

data class [AcpPage](index.md)(val renditions: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [AcpPageRendition](../acp-page-rendition/index.md)&gt;, val task: [AcpPageTask](../acp-page-task/index.md))

## Constructors

| | |
|---|---|
| [AcpPage](acp-page.md) | <br>constructor(renditions: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [AcpPageRendition](../acp-page-rendition/index.md)&gt;, task: [AcpPageTask](../acp-page-task/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [renditions](renditions.md) | <br>@SerialName(value = &quot;rendition&quot;)<br>val [renditions](renditions.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [AcpPageRendition](../acp-page-rendition/index.md)&gt; |
| [task](task.md) | <br>@SerialName(value = &quot;task&quot;)<br>val [task](task.md): [AcpPageTask](../acp-page-task/index.md) |
