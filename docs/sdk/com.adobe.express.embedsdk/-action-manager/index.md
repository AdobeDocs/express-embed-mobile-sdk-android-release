//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ActionManager](index.md)

# ActionManager

[androidJvm]\
internal class [ActionManager](index.md)(configParams: [ConfigParams](../-config-params/index.md), context: [SDKContext](../-s-d-k-context/index.md))

Manages the lifecycle of SDK actions and workflows. Handles launching, closing, and monitoring active actions.

## Constructors

| | |
|---|---|
| [ActionManager](-action-manager.md) | [androidJvm]<br>constructor(configParams: [ConfigParams](../-config-params/index.md), context: [SDKContext](../-s-d-k-context/index.md)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [activeAction](active-action.md) | [androidJvm]<br>var [activeAction](active-action.md): [BaseAction](../-base-action/index.md)? |

## Functions

| Name | Summary |
|---|---|
| [addActionStateListener](add-action-state-listener.md) | [androidJvm]<br>fun [addActionStateListener](add-action-state-listener.md)(listener: [ActionStateListener](../-action-state-listener/index.md))<br>Register a listener for action state changes including launches and timeouts. |
| [cancelLaunchTimer](cancel-launch-timer.md) | [androidJvm]<br>fun [cancelLaunchTimer](cancel-launch-timer.md)() |
| [clearActiveContext](clear-active-context.md) | [androidJvm]<br>fun [clearActiveContext](clear-active-context.md)() |
| [clearRequests](clear-requests.md) | [androidJvm]<br>fun [clearRequests](clear-requests.md)() |
| [close](close.md) | [androidJvm]<br>fun [close](close.md)(closeReason: [ContainerCloseReason](../-container-close-reason/index.md), forced: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) = false): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Closes the currently active action workflow. |
| [getActiveWarmupAction](get-active-warmup-action.md) | [androidJvm]<br>fun [getActiveWarmupAction](get-active-warmup-action.md)(): [WarmupAction](../-warmup-action/index.md)? |
| [isActionCancelled](is-action-cancelled.md) | [androidJvm]<br>fun [isActionCancelled](is-action-cancelled.md)(requestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Check if a specific action has been marked as cancelled. |
| [launch](launch.md) | [androidJvm]<br>suspend fun [launch](launch.md)(actionIntent: [ActionIntent](../-action-intent/index.md), designConfig: [DesignConfig](../-design-config/index.md), fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)? = null)<br>Launches the specified action workflow with the provided configuration. Handles session reuse, timeout management, and action lifecycle. |
| [markActionAsCancelled](mark-action-as-cancelled.md) | [androidJvm]<br>fun [markActionAsCancelled](mark-action-as-cancelled.md)(requestId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html))<br>Mark a specific action as cancelled by request ID for tracking purposes. |
| [notifySessionFinished](notify-session-finished.md) | [androidJvm]<br>fun [notifySessionFinished](notify-session-finished.md)()<br>Should be called once the UI teardown (WebView + Fragment removal) is fully completed. |
| [prepareSessionFinishedCallback](prepare-session-finished-callback.md) | [androidJvm]<br>fun [prepareSessionFinishedCallback](prepare-session-finished-callback.md)(hostHandler: [HostCallbackHandler](../-host-callback-handler/index.md)?, actionIntent: [ActionIntent](../-action-intent/index.md)?)<br>Prepares the session-complete callback so it fires after WebView/Fragment removal, |
| [removeActionStateListener](remove-action-state-listener.md) | [androidJvm]<br>fun [removeActionStateListener](remove-action-state-listener.md)(listener: [ActionStateListener](../-action-state-listener/index.md))<br>Unregister a listener for action state changes. |
| [resetActiveAction](reset-active-action.md) | [androidJvm]<br>fun [resetActiveAction](reset-active-action.md)() |
