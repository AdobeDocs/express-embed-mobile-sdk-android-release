//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[IMSAuthConfig](index.md)/[forceJumpCheck](force-jump-check.md)

# forceJumpCheck

[androidJvm]\
val [forceJumpCheck](force-jump-check.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)? = false

Valid for desktop clients. If sign in should be always done through jump, pass true. The default behavior is that once SSO is done through jump, the next sign in doesn't use jump url and assumes the cookies are present and still valid.
