title: com.ifuture.mt4

# com.ifuture.mt4

[Google Play Store](https://play.google.com/store/apps/details?id=com.ifuture.mt4)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: The application's PagerAdapter changed the adapter's contents without calling PagerAdapter#notifyDataSetChanged! Expected adapter item count: 10, found: 2 Pager id: com.ifuture.mt4:id/viewpager Pager class: class android.support.v4.view.ViewPager Problematic adapter: class com.ifuture.mt4.adapter.IFutureHomeViewPagerAdapter
// 	at android.support.v4.view.ViewPager.populate(ViewPager.java:999)
// 	at android.support.v4.view.ViewPager.populate(ViewPager.java:951)
// 	at android.support.v4.view.ViewPager.onMeasure(ViewPager.java:1473)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1465)
// 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:748)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:630)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at android.view.View.measure(View.java:18794)
// 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:901)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:630)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1465)
// 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:748)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:630)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at com.android.internal.policy.PhoneWindow$DecorView.onMeasure(PhoneWindow.java:2643)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewRootImpl.performMeasure(ViewRootImpl.java:2100)
// 	at android.view.ViewRootImpl.measureHierarchy(ViewRootImpl.java:1216)
// 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1452)
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



