title: com.feiyou.account

# com.feiyou.account

[Google Play Store](https://play.google.com/store/apps/details?id=com.feiyou.account)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'boolean android.content.Intent.migrateExtraStreamToClipData()' on a null object reference
// 	at android.app.Instrumentation.execStartActivity(Instrumentation.java:1505)
// 	at android.app.Activity.startActivityForResult(Activity.java:3930)
// 	at android.support.v4.app.BaseFragmentActivityJB.startActivityForResult(BaseFragmentActivityJB.java)
// 	at android.support.v4.app.FragmentActivity.startActivityForResult(FragmentActivity.java)
// 	at android.support.v4.app.ActivityCompatJB.startActivityForResult(ActivityCompatJB.java)
// 	at android.support.v4.app.ActivityCompat.startActivityForResult(ActivityCompat.java)
// 	at android.support.v4.app.FragmentActivity.startActivityFromFragment(FragmentActivity.java)
// 	at android.support.v4.app.FragmentActivity$HostCallbacks.onStartActivityFromFragment(FragmentActivity.java)
// 	at android.support.v4.app.Fragment.startActivity(Fragment.java)
// 	at android.support.v4.app.Fragment.startActivity(Fragment.java)
// 	at com.feiyou.account.ui.fragment.MineFragment$5.onCopy(MineFragment.java)
// 	at com.feiyou.account.dialog.ServiceIDDialog$1.onClick(ServiceIDDialog.java)
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



