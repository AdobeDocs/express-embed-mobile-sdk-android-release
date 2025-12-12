//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[CoroutineJobManager](index.md)

# CoroutineJobManager

[androidJvm]\
internal object [CoroutineJobManager](index.md)

## Properties

| Name | Summary |
|---|---|
| [currentJob](current-job.md) | [androidJvm]<br>val [currentJob](current-job.md): Job |

## Functions

| Name | Summary |
|---|---|
| [asyncOnIo](async-on-io.md) | [androidJvm]<br>fun &lt;[T](async-on-io.md)&gt; [asyncOnIo](async-on-io.md)(block: suspend CoroutineScope.() -&gt; [T](async-on-io.md)): Deferred&lt;[T](async-on-io.md)&gt; |
| [asyncOnMain](async-on-main.md) | [androidJvm]<br>fun &lt;[T](async-on-main.md)&gt; [asyncOnMain](async-on-main.md)(block: suspend CoroutineScope.() -&gt; [T](async-on-main.md)): Deferred&lt;[T](async-on-main.md)&gt; |
| [cancelAllJobs](cancel-all-jobs.md) | [androidJvm]<br>fun [cancelAllJobs](cancel-all-jobs.md)() |
| [createNewJob](create-new-job.md) | [androidJvm]<br>fun [createNewJob](create-new-job.md)(actionIntent: [ActionIntent](../-action-intent/index.md)) |
| [runOnIo](run-on-io.md) | [androidJvm]<br>fun [runOnIo](run-on-io.md)(block: suspend CoroutineScope.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-unit/index.html)) |
| [runOnMain](run-on-main.md) | [androidJvm]<br>fun [runOnMain](run-on-main.md)(block: suspend CoroutineScope.() -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-unit/index.html)) |
