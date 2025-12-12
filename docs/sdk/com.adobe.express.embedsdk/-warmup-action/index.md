//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WarmupAction](index.md)

# WarmupAction

[androidJvm]\
internal class [WarmupAction](index.md)(actionContext: [ActionContext](../-action-context/index.md)) : [BaseAction](../-base-action/index.md), [ContainerDelegate](../-container-delegate/index.md)

## Constructors

| | |
|---|---|
| [WarmupAction](-warmup-action.md) | [androidJvm]<br>constructor(actionContext: [ActionContext](../-action-context/index.md)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [addPerformanceMarkersIfAny](add-performance-markers-if-any.md) | [androidJvm]<br>open override fun [addPerformanceMarkersIfAny](add-performance-markers-if-any.md)() |
| [close](close.md) | [androidJvm]<br>fun [close](close.md)(closeReason: [ContainerCloseReason](../-container-close-reason/index.md), error: [CCEverywhereError](../-c-c-everywhere-error/index.md)? = null) |
| [didTargetLoad](did-target-load.md) | [androidJvm]<br>open override fun [didTargetLoad](did-target-load.md)(data: DidTargetLoadData) |
| [execute](execute.md) | [androidJvm]<br>open suspend override fun [execute](execute.md)(fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?) |
| [getTargetEndpoint](get-target-endpoint.md) | [androidJvm]<br>open override fun [getTargetEndpoint](get-target-endpoint.md)(): [URL](https://developer.android.com/reference/kotlin/java/net/URL.html) |
| [getTargetInfoInternal](get-target-info-internal.md) | [androidJvm]<br>open override fun [getTargetInfoInternal](get-target-info-internal.md)(): [TargetInfo](../-target-info/index.md) |
| [getWarmupTargetIntent](get-warmup-target-intent.md) | [androidJvm]<br>fun [getWarmupTargetIntent](get-warmup-target-intent.md)(): [ActionIntent](../-action-intent/index.md)? |
| [isPreloadActive](is-preload-active.md) | [androidJvm]<br>fun [isPreloadActive](is-preload-active.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [removePerformanceMarkersIfAny](remove-performance-markers-if-any.md) | [androidJvm]<br>open override fun [removePerformanceMarkersIfAny](remove-performance-markers-if-any.md)() |
| [setPreserveOnClose](set-preserve-on-close.md) | [androidJvm]<br>fun [setPreserveOnClose](set-preserve-on-close.md)(shouldPreserve: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)) |
| [shouldPreserve](should-preserve.md) | [androidJvm]<br>fun [shouldPreserve](should-preserve.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [willTargetLoad](will-target-load.md) | [androidJvm]<br>internal open override fun [willTargetLoad](will-target-load.md)() |
