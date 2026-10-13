//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ImageWorkflowContext](index.md)/[getAsset](get-asset.md)

# getAsset

\
abstract suspend fun [getAsset](get-asset.md)(assetConfig: AssetConfig): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;OutputAsset&gt;

Gets the published assets from the current session.

For the Edit Image workflow, when the input image was supplied as a URL asset, the original image's EXIF metadata (orientation, capture date, camera make/model/settings, and GPS location) is re-embedded into each exported base64 asset, since the web editor strips EXIF on export. GPS location is only retained when the host app declares and holds `ACCESS_MEDIA_LOCATION` (Android 10+); otherwise all non-location EXIF is still preserved. EXIF is not re-embedded for base64 inputs or for other image workflows.

#### Return

List of OutputAsset objects representing the published content,     or empty list if no assets have been published

#### Parameters

androidJvm

| | |
|---|---|
| assetConfig | Configuration for asset retrieval including showProcessingDialog flag and processingDialogTitle |
