//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[BaseAuthController](index.md)/[isSignInOnRequestEnabled](is-sign-in-on-request-enabled.md)

# isSignInOnRequestEnabled

\
open fun [isSignInOnRequestEnabled](is-sign-in-on-request-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)

Whether the host declared AuthMode.IMS_JUMP_ON_REQUEST at initialize(). Guards BaseAction's SIGN_IN_REQUIRED handler so an embed can't drive sign-in the host didn't opt into. Always false for 3P — their AuthOption union has no jump-on-request mode.
