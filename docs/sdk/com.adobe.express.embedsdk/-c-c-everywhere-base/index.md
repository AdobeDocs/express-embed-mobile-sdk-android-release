//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[CCEverywhereBase](index.md)

# CCEverywhereBase

internal open class [CCEverywhereBase](index.md)(validator: [Validator](../-validator/index.md), hostInfoExtended: [HostInfoExtended](../-host-info-extended/index.md), val authProvider: [AuthProvider](../-auth-provider/index.md), configParams: [ConfigParams](../-config-params/index.md), var authController: [AuthControllerConstructor](../-auth-controller-constructor/index.md), appContext: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sdkCallbacks: [EmbedSdkCallbacks](../-embed-sdk-callbacks/index.md)? = null) : [CCEverywhereInterface](../-c-c-everywhere-interface/index.md), RequestIdUpdateListener

Base implementation of the Adobe Express Embed SDK.

#### Inheritors

| |
|---|
| [CCEverywhere3p](../-c-c-everywhere3p/index.md) |

## Constructors

| | |
|---|---|
| [CCEverywhereBase](-c-c-everywhere-base.md) | [androidJvm]<br>constructor(validator: [Validator](../-validator/index.md), hostInfoExtended: [HostInfoExtended](../-host-info-extended/index.md), authProvider: [AuthProvider](../-auth-provider/index.md), configParams: [ConfigParams](../-config-params/index.md), authController: [AuthControllerConstructor](../-auth-controller-constructor/index.md), appContext: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), sdkCallbacks: [EmbedSdkCallbacks](../-embed-sdk-callbacks/index.md)? = null) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [actionManager](action-manager.md) | [androidJvm]<br>internal lateinit var [actionManager](action-manager.md): [ActionManager](../-action-manager/index.md) |
| [authController](auth-controller.md) | [androidJvm]<br>var [authController](auth-controller.md): [AuthControllerConstructor](../-auth-controller-constructor/index.md)<br>Constructor for creating authentication controllers |
| [authProvider](auth-provider.md) | [androidJvm]<br>val [authProvider](auth-provider.md): [AuthProvider](../-auth-provider/index.md)<br>Authentication provider for managing user sessions |
| [context](context.md) | [androidJvm]<br>internal lateinit var [context](context.md): [SDKContext](../-s-d-k-context/index.md) |
| [imageAssetProcessor](image-asset-processor.md) | [androidJvm]<br>internal lateinit var [imageAssetProcessor](image-asset-processor.md): [ImageAssetProcessor](../-image-asset-processor/index.md) |
| [internal](internal.md) | [androidJvm]<br>open override val [internal](internal.md): InternalInterface?<br>Internal SDK functionality for testing (null for External Clients) |

## Functions

| Name | Summary |
|---|---|
| [activeWorkflow](active-workflow.md) | [androidJvm]<br>open override fun [activeWorkflow](active-workflow.md)(): [ActionIntent](../-action-intent/index.md)?<br>Returns the currently active workflow if one is running. |
| [close](close.md) | [androidJvm]<br>open override fun [close](close.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Closes the currently active workflow and releases associated resources. |
| [closeForReinitialization](close-for-reinitialization.md) | [androidJvm]<br>fun [closeForReinitialization](close-for-reinitialization.md)() |
| [onRequestIdUpdate](on-request-id-update.md) | [androidJvm]<br>open override fun [onRequestIdUpdate](on-request-id-update.md)(requestIdMap: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;) |
| [terminate](terminate.md) | [androidJvm]<br>fun [terminate](terminate.md)()<br>Terminates the SDK instance and releases all resources. After calling this method, the SDK must be reinitialized to use again. |
