//[sdk](../../../index.md)/[com.adobe.express.embedsdk.nativeeditor.domain.model](../index.md)/[FeatureState](index.md)

# FeatureState

sealed interface [FeatureState](index.md)

Base sealed class for all feature operation states.

Provides a consistent pattern for tracking feature execution:

- 
   Idle: Feature not started
- 
   InProgress: Feature executing
- 
   Success: Feature completed successfully
- 
   Error: Feature failed

#### Inheritors

| |
|---|
| [Idle](idle/index.md) |
| [InProgress](in-progress/index.md) |
| [Success](success/index.md) |
| [Error](error/index.md) |
| [RemoveOrReplaceBackgroundState](../remove-or-replace-background-state/index.md) |

## Types

| Name | Summary |
|---|---|
| [Error](error/index.md) | <br>interface [Error](error/index.md) : [FeatureState](index.md) |
| [Idle](idle/index.md) | <br>interface [Idle](idle/index.md) : [FeatureState](index.md) |
| [InProgress](in-progress/index.md) | <br>interface [InProgress](in-progress/index.md) : [FeatureState](index.md) |
| [Success](success/index.md) | <br>interface [Success](success/index.md) : [FeatureState](index.md) |
