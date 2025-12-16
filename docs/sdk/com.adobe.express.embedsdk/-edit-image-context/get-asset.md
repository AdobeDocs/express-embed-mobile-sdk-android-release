//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[EditImageContext](index.md)/[getAsset](get-asset.md)

# getAsset

[androidJvm]\
abstract suspend fun [getAsset](get-asset.md)(assetConfig: AssetConfig): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;[OutputAsset](../-output-asset/index.md)&gt;

Gets the published assets from the current editing session

#### Return

List of OutputAsset objects representing the published content,     or empty list if no assets have been published

#### Parameters

androidJvm

| | |
|---|---|
| assetConfig | Configuration for asset retrieval including showProcessingDialog flag |
