//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[IMSAuthConfig](index.md)

# IMSAuthConfig

\
class [IMSAuthConfig](index.md)(val piipStatus: [PIIPStatus](../p-i-i-p-status/index.md)?, val accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?, val userId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?) : [PreSignedInAuthConfig](../pre-signed-in-auth-config/index.md)

IMS authentication configuration for authenticated users. IMS userId corresponding to the provided accessToken.

## Constructors

| | |
|---|---|
| [IMSAuthConfig](i-m-s-auth-config.md) | <br>constructor(piipStatus: [PIIPStatus](../p-i-i-p-status/index.md)?, accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?, userId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?) |

## Properties

| Name | Summary |
|---|---|
| [accessToken](access-token.md) | <br>val [accessToken](access-token.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>IMS access token for authenticated user |
| [forceJumpCheck](force-jump-check.md) | <br>val [forceJumpCheck](force-jump-check.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)? = false<br>Valid for desktop clients. If sign in should be always done through jump, pass true. The default behavior is that once SSO is done through jump, the next sign in doesn't use jump url and assumes the cookies are present and still valid. |
| [piipStatus](piip-status.md) | <br>open override val [piipStatus](piip-status.md): [PIIPStatus](../p-i-i-p-status/index.md)?<br>Analytics opt-in/opt-out status |
| [userId](user-id.md) | <br>open override val [userId](user-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?<br>IMS user identifier |
