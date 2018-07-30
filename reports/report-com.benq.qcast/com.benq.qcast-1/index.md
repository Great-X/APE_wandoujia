title: com.benq.qcast

# com.benq.qcast

[Google Play Store](https://play.google.com/store/apps/details?id=com.benq.qcast)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: An error occurred while executing doInBackground()
// 	at android.os.AsyncTask$3.done(AsyncTask.java:309)
// 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
// 	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
// 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
// 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
// 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
// 	at java.lang.Thread.run(Thread.java:818)
// Caused by: java.lang.IllegalStateException: EzCastSdk was initialized!
// 	at com.actionsmicro.androidkit.ezcast.EzCastSdk.init(SourceFile:175)
// 	at com.actionsmicro.iezvu.StartUpActivity$1.a(SourceFile:52)
// 	at com.actionsmicro.iezvu.StartUpActivity$1.doInBackground(SourceFile:45)
// 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
// 	... 4 more

```



