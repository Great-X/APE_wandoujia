title: com.dw.dwxr2

# com.dw.dwxr2

[Google Play Store](https://play.google.com/store/apps/details?id=com.dw.dwxr2)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Error receiving broadcast Intent { act=http://www.doubiapp.com/money/moneyGetApk.json flg=0x10 (has extras) } in com.lf.view.tools.update.UpdateManager$3@490f94e
// 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:891)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.NumberFormatException: Invalid long: "null"
// 	at java.lang.Long.invalidLong(Long.java:124)
// 	at java.lang.Long.parseLong(Long.java:345)
// 	at java.lang.Long.parseLong(Long.java:321)
// 	at java.lang.Long.valueOf(Long.java:511)
// 	at com.lf.view.tools.update.UpdateManager$3.onReceive(UpdateManager.java:209)
// 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
// 	... 7 more

```



