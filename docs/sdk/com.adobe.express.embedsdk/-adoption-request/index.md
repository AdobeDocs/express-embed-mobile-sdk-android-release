//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[AdoptionRequest](index.md)

# AdoptionRequest

[androidJvm]\
internal data class [AdoptionRequest](index.md)(val targetAction: [ActionIntent](../-action-intent/index.md), val targetContext: [ActionContext](../-action-context/index.md), val targetInfo: [TargetInfo](../-target-info/index.md), val targetEndpoint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), val containerProperties: [ContainerProperties](../-container-properties/index.md)?, val adoptionStrategy: [AdoptionStrategy](../-adoption-strategy/index.md), val newFragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?)

Contains all the parameters needed for container adoption.

## Constructors

| | |
|---|---|
| [AdoptionRequest](-adoption-request.md) | [androidJvm]<br>constructor(targetAction: [ActionIntent](../-action-intent/index.md), targetContext: [ActionContext](../-action-context/index.md), targetInfo: [TargetInfo](../-target-info/index.md), targetEndpoint: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), containerProperties: [ContainerProperties](../-container-properties/index.md)?, adoptionStrategy: [AdoptionStrategy](../-adoption-strategy/index.md), newFragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?) |

## Properties

| Name | Summary |
|---|---|
| [adoptionStrategy](adoption-strategy.md) | [androidJvm]<br>val [adoptionStrategy](adoption-strategy.md): [AdoptionStrategy](../-adoption-strategy/index.md) |
| [containerProperties](container-properties.md) | [androidJvm]<br>val [containerProperties](container-properties.md): [ContainerProperties](../-container-properties/index.md)? |
| [newFragmentOrContext](new-fragment-or-context.md) | [androidJvm]<br>val [newFragmentOrContext](new-fragment-or-context.md): [FragmentOrContext](../-fragment-or-context/index.md)? |
| [targetAction](target-action.md) | [androidJvm]<br>val [targetAction](target-action.md): [ActionIntent](../-action-intent/index.md) |
| [targetContext](target-context.md) | [androidJvm]<br>val [targetContext](target-context.md): [ActionContext](../-action-context/index.md) |
| [targetEndpoint](target-endpoint.md) | [androidJvm]<br>val [targetEndpoint](target-endpoint.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html) |
| [targetInfo](target-info.md) | [androidJvm]<br>val [targetInfo](target-info.md): [TargetInfo](../-target-info/index.md) |
