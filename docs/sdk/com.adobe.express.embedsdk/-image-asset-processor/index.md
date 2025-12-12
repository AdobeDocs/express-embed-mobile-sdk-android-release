//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ImageAssetProcessor](index.md)

# ImageAssetProcessor

[androidJvm]\
internal class [ImageAssetProcessor](index.md)

## Constructors

| | |
|---|---|
| [ImageAssetProcessor](-image-asset-processor.md) | [androidJvm]<br>constructor() |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |
| [RenditionDetails](-rendition-details/index.md) | [androidJvm]<br>data class [RenditionDetails](-rendition-details/index.md)(val imageDimensions: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-pair/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)&gt;, val imageData: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte-array/index.html), val mimeType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), val dataUrl: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [getRenditionDimensionsPromise](get-rendition-dimensions-promise.md) | [androidJvm]<br>fun [getRenditionDimensionsPromise](get-rendition-dimensions-promise.md)(asset: [Asset](../-asset/index.md)): CompletableDeferred&lt;[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-pair/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)&gt;&gt;? |
| [getRenditionResultPromise](get-rendition-result-promise.md) | [androidJvm]<br>fun [getRenditionResultPromise](get-rendition-result-promise.md)(asset: [Asset](../-asset/index.md)): CompletableDeferred&lt;[ImageAssetProcessor.RenditionDetails](-rendition-details/index.md)&gt;? |
| [processAssetForRendition](process-asset-for-rendition.md) | [androidJvm]<br>fun [processAssetForRendition](process-asset-for-rendition.md)(inputAsset: [Asset](../-asset/index.md), context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) |
| [removeAsset](remove-asset.md) | [androidJvm]<br>fun [removeAsset](remove-asset.md)(asset: [AssetBase](../-asset-base/index.md)) |
| [tryGetDeferredResult](try-get-deferred-result.md) | [androidJvm]<br>fun &lt;[T](try-get-deferred-result.md)&gt; [tryGetDeferredResult](try-get-deferred-result.md)(deferred: Deferred&lt;[T](try-get-deferred-result.md)&gt;?): [T](try-get-deferred-result.md)? |
