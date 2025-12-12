//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ContainerManager](index.md)

# ContainerManager

[androidJvm]\
internal class [ContainerManager](index.md)(authController: [BaseAuthController](../-base-auth-controller/index.md), val channelMessageListener: ChannelMessageListener, var analyticsManager: AnalyticsManager, var performanceLogger: PerformanceLogger)

## Constructors

| | |
|---|---|
| [ContainerManager](-container-manager.md) | [androidJvm]<br>constructor(authController: [BaseAuthController](../-base-auth-controller/index.md), channelMessageListener: ChannelMessageListener, analyticsManager: AnalyticsManager, performanceLogger: PerformanceLogger) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [analyticsManager](analytics-manager.md) | [androidJvm]<br>var [analyticsManager](analytics-manager.md): AnalyticsManager |
| [channelMessageListener](channel-message-listener.md) | [androidJvm]<br>val [channelMessageListener](channel-message-listener.md): ChannelMessageListener |
| [performanceLogger](performance-logger.md) | [androidJvm]<br>var [performanceLogger](performance-logger.md): PerformanceLogger |

## Functions

| Name | Summary |
|---|---|
| [clearAdoptionCache](clear-adoption-cache.md) | [androidJvm]<br>fun [clearAdoptionCache](clear-adoption-cache.md)()<br>Clears any cached adoptable container state to avoid stale adoption across actions. |
| [clearAdoptionCacheForIntent](clear-adoption-cache-for-intent.md) | [androidJvm]<br>fun [clearAdoptionCacheForIntent](clear-adoption-cache-for-intent.md)(intent: [ActionIntent](../-action-intent/index.md)) |
| [didEvent](did-event.md) | [androidJvm]<br>fun [didEvent](did-event.md)(eventMessage: EventMessage) |
| [open](open.md) | [androidJvm]<br>suspend fun [open](open.md)(actionContext: [ActionContext](../-action-context/index.md), containerDelegate: [ContainerDelegate](../-container-delegate/index.md), fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)? = null, containerProperties: [ContainerProperties](../-container-properties/index.md)?)<br>Opens a container with the target content. |
