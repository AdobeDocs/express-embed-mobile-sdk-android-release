//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ContainerAdoptionManager](index.md)/[registerContainer](register-container.md)

# registerContainer

[androidJvm]\
abstract fun [registerContainer](register-container.md)(container: [AdoptableContainer](../-adoptable-container/index.md), ownerAction: [ActionIntent](../-action-intent/index.md), ownerIntent: [ActionIntent](../-action-intent/index.md), requestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), isPreloadOptimizationEnabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html))

Registers a new container as potentially adoptable.

#### Parameters

androidJvm

| | |
|---|---|
| container | -     The container to register |
| ownerAction | -     The action that owns the container |
| requestId | -     The request ID of the owner action |
