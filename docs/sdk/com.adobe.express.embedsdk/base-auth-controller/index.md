//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[BaseAuthController](index.md)

# BaseAuthController

abstract class [BaseAuthController](index.md)(authStore: [AuthStore](../auth-store/index.md), locale: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), var analyticsManager: AnalyticsManager, var performanceLogger: PerformanceLogger) : [Function6](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/function6/index.html)&lt;authStore: [AuthStore](../auth-store/index.md), channelMessageListener: ChannelMessageListener, hostInfo: [HostInfoExtended](../host-info-extended/index.md), locale: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), analyticsManager: AnalyticsManager, performanceLogger: PerformanceLogger, [BaseAuthController](index.md)&gt; 

Base abstract class for authentication controllers. Defines the common interface and functionality for managing authentication across both first-party and third-party integrations.

#### Inheritors

| |
|---|
| [AuthController3p](../auth-controller3p/index.md) |

## Constructors

| | |
|---|---|
| [BaseAuthController](base-auth-controller.md) | <br>constructor(authStore: [AuthStore](../auth-store/index.md), locale: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), analyticsManager: AnalyticsManager, performanceLogger: PerformanceLogger) |

## Properties

| Name | Summary |
|---|---|
| [analyticsManager](analytics-manager.md) | <br>var [analyticsManager](analytics-manager.md): AnalyticsManager |
| [performanceLogger](performance-logger.md) | <br>var [performanceLogger](performance-logger.md): PerformanceLogger |

## Functions

| Name | Summary |
|---|---|
| [doesSupportSignInWorkflow](does-support-sign-in-workflow.md) | <br>abstract fun [doesSupportSignInWorkflow](does-support-sign-in-workflow.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)<br>Indicates whether this auth controller supports dedicated sign-in workflows. |
| [getTargetUrl](get-target-url.md) | <br>abstract suspend fun [getTargetUrl](get-target-url.md)(targetInfo: [TargetInfo](../target-info/index.md), skipJumpCheck: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)): [URL](https://developer.android.com/reference/kotlin/java/net/URL.html)<br>Generates the target URL for launching workflows. |
| [refreshAuthOption](refresh-auth-option.md) | <br>fun [refreshAuthOption](refresh-auth-option.md)()<br>Refreshes authentication options by invoking the auth provider. Updates the auth store with the latest authentication configuration. |
| [setAuthProvider](set-auth-provider.md) | <br>fun [setAuthProvider](set-auth-provider.md)(authProvider: [AuthProvider](../auth-provider/index.md))<br>Sets the authentication provider for this controller. The provider supplies [AuthOption](../auth-option/index.md) when authentication is needed. |
| [shouldSkipJump](should-skip-jump.md) | <br>open fun [shouldSkipJump](should-skip-jump.md)(skipJumpCheck: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
