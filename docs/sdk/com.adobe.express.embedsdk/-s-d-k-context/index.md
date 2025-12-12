//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[SDKContext](index.md)

# SDKContext

internal open class [SDKContext](index.md)(var authController: [BaseAuthController](../-base-auth-controller/index.md)? = null, var channelMessageListener: ChannelMessageListener? = null, var validator: [Validator](../-validator/index.md)? = null, val containerManager: [ContainerManager](../-container-manager/index.md)? = null, var authStore: [AuthStore](../-auth-store/index.md)? = null, var hostInfo: [HostInfoExtended](../-host-info-extended/index.md)? = null, var configParams: [ConfigParams](../-config-params/index.md)? = null, var analyticsManager: AnalyticsManager? = null, var performanceLogger: PerformanceLogger? = null, var sdkCallbacks: [EmbedSdkCallbacks](../-embed-sdk-callbacks/index.md)? = null, var webEngineRegistry: [WebEngineRegistry](../-web-engine-registry/index.md) = WebEngineRegistry.instance)

Information that Action needs to be passed by the host.

#### Inheritors

| |
|---|
| [Action](../-action/index.md) |
| [ActionContext](../-action-context/index.md) |

## Constructors

| | |
|---|---|
| [SDKContext](-s-d-k-context.md) | [androidJvm]<br>constructor(authController: [BaseAuthController](../-base-auth-controller/index.md)? = null, channelMessageListener: ChannelMessageListener? = null, validator: [Validator](../-validator/index.md)? = null, containerManager: [ContainerManager](../-container-manager/index.md)? = null, authStore: [AuthStore](../-auth-store/index.md)? = null, hostInfo: [HostInfoExtended](../-host-info-extended/index.md)? = null, configParams: [ConfigParams](../-config-params/index.md)? = null, analyticsManager: AnalyticsManager? = null, performanceLogger: PerformanceLogger? = null, sdkCallbacks: [EmbedSdkCallbacks](../-embed-sdk-callbacks/index.md)? = null, webEngineRegistry: [WebEngineRegistry](../-web-engine-registry/index.md) = WebEngineRegistry.instance) |

## Properties

| Name | Summary |
|---|---|
| [analyticsManager](analytics-manager.md) | [androidJvm]<br>var [analyticsManager](analytics-manager.md): AnalyticsManager? |
| [authController](auth-controller.md) | [androidJvm]<br>var [authController](auth-controller.md): [BaseAuthController](../-base-auth-controller/index.md)? |
| [authStore](auth-store.md) | [androidJvm]<br>var [authStore](auth-store.md): [AuthStore](../-auth-store/index.md)? |
| [channelMessageListener](channel-message-listener.md) | [androidJvm]<br>var [channelMessageListener](channel-message-listener.md): ChannelMessageListener? |
| [configParams](config-params.md) | [androidJvm]<br>var [configParams](config-params.md): [ConfigParams](../-config-params/index.md)? |
| [containerManager](container-manager.md) | [androidJvm]<br>val [containerManager](container-manager.md): [ContainerManager](../-container-manager/index.md)? = null |
| [hostInfo](host-info.md) | [androidJvm]<br>var [hostInfo](host-info.md): [HostInfoExtended](../-host-info-extended/index.md)? |
| [performanceLogger](performance-logger.md) | [androidJvm]<br>var [performanceLogger](performance-logger.md): PerformanceLogger? |
| [sdkCallbacks](sdk-callbacks.md) | [androidJvm]<br>var [sdkCallbacks](sdk-callbacks.md): [EmbedSdkCallbacks](../-embed-sdk-callbacks/index.md)? |
| [validator](validator.md) | [androidJvm]<br>var [validator](validator.md): [Validator](../-validator/index.md)? |
| [webEngineRegistry](web-engine-registry.md) | [androidJvm]<br>var [webEngineRegistry](web-engine-registry.md): [WebEngineRegistry](../-web-engine-registry/index.md) |
