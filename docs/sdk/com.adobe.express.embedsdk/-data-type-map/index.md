//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[DataTypeMap](index.md)

# DataTypeMap

\
data class [DataTypeMap](index.md)(val blob: [Blob](../blob/index.md), val url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val base64: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html))

Represents different data representations available for an asset. Provides multiple formats for the same asset data.

## Constructors

| | |
|---|---|
| [DataTypeMap](data-type-map.md) | <br>constructor(blob: [Blob](../blob/index.md), url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), base64: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [base64](base64.md) | <br>val [base64](base64.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>Base64 encoded string representation of the asset |
| [blob](blob.md) | <br>val [blob](blob.md): [Blob](../blob/index.md)<br>Binary blob representation of the asset |
| [url](url.md) | <br>val [url](url.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>URL pointing to the asset resource |
