//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[AssetBase](index.md)

# AssetBase

open class [AssetBase](index.md)(typeString: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, dataTypeString: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null)

Base class for all asset types used in SDK workflows. Provides common properties and methods for asset management and serialization.

#### Inheritors

| |
|---|
| [OutputAsset](../-output-asset/index.md) |

## Constructors

| | |
|---|---|
| [AssetBase](-asset-base.md) | [androidJvm]<br>constructor(typeString: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, dataTypeString: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null, data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [dataType](data-type.md) | [androidJvm]<br>val [dataType](data-type.md): [AssetDataType](../-asset-data-type/index.md)? |
| [type](type.md) | [androidJvm]<br>val [type](type.md): [AssetType](../-asset-type/index.md)? |

## Functions

| Name | Summary |
|---|---|
| [getData](get-data.md) | [androidJvm]<br>fun [getData](get-data.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>Gets the asset data content |
| [getName](get-name.md) | [androidJvm]<br>fun [getName](get-name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)?<br>Gets the asset name identifier |
| [setData](set-data.md) | [androidJvm]<br>fun [setData](set-data.md)(data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html))<br>Sets the asset data content |
| [setDataType](set-data-type.md) | [androidJvm]<br>fun [setDataType](set-data-type.md)(dataType: [AssetDataType](../-asset-data-type/index.md))<br>Sets the asset data type format |
| [setName](set-name.md) | [androidJvm]<br>fun [setName](set-name.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html))<br>Sets the asset name identifier |
| [setType](set-type.md) | [androidJvm]<br>fun [setType](set-type.md)(type: [AssetType](../-asset-type/index.md))<br>Sets the asset type |
