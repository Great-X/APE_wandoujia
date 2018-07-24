title: cn.alstru.trueaudio

# cn.alstru.trueaudio

[Google Play Store](https://play.google.com/store/apps/details?id=cn.alstru.trueaudio)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{cn.alstru.trueaudio/cn.alstru.trueaudio.activity.MainActivity}: android.view.InflateException: Binary XML file line #264: Binary XML file line #264: Error inflating class cn.alstru.trueaudio.util.PowerImageView
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
// 	at android.app.ActivityThread.-wrap11(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: android.view.InflateException: Binary XML file line #264: Binary XML file line #264: Error inflating class cn.alstru.trueaudio.util.PowerImageView
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:539)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:423)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:374)
// 	at com.android.internal.policy.PhoneWindow.setContentView(PhoneWindow.java:393)
// 	at android.app.Activity.setContentView(Activity.java:2172)
// 	at cn.alstru.trueaudio.activity.MainActivity.onCreate(MainActivity.java:216)
// 	at android.app.Activity.performCreate(Activity.java:6251)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	... 9 more
// Caused by: android.view.InflateException: Binary XML file line #264: Error inflating class cn.alstru.trueaudio.util.PowerImageView
// 	at android.view.LayoutInflater.createView(LayoutInflater.java:645)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:764)
// 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:704)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:835)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:838)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:838)
// 	at android.view.LayoutInflater.rInflateChildren(LayoutInflater.java:798)
// 	at android.view.LayoutInflater.inflate(LayoutInflater.java:515)
// 	... 17 more
// Caused by: java.lang.reflect.InvocationTargetException
// 	at java.lang.reflect.Constructor.newInstance(Native Method)
// 	at android.view.LayoutInflater.createView(LayoutInflater.java:619)
// 	... 26 more
// Caused by: java.lang.RuntimeException: Cannot make calls to a recycled instance!
// 	at android.content.res.TypedArray.getBoolean(TypedArray.java:300)
// 	at cn.alstru.trueaudio.util.PowerImageView.<init>(PowerImageView.java:91)
// 	at cn.alstru.trueaudio.util.PowerImageView.<init>(PowerImageView.java:72)
// 	... 28 more

```



