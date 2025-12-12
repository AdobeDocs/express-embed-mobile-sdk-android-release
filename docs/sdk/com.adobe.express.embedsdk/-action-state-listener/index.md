//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ActionStateListener](index.md)

# ActionStateListener

[androidJvm]\
interface [ActionStateListener](index.md)

Interface for listening to action state changes in ActionManager

## Functions

| Name | Summary |
|---|---|
| [onActionClosed](on-action-closed.md) | [androidJvm]<br>abstract fun [onActionClosed](on-action-closed.md)(actionIntent: [ActionIntent](../-action-intent/index.md)?, closeReason: [ContainerCloseReason](../-container-close-reason/index.md))<br>Called when an action is closed for any reason |
| [onActionLaunched](on-action-launched.md) | [androidJvm]<br>abstract fun [onActionLaunched](on-action-launched.md)(actionIntent: [ActionIntent](../-action-intent/index.md))<br>Called when an action is successfully launched |
| [onActionTimeout](on-action-timeout.md) | [androidJvm]<br>abstract fun [onActionTimeout](on-action-timeout.md)(actionIntent: [ActionIntent](../-action-intent/index.md)?)<br>Called when an action times out during launch |
