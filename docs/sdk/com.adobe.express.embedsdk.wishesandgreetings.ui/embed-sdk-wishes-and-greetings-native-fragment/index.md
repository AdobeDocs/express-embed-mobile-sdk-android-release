//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.ui](../index.md)/[EmbedSdkWishesAndGreetingsNativeFragment](index.md)

# EmbedSdkWishesAndGreetingsNativeFragment

\
class [EmbedSdkWishesAndGreetingsNativeFragment](index.md) : [EmbedSdkWishesAndGreetingsBaseFragment](../embed-sdk-wishes-and-greetings-base-fragment/index.md)

Native fragment for the Wishes & greetings browse workflow.

## Constructors

| | |
|---|---|
| [EmbedSdkWishesAndGreetingsNativeFragment](embed-sdk-wishes-and-greetings-native-fragment.md) | <br>constructor() |

## Types

| Name | Summary |
|---|---|
| [Companion](companion/index.md) | <br>object [Companion](companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [wishesAndGreetingsNativeContext](wishes-and-greetings-native-context.md) | <br>val [wishesAndGreetingsNativeContext](wishes-and-greetings-native-context.md): WishesAndGreetingsNativeContext<br>Host-facing handle for programmatic close. A fragment recreated by the FragmentManager (rotation, restore) is built through the no-arg constructor, so the instance newInstance set is gone; it is rebuilt from the launch params retained in the ViewModel. If those are unrecoverable (process death) the fragment is already removing itself, so `close()` is a no-op instead of a crash. |
