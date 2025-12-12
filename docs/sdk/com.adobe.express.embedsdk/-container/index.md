//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[Container](index.md)

# Container

[androidJvm]\
internal class [Container](index.md) : [Fragment](https://developer.android.com/reference/kotlin/androidx/fragment/app/Fragment.html), [AdoptableContainer](../-adoptable-container/index.md)

## Constructors

| | |
|---|---|
| [Container](-container.md) | [androidJvm]<br>constructor() |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [adoptionState](adoption-state.md) | [androidJvm]<br>open override var [adoptionState](adoption-state.md): [ContainerAdoptionState](../-container-adoption-state/index.md)<br>The current state of the container. |
| [ownerAction](owner-action.md) | [androidJvm]<br>open override var [ownerAction](owner-action.md): [ActionIntent](../-action-intent/index.md)?<br>The action that currently owns this container. |
| [ownerIntent](owner-intent.md) | [androidJvm]<br>open override var [ownerIntent](owner-intent.md): [ActionIntent](../-action-intent/index.md)?<br>The action that wants to adopt this container. |
| [requestId](request-id.md) | [androidJvm]<br>open override var [requestId](request-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>The request ID of the current action. |
| [wasCreatedWithPreloadOptimization](was-created-with-preload-optimization.md) | [androidJvm]<br>var [wasCreatedWithPreloadOptimization](was-created-with-preload-optimization.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [webEngineProvider](web-engine-provider.md) | [androidJvm]<br>var [webEngineProvider](web-engine-provider.md): [WebEngineProvider](../-web-engine-provider/index.md)? |

## Functions

| Name | Summary |
|---|---|
| [adoptForAction](adopt-for-action.md) | [androidJvm]<br>open suspend override fun [adoptForAction](adopt-for-action.md)(adoptionRequest: [AdoptionRequest](../-adoption-request/index.md))<br>Adopts this container for a new action and updates its properties. |
| [getActionContext](get-action-context.md) | [androidJvm]<br>open override fun [getActionContext](get-action-context.md)(): [ActionContext](../-action-context/index.md)?<br>Gets the action context for this container. |
| [initializeForAction](initialize-for-action.md) | [androidJvm]<br>internal fun [initializeForAction](initialize-for-action.md)(actionIntent: [ActionIntent](../-action-intent/index.md), requestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), isPreloadOptimizationEnabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) = false) |
| [markAsAdoptable](mark-as-adoptable.md) | [androidJvm]<br>open override fun [markAsAdoptable](mark-as-adoptable.md)()<br>Marks the container as adoptable. |
| [onCreate](on-create.md) | [androidJvm]<br>open override fun [onCreate](on-create.md)(savedInstanceState: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?) |
| [onCreateView](on-create-view.md) | [androidJvm]<br>open override fun [onCreateView](on-create-view.md)(inflater: [LayoutInflater](https://developer.android.com/reference/kotlin/android/view/LayoutInflater.html), container: [ViewGroup](https://developer.android.com/reference/kotlin/android/view/ViewGroup.html)?, savedInstanceState: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?): [View](https://developer.android.com/reference/kotlin/android/view/View.html) |
| [onDestroyView](on-destroy-view.md) | [androidJvm]<br>open override fun [onDestroyView](on-destroy-view.md)() |
| [onPause](on-pause.md) | [androidJvm]<br>open override fun [onPause](on-pause.md)() |
| [onResume](on-resume.md) | [androidJvm]<br>open override fun [onResume](on-resume.md)() |
| [onViewCreated](on-view-created.md) | [androidJvm]<br>open override fun [onViewCreated](on-view-created.md)(view: [View](https://developer.android.com/reference/kotlin/android/view/View.html), savedInstanceState: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?) |
| [removeListener](remove-listener.md) | [androidJvm]<br>fun [removeListener](remove-listener.md)() |
