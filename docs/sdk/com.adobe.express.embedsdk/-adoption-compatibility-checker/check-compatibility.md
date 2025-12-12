//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[AdoptionCompatibilityChecker](index.md)/[checkCompatibility](check-compatibility.md)

# checkCompatibility

[androidJvm]\
abstract fun [checkCompatibility](check-compatibility.md)(sourceAction: [ActionIntent](../-action-intent/index.md), targetAction: [ActionIntent](../-action-intent/index.md), sourceContainer: [AdoptableContainer](../-adoptable-container/index.md)): [AdoptionCompatibilityResult](../-adoption-compatibility-result/index.md)

Checks if a target action can adopt a container from a source action.

#### Return

AdoptionCompatibilityResult indicating compatibility and strategy

#### Parameters

androidJvm

| | |
|---|---|
| sourceAction | -     The action that currently owns the container |
| targetAction | -     The action that wants to adopt the container |
| sourceContainer | -     The container that currently owns the container |
