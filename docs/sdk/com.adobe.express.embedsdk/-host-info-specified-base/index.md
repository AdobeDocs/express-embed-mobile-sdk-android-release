//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[HostInfoSpecifiedBase](index.md)

# HostInfoSpecifiedBase

interface [HostInfoSpecifiedBase](index.md)

#### Inheritors

| |
|---|
| [HostInfoExtended](../-host-info-extended/index.md) |

## Properties

| Name | Summary |
|---|---|
| [appName](app-name.md) | [androidJvm]<br>abstract val [appName](app-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>Client's application name. This name may be used in creating folder for projects in target application. |
| [appVersion](app-version.md) | [androidJvm]<br>abstract val [appVersion](app-version.md): [Version](../-version/index.md)?<br>Client's current version. |
| [clientId](client-id.md) | [androidJvm]<br>abstract val [clientId](client-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>For 3P - Client id generated from dev console. For 1P - Client id generated from IMSS portal. Environment(stage/prod) specific client id should be passed). |
| [platformCategory](platform-category.md) | [androidJvm]<br>abstract val [platformCategory](platform-category.md): [PlatformCategory](../-platform-category/index.md)<br>Client's application type. |
