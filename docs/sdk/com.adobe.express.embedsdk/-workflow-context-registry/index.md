//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WorkflowContextRegistry](index.md)

# WorkflowContextRegistry

[androidJvm]\
internal object [WorkflowContextRegistry](index.md)

Simple registry to track active WorkflowContext instances This allows message handling to find the correct context by instanceId

## Functions

| Name | Summary |
|---|---|
| [findContext](find-context.md) | [androidJvm]<br>fun [findContext](find-context.md)(instanceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)): [WorkflowContext](../-workflow-context/index.md)?<br>Finds a workflow context by its instance ID |
| [getActiveContextIds](get-active-context-ids.md) | [androidJvm]<br>fun [getActiveContextIds](get-active-context-ids.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;<br>Gets all active context IDs for debugging |
| [register](register.md) | [androidJvm]<br>fun [register](register.md)(context: [WorkflowContext](../-workflow-context/index.md))<br>Registers a workflow context |
| [unregister](unregister.md) | [androidJvm]<br>fun [unregister](unregister.md)(instanceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html))<br>Unregisters a workflow context |
