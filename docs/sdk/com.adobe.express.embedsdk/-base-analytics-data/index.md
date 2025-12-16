//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[BaseAnalyticsData](index.md)

# BaseAnalyticsData

[androidJvm]\
data class [BaseAnalyticsData](index.md)(val hostAppTrigger: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, val hostAnalyticsTestIds: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;? = null, val clientEntitlement: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null)

## Constructors

| | |
|---|---|
| [BaseAnalyticsData](-base-analytics-data.md) | [androidJvm]<br>constructor(hostAppTrigger: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, hostAnalyticsTestIds: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;? = null, clientEntitlement: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [clientEntitlement](client-entitlement.md) | [androidJvm]<br>val [clientEntitlement](client-entitlement.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null<br>Property to pass client's information to the host app. |
| [hostAnalyticsTestIds](host-analytics-test-ids.md) | [androidJvm]<br>val [hostAnalyticsTestIds](host-analytics-test-ids.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;? = null |
| [hostAppTrigger](host-app-trigger.md) | [androidJvm]<br>val [hostAppTrigger](host-app-trigger.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null<br>The action within the host app that triggered the module. |
