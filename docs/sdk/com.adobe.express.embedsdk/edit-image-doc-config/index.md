//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[EditImageDocConfig](index.md)

# EditImageDocConfig

\
open class [EditImageDocConfig](index.md)(val asset: [Asset](../asset/index.md)? = null, val intent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null) : [BaseDocConfig](../base-doc-config/index.md)

Document configuration for image editing workflows. Specifies the input asset and editing intent for the workflow.

## Constructors

| | |
|---|---|
| [EditImageDocConfig](edit-image-doc-config.md) | <br>constructor(asset: [Asset](../asset/index.md)? = null, intent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null) |

## Properties

| Name | Summary |
|---|---|
| [asset](asset.md) | <br>val [asset](asset.md): [Asset](../asset/index.md)? = null<br>Input asset to be edited (image, video, etc.) |
| [intent](intent.md) | <br>val [intent](intent.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null<br>intent that needs to be performed on the asset |
