//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.domain.model](../index.md)/[SearchTerms](index.md)

# SearchTerms

\
class [SearchTerms](index.md)(var displayed: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, var filterQuery: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? = null)

A single free-text + filter query for the ACP search/browse paths.

## Constructors

| | |
|---|---|
| [SearchTerms](search-terms.md) | <br>constructor(displayed: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) = &quot;&quot;, filterQuery: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? = null) |

## Properties

| Name | Summary |
|---|---|
| [displayed](displayed.md) | <br>var [displayed](displayed.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html) |
| [filterQuery](filter-query.md) | <br>var [filterQuery](filter-query.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)&gt;? |

## Functions

| Name | Summary |
|---|---|
| [copy](copy.md) | <br>fun [copy](copy.md)(): [SearchTerms](index.md) |
| [equals](equals.md) | <br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
| [hashCode](hash-code.md) | <br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html) |
| [isNotDefaultFiltersOnly](is-not-default-filters-only.md) | <br>fun [isNotDefaultFiltersOnly](is-not-default-filters-only.md)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)<br>True when this search carries something beyond the default region filter — i.e. |
| [isNotEmpty](is-not-empty.md) | <br>fun [isNotEmpty](is-not-empty.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html) |
