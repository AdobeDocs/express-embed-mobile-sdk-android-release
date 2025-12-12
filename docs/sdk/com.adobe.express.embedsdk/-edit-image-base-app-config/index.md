//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[EditImageBaseAppConfig](index.md)

# EditImageBaseAppConfig

[androidJvm]\
interface [EditImageBaseAppConfig](index.md) : AppConfig

## Properties

| Name | Summary |
|---|---|
| [allowedFileTypes](allowed-file-types.md) | [androidJvm]<br>abstract val [allowedFileTypes](allowed-file-types.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;[ImageModuleFileTypes](../-image-module-file-types/index.md)&gt;?<br>Specify the list of file types that the user can publish. This can be used to limit the publish options as per MIME types for end users. |
| [allowedSubFileTypes](allowed-sub-file-types.md) | [androidJvm]<br>abstract val [allowedSubFileTypes](allowed-sub-file-types.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;?<br>Specify the list of sub-file types that the user can publish. This can be used to limit the publish options as per file types for end users. Currently, only PDF sub-file types are available. |
| [appVersion](app-version.md) | [androidJvm]<br>abstract val [appVersion](app-version.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>Specifies the version of the Edit Image experience to be enabled. |
