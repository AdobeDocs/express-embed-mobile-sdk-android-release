//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WorkflowContext](index.md)

# WorkflowContext

[androidJvm]\
abstract class [WorkflowContext](index.md)

Base class for all workflow contexts Provides common functionality for communicating with the active workflow.

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [instanceId](instance-id.md) | [androidJvm]<br>val [instanceId](instance-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)<br>Unique identifier for this workflow instance |

## Functions

| Name | Summary |
|---|---|
| [cleanupPendingCallback](cleanup-pending-callback.md) | [androidJvm]<br>open fun [cleanupPendingCallback](cleanup-pending-callback.md)(action: MessageType) |
| [clearContext](clear-context.md) | [androidJvm]<br>open fun [clearContext](clear-context.md)()<br>Cleanup method to unregister this context Should be called when the context is no longer needed |
| [getDefaultResponse](get-default-response.md) | [androidJvm]<br>abstract fun [getDefaultResponse](get-default-response.md)(action: MessageType): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-any/index.html)<br>Returns default response values for various message types when asset is not loaded |
| [handleResponse](handle-response.md) | [androidJvm]<br>open fun [handleResponse](handle-response.md)(instanceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), requestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), responseData: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-any/index.html)&gt;)<br>Handles response messages from the web component This should be called when a response message is received |
| [onErrorCallBack](on-error-call-back.md) | [androidJvm]<br>fun [onErrorCallBack](on-error-call-back.md)(errorData: [CCEverywhereError](../-c-c-everywhere-error/index.md)) |
