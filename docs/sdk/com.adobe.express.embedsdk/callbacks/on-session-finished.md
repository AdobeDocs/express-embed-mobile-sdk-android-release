//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[Callbacks](index.md)/[onSessionFinished](on-session-finished.md)

# onSessionFinished

\
abstract var [onSessionFinished](on-session-finished.md): [SessionFinishedCallback](../session-finished-callback/index.md)?

Callback invoked when the previous session (container/webview) is fully finished. Hosts can safely call warmup here to avoid racing fragment/back-stack teardown.
