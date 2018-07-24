title: cn.bluecrane.calendarhd

# cn.bluecrane.calendarhd

[Google Play Store](https://play.google.com/store/apps/details?id=cn.bluecrane.calendarhd)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{cn.bluecrane.calendarhd/cn.bluecrane.calendarhd.MainActivity}: java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.Object java.util.HashMap.get(java.lang.Object)' on a null object reference
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
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.Object java.util.HashMap.get(java.lang.Object)' on a null object reference
// 	at cn.bluecrane.calendarhd.util.initview.InitScheduleUtil.initData(InitScheduleUtil.java:304)
// 	at cn.bluecrane.calendarhd.util.initview.InitScheduleUtil.initView(InitScheduleUtil.java:250)
// 	at cn.bluecrane.calendarhd.fragment.YijiFragment.onCreateView(YijiFragment.java:110)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:870)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1080)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1062)
// 	at android.support.v4.app.FragmentManagerImpl.dispatchActivityCreated(FragmentManager.java:1810)
// 	at android.support.v4.app.FragmentActivity.onStart(FragmentActivity.java:501)
// 	at android.app.Instrumentation.callActivityOnStart(Instrumentation.java:1237)
// 	at android.app.Activity.performStart(Activity.java:6268)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2379)
// 	... 9 more

```



