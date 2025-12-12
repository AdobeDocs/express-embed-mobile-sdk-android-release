//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[FilePickerViewModel](index.md)

# FilePickerViewModel

[androidJvm]\
internal class [FilePickerViewModel](index.md) : [ViewModel](https://developer.android.com/reference/kotlin/androidx/lifecycle/ViewModel.html)

## Constructors

| | |
|---|---|
| [FilePickerViewModel](-file-picker-view-model.md) | [androidJvm]<br>constructor() |

## Properties

| Name | Summary |
|---|---|
| [fileChooserCallback](file-chooser-callback.md) | [androidJvm]<br>var [fileChooserCallback](file-chooser-callback.md): [ValueCallback](https://developer.android.com/reference/kotlin/android/webkit/ValueCallback.html)&lt;[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)&gt;&gt;? |
| [isCallbackPending](is-callback-pending.md) | [androidJvm]<br>var [isCallbackPending](is-callback-pending.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) |
| [pendingPickerRequest](pending-picker-request.md) | [androidJvm]<br>val [pendingPickerRequest](pending-picker-request.md): [LiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/LiveData.html)&lt;[ValueCallback](https://developer.android.com/reference/kotlin/android/webkit/ValueCallback.html)&lt;[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)&gt;&gt;?&gt; |
| [uri](uri.md) | [androidJvm]<br>var [uri](uri.md): [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)? |

## Functions

| Name | Summary |
|---|---|
| [clearRequest](clear-request.md) | [androidJvm]<br>fun [clearRequest](clear-request.md)() |
| [markCallbackComplete](mark-callback-complete.md) | [androidJvm]<br>fun [markCallbackComplete](mark-callback-complete.md)() |
| [requestPicker](request-picker.md) | [androidJvm]<br>fun [requestPicker](request-picker.md)(callback: [ValueCallback](https://developer.android.com/reference/kotlin/android/webkit/ValueCallback.html)&lt;[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)&gt;&gt;?) |
