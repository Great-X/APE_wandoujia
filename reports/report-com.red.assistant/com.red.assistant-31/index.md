title: com.red.assistant

# com.red.assistant

[Google Play Store](https://play.google.com/store/apps/details?id=com.red.assistant)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: setParameters failed
// 	at android.hardware.Camera.native_setParameters(Native Method)
// 	at android.hardware.Camera.setParameters(Camera.java:1878)
// 	at com.red.assistant.view.ZoomView.setPreviewSize(ZoomView.java:95)
// 	at com.red.assistant.view.ZoomView.access$300(ZoomView.java:18)
// 	at com.red.assistant.view.ZoomView$1.surfaceChanged(ZoomView.java:67)
// 	at android.view.SurfaceView.updateWindow(SurfaceView.java:594)
// 	at android.view.SurfaceView.setVisibility(SurfaceView.java:257)
// 	at com.red.assistant.activity.ProtractorActivity$1.onClick(ProtractorActivity.java:36)
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



