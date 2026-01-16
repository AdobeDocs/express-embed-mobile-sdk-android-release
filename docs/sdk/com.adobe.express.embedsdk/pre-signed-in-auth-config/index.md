//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[PreSignedInAuthConfig](index.md)

# PreSignedInAuthConfig

interface [PreSignedInAuthConfig](index.md)

Authentication configuration for pre-signed-in users.

#### Inheritors

| |
|---|
| [IMSAuthConfig](../i-m-s-auth-config/index.md) |

## Properties

| Name | Summary |
|---|---|
| [piipStatus](piip-status.md) | <br>abstract val [piipStatus](piip-status.md): [PIIPStatus](../p-i-i-p-status/index.md)?<br>Represents whether analytics are sent. By default analytics are sent. |
| [userId](user-id.md) | <br>abstract val [userId](user-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>IMS userId Needed to avoid check token failure in scenarios with multiple profiles, enabling IMS to identify which profile is already signed in |
