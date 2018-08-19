title: com.mjiayou.trecore

# com.mjiayou.trecore

[Google Play Store](https://play.google.com/store/apps/details?id=com.mjiayou.trecore)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to create service com.mjiayou.trecore.widget.FloatViewService: android.view.WindowManager$BadTokenException: Unable to add window android.view.ViewRootImpl$W@1570ebe -- permission denied for this window type
// 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2887)
// 	at android.app.ActivityThread.-wrap4(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1427)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: android.view.WindowManager$BadTokenException: Unable to add window android.view.ViewRootImpl$W@1570ebe -- permission denied for this window type
// 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:591)
// 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:310)
// 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:85)
// 	at com.mjiayou.trecore.widget.FloatViewService.refresh(SourceFile:150)
// 	at com.mjiayou.trecore.widget.FloatViewService.refreshView(SourceFile:143)
// 	at com.mjiayou.trecore.widget.FloatViewService.onCreateFloat(SourceFile:67)
// 	at com.mjiayou.trecore.widget.FloatViewService.onCreate(SourceFile:47)
// 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2877)
// 	... 8 more

```



