//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[FilterUtils](index.md)

# FilterUtils

\
object [FilterUtils](index.md)

ACP filter field names + region defaults for the Wishes & greetings browse path.

## Properties

| Name | Summary |
|---|---|
| [FILTER_FIELD_APPLICABLE_REGIONS](f-i-l-t-e-r_-f-i-e-l-d_-a-p-p-l-i-c-a-b-l-e_-r-e-g-i-o-n-s.md) | <br>const val [FILTER_FIELD_APPLICABLE_REGIONS](f-i-l-t-e-r_-f-i-e-l-d_-a-p-p-l-i-c-a-b-l-e_-r-e-g-i-o-n-s.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [FILTER_FIELD_LICENSING_CATEGORY](f-i-l-t-e-r_-f-i-e-l-d_-l-i-c-e-n-s-i-n-g_-c-a-t-e-g-o-r-y.md) | <br>const val [FILTER_FIELD_LICENSING_CATEGORY](f-i-l-t-e-r_-f-i-e-l-d_-l-i-c-e-n-s-i-n-g_-c-a-t-e-g-o-r-y.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [FREE_LICENSING_FILTER](f-r-e-e_-l-i-c-e-n-s-i-n-g_-f-i-l-t-e-r.md) | <br>const val [FREE_LICENSING_FILTER](f-r-e-e_-l-i-c-e-n-s-i-n-g_-f-i-l-t-e-r.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [REGION_CODES](r-e-g-i-o-n_-c-o-d-e-s.md) | <br>val [REGION_CODES](r-e-g-i-o-n_-c-o-d-e-s.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;<br>Region codes the content service recognizes for the `applicableRegions` filter. |

## Functions

| Name | Summary |
|---|---|
| [getDefaultRegions](get-default-regions.md) | <br>fun [getDefaultRegions](get-default-regions.md)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/set/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;<br>Default region set for the device (or [countryCode](get-default-regions.md) when provided): the device/override region if recognized, plus the &quot;ZZ&quot; (global) region. |
| [withFreeLicensingFilter](with-free-licensing-filter.md) | <br>fun [withFreeLicensingFilter](with-free-licensing-filter.md)(filterQuery: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;<br>Returns [filterQuery](with-free-licensing-filter.md) with [FREE_LICENSING_FILTER](f-r-e-e_-l-i-c-e-n-s-i-n-g_-f-i-l-t-e-r.md) appended, unless it already constrains `licensingCategory` (ported from theo `addFreeLicensingFilterIfNotExists`). |
