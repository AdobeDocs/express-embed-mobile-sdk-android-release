//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ConfigParams](index.md)

# ConfigParams

[androidJvm]\
class [ConfigParams](index.md)(var locale: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = &quot;en_US&quot;, var env: [Environment](../-environment/index.md)? = Environment.PRODUCTION)

SDK configuration parameters. Controls SDK behavior including localization and environment targeting.

## Constructors

| | |
|---|---|
| [ConfigParams](-config-params.md) | [androidJvm]<br>constructor(locale: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = &quot;en_US&quot;, env: [Environment](../-environment/index.md)? = Environment.PRODUCTION) |

## Properties

| Name | Summary |
|---|---|
| [env](env.md) | [androidJvm]<br>var [env](env.md): [Environment](../-environment/index.md)?<br>Target environment for SDK services. Use [Environment.PRODUCTION](../-environment/-p-r-o-d-u-c-t-i-o-n/index.md) for production apps or [Environment.STAGE](../-environment/-s-t-a-g-e/index.md) for development/testing. Defaults to PRODUCTION. |
| [locale](locale.md) | [androidJvm]<br>var [locale](locale.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>Language and region code for UI localization (e.g., &quot;en_US&quot;, &quot;fr_FR&quot;). Defaults to &quot;en_US&quot; if not specified. |
