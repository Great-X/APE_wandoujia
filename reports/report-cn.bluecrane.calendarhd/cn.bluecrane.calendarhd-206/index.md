title: cn.bluecrane.calendarhd

# cn.bluecrane.calendarhd

[Google Play Store](https://play.google.com/store/apps/details?id=cn.bluecrane.calendarhd)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// android.content.ActivityNotFoundException: No Activity found to handle Intent { act=android.provider.MediaStore.RECORD_SOUND }
// 	at android.app.Instrumentation.checkStartActivityResult(Instrumentation.java:1798)
// 	at android.app.Instrumentation.execStartActivity(Instrumentation.java:1512)
// 	at android.app.Activity.startActivityForResult(Activity.java:3930)
// 	at android.app.Activity.startActivityForResult(Activity.java:3890)
// 	at android.support.v4.app.FragmentActivity.startActivityForResult(FragmentActivity.java:674)
// 	at cn.bluecrane.calendarhd.CreateMemoActivity.onOptionsItemSelected(CreateMemoActivity.java:643)
// 	at android.support.v4.app.Watson.onMenuItemSelected(Watson.java:119)
// 	at com.actionbarsherlock.ActionBarSherlock.callbackOptionsItemSelected(ActionBarSherlock.java:603)
// 	at com.actionbarsherlock.internal.ActionBarSherlockNative.dispatchOptionsItemSelected(ActionBarSherlockNative.java:78)
// 	at com.actionbarsherlock.app.SherlockFragmentActivity.onMenuItemSelected(SherlockFragmentActivity.java:205)
// 	at com.android.internal.policy.PhoneWindow.onMenuItemSelected(PhoneWindow.java:1151)
// 	at com.android.internal.view.menu.MenuBuilder.dispatchMenuItemSelected(MenuBuilder.java:761)
// 	at com.android.internal.view.menu.MenuItemImpl.invoke(MenuItemImpl.java:152)
// 	at com.android.internal.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:904)
// 	at com.android.internal.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:894)
// 	at android.widget.ActionMenuView.invokeItem(ActionMenuView.java:616)
// 	at com.android.internal.view.menu.ActionMenuItemView.onClick(ActionMenuItemView.java:141)
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



