//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[Action](index.md)

# Action

internal abstract class [Action](index.md)(val context: [SDKContext](../-s-d-k-context/index.md)? = null, val intent: [ActionIntent](../-action-intent/index.md)? = null, isCancellable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)? = null, actionProperties: [ActionProperties](../-action-properties/index.md)? = null, callbacks: [Callbacks](../-callbacks/index.md)? = null, messagesList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;MessageType&gt;, val analyticsWorkflow: AnalyticsWorkflow, requestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null) : [SDKContext](../-s-d-k-context/index.md)

#### Inheritors

| |
|---|
| [BaseAction](../-base-action/index.md) |

## Constructors

| | |
|---|---|
| [Action](-action.md) | [androidJvm]<br>constructor(context: [SDKContext](../-s-d-k-context/index.md)? = null, intent: [ActionIntent](../-action-intent/index.md)? = null, isCancellable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)? = null, actionProperties: [ActionProperties](../-action-properties/index.md)? = null, callbacks: [Callbacks](../-callbacks/index.md)? = null, messagesList: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;MessageType&gt;, analyticsWorkflow: AnalyticsWorkflow, requestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [actionListener](action-listener.md) | [androidJvm]<br>val [actionListener](action-listener.md): [ActionMessageListenerDelegate](../-action-message-listener-delegate/index.md) |
| [analyticsWorkflow](analytics-workflow.md) | [androidJvm]<br>val [analyticsWorkflow](analytics-workflow.md): AnalyticsWorkflow |
| [context](context.md) | [androidJvm]<br>val [context](context.md): [SDKContext](../-s-d-k-context/index.md)? = null |
| [hostCallbackHandler](host-callback-handler.md) | [androidJvm]<br>val [hostCallbackHandler](host-callback-handler.md): [HostCallbackHandler](../-host-callback-handler/index.md) |
| [intent](intent.md) | [androidJvm]<br>val [intent](intent.md): [ActionIntent](../-action-intent/index.md)? = null |
| [mPerformanceLogger](m-performance-logger.md) | [androidJvm]<br>var [mPerformanceLogger](m-performance-logger.md): PerformanceLogger |

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [androidJvm]<br>fun [close](close.md)(closeReason: [ContainerCloseReason](../-container-close-reason/index.md)) |
| [execute](execute.md) | [androidJvm]<br>abstract suspend fun [execute](execute.md)(fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)? = null) |
| [getAnalyticsCustomProperties](get-analytics-custom-properties.md) | [androidJvm]<br>open fun [getAnalyticsCustomProperties](get-analytics-custom-properties.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-any/index.html)&gt; |
| [getAnalyticsStageEvent](get-analytics-stage-event.md) | [androidJvm]<br>open fun [getAnalyticsStageEvent](get-analytics-stage-event.md)(pair: AnalyticsWorkflowStageParamPair, event: Event): Event |
| [getWorkflowLoadCompleted](get-workflow-load-completed.md) | [androidJvm]<br>fun [getWorkflowLoadCompleted](get-workflow-load-completed.md)(): WorkflowLoadCompleted |
| [isActive](is-active.md) | [androidJvm]<br>fun [isActive](is-active.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [isCancellable](is-cancellable.md) | [androidJvm]<br>fun [isCancellable](is-cancellable.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [isLoaded](is-loaded.md) | [androidJvm]<br>fun [isLoaded](is-loaded.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [isTerminated](is-terminated.md) | [androidJvm]<br>fun [isTerminated](is-terminated.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [isTerminating](is-terminating.md) | [androidJvm]<br>fun [isTerminating](is-terminating.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [setWorkflowLoadCompleted](set-workflow-load-completed.md) | [androidJvm]<br>fun [setWorkflowLoadCompleted](set-workflow-load-completed.md)(completed: WorkflowLoadCompleted) |
| [showConfirmationDialog](show-confirmation-dialog.md) | [androidJvm]<br>fun [showConfirmationDialog](show-confirmation-dialog.md)() |
