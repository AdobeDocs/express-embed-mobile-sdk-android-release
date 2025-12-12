//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ActionManager](index.md)/[close](close.md)

# close

[androidJvm]\
fun [close](close.md)(closeReason: [ContainerCloseReason](../-container-close-reason/index.md), forced: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) = false): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)

Closes the currently active action workflow.

#### Return

true if action was successfully closed, false otherwise

#### Parameters

androidJvm

| | |
|---|---|
| closeReason | The reason for closing the action (user initiated, SDK initiated, etc.) |
| forced | If true, forces closure even if no active workflow exists |
