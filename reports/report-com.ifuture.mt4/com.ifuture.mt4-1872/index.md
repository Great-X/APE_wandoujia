title: com.ifuture.mt4

# com.ifuture.mt4

[Google Play Store](https://play.google.com/store/apps/details?id=com.ifuture.mt4)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: The application's PagerAdapter changed the adapter's contents without calling PagerAdapter#notifyDataSetChanged! Expected adapter item count: 10, found: 6 Pager id: com.ifuture.mt4:id/viewpager Pager class: class android.support.v4.view.ViewPager Problematic adapter: class com.ifuture.mt4.adapter.IFutureHomeViewPagerAdapter
// 	at android.support.v4.view.ViewPager.populate(ViewPager.java:999)
// 	at android.support.v4.view.ViewPager.setCurrentItemInternal(ViewPager.java:551)
// 	at android.support.v4.view.ViewPager.setCurrentItemInternal(ViewPager.java:513)
// 	at android.support.v4.view.ViewPager.dataSetChanged(ViewPager.java:945)
// 	at android.support.v4.view.ViewPager$PagerObserver.onChanged(ViewPager.java:2905)
// 	at android.database.DataSetObservable.notifyChanged(DataSetObservable.java:37)
// 	at android.support.v4.view.PagerAdapter.notifyDataSetChanged(PagerAdapter.java:276)
// 	at com.ifuture.mt4.fragment.IFutureHomeFragment$8.onPostExecute(IFutureHomeFragment.java:662)
// 	at com.ifuture.mt4.fragment.IFutureHomeFragment$8.onPostExecute(IFutureHomeFragment.java:619)
// 	at android.os.AsyncTask.finish(AsyncTask.java:651)
// 	at android.os.AsyncTask.-wrap1(AsyncTask.java)
// 	at android.os.AsyncTask$InternalHandler.handleMessage(AsyncTask.java:668)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



