title: com.feiyou.account

# com.feiyou.account

[Google Play Store](https://play.google.com/store/apps/details?id=com.feiyou.account)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Can not perform this action after onSaveInstanceState
// 	at android.support.v4.app.FragmentManagerImpl.checkStateLoss(FragmentManager.java)
// 	at android.support.v4.app.FragmentManagerImpl.enqueueAction(FragmentManager.java)
// 	at android.support.v4.app.BackStackRecord.commitInternal(BackStackRecord.java)
// 	at android.support.v4.app.BackStackRecord.commit(BackStackRecord.java)
// 	at android.support.v4.app.FragmentTabHost.onAttachedToWindow(FragmentTabHost.java)
// 	at android.view.View.dispatchAttachedToWindow(View.java:14520)
// 	at android.view.ViewGroup.dispatchAttachedToWindow(ViewGroup.java:2836)
// 	at android.view.ViewGroup.dispatchAttachedToWindow(ViewGroup.java:2843)
// 	at android.view.ViewGroup.dispatchAttachedToWindow(ViewGroup.java:2843)
// 	at android.view.ViewGroup.dispatchAttachedToWindow(ViewGroup.java:2843)
// 	at android.view.ViewGroup.dispatchAttachedToWindow(ViewGroup.java:2843)
// 	at android.view.ViewGroup.dispatchAttachedToWindow(ViewGroup.java:2843)
// 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1364)
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



