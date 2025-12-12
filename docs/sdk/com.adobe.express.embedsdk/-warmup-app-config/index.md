//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WarmupAppConfig](index.md)

# WarmupAppConfig

[androidJvm]\
internal class [WarmupAppConfig](index.md)(val warmupIntent: [ActionIntent](../-action-intent/index.md), val callbacks: [Callbacks](../-callbacks/index.md)?, var analyticsData: [BaseAnalyticsData](../-base-analytics-data/index.md)? = null, val enablePreloadOptimization: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) = false, val moduleWarmupConfig: ModuleWarmupConfig? = null) : [BaseAppConfig](../-base-app-config/index.md)

## Constructors

| | |
|---|---|
| [WarmupAppConfig](-warmup-app-config.md) | [androidJvm]<br>constructor(warmupIntent: [ActionIntent](../-action-intent/index.md), callbacks: [Callbacks](../-callbacks/index.md)?, analyticsData: [BaseAnalyticsData](../-base-analytics-data/index.md)? = null, enablePreloadOptimization: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) = false, moduleWarmupConfig: ModuleWarmupConfig? = null) |

## Properties

| Name | Summary |
|---|---|
| [analyticsData](analytics-data.md) | [androidJvm]<br>open override var [analyticsData](analytics-data.md): [BaseAnalyticsData](../-base-analytics-data/index.md)?<br>Analytics data that can be provided by the host application for tracking and measurement purposes. |
| [callbacks](callbacks.md) | [androidJvm]<br>open override val [callbacks](callbacks.md): [Callbacks](../-callbacks/index.md)?<br>Callback functions for workflow lifecycle events |
| [enablePreloadOptimization](enable-preload-optimization.md) | [androidJvm]<br>val [enablePreloadOptimization](enable-preload-optimization.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) = false<br>Enable preload mechanism for container reuse optimization. When true: loads target URL with preload=true parameter. When false: loads traditional warmup/preload routes. |
| [moduleWarmupConfig](module-warmup-config.md) | [androidJvm]<br>val [moduleWarmupConfig](module-warmup-config.md): ModuleWarmupConfig? = null |
| [warmupIntent](warmup-intent.md) | [androidJvm]<br>val [warmupIntent](warmup-intent.md): [ActionIntent](../-action-intent/index.md)<br>The intent to warmup the target. |
