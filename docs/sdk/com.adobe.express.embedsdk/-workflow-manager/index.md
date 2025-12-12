//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WorkflowManager](index.md)

# WorkflowManager

[androidJvm]\
internal object [WorkflowManager](index.md)

Utility class to manage close operation synchronization across multiple APIs. This ensures that new API calls wait for any pending close operations to complete.

## Functions

| Name | Summary |
|---|---|
| [clearCloseOperation](clear-close-operation.md) | [androidJvm]<br>fun [clearCloseOperation](clear-close-operation.md)() |
| [hasPendingCloseOperation](has-pending-close-operation.md) | [androidJvm]<br>fun [hasPendingCloseOperation](has-pending-close-operation.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [signalCloseCompletion](signal-close-completion.md) | [androidJvm]<br>fun [signalCloseCompletion](signal-close-completion.md)() |
| [startCloseOperation](start-close-operation.md) | [androidJvm]<br>fun [startCloseOperation](start-close-operation.md)() |
| [waitForCloseCompletion](wait-for-close-completion.md) | [androidJvm]<br>suspend fun [waitForCloseCompletion](wait-for-close-completion.md)(apiName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)) |
