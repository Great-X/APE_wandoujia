title: com.icraft.bsocr.paparecipes

# com.icraft.bsocr.paparecipes

[Google Play Store](https://play.google.com/store/apps/details?id=com.icraft.bsocr.paparecipes)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to resume activity {com.icraft.bsocr.paparecipes/com.icraft.bsocr.ui.TagReader_Main_Activity}: java.lang.NullPointerException: Attempt to invoke virtual method 'android.hardware.Camera$Parameters android.hardware.Camera.getParameters()' on a null object reference
// 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3103)
// 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3134)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1388)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'android.hardware.Camera$Parameters android.hardware.Camera.getParameters()' on a null object reference
// 	at com.icraft.bsocr.ui.TagReader_Main_Activity.onResume(Unknown Source)
// 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1258)
// 	at android.app.Activity.performResume(Activity.java:6327)
// 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3092)
// 	... 8 more

```



