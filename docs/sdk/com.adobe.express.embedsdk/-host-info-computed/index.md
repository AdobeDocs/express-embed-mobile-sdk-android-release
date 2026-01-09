//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[HostInfoComputed](index.md)

# HostInfoComputed

open class [HostInfoComputed](index.md)(var referrer: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, var id: [HostId](../-host-id/index.md)? = null, var type: [HostType](../-host-type/index.md)? = null, var isFirstPartyHost: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)? = null, var deviceInfo: [DeviceInfo](../-device-info/index.md)? = null, var sdkVersion: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, var appId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null)

Computed host information automatically determined by the SDK.

#### Inheritors

| |
|---|
| [HostInfoExtended](../-host-info-extended/index.md) |

## Constructors

| | |
|---|---|
| [HostInfoComputed](-host-info-computed.md) | [androidJvm]<br>constructor(referrer: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, id: [HostId](../-host-id/index.md)? = null, type: [HostType](../-host-type/index.md)? = null, isFirstPartyHost: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)? = null, deviceInfo: [DeviceInfo](../-device-info/index.md)? = null, sdkVersion: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, appId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [appId](app-id.md) | [androidJvm]<br>open var [appId](app-id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>Application identifier (package name) |
| [deviceInfo](device-info.md) | [androidJvm]<br>open var [deviceInfo](device-info.md): [DeviceInfo](../-device-info/index.md)?<br>Hardware and network information for the device |
| [id](id.md) | [androidJvm]<br>open var [id](id.md): [HostId](../-host-id/index.md)?<br>Computed host identifier based on client configuration |
| [isFirstPartyHost](is-first-party-host.md) | [androidJvm]<br>open var [isFirstPartyHost](is-first-party-host.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)?<br>True if this is an Adobe first-party application |
| [referrer](referrer.md) | [androidJvm]<br>open var [referrer](referrer.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>URL or source that referred to the SDK |
| [sdkVersion](sdk-version.md) | [androidJvm]<br>open var [sdkVersion](sdk-version.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>Version of the SDK being used |
| [type](type.md) | [androidJvm]<br>open var [type](type.md): [HostType](../-host-type/index.md)?<br>Host type (first-party or third-party) |
