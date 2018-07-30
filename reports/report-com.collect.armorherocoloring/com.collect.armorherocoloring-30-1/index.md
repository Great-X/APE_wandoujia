title: com.collect.armorherocoloring

# com.collect.armorherocoloring

[Google Play Store](https://play.google.com/store/apps/details?id=com.collect.armorherocoloring)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to resume activity {com.collect.armorherocoloring/com.collect.armorherocoloring.MenuItemActivity}: java.lang.IllegalArgumentException: width and height must be > 0
// 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3103)
// 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3134)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2481)
// 	at android.app.ActivityThread.-wrap11(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.IllegalArgumentException: width and height must be > 0
// 	at android.graphics.Bitmap.createBitmap(Bitmap.java:829)
// 	at android.graphics.Bitmap.createBitmap(Bitmap.java:808)
// 	at android.graphics.Bitmap.createBitmap(Bitmap.java:739)
// 	at com.collect.armorherocoloring.utils.Constant.getResizedBitmap(Constant.java:115)
// 	at com.collect.armorherocoloring.MenuItemActivity.setSize(MenuItemActivity.java:159)
// 	at com.collect.armorherocoloring.MenuItemActivity.onResume(MenuItemActivity.java:438)
// 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1258)
// 	at android.app.Activity.performResume(Activity.java:6327)
// 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3092)
// 	... 10 more

```



