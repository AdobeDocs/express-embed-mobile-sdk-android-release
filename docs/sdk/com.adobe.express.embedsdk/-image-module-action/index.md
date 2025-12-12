//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ImageModuleAction](index.md)

# ImageModuleAction

[androidJvm]\
internal class [ImageModuleAction](index.md)(actionContext: [ActionContext](../-action-context/index.md)) : [BaseAction](../-base-action/index.md)

## Constructors

| | |
|---|---|
| [ImageModuleAction](-image-module-action.md) | [androidJvm]<br>constructor(actionContext: [ActionContext](../-action-context/index.md)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [addPerformanceMarkersIfAny](add-performance-markers-if-any.md) | [androidJvm]<br>open override fun [addPerformanceMarkersIfAny](add-performance-markers-if-any.md)() |
| [awaitParamsReady](await-params-ready.md) | [androidJvm]<br>open suspend override fun [awaitParamsReady](await-params-ready.md)() |
| [didTargetLoad](did-target-load.md) | [androidJvm]<br>open override fun [didTargetLoad](did-target-load.md)(data: DidTargetLoadData) |
| [execute](execute.md) | [androidJvm]<br>open suspend override fun [execute](execute.md)(fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?) |
| [getAnalyticsCustomProperties](get-analytics-custom-properties.md) | [androidJvm]<br>open override fun [getAnalyticsCustomProperties](get-analytics-custom-properties.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-any/index.html)&gt; |
| [getAnalyticsStageEvent](get-analytics-stage-event.md) | [androidJvm]<br>open override fun [getAnalyticsStageEvent](get-analytics-stage-event.md)(pair: AnalyticsWorkflowStageParamPair, event: Event): Event |
| [getInputAsset](get-input-asset.md) | [androidJvm]<br>fun [getInputAsset](get-input-asset.md)(): [Asset](../-asset/index.md)? |
| [getShimmerImageUri](get-shimmer-image-uri.md) | [androidJvm]<br>fun [getShimmerImageUri](get-shimmer-image-uri.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>Get the shimmer image URI for WebView JavaScript interface |
| [getTargetEndpoint](get-target-endpoint.md) | [androidJvm]<br>open override fun [getTargetEndpoint](get-target-endpoint.md)(): [URL](https://developer.android.com/reference/kotlin/java/net/URL.html) |
| [handleDidTargetLoad](handle-did-target-load.md) | [androidJvm]<br>open override fun [handleDidTargetLoad](handle-did-target-load.md)(data: DidTargetLoadData) |
| [removePerformanceMarkersIfAny](remove-performance-markers-if-any.md) | [androidJvm]<br>open override fun [removePerformanceMarkersIfAny](remove-performance-markers-if-any.md)() |
| [willTargetLoad](will-target-load.md) | [androidJvm]<br>internal open override fun [willTargetLoad](will-target-load.md)() |
