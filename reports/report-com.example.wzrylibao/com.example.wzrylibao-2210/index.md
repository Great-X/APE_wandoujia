title: com.example.wzrylibao

# com.example.wzrylibao

[Google Play Store](https://play.google.com/store/apps/details?id=com.example.wzrylibao)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.Object android.content.Context.getSystemService(java.lang.String)' on a null object reference
// 	at android.view.LayoutInflater.from(LayoutInflater.java:229)
// 	at android.view.View.inflate(View.java:19789)
// 	at com.example.wzrylibao.fragment.home.GameDetailFragment.onLoadSuccessView(GameDetailFragment.java:70)
// 	at com.example.wzrylibao.fragment.BaseFragment$1.initSuccessView(BaseFragment.java:37)
// 	at com.example.wzrylibao.ui.LoadingPager.updateUI(LoadingPager.java:115)
// 	at com.example.wzrylibao.ui.LoadingPager.access$000(LoadingPager.java:25)
// 	at com.example.wzrylibao.ui.LoadingPager$1.run(LoadingPager.java:105)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



