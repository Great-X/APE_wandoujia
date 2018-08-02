title: com.feiyou.account

# com.feiyou.account

[Google Play Store](https://play.google.com/store/apps/details?id=com.feiyou.account)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String com.feiyou.account.bean.PostItemDetailsInfo$DataBean.getContent()' on a null object reference
// 	at com.feiyou.account.ui.activity.PostDetailsActivity.share(PostDetailsActivity.java)
// 	at com.feiyou.account.ui.activity.PostDetailsActivity.access$2700(PostDetailsActivity.java)
// 	at com.feiyou.account.ui.activity.PostDetailsActivity$14.onClickView(PostDetailsActivity.java)
// 	at com.feiyou.account.dialog.ShareDialog.onClick(ShareDialog.java)
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



