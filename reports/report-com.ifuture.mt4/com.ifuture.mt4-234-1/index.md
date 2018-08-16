title: com.ifuture.mt4

# com.ifuture.mt4

[Google Play Store](https://play.google.com/store/apps/details?id=com.ifuture.mt4)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.ifuture.mt4/com.ifuture.mt4.MainActivity}: android.app.Fragment$InstantiationException: Unable to instantiate fragment com.ifuture.mt4.fragment.IFutureVIPNewsFragment: make sure class name exists, is public, and has an empty constructor that is public
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
// Caused by: android.app.Fragment$InstantiationException: Unable to instantiate fragment com.ifuture.mt4.fragment.IFutureVIPNewsFragment: make sure class name exists, is public, and has an empty constructor that is public
// 	at android.app.Fragment.instantiate(Fragment.java:624)
// 	at android.app.FragmentState.instantiate(Fragment.java:106)
// 	at android.app.FragmentManagerImpl.restoreAllState(FragmentManager.java:1858)
// 	at android.app.FragmentController.restoreAllState(FragmentController.java:122)
// 	at android.app.Activity.onCreate(Activity.java:918)
// 	at android.support.v4.app.FragmentActivity.onCreate(FragmentActivity.java:257)
// 	at com.ifuture.mt4.MainActivity.onCreate(MainActivity.java:107)
// 	at android.app.Activity.performCreate(Activity.java:6251)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at cn.jiguang.a.a.c.a.a.d.callActivityOnCreate(Unknown Source)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	... 9 more
// Caused by: java.lang.InstantiationException: java.lang.Class<com.ifuture.mt4.fragment.IFutureVIPNewsFragment> has no zero argument constructor
// 	at java.lang.Class.newInstance(Native Method)
// 	at android.app.Fragment.instantiate(Fragment.java:613)
// 	... 19 more

```



