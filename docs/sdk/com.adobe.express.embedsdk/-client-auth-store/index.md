//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ClientAuthStore](index.md)

# ClientAuthStore

[androidJvm]\
class [ClientAuthStore](index.md)(clientAuthProvider: [ClientAuthProvider](../-client-auth-provider/index.md), clientAuthDetailsValidatorFn: ([ClientAuthDetails](../-client-auth-details/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-unit/index.html))

Store for managing client authentication details with proactive refresh scheduling.

## Constructors

| | |
|---|---|
| [ClientAuthStore](-client-auth-store.md) | [androidJvm]<br>constructor(clientAuthProvider: [ClientAuthProvider](../-client-auth-provider/index.md), clientAuthDetailsValidatorFn: ([ClientAuthDetails](../-client-auth-details/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-unit/index.html)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [getClientAuthDetails](get-client-auth-details.md) | [androidJvm]<br>suspend fun [getClientAuthDetails](get-client-auth-details.md)(): [ClientAuthDetails](../-client-auth-details/index.md)?<br>Get the client auth details. If the client auth details are not available, it will fetch them. |
| [isRefreshInProgress](is-refresh-in-progress.md) | [androidJvm]<br>fun [isRefreshInProgress](is-refresh-in-progress.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Check if a refresh operation is currently in progress. |
| [isRefreshScheduled](is-refresh-scheduled.md) | [androidJvm]<br>fun [isRefreshScheduled](is-refresh-scheduled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Check if a client auth refresh is scheduled to happen. |
| [scheduleClientAuthRefresh](schedule-client-auth-refresh.md) | [androidJvm]<br>suspend fun [scheduleClientAuthRefresh](schedule-client-auth-refresh.md)()<br>Schedule the client auth refresh. This will fetch the client auth details and schedule the next refresh. Calls onClientAuthRefreshed callback with the new client auth details. Prevents multiple concurrent refresh operations. |
| [setOnClientAuthRefreshed](set-on-client-auth-refreshed.md) | [androidJvm]<br>fun [setOnClientAuthRefreshed](set-on-client-auth-refreshed.md)(onClientAuthRefreshed: ([ClientAuthDetails](../-client-auth-details/index.md)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-unit/index.html))<br>Set the callback to be called when the client auth is refreshed. |
| [setOnClientAuthRefreshFailed](set-on-client-auth-refresh-failed.md) | [androidJvm]<br>fun [setOnClientAuthRefreshFailed](set-on-client-auth-refresh-failed.md)(onClientAuthRefreshFailed: ([Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-throwable/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-unit/index.html))<br>Set the callback to be called when the client auth refresh fails. |
| [stopClientAuthRefresh](stop-client-auth-refresh.md) | [androidJvm]<br>fun [stopClientAuthRefresh](stop-client-auth-refresh.md)()<br>Stop the client auth refresh. This will clear the refresh timer and stop the client auth refresh. |
