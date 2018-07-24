title: cn.com.fetion.mvclip

# cn.com.fetion.mvclip

[Google Play Store](https://play.google.com/store/apps/details?id=cn.com.fetion.mvclip)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'void android.hardware.Camera.stopPreview()' on a null object reference
// 	at cn.com.fetion.mvclip.activity.VideoRecordActivity.n(Unknown Source)
// 	at cn.com.fetion.mvclip.activity.VideoRecordActivity$1.handleMessage(Unknown Source)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



