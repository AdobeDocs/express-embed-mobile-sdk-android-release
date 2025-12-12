//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[AdoptableContainer](index.md)

# AdoptableContainer

internal interface [AdoptableContainer](index.md)

Interface for managing adoptable containers.

#### Inheritors

| |
|---|
| [Container](../-container/index.md) |

## Properties

| Name | Summary |
|---|---|
| [adoptionState](adoption-state.md) | [androidJvm]<br>abstract val [adoptionState](adoption-state.md): [ContainerAdoptionState](../-container-adoption-state/index.md)<br>The current state of the container. |
| [ownerAction](owner-action.md) | [androidJvm]<br>abstract val [ownerAction](owner-action.md): [ActionIntent](../-action-intent/index.md)?<br>The action that currently owns this container. |
| [ownerIntent](owner-intent.md) | [androidJvm]<br>abstract var [ownerIntent](owner-intent.md): [ActionIntent](../-action-intent/index.md)?<br>The action that wants to adopt this container. |
| [requestId](request-id.md) | [androidJvm]<br>abstract val [requestId](request-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>The request ID of the current action. |

## Functions

| Name | Summary |
|---|---|
| [adoptForAction](adopt-for-action.md) | [androidJvm]<br>abstract suspend fun [adoptForAction](adopt-for-action.md)(adoptionRequest: [AdoptionRequest](../-adoption-request/index.md))<br>Adopts this container for a new action and updates its properties. |
| [getActionContext](get-action-context.md) | [androidJvm]<br>abstract fun [getActionContext](get-action-context.md)(): [ActionContext](../-action-context/index.md)?<br>Gets the action context for this container. |
| [markAsAdoptable](mark-as-adoptable.md) | [androidJvm]<br>abstract fun [markAsAdoptable](mark-as-adoptable.md)()<br>Marks the container as adoptable. |
