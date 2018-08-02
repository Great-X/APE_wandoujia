title: com.guzhuang.www

# com.guzhuang.www

[Google Play Store](https://play.google.com/store/apps/details?id=com.guzhuang.www)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'void android.view.View.setVisibility(int)' on a null object reference
// 	at com.mob.bbssdk.theme1.view.Theme1ForumThreadPullToRequestView.updateTabView(Theme1ForumThreadPullToRequestView.java:196)
// 	at com.mob.bbssdk.theme1.view.Theme1ForumThreadPullToRequestView.clickTab(Theme1ForumThreadPullToRequestView.java:183)
// 	at com.mob.bbssdk.theme1.page.Theme1PageForumThread$7.onClick(Theme1PageForumThread.java:152)
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



