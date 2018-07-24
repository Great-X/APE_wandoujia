title: cn.bluecrane.calendarhd

# cn.bluecrane.calendarhd

[Google Play Store](https://play.google.com/store/apps/details?id=cn.bluecrane.calendarhd)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Error receiving broadcast Intent { act=action_calendar_update flg=0x10 } in cn.bluecrane.calendarhd.fragment.CalendarFragment$CalendarReceiver@c615eb0
// 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:891)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'void android.widget.TextView.setText(java.lang.CharSequence)' on a null object reference
// 	at cn.bluecrane.calendarhd.fragment.CalendarFragment.initCalendarByReceiver(CalendarFragment.java:256)
// 	at cn.bluecrane.calendarhd.fragment.CalendarFragment.access$0(CalendarFragment.java:252)
// 	at cn.bluecrane.calendarhd.fragment.CalendarFragment$CalendarReceiver.onReceive(CalendarFragment.java:109)
// 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
// 	... 7 more

```



