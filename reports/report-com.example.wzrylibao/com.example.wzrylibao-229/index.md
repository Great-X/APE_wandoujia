title: com.example.wzrylibao

# com.example.wzrylibao

[Google Play Store](https://play.google.com/store/apps/details?id=com.example.wzrylibao)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{cd6c046 V.E...... R......D 0,0-1080,1776} not attached to window manager
// 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
// 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
// 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
// 	at android.app.Dialog.dismissDialog(Dialog.java:362)
// 	at android.app.Dialog.dismiss(Dialog.java:345)
// 	at com.tencent.connect.auth.AuthDialog.dismiss(ProGuard:668)
// 	at com.tencent.connect.auth.AuthDialog$LoginWebViewClient.onReceivedError(ProGuard:367)
// 	at android.webkit.WebViewClient.onReceivedError(WebViewClient.java:235)
// 	at com.android.webview.chromium.WebViewContentsClientAdapter.onReceivedError2(WebViewContentsClientAdapter.java:640)
// 	at org.chromium.android_webview.AwContentsClient.onReceivedError(AwContentsClient.java:334)
// 	at org.chromium.android_webview.AwContentsClientCallbackHelper$MyHandler.handleMessage(AwContentsClientCallbackHelper.java:137)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



