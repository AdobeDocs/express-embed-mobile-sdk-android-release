//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[QuickActionWorkflow3p](index.md)

# QuickActionWorkflow3p

[androidJvm]\
internal class [QuickActionWorkflow3p](index.md)(val quickActionWorkflowImpl: QuickActionWorkflowImpl) : QuickActionWorkflowInterface

Third-party quick action workflow implementation.

**Third-Party Limitations:** Currently, quick action workflows are NOT supported for third-party applications. All methods in this class will throw [CCEverywhereError](../-c-c-everywhere-error/index.md) with [ErrorCode.UNSUPPORTED_API](../-error-code/-u-n-s-u-p-p-o-r-t-e-d_-a-p-i/index.md).

This may change in future SDK versions to provide limited quick action support for third-party integrations.

## Constructors

| | |
|---|---|
| [QuickActionWorkflow3p](-quick-action-workflow3p.md) | [androidJvm]<br>constructor(quickActionWorkflowImpl: QuickActionWorkflowImpl) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [quickActionWorkflowImpl](quick-action-workflow-impl.md) | [androidJvm]<br>val [quickActionWorkflowImpl](quick-action-workflow-impl.md): QuickActionWorkflowImpl |
