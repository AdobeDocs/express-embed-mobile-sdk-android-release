//[sdk](../../index.md)/[com.adobe.express.embedsdk](index.md)/[replaceFragmentSafely](replace-fragment-safely.md)

# replaceFragmentSafely

[androidJvm]\
internal fun [FragmentManager](https://developer.android.com/reference/kotlin/androidx/fragment/app/FragmentManager.html).[replaceFragmentSafely](replace-fragment-safely.md)(fragment: [Fragment](https://developer.android.com/reference/kotlin/androidx/fragment/app/Fragment.html), containerId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html), tag: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), allowStateLoss: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) = false, executePendingTransactions: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html) = false): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)

Extension function to safely replace a fragment with consistent transaction handling.

#### Return

true if the transaction was executed, false if skipped due to saved state

#### Parameters

androidJvm

| | |
|---|---|
| fragment | The fragment to add/replace |
| containerId | The container ID where to place the fragment |
| tag | The tag for the fragment |
| allowStateLoss | Whether to use commitAllowingStateLoss() instead of commit() |
| executePendingTransactions | Whether to call executePendingTransactions() after commit |
