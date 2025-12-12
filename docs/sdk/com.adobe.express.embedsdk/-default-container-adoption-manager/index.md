//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[DefaultContainerAdoptionManager](index.md)

# DefaultContainerAdoptionManager

[androidJvm]\
internal class [DefaultContainerAdoptionManager](index.md)(compatibilityChecker: [AdoptionCompatibilityChecker](../-adoption-compatibility-checker/index.md)) : [ContainerAdoptionManager](../-container-adoption-manager/index.md)

Orchestrates the WebView adoption process.

## Constructors

| | |
|---|---|
| [DefaultContainerAdoptionManager](-default-container-adoption-manager.md) | [androidJvm]<br>constructor(compatibilityChecker: [AdoptionCompatibilityChecker](../-adoption-compatibility-checker/index.md)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [attemptAdoption](attempt-adoption.md) | [androidJvm]<br>open suspend override fun [attemptAdoption](attempt-adoption.md)(targetAction: [ActionIntent](../-action-intent/index.md), targetContext: [ActionContext](../-action-context/index.md), targetInfo: [TargetInfo](../-target-info/index.md), containerProperties: [ContainerProperties](../-container-properties/index.md)?, newFragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?, targetEndpointPromise: Deferred&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;?): [AdoptableContainer](../-adoptable-container/index.md)?<br>Attempts to adopt an existing container for the given action. |
| [clearAdoptableContainer](clear-adoptable-container.md) | [androidJvm]<br>open override fun [clearAdoptableContainer](clear-adoptable-container.md)()<br>Clears any cached adoptable container state. |
| [clearAdoptableContainerForIntent](clear-adoptable-container-for-intent.md) | [androidJvm]<br>fun [clearAdoptableContainerForIntent](clear-adoptable-container-for-intent.md)(intent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)) |
| [registerContainer](register-container.md) | [androidJvm]<br>open override fun [registerContainer](register-container.md)(container: [AdoptableContainer](../-adoptable-container/index.md), ownerAction: [ActionIntent](../-action-intent/index.md), ownerIntent: [ActionIntent](../-action-intent/index.md), requestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), isPreloadOptimizationEnabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html))<br>Registers a new container as potentially adoptable. |
| [unregisterContainer](unregister-container.md) | [androidJvm]<br>open override fun [unregisterContainer](unregister-container.md)(container: [AdoptableContainer](../-adoptable-container/index.md))<br>Unregisters a container from adoption management. |
