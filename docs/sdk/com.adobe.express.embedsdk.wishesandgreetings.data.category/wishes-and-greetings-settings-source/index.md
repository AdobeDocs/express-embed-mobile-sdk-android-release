//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.data.category](../index.md)/[WishesAndGreetingsSettingsSource](index.md)

# WishesAndGreetingsSettingsSource

fun interface [WishesAndGreetingsSettingsSource](index.md)

Clean seam for reading a remote experimentation &quot;setting&quot; value by key.

#### Inheritors

| |
|---|
| [WishesAndGreetingsRemoteSettingsSource](../wishes-and-greetings-remote-settings-source/index.md) |

## Functions

| Name | Summary |
|---|---|
| [getSetting](get-setting.md) | <br>abstract suspend fun [getSetting](get-setting.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>JSON string for [key](get-setting.md), or null when unavailable. |
