title: com.example.wzrylibao

# com.example.wzrylibao

[Google Play Store](https://play.google.com/store/apps/details?id=com.example.wzrylibao)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// android.view.InflateException: Binary XML file line #7: Binary XML file line #7: Error inflating class <unknown>
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:539)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:423)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:374)
// 	at com.example.wzrylibao.holder.PersonInfoUserHolder.initView(PersonInfoUserHolder.java:53)
// 	at com.example.wzrylibao.holder.BaseHolder.<init>(BaseHolder.java:17)
// 	at com.example.wzrylibao.holder.PersonInfoUserHolder.<init>(PersonInfoUserHolder.java:35)
// 	at com.example.wzrylibao.fragment.PersonInfoFragment$1.<init>(PersonInfoFragment.java:79)
// 	at com.example.wzrylibao.fragment.PersonInfoFragment.onLoadSuccessView(PersonInfoFragment.java:79)
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
// Caused by: android.view.InflateException: Binary XML file line #7: Error inflating class <unknown>
// 	at android.view.LayoutInflater.createView(LayoutInflater.java:645)
// 	at com.android.internal.policy.PhoneLayoutInflater.onCreateView(PhoneLayoutInflater.java:58)
// 	at android.view.LayoutInflater.onCreateView(LayoutInflater.java:694)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:762)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:704)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:835)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:515)
// 	... 18 more
// Caused by: java.lang.reflect.InvocationTargetException
// 	at java.lang.reflect.Constructor.newInstance(Native Method)
// 	at android.view.LayoutInflater.createView(LayoutInflater.java:619)
// 	... 25 more
// Caused by: java.lang.OutOfMemoryError: Failed to allocate a 33177612 byte allocation with 14644472 free bytes and 13MB until OOM
// 	at dalvik.system.VMRuntime.newNonMovableArray(Native Method)
// 	at android.graphics.BitmapFactory.nativeDecodeAsset(Native Method)
// 	at android.graphics.BitmapFactory.decodeStream(BitmapFactory.java:609)
// 	at android.graphics.BitmapFactory.decodeResourceStream(BitmapFactory.java:444)
// 	at android.graphics.drawable.Drawable.createFromResourceStream(Drawable.java:1080)
// 	at android.content.res.Resources.loadDrawableForCookie(Resources.java:2635)
// 	at android.content.res.Resources.loadDrawable(Resources.java:2540)
// 	at android.content.res.TypedArray.getDrawable(TypedArray.java:870)
// 	at android.view.View.<init>(View.java:3954)
// 	at android.view.View.<init>(View.java:3861)
// 	at android.view.View.<init>(View.java:3840)
// 	... 27 more

```



