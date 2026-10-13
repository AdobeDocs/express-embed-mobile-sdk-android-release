//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[FilterUtils](index.md)/[withFreeLicensingFilter](with-free-licensing-filter.md)

# withFreeLicensingFilter

\
fun [withFreeLicensingFilter](with-free-licensing-filter.md)(filterQuery: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;

Returns [filterQuery](with-free-licensing-filter.md) with [FREE_LICENSING_FILTER](f-r-e-e_-l-i-c-e-n-s-i-n-g_-f-i-l-t-e-r.md) appended, unless it already constrains `licensingCategory` (ported from theo `addFreeLicensingFilterIfNotExists`).
