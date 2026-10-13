//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[Blob](index.md)

# Blob

\
interface [Blob](index.md)

Custom interface that represents a Blob object for binary data handling. Should be used instead of the default Blob type for asset data operations.

## Properties

| Name | Summary |
|---|---|
| [size](size.md) | <br>abstract val [size](size.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html) |
| [type](type.md) | <br>abstract val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |

## Functions

| Name | Summary |
|---|---|
| [arrayBuffer](array-buffer.md) | <br>abstract fun [arrayBuffer](array-buffer.md)(): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/byte-array/index.html)&gt;<br>Reads the blob data as a byte array. |
| [slice](slice.md) | <br>abstract fun [slice](slice.md)(start: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)? = null, end: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)? = null, contentType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)? = null): [Blob](index.md)<br>Creates a new Blob containing a subset of this blob's data. |
| [stream](stream.md) | <br>abstract fun [stream](stream.md)(): [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)<br>Returns an InputStream for reading the blob data. |
| [text](text.md) | <br>abstract fun [text](text.md)(): [CompletableFuture](https://developer.android.com/reference/kotlin/java/util/concurrent/CompletableFuture.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;<br>Reads the blob data as a text string. |
