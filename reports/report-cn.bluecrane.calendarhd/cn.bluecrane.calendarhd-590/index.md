title: cn.bluecrane.calendarhd

# cn.bluecrane.calendarhd

[Google Play Store](https://play.google.com/store/apps/details?id=cn.bluecrane.calendarhd)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Can not perform this action after onSaveInstanceState
// 	at android.support.v4.app.FragmentManagerImpl.checkStateLoss(FragmentManager.java:1299)
// 	at android.support.v4.app.FragmentManagerImpl.enqueueAction(FragmentManager.java:1310)
// 	at android.support.v4.app.FragmentManagerImpl.popBackStack(FragmentManager.java:436)
// 	at cn.bluecrane.calendarhd.MainActivity.yiji(MainActivity.java:256)
// 	at cn.bluecrane.calendarhd.fragment.MenuFragment$1$1.run(MenuFragment.java:78)

```



