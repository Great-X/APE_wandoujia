title: com.michael.youkecn

# com.michael.youkecn

[Google Play Store](https://play.google.com/store/apps/details?id=com.michael.youkecn)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'android.os.IBinder android.view.View.getWindowToken()' on a null object reference
// 	at com.michael.util.UIHelper.hideSoftInputFromWindow(UIHelper.java:121)
// 	at com.michael.youkecn.activity.UserLoginActivity.btnLogin(UserLoginActivity.java:74)
// 	at com.michael.youkecn.activity.UserLoginActivity_$2.onClick(UserLoginActivity_.java:103)
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



