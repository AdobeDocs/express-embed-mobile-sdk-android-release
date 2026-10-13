//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ClientAuthProvider](index.md)

# ClientAuthProvider

\
fun interface [ClientAuthProvider](index.md)

Functional interface representing a provider that supplies client authentication details. This function should be implemented by partners to fetch client authentication details.

#### Return

ClientAuthDetails The client authentication details

## Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | <br>abstract suspend operator fun [invoke](invoke.md)(): [ClientAuthDetails](../client-auth-details/index.md) |
