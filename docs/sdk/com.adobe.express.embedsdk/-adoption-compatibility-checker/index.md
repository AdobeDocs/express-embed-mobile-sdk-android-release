//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[AdoptionCompatibilityChecker](index.md)

# AdoptionCompatibilityChecker

internal interface [AdoptionCompatibilityChecker](index.md)

Interface for checking compatibility between actions for container adoption.

#### Inheritors

| |
|---|
| [DefaultAdoptionCompatibilityChecker](../-default-adoption-compatibility-checker/index.md) |

## Functions

| Name | Summary |
|---|---|
| [checkCompatibility](check-compatibility.md) | [androidJvm]<br>abstract fun [checkCompatibility](check-compatibility.md)(sourceAction: [ActionIntent](../-action-intent/index.md), targetAction: [ActionIntent](../-action-intent/index.md), sourceContainer: [AdoptableContainer](../-adoptable-container/index.md)): [AdoptionCompatibilityResult](../-adoption-compatibility-result/index.md)<br>Checks if a target action can adopt a container from a source action. |
