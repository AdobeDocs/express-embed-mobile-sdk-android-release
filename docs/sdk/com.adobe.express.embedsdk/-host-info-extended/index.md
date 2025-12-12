//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[HostInfoExtended](index.md)

# HostInfoExtended

[androidJvm]\
class [HostInfoExtended](index.md)(val clientId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?, val appName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?, var appVersion: [Version](../-version/index.md)?, var platformCategory: [PlatformCategory](../-platform-category/index.md) = PlatformCategory.MOBILE) : [HostInfoComputed](../-host-info-computed/index.md), [HostInfoSpecifiedBase](../-host-info-specified-base/index.md)

## Constructors

| | |
|---|---|
| [HostInfoExtended](-host-info-extended.md) | [androidJvm]<br>constructor(clientId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?, appName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?, appVersion: [Version](../-version/index.md)?, platformCategory: [PlatformCategory](../-platform-category/index.md) = PlatformCategory.MOBILE) |

## Properties

| Name | Summary |
|---|---|
| [appName](app-name.md) | [androidJvm]<br>open override val [appName](app-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>Client's application name. This name may be used in creating folder for projects in target application. |
| [appVersion](app-version.md) | [androidJvm]<br>open override var [appVersion](app-version.md): [Version](../-version/index.md)?<br>Client's current version. |
| [clientId](client-id.md) | [androidJvm]<br>open override val [clientId](client-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>For 3P - Client id generated from dev console. For 1P - Client id generated from IMSS portal. Environment(stage/prod) specific client id should be passed). |
| [platformCategory](platform-category.md) | [androidJvm]<br>open override var [platformCategory](platform-category.md): [PlatformCategory](../-platform-category/index.md)<br>Client's application type. |
