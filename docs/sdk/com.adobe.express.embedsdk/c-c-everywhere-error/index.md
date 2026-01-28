//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[CCEverywhereError](index.md)

# CCEverywhereError

\
class [CCEverywhereError](index.md)(val code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val subError: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/any/index.html)? = null, val customData: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/any/index.html)? = null) : [Exception](https://developer.android.com/reference/kotlin/java/lang/Exception.html)

Main exception class for all Adobe Express Embed SDK errors.

## Constructors

| | |
|---|---|
| [CCEverywhereError](c-c-everywhere-error.md) | <br>constructor(error: [ErrorCodeMessages](../error-code-messages/index.md), subError: [CCEverywhereError](index.md)? = null)<br>Constructs a CCEverywhereError from structured error information.<br>constructor(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), subError: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/any/index.html)? = null, customData: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/any/index.html)? = null) |

## Types

| Name | Summary |
|---|---|
| [Companion](companion/index.md) | <br>object [Companion](companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [code](code.md) | <br>val [code](code.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null<br>Error code identifier from [ErrorCode](../error-code/index.md) constants |
| [customData](custom-data.md) | <br>val [customData](custom-data.md): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/any/index.html)? = null<br>Optional additional context data for debugging |
| [message](message.md) | <br>open override val [message](message.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>Human-readable error description |
| [subError](sub-error.md) | <br>val [subError](sub-error.md): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/any/index.html)? = null<br>Optional nested error that caused this error (error chaining) |
