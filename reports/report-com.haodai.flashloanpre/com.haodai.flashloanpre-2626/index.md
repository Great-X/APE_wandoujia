title: com.haodai.flashloanpre

# com.haodai.flashloanpre

[Google Play Store](https://play.google.com/store/apps/details?id=com.haodai.flashloanpre)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Can not perform this action after onSaveInstanceState
// 	at android.support.v4.app.FragmentManagerImpl.checkStateLoss(FragmentManager.java:1493)
// 	at android.support.v4.app.FragmentManagerImpl.enqueueAction(FragmentManager.java:1511)
// 	at android.support.v4.app.BackStackRecord.commitInternal(BackStackRecord.java:634)
// 	at android.support.v4.app.BackStackRecord.commit(BackStackRecord.java:613)
// 	at com.haodai.flashloanpre.main.activity.MainActivity.a(MainActivity.java:434)
// 	at com.haodai.flashloanpre.main.activity.MainActivity.onClick(MainActivity.java:342)
// 	at android.view.View.performClick(View.java:5204)
// 	at android.view.View$PerformClick.run(View.java:21153)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



