//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[DefaultAdoptionCompatibilityChecker](index.md)

# DefaultAdoptionCompatibilityChecker

[androidJvm]\
internal class [DefaultAdoptionCompatibilityChecker](index.md) : [AdoptionCompatibilityChecker](../-adoption-compatibility-checker/index.md)

Checks compatibility between actions for WebView adoption.

## Constructors

| | |
|---|---|
| [DefaultAdoptionCompatibilityChecker](-default-adoption-compatibility-checker.md) | [androidJvm]<br>constructor() |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [androidJvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [checkCompatibility](check-compatibility.md) | [androidJvm]<br>open override fun [checkCompatibility](check-compatibility.md)(sourceAction: [ActionIntent](../-action-intent/index.md), targetAction: [ActionIntent](../-action-intent/index.md), sourceContainer: [AdoptableContainer](../-adoptable-container/index.md)): [AdoptionCompatibilityResult](../-adoption-compatibility-result/index.md)<br>Checks if a target action can adopt a container from a source action. |
