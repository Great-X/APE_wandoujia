title: com.nan37.android

# com.nan37.android

[Google Play Store](https://play.google.com/store/apps/details?id=com.nan37.android)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// android.view.WindowManager$BadTokenException: Unable to add window -- token android.os.BinderProxy@fd81138 is not valid; is your activity running?
// 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:567)
// 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:310)
// 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:85)
// 	at android.app.Dialog.show(Dialog.java:319)
// 	at com.nan37.android.activity.SplashActivity.createGuideDialog(SplashActivity.java:197)
// 	at com.nan37.android.activity.SplashActivity.access$1(SplashActivity.java:175)
// 	at com.nan37.android.activity.SplashActivity$1.handleMessage(SplashActivity.java:157)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



