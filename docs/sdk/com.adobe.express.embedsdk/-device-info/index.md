//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[DeviceInfo](index.md)

# DeviceInfo

[androidJvm]\
data class [DeviceInfo](index.md)(val deviceName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), val totalRamMB: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html), val networkType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), val numberOfCores: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html))

Device hardware and network information for analytics and optimization.

## Constructors

| | |
|---|---|
| [DeviceInfo](-device-info.md) | [androidJvm]<br>constructor(deviceName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), totalRamMB: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html), networkType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), numberOfCores: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [deviceName](device-name.md) | [androidJvm]<br>val [deviceName](device-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)<br>Name of the device model |
| [networkType](network-type.md) | [androidJvm]<br>val [networkType](network-type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)<br>Current network connection type (WiFi, Cellular, etc.) |
| [numberOfCores](number-of-cores.md) | [androidJvm]<br>val [numberOfCores](number-of-cores.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Number of CPU cores available |
| [totalRamMB](total-ram-m-b.md) | [androidJvm]<br>val [totalRamMB](total-ram-m-b.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Total device RAM in megabytes |
