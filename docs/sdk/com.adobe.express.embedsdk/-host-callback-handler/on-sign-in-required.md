//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[HostCallbackHandler](index.md)/[onSignInRequired](on-sign-in-required.md)

# onSignInRequired

\
fun [onSignInRequired](on-sign-in-required.md)(reason: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?, complete: (credentials: SignInCredentials?) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/unit/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)

Dispatches a mid-session sign-in request to the host. Returns true if a handler was wired and invoked, false if the host never registered [onSignInRequired](on-sign-in-required.md) — the caller resets its in-flight state on false so a missing callback can't permanently wedge the action.
