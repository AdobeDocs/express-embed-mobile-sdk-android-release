//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[CCEverywhereError](index.md)/[CCEverywhereError](c-c-everywhere-error.md)

# CCEverywhereError

\
constructor(error: [ErrorCodeMessages](../error-code-messages/index.md), subError: [CCEverywhereError](index.md)? = null)

Constructs a CCEverywhereError from structured error information.

#### Parameters

androidJvm

| | |
|---|---|
| error | Structured error information with code and message |
| subError | Optional nested error that caused this error |

\
constructor(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null, message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), subError: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/any/index.html)? = null, customData: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/any/index.html)? = null)
