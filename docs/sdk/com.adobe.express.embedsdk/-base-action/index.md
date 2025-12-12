//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[BaseAction](index.md)

# BaseAction

internal abstract class [BaseAction](index.md)(actionContext: [ActionContext](../-action-context/index.md), actionProperties: [ActionProperties](../-action-properties/index.md)? = null, isCancellable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)? = false, analyticsWorkflow: AnalyticsWorkflow, messageList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;MessageType&gt;? = null) : [Action](../-action/index.md), [ContainerDelegate](../-container-delegate/index.md)

#### Inheritors

| |
|---|
| [WarmupAction](../-warmup-action/index.md) |
| [ImageModuleAction](../-image-module-action/index.md) |
| [TextToImageAction](../-text-to-image-action/index.md) |
| [QuickAction](../-quick-action/index.md) |

## Constructors

| | |
|---|---|
| [BaseAction](-base-action.md) | [androidJvm]<br>constructor(actionContext: [ActionContext](../-action-context/index.md), actionProperties: [ActionProperties](../-action-properties/index.md)? = null, isCancellable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)? = false, analyticsWorkflow: AnalyticsWorkflow, messageList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;MessageType&gt;? = null) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [addPerformanceMarkersIfAny](add-performance-markers-if-any.md) | [androidJvm]<br>abstract fun [addPerformanceMarkersIfAny](add-performance-markers-if-any.md)() |
| [awaitParamsReady](await-params-ready.md) | [androidJvm]<br>open suspend fun [awaitParamsReady](await-params-ready.md)() |
| [didTargetLoad](did-target-load.md) | [androidJvm]<br>open fun [didTargetLoad](did-target-load.md)(data: DidTargetLoadData) |
| [execute](execute.md) | [androidJvm]<br>open suspend override fun [execute](execute.md)(fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?) |
| [getActionContextInternal](get-action-context-internal.md) | [androidJvm]<br>internal fun [getActionContextInternal](get-action-context-internal.md)(): [ActionContext](../-action-context/index.md)<br>Get the action context for this action |
| [getAppConfig](get-app-config.md) | [androidJvm]<br>fun [getAppConfig](get-app-config.md)(): [BaseAppConfig](../-base-app-config/index.md)?<br>Get the app configuration for this action |
| [getExportConfig](get-export-config.md) | [androidJvm]<br>fun [getExportConfig](get-export-config.md)(): [ExportConfig](../-export-config/index.md)? |
| [getTargetEndpoint](get-target-endpoint.md) | [androidJvm]<br>abstract fun [getTargetEndpoint](get-target-endpoint.md)(): [URL](https://developer.android.com/reference/kotlin/java/net/URL.html) |
| [getTargetInfoInternal](get-target-info-internal.md) | [androidJvm]<br>open override fun [getTargetInfoInternal](get-target-info-internal.md)(): [TargetInfo](../-target-info/index.md) |
| [handleDidTargetLoad](handle-did-target-load.md) | [androidJvm]<br>open fun [handleDidTargetLoad](handle-did-target-load.md)(data: DidTargetLoadData) |
| [invokeCancelCallbackWithAnalytics](invoke-cancel-callback-with-analytics.md) | [androidJvm]<br>open fun [invokeCancelCallbackWithAnalytics](invoke-cancel-callback-with-analytics.md)(cancelActionReason: CancelActionReason) |
| [removePerformanceMarkersIfAny](remove-performance-markers-if-any.md) | [androidJvm]<br>abstract fun [removePerformanceMarkersIfAny](remove-performance-markers-if-any.md)() |
| [willTargetLoad](will-target-load.md) | [androidJvm]<br>internal open fun [willTargetLoad](will-target-load.md)() |
