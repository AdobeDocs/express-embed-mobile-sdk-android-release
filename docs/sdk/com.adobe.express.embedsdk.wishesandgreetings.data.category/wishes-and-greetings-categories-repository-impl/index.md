//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.data.category](../index.md)/[WishesAndGreetingsCategoriesRepositoryImpl](index.md)

# WishesAndGreetingsCategoriesRepositoryImpl

\
class [WishesAndGreetingsCategoriesRepositoryImpl](index.md)(settingsSource: [WishesAndGreetingsSettingsSource](../wishes-and-greetings-settings-source/index.md), isProd: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html), gson: Gson = Gson()) : [WishesAndGreetingsCategoriesRepository](../../com.adobe.express.embedsdk.wishesandgreetings.domain.repository/wishes-and-greetings-categories-repository/index.md)

Loads the Wishes & greetings category catalog: attempts the remote `wishesTemplateCategories` settings fetch, gson-parses `{ "categories": [...] }`, and falls back to [WishesAndGreetingsCategoryDefaults](../wishes-and-greetings-category-defaults/index.md) on a null value, parse failure, exception, or empty parsed list.

## Constructors

| | |
|---|---|
| [WishesAndGreetingsCategoriesRepositoryImpl](wishes-and-greetings-categories-repository-impl.md) | <br>constructor(settingsSource: [WishesAndGreetingsSettingsSource](../wishes-and-greetings-settings-source/index.md), isProd: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html), gson: Gson = Gson()) |

## Types

| Name | Summary |
|---|---|
| [Companion](companion/index.md) | <br>object [Companion](companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [getCategories](get-categories.md) | <br>open suspend override fun [getCategories](get-categories.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[WishesAndGreetingsCategory](../../com.adobe.express.embedsdk.wishesandgreetings.domain.model/wishes-and-greetings-category/index.md)&gt; |
