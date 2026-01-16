//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ClientAuthDetails](index.md)

# ClientAuthDetails

\
data class [ClientAuthDetails](index.md)(val clientAccessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val tokenExpiryTimestampMs: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/long/index.html), val userGuid: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html))

Data class representing the client authentication details. This includes the client token, its expiry time, and optional client identifier.

## Constructors

| | |
|---|---|
| [ClientAuthDetails](client-auth-details.md) | <br>constructor(clientAccessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), tokenExpiryTimestampMs: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/long/index.html), userGuid: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [clientAccessToken](client-access-token.md) | <br>val [clientAccessToken](client-access-token.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>The client access token. |
| [tokenExpiryTimestampMs](token-expiry-timestamp-ms.md) | <br>val [tokenExpiryTimestampMs](token-expiry-timestamp-ms.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/long/index.html)<br>The expiration timestamp (in milliseconds since epoch) for the client access token. This is used to determine when the token needs to be refreshed. |
| [userGuid](user-guid.md) | <br>val [userGuid](user-guid.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>Unique identifier (UUID) for the logged-in user. Useful for rate limiting. The UUID must follow the pattern described here: https://developer.mozilla.org/en-US/docs/Glossary/UUID. Example: '75df9e44-98a5-43a9-b2ff-d884d3af12cc'. It's a 36-character, hyphenated, case-insensitive hexadecimal string. |
