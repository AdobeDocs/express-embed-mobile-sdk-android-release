//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[ModuleWorkflowInterface](index.md)/[wishesAndGreetingsNative](wishes-and-greetings-native.md)

# wishesAndGreetingsNative

\
abstract fun [wishesAndGreetingsNative](wishes-and-greetings-native.md)(wishesAndGreetingsNativeDocConfig: WishesAndGreetingsNativeDocConfig = WishesAndGreetingsNativeDocConfig(), wishesAndGreetingsNativeAppConfig: WishesAndGreetingsNativeAppConfig, exportConfig: ExportConfig? = null, containerConfig: ContainerConfig? = null): [EmbedSdkWishesAndGreetingsNativeFragment](../../com.adobe.express.embedsdk.wishesandgreetings.ui/embed-sdk-wishes-and-greetings-native-fragment/index.md)

Launches the native Wishes & greetings browse workflow. Available to **both 1P and 3P** clients.

#### Parameters

androidJvm

| | |
|---|---|
| wishesAndGreetingsNativeDocConfig | Optional launch configuration (e.g. a preselected category). |
| wishesAndGreetingsNativeAppConfig | Callbacks, dismiss handler and app-level settings for the whole workflow |
| exportConfig | Optional export options for the editor. |
| containerConfig | Optional SDK container options for the editor. Leave null so the editor mounts over the browse surface (`android.R.id.content`) and the browse surface is restored on close. |
