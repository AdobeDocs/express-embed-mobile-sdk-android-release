//[sdk](../../../index.md)/[com.adobe.express.embedsdk.nativeeditor.domain.model](../index.md)/[NativeMobileToolbarOption](index.md)

# NativeMobileToolbarOption

\
data class [NativeMobileToolbarOption](index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), val icon: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html), val badge: [NativeMobileToolbarOptionBadgeConfig](../native-mobile-toolbar-option-badge-config/index.md)? = null)

Host-provided toolbar entry for native workflows.

## Constructors

| | |
|---|---|
| [NativeMobileToolbarOption](native-mobile-toolbar-option.md) | <br>constructor(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html), icon: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html), badge: [NativeMobileToolbarOptionBadgeConfig](../native-mobile-toolbar-option-badge-config/index.md)? = null) |

## Properties

| Name | Summary |
|---|---|
| [badge](badge.md) | <br>val [badge](badge.md): [NativeMobileToolbarOptionBadgeConfig](../native-mobile-toolbar-option-badge-config/index.md)? = null |
| [icon](icon.md) | <br>val [icon](icon.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/int/index.html)<br>Vector drawable resource ID rendered as the entry icon. |
| [id](id.md) | <br>val [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>Stable identifier emitted back to the host when the entry is tapped. |
| [label](label.md) | <br>val [label](label.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/string/index.html)<br>Display label. |
