title: com.ctbri.youeryuandaquan

# com.ctbri.youeryuandaquan

[Google Play Store](https://play.google.com/store/apps/details?id=com.ctbri.youeryuandaquan)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Exception thrown on Scheduler.Worker thread. Add `onError` handling.
// 	at rx.android.schedulers.LooperScheduler$ScheduledAction.run(LooperScheduler.java:112)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: rx.exceptions.OnErrorNotImplementedException: Attempt to invoke virtual method 'void com.ctbri.youeryuandaquan.adapter.BannerAdapter.add(java.util.List)' on a null object reference
// 	at rx.internal.util.InternalObservableUtils$ErrorNotImplementedAction.call(InternalObservableUtils.java:374)
// 	at rx.internal.util.InternalObservableUtils$ErrorNotImplementedAction.call(InternalObservableUtils.java:371)
// 	at rx.internal.util.ActionSubscriber.onError(ActionSubscriber.java:44)
// 	at rx.observers.SafeSubscriber._onError(SafeSubscriber.java:157)
// 	at rx.observers.SafeSubscriber.onError(SafeSubscriber.java:120)
// 	at rx.exceptions.Exceptions.throwOrReport(Exceptions.java:204)
// 	at rx.observers.SafeSubscriber.onNext(SafeSubscriber.java:144)
// 	at rx.internal.operators.OperatorObserveOn$ObserveOnSubscriber.call(OperatorObserveOn.java:215)
// 	at rx.android.schedulers.LooperScheduler$ScheduledAction.run(LooperScheduler.java:107)
// 	... 7 more
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'void com.ctbri.youeryuandaquan.adapter.BannerAdapter.add(java.util.List)' on a null object reference
// 	at com.ctbri.youeryuandaquan.fragment.YeyFragment.onRxStoreChanged(YeyFragment.java:513)
// 	at com.hardsoftstudio.rxflux.dispatcher.Dispatcher$5.call(Dispatcher.java:89)
// 	at rx.internal.util.ActionSubscriber.onNext(ActionSubscriber.java:39)
// 	at rx.observers.SafeSubscriber.onNext(SafeSubscriber.java:139)
// 	... 9 more

```



