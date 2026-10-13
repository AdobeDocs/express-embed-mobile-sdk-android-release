//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[HostCallbackHandler](index.md)

# HostCallbackHandler

\
class [HostCallbackHandler](index.md)(hostCallbacks: Callbacks? = null)

## Constructors

| | |
|---|---|
| [HostCallbackHandler](host-callback-handler.md) | <br>constructor(hostCallbacks: Callbacks? = null) |

## Functions

| Name | Summary |
|---|---|
| [onCancel](on-cancel.md) | <br>fun [onCancel](on-cancel.md)(reason: CancelReason, cancelMessageData: CancelCTA? = null) |
| [onError](on-error.md) | <br>fun [onError](on-error.md)(error: [CCEverywhereError](../c-c-everywhere-error/index.md)) |
| [onEvent](on-event.md) | <br>fun [onEvent](on-event.md)(data: HostEventData) |
| [onLoad](on-load.md) | <br>fun [onLoad](on-load.md)() |
| [onLoadInit](on-load-init.md) | <br>fun [onLoadInit](on-load-init.md)() |
| [onLoadInitBegin](on-load-init-begin.md) | <br>fun [onLoadInitBegin](on-load-init-begin.md)() |
| [onLoadStart](on-load-start.md) | <br>fun [onLoadStart](on-load-start.md)() |
| [onLoadStartBegin](on-load-start-begin.md) | <br>fun [onLoadStartBegin](on-load-start-begin.md)() |
| [onPublish](on-publish.md) | <br>fun [onPublish](on-publish.md)(intent: ActionIntent, publishParams: PublishParams) |
| [onPublishStart](on-publish-start.md) | <br>fun [onPublishStart](on-publish-start.md)() |
| [onSessionFinished](on-session-finished.md) | <br>fun [onSessionFinished](on-session-finished.md)(forIntent: ActionIntent?) |
| [onSignInFailed](on-sign-in-failed.md) | <br>fun [onSignInFailed](on-sign-in-failed.md)() |
| [onSignInRequired](on-sign-in-required.md) | <br>fun [onSignInRequired](on-sign-in-required.md)(reason: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?, complete: (credentials: SignInCredentials?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/unit/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)<br>Dispatches a mid-session sign-in request to the host. Returns true if a handler was wired and invoked, false if the host never registered [onSignInRequired](on-sign-in-required.md) — the caller resets its in-flight state on false so a missing callback can't permanently wedge the action. |
| [onWarmupComplete](on-warmup-complete.md) | <br>fun [onWarmupComplete](on-warmup-complete.md)(forIntent: ActionIntent?) |
