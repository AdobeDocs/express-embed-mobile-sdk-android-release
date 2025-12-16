//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ClientAuthStore](index.md)/[scheduleClientAuthRefresh](schedule-client-auth-refresh.md)

# scheduleClientAuthRefresh

[androidJvm]\
suspend fun [scheduleClientAuthRefresh](schedule-client-auth-refresh.md)()

Schedule the client auth refresh. This will fetch the client auth details and schedule the next refresh. Calls onClientAuthRefreshed callback with the new client auth details. Prevents multiple concurrent refresh operations.
