//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[DefaultContainerAdoptionManager](index.md)/[attemptAdoption](attempt-adoption.md)

# attemptAdoption

[androidJvm]\
open suspend override fun [attemptAdoption](attempt-adoption.md)(targetAction: [ActionIntent](../-action-intent/index.md), targetContext: [ActionContext](../-action-context/index.md), targetInfo: [TargetInfo](../-target-info/index.md), containerProperties: [ContainerProperties](../-container-properties/index.md)?, newFragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?, targetEndpointPromise: Deferred&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;?): [AdoptableContainer](../-adoptable-container/index.md)?

Attempts to adopt an existing container for the given action.

#### Return

The adopted container if successful, null if no adoption possible

#### Parameters

androidJvm

| | |
|---|---|
| targetAction | -     The action requesting a container |
| targetContext | -     The context of the target action |
| targetInfo | -     The target information for the new action |
| targetEndpoint | -     The target endpoint URL for the new action |
| containerProperties | -     The properties for the container |
| newFragmentOrContext | -     The new fragment context for the adopted container |
