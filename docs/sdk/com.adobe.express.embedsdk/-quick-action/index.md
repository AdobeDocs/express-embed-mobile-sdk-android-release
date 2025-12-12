//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[QuickAction](index.md)

# QuickAction

internal open class [QuickAction](index.md)(val actionContext: [ActionContext](../-action-context/index.md)) : [BaseAction](../-base-action/index.md)

#### Inheritors

| |
|---|
| [TemplateEditorQuickAction](../-template-editor-quick-action/index.md) |

## Constructors

| | |
|---|---|
| [QuickAction](-quick-action.md) | [androidJvm]<br>constructor(actionContext: [ActionContext](../-action-context/index.md)) |

## Properties

| Name | Summary |
|---|---|
| [actionContext](action-context.md) | [androidJvm]<br>val [actionContext](action-context.md): [ActionContext](../-action-context/index.md) |

## Functions

| Name | Summary |
|---|---|
| [addPerformanceMarkersIfAny](add-performance-markers-if-any.md) | [androidJvm]<br>open override fun [addPerformanceMarkersIfAny](add-performance-markers-if-any.md)() |
| [didTargetLoad](did-target-load.md) | [androidJvm]<br>open override fun [didTargetLoad](did-target-load.md)(data: DidTargetLoadData) |
| [getAnalyticsCustomProperties](get-analytics-custom-properties.md) | [androidJvm]<br>open override fun [getAnalyticsCustomProperties](get-analytics-custom-properties.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-any/index.html)&gt; |
| [getAnalyticsStageEvent](get-analytics-stage-event.md) | [androidJvm]<br>open override fun [getAnalyticsStageEvent](get-analytics-stage-event.md)(pair: AnalyticsWorkflowStageParamPair, event: Event): Event |
| [getQuickActionQueryParamsArray](get-quick-action-query-params-array.md) | [androidJvm]<br>open fun [getQuickActionQueryParamsArray](get-quick-action-query-params-array.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-pair/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;&gt; |
| [getTargetEndpoint](get-target-endpoint.md) | [androidJvm]<br>open override fun [getTargetEndpoint](get-target-endpoint.md)(): [URL](https://developer.android.com/reference/kotlin/java/net/URL.html) |
| [removePerformanceMarkersIfAny](remove-performance-markers-if-any.md) | [androidJvm]<br>open override fun [removePerformanceMarkersIfAny](remove-performance-markers-if-any.md)() |
