title: gov.seoul.android.maps.MapActivity

# gov.seoul.android.maps.MapActivity

```
// java.lang.RuntimeException: An error occurred while executing doInBackground()
// 	at android.os.AsyncTask$3.done(AsyncTask.java:309)
// 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
// 	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
// 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
// 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
// 	at java.lang.Thread.run(Thread.java:818)
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'java.util.List gov.seoul.android.maps.MapActivity.bean.v2.ProhibitWordListBean.getBody()' on a null object reference
// 	at gov.seoul.android.maps.MapActivity.app.util.GisTransportManager.prohibitWordList(GisTransportManager.java:786)
// 	at gov.seoul.android.maps.MapActivity.app.util.ProhibitTask.doInBackground(ProhibitTask.java:27)
// 	at gov.seoul.android.maps.MapActivity.app.util.ProhibitTask.doInBackground(ProhibitTask.java:10)
// 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
// 	... 3 more

```



