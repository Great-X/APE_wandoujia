title: com.putitonline.da

# com.putitonline.da

[Google Play Store](https://play.google.com/store/apps/details?id=com.putitonline.da)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.putitonline.da/com.putitonline.da.activity.main.DigitalAlbumActivity}: android.view.InflateException: Binary XML file line #129: Binary XML file line #129: Error inflating class com.putitonline.da.views.gesturelist.GesturesListView
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
// 	at android.app.ActivityThread.-wrap11(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: android.view.InflateException: Binary XML file line #129: Binary XML file line #129: Error inflating class com.putitonline.da.views.gesturelist.GesturesListView
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:539)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:423)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:374)
// 	at com.android.internal.policy.PhoneWindow.setContentView(PhoneWindow.java:393)
// 	at android.app.Activity.setContentView(Activity.java:2172)
// 	at com.putitonline.da.activity.main.DigitalAlbumActivity.onCreate(DigitalAlbumActivity.java:295)
// 	at android.app.Activity.performCreate(Activity.java:6251)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	... 9 more
// Caused by: android.view.InflateException: Binary XML file line #129: Error inflating class com.putitonline.da.views.gesturelist.GesturesListView
// 	at android.view.LayoutInflater.createView(LayoutInflater.java:645)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:764)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:704)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:835)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:838)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:838)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:838)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:838)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:838)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:838)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:515)
// 	... 17 more
// Caused by: java.lang.reflect.InvocationTargetException
// 	at java.lang.reflect.Constructor.newInstance(Native Method)
// 	at android.view.LayoutInflater.createView(LayoutInflater.java:619)
// 	... 34 more
// Caused by: java.lang.IllegalStateException: null handler
// 	at com.putitonline.da.DigitalAlbumApplication.getHandler(DigitalAlbumApplication.java:114)
// 	at com.putitonline.da.views.gesturelist.TouchPadController.<init>(TouchPadController.java:46)
// 	at com.putitonline.da.views.gesturelist.GesturesListView.<init>(GesturesListView.java:252)
// 	... 36 more

```



