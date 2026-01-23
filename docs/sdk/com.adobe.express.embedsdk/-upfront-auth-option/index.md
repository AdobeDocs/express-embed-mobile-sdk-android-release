//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[UpfrontAuthOption](index.md)

# UpfrontAuthOption

\
interface [UpfrontAuthOption](index.md) : [BaseAuthOption](../base-auth-option/index.md)

Authentication option requiring user to sign in before accessing features.

## Properties

| Name | Summary |
|---|---|
| [config](config.md) | <br>abstract val [config](config.md): [AuthConfig](../auth-config/index.md)?<br>Optional authentication configuration |
| [mode](mode.md) | <br>open override val [mode](mode.md): [AuthMode](../auth-mode/index.md)<br>The authentication mode for this option |
