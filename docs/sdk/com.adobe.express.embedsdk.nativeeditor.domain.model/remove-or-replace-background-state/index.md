//[sdk](../../../index.md)/[com.adobe.express.embedsdk.nativeeditor.domain.model](../index.md)/[RemoveOrReplaceBackgroundState](index.md)

# RemoveOrReplaceBackgroundState

sealed class [RemoveOrReplaceBackgroundState](index.md) : [FeatureState](../feature-state/index.md)

Common state for image background modification operations (remove and replace background). Both features share the same subject mask preparation pipeline and thus have identical states.

#### Inheritors

| |
|---|
| [Idle](idle/index.md) |
| [DownloadingModel](downloading-model/index.md) |
| [Classifying](classifying/index.md) |
| [SelectingSubject](selecting-subject/index.md) |
| [Refining](refining/index.md) |
| [RunningInference](running-inference/index.md) |
| [Applying](applying/index.md) |
| [Success](success/index.md) |
| [Error](error/index.md) |

## Types

| Name | Summary |
|---|---|
| [Applying](applying/index.md) | <br>data object [Applying](applying/index.md) : [RemoveOrReplaceBackgroundState](index.md), [FeatureState.InProgress](../feature-state/-in-progress/index.md) |
| [Classifying](classifying/index.md) | <br>data object [Classifying](classifying/index.md) : [RemoveOrReplaceBackgroundState](index.md), [FeatureState.InProgress](../feature-state/-in-progress/index.md) |
| [DownloadingModel](downloading-model/index.md) | <br>data object [DownloadingModel](downloading-model/index.md) : [RemoveOrReplaceBackgroundState](index.md), [FeatureState.InProgress](../feature-state/-in-progress/index.md) |
| [Error](error/index.md) | <br>data class [Error](error/index.md)(val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val cause: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/throwable/index.html)? = null) : [RemoveOrReplaceBackgroundState](index.md), [FeatureState.Error](../feature-state/-error/index.md) |
| [Idle](idle/index.md) | <br>data object [Idle](idle/index.md) : [RemoveOrReplaceBackgroundState](index.md), [FeatureState.Idle](../feature-state/-idle/index.md) |
| [Refining](refining/index.md) | <br>data object [Refining](refining/index.md) : [RemoveOrReplaceBackgroundState](index.md), [FeatureState.InProgress](../feature-state/-in-progress/index.md) |
| [RunningInference](running-inference/index.md) | <br>data object [RunningInference](running-inference/index.md) : [RemoveOrReplaceBackgroundState](index.md), [FeatureState.InProgress](../feature-state/-in-progress/index.md) |
| [SelectingSubject](selecting-subject/index.md) | <br>data object [SelectingSubject](selecting-subject/index.md) : [RemoveOrReplaceBackgroundState](index.md), [FeatureState.InProgress](../feature-state/-in-progress/index.md) |
| [Success](success/index.md) | <br>data object [Success](success/index.md) : [RemoveOrReplaceBackgroundState](index.md), [FeatureState.Success](../feature-state/-success/index.md) |
