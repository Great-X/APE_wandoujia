title: com.mjiayou.trecore

# com.mjiayou.trecore

[Google Play Store](https://play.google.com/store/apps/details?id=com.mjiayou.trecore)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.mjiayou.trecore/com.mjiayou.trecore.activity.menu.MenuComActivity}: java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
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
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
// 	at com.mjiayou.trecore.activity.MenuAdapter.getCount(SourceFile:35)
// 	at android.widget.ListView.setAdapter(ListView.java:491)
// 	at com.mjiayou.trecore.activity.MenuFragment.l(SourceFile:66)
// 	at com.mjiayou.trecore.activity.MenuFragment.onViewCreated(SourceFile:58)
// 	at android.support.v4.app.FragmentManagerImpl.a(SourceFile:961)
// 	at android.support.v4.app.FragmentManagerImpl.a(SourceFile:1126)
// 	at android.support.v4.app.BackStackRecord.run(SourceFile:739)
// 	at android.support.v4.app.FragmentManagerImpl.b(SourceFile:1489)
// 	at android.support.v4.app.FragmentActivity.onStart(SourceFile:548)
// 	at com.mjiayou.trecore.activity.BaseActivity.onStart(SourceFile:48)
// 	at android.app.Instrumentation.callActivityOnStart(Instrumentation.java:1237)
// 	at android.app.Activity.performStart(Activity.java:6268)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2379)
// 	... 9 more

```



