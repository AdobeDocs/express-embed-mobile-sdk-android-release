//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[PreSignedInAuthOption](index.md)

# PreSignedInAuthOption

[androidJvm]\
interface [PreSignedInAuthOption](index.md) : [BaseAuthOption](../-base-auth-option/index.md)

Authentication option for users already signed in to the host application.

## Properties

| Name | Summary |
|---|---|
| [config](config.md) | [androidJvm]<br>abstract val [config](config.md): [PreSignedInAuthConfig](../-pre-signed-in-auth-config/index.md)?<br>Pre-signed-in authentication configuration |
| [mode](mode.md) | [androidJvm]<br>open override val [mode](mode.md): [AuthMode](../-auth-mode/index.md)<br>The authentication mode for this option |
