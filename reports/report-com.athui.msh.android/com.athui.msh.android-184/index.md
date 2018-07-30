title: com.athui.msh.android

# com.athui.msh.android

[Google Play Store](https://play.google.com/store/apps/details?id=com.athui.msh.android)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/MOB30H/2751534:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 24982, tid: 24982, name: hui.msh.android  >>> com.athui.msh.android <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: '[FATAL:jni_android.cc(249)] Check failed: false. Please include Java exception stack in crash report
// '
//     r0 00000000  r1 00006196  r2 00000006  r3 b6fa9b7c
//     r4 b6fa9b84  r5 b6fa9b34  r6 0000000b  r7 0000010c
//     r8 b6d52ec0  r9 bedc7f78  sl 00000000  fp bedc80e0
//     ip 00000006  sp bedc7a90  lr b6d18b61  pc b6d1af50  cpsr 400f0010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 002b9125  /system/app/WebViewGoogle/WebViewGoogle.apk (offset 0x7f2000)

```



