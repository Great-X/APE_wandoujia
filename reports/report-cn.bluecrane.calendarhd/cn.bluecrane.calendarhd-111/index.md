title: cn.bluecrane.calendarhd

# cn.bluecrane.calendarhd

[Google Play Store](https://play.google.com/store/apps/details?id=cn.bluecrane.calendarhd)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.Object java.util.HashMap.get(java.lang.Object)' on a null object reference
// 	at cn.bluecrane.calendarhd.util.initview.InitScheduleUtil.initData(InitScheduleUtil.java:304)
// 	at cn.bluecrane.calendarhd.util.initview.InitScheduleUtil.initView(InitScheduleUtil.java:250)
// 	at cn.bluecrane.calendarhd.fragment.YijiFragment.onCreateView(YijiFragment.java:110)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:870)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1080)
// 	at android.support.v4.app.BackStackRecord.run(BackStackRecord.java:622)
// 	at android.support.v4.app.FragmentManagerImpl.execPendingActions(FragmentManager.java:1416)
// 	at android.support.v4.app.FragmentManagerImpl$1.run(FragmentManager.java:420)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



