//[sdk](../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.data.di](index.md)/[wishesAndGreetingsDataModule](wishes-and-greetings-data-module.md)

# wishesAndGreetingsDataModule

\
fun [wishesAndGreetingsDataModule](wishes-and-greetings-data-module.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), isProd: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)): Module

Koin data module for the Wishes & greetings ACP content layer: HTTP client, anonymous content-service API, and content repository. [isProd](wishes-and-greetings-data-module.md) selects the prod or stage content endpoint, root, settings feed, and fallback category catalog.
