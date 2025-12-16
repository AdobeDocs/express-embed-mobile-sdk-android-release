//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[AuthController3p](index.md)

# AuthController3p

[androidJvm]\
class [AuthController3p](index.md)(authStore: [AuthStore](../-auth-store/index.md), channelMessageListener: ChannelMessageListener, hostInfo: [HostInfoExtended](../-host-info-extended/index.md), locale: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), analyticsManager: AnalyticsManager, performanceLogger: PerformanceLogger) : [BaseAuthController](../-base-auth-controller/index.md)

Authentication controller for third-party applications.

## Constructors

| | |
|---|---|
| [AuthController3p](-auth-controller3p.md) | [androidJvm]<br>constructor(authStore: [AuthStore](../-auth-store/index.md), channelMessageListener: ChannelMessageListener, hostInfo: [HostInfoExtended](../-host-info-extended/index.md), locale: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), analyticsManager: AnalyticsManager, performanceLogger: PerformanceLogger) |

## Functions

| Name | Summary |
|---|---|
| [doesSupportSignInWorkflow](does-support-sign-in-workflow.md) | [androidJvm]<br>open override fun [doesSupportSignInWorkflow](does-support-sign-in-workflow.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether this auth controller supports dedicated sign-in workflows. |
| [getTargetUrl](get-target-url.md) | [androidJvm]<br>open suspend override fun [getTargetUrl](get-target-url.md)(targetInfo: [TargetInfo](../-target-info/index.md), skipJumpCheck: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)): [URL](https://developer.android.com/reference/kotlin/java/net/URL.html)<br>Generates the target URL for launching workflows. |
| [invoke](invoke.md) | [androidJvm]<br>open operator override fun [invoke](invoke.md)(authStore: [AuthStore](../-auth-store/index.md), channelMessageListener: ChannelMessageListener, hostInfo: [HostInfoExtended](../-host-info-extended/index.md), locale: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), analyticsManager: AnalyticsManager, performanceLogger: PerformanceLogger): [BaseAuthController](../-base-auth-controller/index.md) |
