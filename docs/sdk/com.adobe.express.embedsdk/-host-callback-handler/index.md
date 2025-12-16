//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[HostCallbackHandler](index.md)

# HostCallbackHandler

[androidJvm]\
class [HostCallbackHandler](index.md)(hostCallbacks: [Callbacks](../-callbacks/index.md)? = null)

## Constructors

| | |
|---|---|
| [HostCallbackHandler](-host-callback-handler.md) | [androidJvm]<br>constructor(hostCallbacks: [Callbacks](../-callbacks/index.md)? = null) |

## Functions

| Name | Summary |
|---|---|
| [onCancel](on-cancel.md) | [androidJvm]<br>fun [onCancel](on-cancel.md)(reason: CancelReason) |
| [onError](on-error.md) | [androidJvm]<br>fun [onError](on-error.md)(error: [CCEverywhereError](../-c-c-everywhere-error/index.md)) |
| [onEvent](on-event.md) | [androidJvm]<br>fun [onEvent](on-event.md)(data: HostEventData) |
| [onLoad](on-load.md) | [androidJvm]<br>fun [onLoad](on-load.md)() |
| [onLoadInit](on-load-init.md) | [androidJvm]<br>fun [onLoadInit](on-load-init.md)() |
| [onLoadInitBegin](on-load-init-begin.md) | [androidJvm]<br>fun [onLoadInitBegin](on-load-init-begin.md)() |
| [onLoadStart](on-load-start.md) | [androidJvm]<br>fun [onLoadStart](on-load-start.md)() |
| [onLoadStartBegin](on-load-start-begin.md) | [androidJvm]<br>fun [onLoadStartBegin](on-load-start-begin.md)() |
| [onPublish](on-publish.md) | [androidJvm]<br>fun [onPublish](on-publish.md)(intent: [ActionIntent](../-action-intent/index.md), publishParams: [PublishParams](../-publish-params/index.md)) |
| [onPublishStart](on-publish-start.md) | [androidJvm]<br>fun [onPublishStart](on-publish-start.md)() |
| [onSessionFinished](on-session-finished.md) | [androidJvm]<br>fun [onSessionFinished](on-session-finished.md)(forIntent: [ActionIntent](../-action-intent/index.md)?) |
| [onWarmupComplete](on-warmup-complete.md) | [androidJvm]<br>fun [onWarmupComplete](on-warmup-complete.md)(forIntent: [ActionIntent](../-action-intent/index.md)?) |
