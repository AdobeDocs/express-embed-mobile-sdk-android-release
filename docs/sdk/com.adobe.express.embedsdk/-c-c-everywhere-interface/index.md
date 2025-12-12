//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[CCEverywhereInterface](index.md)

# CCEverywhereInterface

[androidJvm]\
interface [CCEverywhereInterface](index.md)

Main interface providing access to Adobe Express Embed SDK functionality. Entry point for all SDK operations including workflows and lifecycle management.

## Properties

| Name | Summary |
|---|---|
| [analyticsController](analytics-controller.md) | [androidJvm]<br>open val [analyticsController](analytics-controller.md): AnalyticsController? |
| [internal](internal.md) | [androidJvm]<br>abstract val [internal](internal.md): InternalInterface?<br>Internal SDK functionality for testing (null for External Clients) |
| [module](module.md) | [androidJvm]<br>open val [module](module.md): [ModuleWorkflowInterface](../-module-workflow-interface/index.md)? |
| [quickAction](quick-action.md) | [androidJvm]<br>open val [quickAction](quick-action.md): [QuickActionWorkflowInterface](../-quick-action-workflow-interface/index.md)? |

## Functions

| Name | Summary |
|---|---|
| [activeWorkflow](active-workflow.md) | [androidJvm]<br>abstract fun [activeWorkflow](active-workflow.md)(): [ActionIntent](../-action-intent/index.md)?<br>Returns the currently active workflow, if any. |
| [close](close.md) | [androidJvm]<br>abstract fun [close](close.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Closes the current active workflow and cleans up resources. |
