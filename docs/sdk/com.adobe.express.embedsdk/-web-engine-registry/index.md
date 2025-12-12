//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WebEngineRegistry](index.md)

# WebEngineRegistry

[androidJvm]\
internal class [WebEngineRegistry](index.md)

Centralized registry for managing WebEngine instances across the SDK. This prevents creating multiple WebEngine and allows reuse across different actions.

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [clearAllWebEngines](clear-all-web-engines.md) | [androidJvm]<br>fun [clearAllWebEngines](clear-all-web-engines.md)() |
| [getWebEngine](get-web-engine.md) | [androidJvm]<br>fun [getWebEngine](get-web-engine.md)(actionIntent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)): [WebEngine](../-web-engine/index.md)? |
| [removeWebEngine](remove-web-engine.md) | [androidJvm]<br>fun [removeWebEngine](remove-web-engine.md)(actionIntent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)) |
| [setWebEngine](set-web-engine.md) | [androidJvm]<br>fun [setWebEngine](set-web-engine.md)(actionIntent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), webEngine: [WebEngine](../-web-engine/index.md)) |
