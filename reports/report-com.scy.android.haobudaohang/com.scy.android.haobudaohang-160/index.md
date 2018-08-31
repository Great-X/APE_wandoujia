title: com.scy.android.haobudaohang

# com.scy.android.haobudaohang

[Google Play Store](https://play.google.com/store/apps/details?id=com.scy.android.haobudaohang)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.scy.android.haobudaohang/com.scy.android.haobudaohang.activity.MainTabActivity}: java.lang.RuntimeException: Unable to start activity ComponentInfo{com.scy.android.haobudaohang/com.scy.android.haobudaohang.activity.HomeActivity}: android.view.WindowManager$BadTokenException: Unable to add window -- token null is not valid; is your activity running?
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
// Caused by: java.lang.RuntimeException: Unable to start activity ComponentInfo{com.scy.android.haobudaohang/com.scy.android.haobudaohang.activity.HomeActivity}: android.view.WindowManager$BadTokenException: Unable to add window -- token null is not valid; is your activity running?
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
// 	at android.app.ActivityThread.startActivityNow(ActivityThread.java:2240)
// 	at android.app.LocalActivityManager.moveToState(LocalActivityManager.java:136)
// 	at android.app.LocalActivityManager.startActivity(LocalActivityManager.java:348)
// 	at android.widget.TabHost$IntentContentStrategy.getContentView(TabHost.java:724)
// 	at android.widget.TabHost.setCurrentTab(TabHost.java:388)
// 	at android.widget.TabHost.addTab(TabHost.java:222)
// 	at com.scy.android.haobudaohang.activity.MainTabActivity.setupIntent(MainTabActivity.java:142)
// 	at com.scy.android.haobudaohang.activity.MainTabActivity.onCreate(MainTabActivity.java:83)
// 	at android.app.Activity.performCreate(Activity.java:6251)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	... 9 more
// Caused by: android.view.WindowManager$BadTokenException: Unable to add window -- token null is not valid; is your activity running?
// 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:567)
// 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:310)
// 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:85)
// 	at android.widget.PopupWindow.invokePopup(PopupWindow.java:1258)
// 	at android.widget.PopupWindow.showAsDropDown(PopupWindow.java:1110)
// 	at android.widget.ListPopupWindow.show(ListPopupWindow.java:658)
// 	at android.widget.AutoCompleteTextView.showDropDown(AutoCompleteTextView.java:1106)
// 	at com.scy.android.haobudaohang.activity.HomeActivity$3.onFocusChange(HomeActivity.java:253)
// 	at android.view.View.onFocusChanged(View.java:5723)
// 	at android.widget.TextView.onFocusChanged(TextView.java:8224)
// 	at android.widget.AutoCompleteTextView.onFocusChanged(AutoCompleteTextView.java:1008)
// 	at android.view.View.handleFocusGainInternal(View.java:5478)
// 	at android.view.View.requestFocusNoSearch(View.java:8476)
// 	at android.view.View.requestFocus(View.java:8455)
// 	at android.view.View.requestFocus(View.java:8422)
// 	at android.view.View.requestFocus(View.java:8401)
// 	at com.android.internal.policy.PhoneWindow.restoreHierarchyState(PhoneWindow.java:2043)
// 	at android.app.Activity.onRestoreInstanceState(Activity.java:1008)
// 	at android.app.Activity.performRestoreInstanceState(Activity.java:963)
// 	at android.app.Instrumentation.callActivityOnRestoreInstanceState(Instrumentation.java:1163)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2389)
// 	... 20 more

```



