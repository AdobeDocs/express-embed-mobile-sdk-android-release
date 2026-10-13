//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.data.category](../index.md)/[WishesAndGreetingsRemoteSettingsSource](index.md)

# WishesAndGreetingsRemoteSettingsSource

\
class [WishesAndGreetingsRemoteSettingsSource](index.md)(baseUrl: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), httpClient: HttpClient, json: Json = Json { ignoreUnknownKeys = true }) : [WishesAndGreetingsSettingsSource](../wishes-and-greetings-settings-source/index.md)

Ports theo-android's `NativeFeatureFlagsRepository.getSettingValue` HTTP contract for the Wishes & greetings category catalog: a single unauthenticated `GET {baseUrl}default?feature-flags=…& settings=<key>` against the Hz experimentation (`_rr_`) endpoint, whose response envelope is `{ "features": { … }, "settings": { "<key>": <value> } }`.

## Constructors

| | |
|---|---|
| [WishesAndGreetingsRemoteSettingsSource](wishes-and-greetings-remote-settings-source.md) | <br>constructor(baseUrl: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), httpClient: HttpClient, json: Json = Json { ignoreUnknownKeys = true }) |

## Types

| Name | Summary |
|---|---|
| [Companion](companion/index.md) | <br>object [Companion](companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [getSetting](get-setting.md) | <br>open suspend override fun [getSetting](get-setting.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>JSON string for [key](get-setting.md), or null when unavailable. |
