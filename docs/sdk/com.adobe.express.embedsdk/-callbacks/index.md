//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[Callbacks](index.md)

# Callbacks

\
interface [Callbacks](index.md)

## Properties

| Name | Summary |
|---|---|
| [onCancel](on-cancel.md) | <br>abstract var [onCancel](on-cancel.md): [CancelCallback](../cancel-callback/index.md)<br>Callback maybe invoked when user cancels the workflow. |
| [onError](on-error.md) | <br>abstract var [onError](on-error.md): [ErrorCallback](../error-callback/index.md)&lt;[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/any/index.html)&gt;?<br>Callback maybe invoked in case of error scenarios. |
| [onEvent](on-event.md) | <br>abstract var [onEvent](on-event.md): [EventCallback](../event-callback/index.md)?<br>Callback maybe invoked in case of some event like information events. |
| [onIntentChange](on-intent-change.md) | <br>abstract var [onIntentChange](on-intent-change.md): [IntentChangeCallback](../intent-change-callback/index.md)?<br>Callback invoked when user navigates from one design workflow to another For example: Quick action to Express. |
| [onLoad](on-load.md) | <br>abstract var [onLoad](on-load.md): [LoadCallback](../load-callback/index.md)?<br>Callback maybe invoked when target application has finished loading. |
| [onLoadInit](on-load-init.md) | <br>abstract var [onLoadInit](on-load-init.md): [LoadInitCallback](../load-init-callback/index.md)<br>Callback that may be invoked when the target application has started loading and the spinner starts. |
| [onLoadInitBegin](on-load-init-begin.md) | <br>open val [onLoadInitBegin](on-load-init-begin.md): [LoadInitBeginCallback](../load-init-begin-callback/index.md)?<br>Callback invoked before onLoadInit |
| [onLoadStart](on-load-start.md) | <br>abstract var [onLoadStart](on-load-start.md): [LoadStartCallback](../load-start-callback/index.md)?<br>Callback maybe invoked when target application has started loading. |
| [onLoadStartBegin](on-load-start-begin.md) | <br>open val [onLoadStartBegin](on-load-start-begin.md): [LoadStartBeginCallback](../load-start-begin-callback/index.md)?<br>Callback invoked before onLoadStart |
| [onPublish](on-publish.md) | <br>abstract var [onPublish](on-publish.md): [PublishCallback](../publish-callback/index.md)?<br>Callback maybe invoked when export of the asset finishes. |
| [onPublishStart](on-publish-start.md) | <br>abstract var [onPublishStart](on-publish-start.md): [PublishStartCallback](../publish-start-callback/index.md)?<br>Callback maybe invoked when user starts export of the asset to host app by click on save button. |
| [onSessionFinished](on-session-finished.md) | <br>abstract var [onSessionFinished](on-session-finished.md): [SessionFinishedCallback](../session-finished-callback/index.md)?<br>Callback invoked when the previous session (container/webview) is fully finished. Hosts can safely call warmup here to avoid racing fragment/back-stack teardown. |
| [onWarmupComplete](on-warmup-complete.md) | <br>abstract var [onWarmupComplete](on-warmup-complete.md): [WarmupCompleteCallback](../warmup-complete-callback/index.md)?<br>Callback invoked when warmup is complete. |
| [onWorkflowStarted](on-workflow-started.md) | <br>open val [onWorkflowStarted](on-workflow-started.md): [WorkflowStartedCallback](../workflow-started-callback/index.md)?<br>Callback invoked when the workflow starts (at the very beginning of launch) |
