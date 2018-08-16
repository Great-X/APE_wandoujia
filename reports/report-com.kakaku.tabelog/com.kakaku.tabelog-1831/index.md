title: com.kakaku.tabelog

# com.kakaku.tabelog

[Google Play Store](https://play.google.com/store/apps/details?id=com.kakaku.tabelog)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Can not perform this action after onSaveInstanceState
// 	at android.support.v4.app.FragmentManagerImpl.checkStateLoss(SourceFile:1377)
// 	at android.support.v4.app.FragmentManagerImpl.enqueueAction(SourceFile:1395)
// 	at android.support.v4.app.BackStackRecord.commitInternal(SourceFile:637)
// 	at android.support.v4.app.BackStackRecord.commit(SourceFile:616)
// 	at android.support.v4.app.DialogFragment.show(SourceFile:139)
// 	at com.kakaku.tabelog.app.account.helper.facebook.FacebookAuthErrorDialogHelper.a(SourceFile:26)
// 	at com.kakaku.tabelog.app.account.login.activity.login.AccountAuthLoginFragment.a(SourceFile:276)
// 	at com.kakaku.tabelog.app.account.login.activity.login.AccountAuthLoginFragment.call(SourceFile:246)
// 	at com.facebook.Session$3$1.run(SourceFile:1303)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



