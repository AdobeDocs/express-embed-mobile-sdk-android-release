//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[Validator](index.md)/[validateClientAuthDetails](validate-client-auth-details.md)

# validateClientAuthDetails

\
fun [validateClientAuthDetails](validate-client-auth-details.md)(clientAuthDetails: [ClientAuthDetails](../client-auth-details/index.md))

Validates client authentication details. Ensures that the clientAccessToken and userGuid are not empty, and that the userGuid follows the UUID format.

#### Parameters

androidJvm

| | |
|---|---|
| clientAuthDetails | The client authentication details to validate |

#### Throws

| | |
|---|---|
| [IllegalArgumentException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/illegal-argument-exception/index.html) | if validation fails |
