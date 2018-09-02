title: com.wlhy.app

# com.wlhy.app

[Google Play Store](https://play.google.com/store/apps/details?id=com.wlhy.app)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.wlhy.app/com.wlhy.app.HomeActivity}: android.view.InflateException: Binary XML file line #2: Binary XML file line #2: Error inflating class <unknown>
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
// Caused by: android.view.InflateException: Binary XML file line #2: Binary XML file line #2: Error inflating class <unknown>
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:539)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:423)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:374)
// 	at com.android.internal.policy.PhoneWindow.setContentView(PhoneWindow.java:393)
// 	at android.app.Activity.setContentView(Activity.java:2172)
// 	at com.wlhy.app.HomeActivity.onCreate(HomeActivity.java:111)
// 	at android.app.Activity.performCreate(Activity.java:6251)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	... 9 more
// Caused by: android.view.InflateException: Binary XML file line #2: Error inflating class <unknown>
// 	at android.view.LayoutInflater.createView(LayoutInflater.java:645)
// 	at com.android.internal.policy.PhoneLayoutInflater.onCreateView(PhoneLayoutInflater.java:58)
// 	at android.view.LayoutInflater.onCreateView(LayoutInflater.java:694)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:762)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:704)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:492)
// 	... 17 more
// Caused by: java.lang.reflect.InvocationTargetException
// 	at java.lang.reflect.Constructor.newInstance(Native Method)
// 	at android.view.LayoutInflater.createView(LayoutInflater.java:619)
// 	... 22 more
// Caused by: java.lang.OutOfMemoryError: Failed to allocate a 36864012 byte allocation with 16777056 free bytes and 29MB until OOM
// 	at dalvik.system.VMRuntime.newNonMovableArray(Native Method)
// 	at android.graphics.BitmapFactory.nativeDecodeAsset(Native Method)
// 	at android.graphics.BitmapFactory.decodeStream(BitmapFactory.java:609)
// 	at android.graphics.BitmapFactory.decodeResourceStream(BitmapFactory.java:444)
// 	at android.graphics.drawable.Drawable.createFromResourceStream(Drawable.java:1080)
// 	at android.content.res.Resources.loadDrawableForCookie(Resources.java:2635)
// 	at android.content.res.Resources.loadDrawable(Resources.java:2540)
// 	at android.content.res.TypedArray.getDrawable(TypedArray.java:870)
// 	at android.view.View.<init>(View.java:3954)
// 	at android.view.ViewGroup.<init>(ViewGroup.java:573)
// 	at android.widget.RelativeLayout.<init>(RelativeLayout.java:248)
// 	at android.widget.RelativeLayout.<init>(RelativeLayout.java:244)
// 	at android.widget.RelativeLayout.<init>(RelativeLayout.java:240)
// 	... 24 more

```



