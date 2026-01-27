//[sdk](../../../../index.md)/[com.adobe.express.embedsdk](../../index.md)/[ExpressEmbedSdk](../index.md)/[Companion](index.md)

# Companion

\
object [Companion](index.md)

## Functions

| Name | Summary |
|---|---|
| [getCCEverywhereInstance](get-c-c-everywhere-instance.md) | <br>fun [getCCEverywhereInstance](get-c-c-everywhere-instance.md)(): [CCEverywhereInterface](../../c-c-everywhere-interface/index.md)?<br>Returns the current active SDK instance if the SDK has been successfully initialized. |
| [initialize](initialize.md) | <br>fun [initialize](initialize.md)(hostInfo: HostInfo, configParams: ConfigParams, authProvider: [AuthProvider](../../auth-provider/index.md)? = null, appContext: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sdkCallBacks: EmbedSdkCallbacks? = null, clientAuthProvider: [ClientAuthProvider](../../client-auth-provider/index.md)? = null): [CCEverywhereInterface](../../c-c-everywhere-interface/index.md)<br>This is the main API which is used for initializing the SDK. Please ensure to call this API only once. |
