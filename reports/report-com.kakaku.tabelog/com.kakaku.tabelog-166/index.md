title: com.kakaku.tabelog

# com.kakaku.tabelog

[Google Play Store](https://play.google.com/store/apps/details?id=com.kakaku.tabelog)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to read from field 'com.kakaku.tabelog.entity.search.TBSearchSet com.kakaku.tabelog.app.rst.search.condition.sub.parameter.RstSearchSubFilterParameter.mSearchSet' on a null object reference
// 	at com.kakaku.tabelog.app.rst.search.condition.sub.fragment.AbstractRstSearchFilterFragment.onActivityCreated(SourceFile:3065)
// 	at android.support.v4.app.Fragment.performActivityCreated(SourceFile:1797)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(SourceFile:979)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(SourceFile:1138)
// 	at android.support.v4.app.BackStackRecord.run(SourceFile:740)
// 	at android.support.v4.app.FragmentManagerImpl.execPendingActions(SourceFile:1501)
// 	at android.support.v4.app.FragmentActivity.onResume(SourceFile:426)
// 	at com.kakaku.framework.activity.K3Activity.onResume(SourceFile:235)
// 	at com.kakaku.tabelog.activity.TBBaseActivity.onResume(SourceFile:98)
// 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1258)
// 	at android.app.Activity.performResume(Activity.java:6327)
// 	at android.app.ActivityThread.handleSendResult(ActivityThread.java:3744)
// 	at android.app.ActivityThread.-wrap16(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1393)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



