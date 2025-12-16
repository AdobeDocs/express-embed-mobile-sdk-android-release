//[sdk](../../../../index.md)/[com.adobe.express.embedsdk](../../index.md)/[ExpressEmbedSdk](../index.md)/[Companion](index.md)/[initialize](initialize.md)

# initialize

[androidJvm]\
fun [initialize](initialize.md)(hostInfo: HostInfo, configParams: [ConfigParams](../../-config-params/index.md), authProvider: [AuthProvider](../../-auth-provider/index.md)? = null, appContext: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sdkCallBacks: [EmbedSdkCallbacks](../../-embed-sdk-callbacks/index.md)? = null, clientAuthProvider: [ClientAuthProvider](../../-client-auth-provider/index.md)? = null): [CCEverywhereInterface](../../-c-c-everywhere-interface/index.md)

This is the main API which is used for initializing the SDK. Please ensure to call this API only once.

## Example

val sdk = ExpressEmbedSdk.initialize(     hostInfo = HostInfo(         clientId = &quot;your-dev-console-client-id&quot;,         appName = &quot;MyApp&quot;,         appVersion = Version(&quot;1.0.0&quot;),         platformCategory = PlatformCategory.MOBILE     ),     configParams = ConfigParams(         env = Environment.PRODUCTION,         locale = &quot;en_US&quot;     ),     appContext = applicationContext ) // Access workflows sdk.module?.createImageFromText(...)

#### Return

Promise with CCEverywhereInterface object which can be used to call other APIs of SDK

#### Parameters

androidJvm

| | |
|---|---|
| hostInfo | Host application information containing client ID from Developer Console (3rd party) or IMSS portal (1st party), application name, version |
| configParams | Configuration parameters for specifying locale preferences and environment settings (production, stage) |
| authProvider | Authentication provider for managing authentication and setting IMS session. If not provided, defaults to PRE_SIGNED_IN mode |
| appContext | Android application context required for SDK initialization and resource access |
| sdkCallBacks | Callbacks for SDK lifecycle events |

#### Throws

| | |
|---|---|
| [CCEverywhereError](../../-c-c-everywhere-error/index.md) | if SDK initialization fails or is already in progress |
