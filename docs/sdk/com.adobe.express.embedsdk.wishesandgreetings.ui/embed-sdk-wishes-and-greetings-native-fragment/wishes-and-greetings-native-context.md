//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.ui](../index.md)/[EmbedSdkWishesAndGreetingsNativeFragment](index.md)/[wishesAndGreetingsNativeContext](wishes-and-greetings-native-context.md)

# wishesAndGreetingsNativeContext

\
val [wishesAndGreetingsNativeContext](wishes-and-greetings-native-context.md): WishesAndGreetingsNativeContext

Host-facing handle for programmatic close. A fragment recreated by the FragmentManager (rotation, restore) is built through the no-arg constructor, so the instance newInstance set is gone; it is rebuilt from the launch params retained in the ViewModel. If those are unrecoverable (process death) the fragment is already removing itself, so `close()` is a no-op instead of a crash.
