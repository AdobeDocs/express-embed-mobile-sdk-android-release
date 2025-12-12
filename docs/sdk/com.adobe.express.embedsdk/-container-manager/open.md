//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ContainerManager](index.md)/[open](open.md)

# open

[androidJvm]\
suspend fun [open](open.md)(actionContext: [ActionContext](../-action-context/index.md), containerDelegate: [ContainerDelegate](../-container-delegate/index.md), fragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)? = null, containerProperties: [ContainerProperties](../-container-properties/index.md)?)

Opens a container with the target content.

This method implements an optimized loading strategy:

- 
   For scenarios where URL fetching might be slow (authentication/jump flows), it shows a loading webview immediately and fetches the URL in the background
- 
   For scenarios where URL fetching is fast (skipJump=true, WARMUP (keepTargetHidden=true)), it uses the standard flow to avoid unnecessary complexity
