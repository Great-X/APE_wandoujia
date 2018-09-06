title: ly.bms.activity

# ly.bms.activity

[Google Play Store](https://play.google.com/store/apps/details?id=ly.bms.activity)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalThreadStateException: Thread already started
// 	at java.lang.Thread.checkNotStarted(Thread.java:849)
// 	at java.lang.Thread.start(Thread.java:1059)
// 	at ly.bms.activity.Start$2.onUpdateReturned(Start.java:67)
// 	at com.umeng.update.a.handleMessage(UmengUpdateAgent.java:44)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



