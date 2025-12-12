//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[WebViewEngine](index.md)/[updateFragmentContext](update-fragment-context.md)

# updateFragmentContext

[androidJvm]\
open override fun [updateFragmentContext](update-fragment-context.md)(newFragmentOrContext: [FragmentOrContext](../-fragment-or-context/index.md)?)

Updates the fragment context for this WebViewEngine instance (for container adoption workflow).

The stored _fragmentOrContext is later used by:

1. 
   removeWebviewAndCloseFragment(): when(_fragmentOrContext) block determines     the appropriate FragmentManager for removing Container fragments based on wrapper type
2. 
   handleOnBackPress(): when(_fragmentOrContext) block extracts orientation     from context to conditionally close actions in landscape mode
3. 
   addLoaderWebView(): _fragmentOrContext?.let block ensures WebViews     are created with the correct context for proper lifecycle management

#### Parameters

androidJvm

| | |
|---|---|
| newFragmentOrContext | The new fragment or context to associate with this WebEngine |
