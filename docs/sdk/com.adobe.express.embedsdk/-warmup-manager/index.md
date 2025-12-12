//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WarmupManager](index.md)

# WarmupManager

[androidJvm]\
internal object [WarmupManager](index.md)

WarmupManager manages multiple preload operations and their execution states.

## Functions

| Name | Summary |
|---|---|
| [allowWarmupExecution](allow-warmup-execution.md) | [androidJvm]<br>fun [allowWarmupExecution](allow-warmup-execution.md)() |
| [clearAllWarmedUpIntents](clear-all-warmed-up-intents.md) | [androidJvm]<br>fun [clearAllWarmedUpIntents](clear-all-warmed-up-intents.md)() |
| [clearWarmupExecution](clear-warmup-execution.md) | [androidJvm]<br>fun [clearWarmupExecution](clear-warmup-execution.md)() |
| [closeAnyPendingPreload](close-any-pending-preload.md) | [androidJvm]<br>fun [closeAnyPendingPreload](close-any-pending-preload.md)() |
| [doesWarmupExist](does-warmup-exist.md) | [androidJvm]<br>fun [doesWarmupExist](does-warmup-exist.md)(intent: [ActionIntent](../-action-intent/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [getWarmedUpIntents](get-warmed-up-intents.md) | [androidJvm]<br>fun [getWarmedUpIntents](get-warmed-up-intents.md)(): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-set/index.html)&lt;[ActionIntent](../-action-intent/index.md)&gt; |
| [getWarmupComplete](get-warmup-complete.md) | [androidJvm]<br>fun [getWarmupComplete](get-warmup-complete.md)(intent: [ActionIntent](../-action-intent/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [hasPendingWarmupExecution](has-pending-warmup-execution.md) | [androidJvm]<br>fun [hasPendingWarmupExecution](has-pending-warmup-execution.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [isIntentWarmedUp](is-intent-warmed-up.md) | [androidJvm]<br>fun [isIntentWarmedUp](is-intent-warmed-up.md)(intent: [ActionIntent](../-action-intent/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [removeAllWarmupComplete](remove-all-warmup-complete.md) | [androidJvm]<br>fun [removeAllWarmupComplete](remove-all-warmup-complete.md)() |
| [removeWarmedUpIntent](remove-warmed-up-intent.md) | [androidJvm]<br>fun [removeWarmedUpIntent](remove-warmed-up-intent.md)(intent: [ActionIntent](../-action-intent/index.md)) |
| [setWarmupComplete](set-warmup-complete.md) | [androidJvm]<br>fun [setWarmupComplete](set-warmup-complete.md)(intent: [ActionIntent](../-action-intent/index.md)) |
| [setWarmupStart](set-warmup-start.md) | [androidJvm]<br>fun [setWarmupStart](set-warmup-start.md)(intent: [ActionIntent](../-action-intent/index.md)) |
| [shouldWaitForWarmupExecution](should-wait-for-warmup-execution.md) | [androidJvm]<br>fun [shouldWaitForWarmupExecution](should-wait-for-warmup-execution.md)(actionIntent: [ActionIntent](../-action-intent/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [waitForWarmupExecution](wait-for-warmup-execution.md) | [androidJvm]<br>suspend fun [waitForWarmupExecution](wait-for-warmup-execution.md)() |
