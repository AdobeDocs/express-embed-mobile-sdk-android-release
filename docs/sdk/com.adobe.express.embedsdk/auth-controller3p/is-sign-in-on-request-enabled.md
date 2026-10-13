//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[AuthController3p](index.md)/[isSignInOnRequestEnabled](is-sign-in-on-request-enabled.md)

# isSignInOnRequestEnabled

\
open override fun [isSignInOnRequestEnabled](is-sign-in-on-request-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)

Always false for 3P: the third-party auth option surface has no jump modes, so a 3P host can't declare AuthMode.IMS_JUMP_ON_REQUEST and SIGN_IN_REQUIRED is a no-op there.
