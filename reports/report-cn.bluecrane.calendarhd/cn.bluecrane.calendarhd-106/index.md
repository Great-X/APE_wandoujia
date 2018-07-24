title: cn.bluecrane.calendarhd

# cn.bluecrane.calendarhd

[Google Play Store](https://play.google.com/store/apps/details?id=cn.bluecrane.calendarhd)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Failure delivering result ResultInfo{who=null, request=1, result=1, data=Intent { cmp=cn.bluecrane.calendarhd/.CreateMemoActivity }} to activity {cn.bluecrane.calendarhd/cn.bluecrane.calendarhd.MainActivity}: java.lang.IllegalStateException: Can not perform this action after onSaveInstanceState
// 	at android.app.ActivityThread.deliverResults(ActivityThread.java:3699)
// 	at android.app.ActivityThread.handleSendResult(ActivityThread.java:3742)
// 	at android.app.ActivityThread.-wrap16(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1393)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.IllegalStateException: Can not perform this action after onSaveInstanceState
// 	at android.support.v4.app.FragmentManagerImpl.checkStateLoss(FragmentManager.java:1299)
// 	at android.support.v4.app.FragmentManagerImpl.enqueueAction(FragmentManager.java:1310)
// 	at android.support.v4.app.FragmentManagerImpl.popBackStack(FragmentManager.java:436)
// 	at cn.bluecrane.calendarhd.MainActivity.yiji(MainActivity.java:291)
// 	at cn.bluecrane.calendarhd.MainActivity.onActivityResult(MainActivity.java:168)
// 	at android.app.Activity.dispatchActivityResult(Activity.java:6456)
// 	at android.app.ActivityThread.deliverResults(ActivityThread.java:3695)
// 	... 9 more

```



