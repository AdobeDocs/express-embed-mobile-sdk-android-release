//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ActionManager](index.md)/[launch](launch.md)

# launch

[androidJvm]\
suspend fun [launch](launch.md)(actionIntent: [ActionIntent](../-action-intent/index.md), designConfig: [DesignConfig](../-design-config/index.md), fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)? = null)

Launches the specified action workflow with the provided configuration. Handles session reuse, timeout management, and action lifecycle.

#### Parameters

androidJvm

| | |
|---|---|
| actionIntent | The action intent specifying which workflow to launch |
| designConfig | Configuration for the design interface and callbacks |
| fragmentOrContext | Android Fragment or Context where the action UI will be displayed |
