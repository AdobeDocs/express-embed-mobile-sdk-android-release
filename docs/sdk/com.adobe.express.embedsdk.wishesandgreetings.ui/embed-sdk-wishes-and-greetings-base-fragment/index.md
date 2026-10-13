//[sdk](../../../index.md)/[com.adobe.express.embedsdk.wishesandgreetings.ui](../index.md)/[EmbedSdkWishesAndGreetingsBaseFragment](index.md)

# EmbedSdkWishesAndGreetingsBaseFragment

open class [EmbedSdkWishesAndGreetingsBaseFragment](index.md) : [Fragment](https://developer.android.com/reference/kotlin/androidx/fragment/app/Fragment.html)

Base fragment for the native Wishes & greetings browse surface.

#### Inheritors

| |
|---|
| [EmbedSdkWishesAndGreetingsNativeFragment](../embed-sdk-wishes-and-greetings-native-fragment/index.md) |

## Constructors

| | |
|---|---|
| [EmbedSdkWishesAndGreetingsBaseFragment](embed-sdk-wishes-and-greetings-base-fragment.md) | <br>constructor() |

## Types

| Name | Summary |
|---|---|
| [Companion](companion/index.md) | <br>object [Companion](companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [onCreate](on-create.md) | <br>open override fun [onCreate](on-create.md)(savedInstanceState: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?) |
| [onCreateView](on-create-view.md) | <br>open override fun [onCreateView](on-create-view.md)(inflater: [LayoutInflater](https://developer.android.com/reference/kotlin/android/view/LayoutInflater.html), container: [ViewGroup](https://developer.android.com/reference/kotlin/android/view/ViewGroup.html)?, savedInstanceState: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?): [View](https://developer.android.com/reference/kotlin/android/view/View.html) |
| [onDestroy](on-destroy.md) | <br>open override fun [onDestroy](on-destroy.md)() |
| [onDestroyView](on-destroy-view.md) | <br>open override fun [onDestroyView](on-destroy-view.md)() |
| [onHiddenChanged](on-hidden-changed.md) | <br>open override fun [onHiddenChanged](on-hidden-changed.md)(hidden: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/boolean/index.html)) |
| [onResume](on-resume.md) | <br>open override fun [onResume](on-resume.md)()<br>Releases the template-launch latch every time the browse surface becomes interactive again. |
| [onViewCreated](on-view-created.md) | <br>open override fun [onViewCreated](on-view-created.md)(view: [View](https://developer.android.com/reference/kotlin/android/view/View.html), savedInstanceState: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?) |
