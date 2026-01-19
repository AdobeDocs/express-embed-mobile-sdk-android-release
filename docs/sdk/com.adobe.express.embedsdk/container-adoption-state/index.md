//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ContainerAdoptionState](index.md)

# ContainerAdoptionState

\
enum [ContainerAdoptionState](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/enum/index.html)&lt;[ContainerAdoptionState](index.md)&gt; 

Represents the current state of a container in the adoption lifecycle.

## Entries

| | |
|---|---|
| [CREATED](c-r-e-a-t-e-d/index.md) | <br>[CREATED](c-r-e-a-t-e-d/index.md)<br>Container just created. |
| [LOADING](l-o-a-d-i-n-g/index.md) | <br>[LOADING](l-o-a-d-i-n-g/index.md)<br>Loading content. |
| [LOADED](l-o-a-d-e-d/index.md) | <br>[LOADED](l-o-a-d-e-d/index.md)<br>Content loaded successfully. |
| [VISIBLE](v-i-s-i-b-l-e/index.md) | <br>[VISIBLE](v-i-s-i-b-l-e/index.md)<br>Container visible to user. |
| [HIDDEN](h-i-d-d-e-n/index.md) | <br>[HIDDEN](h-i-d-d-e-n/index.md)<br>Container hidden but alive. |
| [ADOPTABLE](a-d-o-p-t-a-b-l-e/index.md) | <br>[ADOPTABLE](a-d-o-p-t-a-b-l-e/index.md)<br>Container can be adopted. |
| [ADOPTED](a-d-o-p-t-e-d/index.md) | <br>[ADOPTED](a-d-o-p-t-e-d/index.md)<br>Container has been adopted. |
| [DESTROYED](d-e-s-t-r-o-y-e-d/index.md) | <br>[DESTROYED](d-e-s-t-r-o-y-e-d/index.md)<br>Container destroyed. |

## Properties

| Name | Summary |
|---|---|
| [entries](entries.md) | <br>val [entries](entries.md): [EnumEntries](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.enums/enum-entries/index.html)&lt;[ContainerAdoptionState](index.md)&gt;<br>Returns a representation of an immutable list of all enum entries, in the order they're declared. |

## Functions

| Name | Summary |
|---|---|
| [valueOf](value-of.md) | <br>fun [valueOf](value-of.md)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)): [ContainerAdoptionState](index.md)<br>Returns the enum constant of this type with the specified name. The string must match exactly an identifier used to declare an enum constant in this type. (Extraneous whitespace characters are not permitted.) |
| [values](values.md) | <br>fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/array/index.html)&lt;[ContainerAdoptionState](index.md)&gt;<br>Returns an array containing the constants of this enum type, in the order they're declared. |
