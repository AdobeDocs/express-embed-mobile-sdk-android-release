//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ModuleWorkflowInterface](index.md)/[purgeWarmupSession](purge-warmup-session.md)

# purgeWarmupSession

\
abstract fun [purgeWarmupSession](purge-warmup-session.md)(intent: ActionIntent? = null): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)

Purge the background warmup session for the given intent. This closes any preload/precache WebView and ends the warmup action.

#### Return

true if warmup session was successfully purged, false otherwise
