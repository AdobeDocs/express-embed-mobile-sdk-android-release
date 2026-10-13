//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[Link](index.md)

# Link

\
@Serializable

data class [Link](index.md)(val href: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val templated: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false, val name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;)

## Constructors

| | |
|---|---|
| [Link](link.md) | <br>constructor(href: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), templated: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;) |

## Properties

| Name | Summary |
|---|---|
| [href](href.md) | <br>@SerialName(value = &quot;href&quot;)<br>val [href](href.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [name](name.md) | <br>@SerialName(value = &quot;name&quot;)<br>val [name](name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [templated](templated.md) | <br>@SerialName(value = &quot;templated&quot;)<br>val [templated](templated.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) = false |

## Functions

| Name | Summary |
|---|---|
| [hrefWithParams](href-with-params.md) | <br>fun [hrefWithParams](href-with-params.md)(params: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/any/index.html)&gt;): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>Expands a templated ACP link with [params](href-with-params.md). |
