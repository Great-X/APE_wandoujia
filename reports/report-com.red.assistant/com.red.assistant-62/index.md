title: com.red.assistant

# com.red.assistant

[Google Play Store](https://play.google.com/store/apps/details?id=com.red.assistant)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: setParameters failed
// 	at android.hardware.Camera.native_setParameters(Native Method)
// 	at android.hardware.Camera.setParameters(Camera.java:1878)
// 	at com.red.assistant.view.MirrorView.setPreviewSize(MirrorView.java:94)
// 	at com.red.assistant.view.MirrorView.access$300(MirrorView.java:18)
// 	at com.red.assistant.view.MirrorView$1.surfaceChanged(MirrorView.java:66)
// 	at android.view.SurfaceView.updateWindow(SurfaceView.java:594)
// 	at android.view.SurfaceView$3.onPreDraw(SurfaceView.java:177)
// 	at android.view.ViewTreeObserver.dispatchOnPreDraw(ViewTreeObserver.java:944)
// 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:2055)
// 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1107)
// 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6013)
// 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
// 	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
// 	at android.view.Choreographer.doFrame(Choreographer.java:606)
// 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



