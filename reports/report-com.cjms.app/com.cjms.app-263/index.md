title: com.cjms.app

# com.cjms.app

[Google Play Store](https://play.google.com/store/apps/details?id=com.cjms.app)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'android.content.res.Resources android.content.Context.getResources()' on a null object reference
// 	at android.widget.Toast.<init>(Toast.java:102)
// 	at android.widget.Toast.makeText(Toast.java:259)
// 	at com.xinshangyun.app.lg4e.ui.activity.fragment.RegisterFragment.OnMessageResponse(RegisterFragment.java:202)
// 	at com.xinshangyun.app.model.net.okhttps.BaseModel.OnMessageResponse(BaseModel.java:41)
// 	at com.xinshangyun.app.model.net.okhttps.OkHttps$1.handleMessage(OkHttps.java:87)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



