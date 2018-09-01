title: com.sundaybugs.spring.pro

# com.sundaybugs.spring.pro

[Google Play Store](https://play.google.com/store/apps/details?id=com.sundaybugs.spring.pro)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/MOB30H/2751534:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 32766, tid: 32766, name: bugs.spring.pro  >>> com.sundaybugs.spring.pro <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: '[FATAL:jni_android.cc(249)] Check failed: false. Please include Java exception stack in crash report
// '
//     r0 00000000  r1 00007ffe  r2 00000006  r3 b6efeb7c
//     r4 b6efeb84  r5 b6efeb34  r6 0000000b  r7 0000010c
//     r8 b6ca7ec0  r9 bea4bac8  sl 00000000  fp 00000004
//     ip 00000006  sp bea4b5e0  lr b6c6db61  pc b6c6ff50  cpsr 400f0010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 002b9125  /system/app/WebViewGoogle/WebViewGoogle.apk (offset 0x7f2000)

```



