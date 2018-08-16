title: com.kakaku.tabelog

# com.kakaku.tabelog

[Google Play Store](https://play.google.com/store/apps/details?id=com.kakaku.tabelog)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: An error occured while executing doInBackground()
// 	at android.support.v4.content.ModernAsyncTask$3.done(SourceFile:137)
// 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
// 	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
// 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
// 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
// 	at java.lang.Thread.run(Thread.java:818)
// Caused by: java.lang.IllegalStateException: Can not perform this action after onSaveInstanceState
// 	at android.support.v4.app.FragmentManagerImpl.checkStateLoss(SourceFile:1377)
// 	at android.support.v4.app.FragmentManagerImpl.enqueueAction(SourceFile:1395)
// 	at android.support.v4.app.BackStackRecord.commitInternal(SourceFile:637)
// 	at android.support.v4.app.BackStackRecord.commit(SourceFile:616)
// 	at android.support.v4.app.DialogFragment.show(SourceFile:139)
// 	at com.kakaku.tabelog.app.account.helper.twitter.TwitterAuthErrorDialogHelper.a(SourceFile:27)
// 	at com.kakaku.tabelog.app.account.login.activity.login.AccountAuthLoginFragment.a(SourceFile:298)
// 	at com.kakaku.tabelog.app.account.helper.twitter.TwitterAuthModel$1.a(SourceFile:2144)
// 	at com.kakaku.tabelog.app.account.helper.twitter.TwitterAuthModel$1.loadInBackground(SourceFile:126)
// 	at android.support.v4.content.AsyncTaskLoader.onLoadInBackground(SourceFile:242)
// 	at android.support.v4.content.AsyncTaskLoader$LoadTask.doInBackground(SourceFile:51)
// 	at android.support.v4.content.AsyncTaskLoader$LoadTask.doInBackground(SourceFile:40)
// 	at android.support.v4.content.ModernAsyncTask$2.call(SourceFile:123)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
// 	... 3 more

```



