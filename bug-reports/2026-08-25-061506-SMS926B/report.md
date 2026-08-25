# Hlásenie problému s článkom

- **čas:** 2026-08-25 06:15:06
- **titulok:** Netflixu vyrástla lacná konkurencia. Vyše 1 300 filmov teraz vyjde len na 2 € mesačne
- **odkaz:** https://www.techbyte.sk/2026/08/netflixu-lacna-konkurencie-1-300-filmov-2-eura-mesacne/
- **verzia:** 0.1.107 (107)
- **zariadenie:** samsung SM-S926B, Android 16

## Popis problému od používateľa

článok sa nepodarilo extrahovať - navrhni opravu 
zanalyzuje prečo sa nenancital spravne

## Prílohy

- `page.html` — zobrazený obsah článku v readeri
- `screenshot.png` — snímka obrazovky readeru

## Diagnostika

```
=== Briefly ===
verzia:      0.1.107 (107)
zariadenie:  samsung SM-S926B
android:     16 (API 36)
abi:         arm64-v8a
RAM:         11203 MB celkom, 3195 MB voľných

=== denník aplikácie ===
08-25 06:11:23.743 [logy] odoslané ako 2026-08-25-061121-SMS926B-auto.txt
08-25 06:11:33.078 [app] štart, verzia 0.1.107
08-25 06:11:33.161 [update] výsledok inštalácie: 0
08-25 06:11:33.163 [update] zmazaný balík briefly-107.apk
08-25 06:13:23.676 [nahlad] dotiahnutych 2 nahladov z 2 clankov


=== logcat ===
--------- beginning of main
08-25 06:11:33.024 I/Zygote  (24343): Process 24343 created for sk.frodo21.reader
08-25 06:11:33.025 I/.frodo21.reader(24343): Using generational CollectorTypeCMC GC.
08-25 06:11:33.036 D/nativeloader(24343): Load libframework-connectivity-tiramisu-jni.so using APEX ns com_android_tethering for caller /apex/com.android.tethering/javalib/framework-connectivity-t.jar: ok
08-25 06:11:33.041 D/ActivityThread(24343): setConscryptValidator
08-25 06:11:33.042 D/ActivityThread(24343): setConscryptValidator - put
08-25 06:11:33.059 D/nativeloader(24343): Configuring clns-9 for other apk /data/app/~~2SqE2iobsk5gZubxGQLAtA==/sk.frodo21.reader-VCd1d4l4V6tSzJN5Hh0vRQ==/base.apk. target_sdk_version=36, uses_libraries=, library_path=/data/app/~~2SqE2iobsk5gZubxGQLAtA==/sk.frodo21.reader-VCd1d4l4V6tSzJN5Hh0vRQ==/lib/arm64:/data/app/~~2SqE2iobsk5gZubxGQLAtA==/sk.frodo21.reader-VCd1d4l4V6tSzJN5Hh0vRQ==/base.apk!/lib/arm64-v8a, permitted_path=/data:/mnt/expand:/data/user/0/sk.frodo21.reader
08-25 06:11:33.063 V/GraphicsEnvironment(24343): Currently set values for:
08-25 06:11:33.063 V/GraphicsEnvironment(24343):   angle_gl_driver_selection_pkgs=[]
08-25 06:11:33.063 V/GraphicsEnvironment(24343):   angle_gl_driver_selection_values=[]
08-25 06:11:33.063 V/GraphicsEnvironment(24343): sk.frodo21.reader is not listed in per-application setting
08-25 06:11:33.063 V/GraphicsEnvironment(24343): ANGLE allowlist from config: com.dreamgames.royalmatch com.dts.freefiremax com.dxx.firenow com.gramgames.mergedragons com.ludo.king com.mojang.minecraftpe com.my.defense com.nintendo.zaka com.os.airforce com.playrix.fishdomdd.gplay io.teslatech.callbreak jp.konami.prospia net.peakgames.toonblast
08-25 06:11:33.063 V/GraphicsEnvironment(24343): No special selections for ANGLE, returning default driver choice
08-25 06:11:33.063 V/GraphicsEnvironment(24343): App is not on the allowlist for updatable production driver.
08-25 06:11:33.068 D/WM-WrkMgrInitializer(24343): Initializing WorkManager with default configuration.
08-25 06:11:33.070 D/WM-PackageManagerHelper(24343): Skipping component enablement for androidx.work.impl.background.systemjob.SystemJobService
08-25 06:11:33.070 D/WM-Schedulers(24343): Created SystemJobScheduler and enabled SystemJobService
08-25 06:11:33.075 I/HWUI    (24343): Using FreeType backend (prop=Auto)
08-25 06:11:33.095 E/ashmem  (24343): Pinning is deprecated since Android Q. Please use trim or other methods.
--------- beginning of system
08-25 06:11:38.254 D/ActivityThread(24343): sk.frodo21.reader will use render engine as VK
08-25 06:11:38.257 D/vulkan  (24343): searching for layers in '/data/app/~~2SqE2iobsk5gZubxGQLAtA==/sk.frodo21.reader-VCd1d4l4V6tSzJN5Hh0vRQ==/lib/arm64'
08-25 06:11:38.257 D/vulkan  (24343): searching for layers in '/data/app/~~2SqE2iobsk5gZubxGQLAtA==/sk.frodo21.reader-VCd1d4l4V6tSzJN5Hh0vRQ==/base.apk!/lib/arm64-v8a'
08-25 06:11:38.258 V/XGL     (24343): ----------------------------------------------------------------------
08-25 06:11:38.258 V/XGL     (24343): SUMD version compiled date     = 2026-01-09 09:57 - KST
08-25 06:11:38.258 V/XGL     (24343): SUMD version revision number   = 1900168dcb
08-25 06:11:38.258 V/XGL     (24343): SUMD version info              = Driver version: 24.0.534, git hash: 1900168dcb
08-25 06:11:38.258 V/XGL     (24343): ----------------------------------------------------------------------
08-25 06:11:38.258 V/XGL     (24343): Entering: Create
08-25 06:11:38.270 V/XGL     (24343): Exiting: Create
08-25 06:11:38.276 D/DesktopExperienceFlags(24343): Toggle override initialized to: false
08-25 06:11:38.280 D/CompatChangeReporter(24343): Compat change id reported: 377864165; UID 10606; state: ENABLED
08-25 06:11:38.281 D/DesktopModeFlags(24343): Toggle override initialized to: OVERRIDE_UNSET
08-25 06:11:38.281 I/DecorView(24343): setWindowBackground: isPopOver=false color=fffafafa d=android.graphics.drawable.ColorDrawable@4cec4a7
08-25 06:11:38.287 D/ViewRootImpl(24343): desktopMode is false
08-25 06:11:38.287 I/ViewRootImpl(24343): dVRR is disabled
08-25 06:11:38.287 D/HardwareRenderer(24343): onDisplayChanged. displayId=0 current wxh=1440x3120 mLargest wxh=0x0
08-25 06:11:38.288 D/HardwareRenderer(24343): Set largestWidth and largestHeight as logical resolution. (1440x3120)
08-25 06:11:38.288 D/NativeCustomFrequencyManager(24343): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-25 06:11:38.291 I/.frodo21.reader(24343): [HIDL_FETCH_IMapper] android.hardware.graphics.mapper@4.0: Loaded Mapper successfully.
08-25 06:11:38.295 I/IDS_TAG (24343): Clearing training data of sk.frodo21.reader.ReaderApp@d213778
08-25 06:11:38.299 I/IDS_TAG (24343): Starting IDS observe window
08-25 06:11:38.299 I/IDS_TAG (24343): Getting Shared Preference for sk.frodo21.reader.ReaderApp@d213778 uid = 10606
08-25 06:11:38.299 I/IDS_TAG (24343): App sk.frodo21.reader.ReaderApp@d213778 has not finished training
08-25 06:11:38.300 I/IDS_TAG (24343): Closing IDS observe window
08-25 06:11:38.300 I/IDS_TAG (24343): Getting Shared Preference for sk.frodo21.reader.ReaderApp@d213778 uid = 10606
08-25 06:11:38.300 I/IDS_TAG (24343): IDS count updated to 1 for sk.frodo21.reader.ReaderApp@d213778
08-25 06:11:38.301 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@dc04411
08-25 06:11:38.352 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:11:38.352 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:11:38.509 D/ConnectivityManager(24343): StackLog: [android.net.ConnectivityManager.sendRequestForNetwork(ConnectivityManager.java:4744)] [android.net.ConnectivityManager.sendRequestForNetwork(ConnectivityManager.java:4912)] [android.net.ConnectivityManager.registerNetworkCallback(ConnectivityManager.java:5329)] [android.net.ConnectivityManager.registerNetworkCallback(ConnectivityManager.java:5299)] [coil.network.RealNetworkObserver.<init>(SourceFile:29)] [coil.network.NetworkObserverKt.NetworkObserver(SourceFile:23)] [coil.util.SystemCallbacks.registerNetworkObserver(SourceFile:33)] [coil.util.SystemCallbacks.isOnline(SourceFile:1)] [coil.request.RequestService.updateOptionsOnWorkerThread(SourceFile:36)] [coil.intercept.EngineInterceptor.execute(SourceFile:170)] [coil.intercept.EngineInterceptor.access$execute(SourceFile:0)] [coil.intercept.EngineInterceptor$intercept$2.invokeSuspend(SourceFile:38)] [kotlin.coroutines.jvm.internal.BaseContinuationImpl.resumeWith(SourceFile:8)] [kotlinx.coroutines.DispatchedTask.run(SourceFile:112)] [androidx.work.Worker$2.run(SourceFile:10)] [kotlinx.coroutines.scheduling.TaskImpl.run(SourceFile:2)] [kotlinx.coroutines.scheduling.CoroutineScheduler$Worker.run(SourceFile:95)]
08-25 06:11:38.535 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:11:38.535 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:11:38.536 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:11:38.536 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:11:38.536 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:11:38.536 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:11:38.537 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:11:38.537 D/Kumiho-Kumiho(24343): updateList: inserting 'com.whatsapp' in the Kumiho client list
08-25 06:11:38.537 D/Kumiho-Kumiho(24343): updateList: inserting 'com.facebook.orca' in the Kumiho client list
08-25 06:11:38.537 D/Kumiho-Kumiho(24343): updateList: inserting 'org.telegram.messenger' in the Kumiho client list
08-25 06:11:38.537 D/Kumiho-Kumiho(24343): updateList: inserting 'com.kakao.talk' in the Kumiho client list
08-25 06:11:38.537 D/Kumiho-Kumiho(24343): updateList: inserting 'jp.naver.line.android' in the Kumiho client list
08-25 06:11:38.537 D/Kumiho-Kumiho(24343): updateList: inserting 'com.discord' in the Kumiho client list
08-25 06:11:38.537 D/Kumiho-Kumiho(24343): updateList: inserting 'com.tencent.mm' in the Kumiho client list
08-25 06:11:38.537 D/Kumiho-Kumiho(24343): updateList: inserting 'com.snapchat.android' in the Kumiho client list
08-25 06:11:38.538 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:11:38.544 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:11:38.545 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:11:38.886 D/ProfileInstaller(24343): Installing profile for sk.frodo21.reader
08-25 06:11:41.205 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:12:02.165 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.view.ImeBackAnimationController@944b648
08-25 06:12:02.259 W/InteractionJankMonitor(24343): Initializing without READ_DEVICE_CONFIG permission. enabled=false, interval=1, missedFrameThreshold=3, frameTimeThreshold=64, package=sk.frodo21.reader
08-25 06:12:04.402 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:12:29.909 I/Dialog  (24343): mIsDeviceDefault = false, mIsSamsungBasicInteraction = false, isMetaDataInActivity = false
08-25 06:12:29.913 I/DecorView(24343): setWindowBackground: isPopOver=false color=0 d=android.graphics.drawable.ColorDrawable@aa3746f
08-25 06:12:29.918 I/WindowManager(24343): WindowManagerGlobal#addView, ty=2, view=com.android.internal.policy.DecorView{5ad1275 V.E...... R.....I. 0,0-0,0}[MainActivity], caller=android.view.WindowManagerImpl.addView:167 android.app.Dialog.show:544 androidx.compose.ui.window.DialogWrapper$2.invoke:9 
08-25 06:12:29.919 D/ViewRootImpl(24343): desktopMode is false
08-25 06:12:29.919 I/ViewRootImpl(24343): dVRR is disabled
08-25 06:12:29.919 D/NativeCustomFrequencyManager(24343): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-25 06:12:29.928 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Dialog$$ExternalSyntheticLambda4@5821b2d
08-25 06:12:29.928 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@e7b7862
08-25 06:12:29.949 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:12:29.950 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:13:16.803 I/WindowManager(24343): WindowManagerGlobal#removeView, ty=2, view=com.android.internal.policy.DecorView{5ad1275 V.E...... R....... 0,0-1120,924 aid=1073741825}[MainActivity], caller=android.view.WindowManagerGlobal.removeView:654 android.view.WindowManagerImpl.removeViewImmediate:254 android.app.Dialog.dismissDialog:854 
08-25 06:13:16.804 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): null
08-25 06:13:18.820 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@dc04411
08-25 06:13:21.067 I/WebViewFactory(24343): Loading com.google.android.webview version 151.0.7922.169 (code 792216903)
08-25 06:13:21.067 W/ResourcesManager(24343): Found a null ResourcesImpl, skipped.
08-25 06:13:21.071 V/ResourcesManager(24343): The following library key has been added: ResourcesKey{ mHash=940094f6 mResDir=null mSplitDirs=[] mOverlayDirs=[] mLibDirs=[/data/app/~~RCozkHdGq47v2PK9XPgslw==/com.google.android.webview-jR8uUOFtzWjlUhSoRHRmNQ==/base.apk,/system/framework/android.test.base.jar,/system_ext/framework/androidx.window.extensions.jar] mDisplayId=0 mOverrideConfig=v36 mCompatInfo={450dpi always-compat} mLoaders=[]}
08-25 06:13:21.072 D/ApplicationLoaders(24343): Returning zygote-cached class loader: /system/framework/android.test.base.jar
08-25 06:13:21.072 D/ApplicationLoaders(24343): Returning zygote-cached class loader: /system_ext/framework/androidx.window.extensions.jar
08-25 06:13:21.079 D/nativeloader(24343): Configuring clns-10 for other apk /data/app/~~RCozkHdGq47v2PK9XPgslw==/com.google.android.webview-jR8uUOFtzWjlUhSoRHRmNQ==/base.apk. target_sdk_version=36, uses_libraries=, library_path=/data/app/~~RCozkHdGq47v2PK9XPgslw==/com.google.android.webview-jR8uUOFtzWjlUhSoRHRmNQ==/lib/arm64:/data/app/~~RCozkHdGq47v2PK9XPgslw==/com.google.android.webview-jR8uUOFtzWjlUhSoRHRmNQ==/base.apk!/lib/arm64-v8a, permitted_path=/data:/mnt/expand
08-25 06:13:21.104 I/cr_WVCFactoryProvider(24343): version=151.0.7922.169 (792216903) minSdkVersion=29 multiprocess=true packageId=2 splits=<none>
08-25 06:13:21.108 D/nativeloader(24343): Load /data/app/~~RCozkHdGq47v2PK9XPgslw==/com.google.android.webview-jR8uUOFtzWjlUhSoRHRmNQ==/base.apk!/lib/arm64-v8a/libwebviewchromium.so using class loader ns clns-10 (caller=/data/app/~~RCozkHdGq47v2PK9XPgslw==/com.google.android.webview-jR8uUOFtzWjlUhSoRHRmNQ==/base.apk): ok
08-25 06:13:21.110 D/nativeloader(24343): Load /system/lib64/libwebviewchromium_plat_support.so using class loader ns clns-10 (caller=/data/app/~~RCozkHdGq47v2PK9XPgslw==/com.google.android.webview-jR8uUOFtzWjlUhSoRHRmNQ==/base.apk): ok
08-25 06:13:21.113 I/chromium(24343): [0825/061321.113122:INFO:android_webview/browser/variations/variations_seed_loader.cc:67] Failed to open file for reading.: No such file or directory (2)
08-25 06:13:21.116 I/cr_LibraryLoader(24343): Successfully loaded native library
08-25 06:13:21.117 I/cr_CachingUmaRecorder(24343): Flushed 39 samples from 19 histograms, 0 samples were dropped.
08-25 06:13:21.512 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:13:21.513 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:13:23.733 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:13:23.734 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:13:23.902 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:13:23.904 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:13:28.450 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:13:28.484 I/cr_ChildProcLH(24343): ScopedServiceBindingBatch.tryActivate: false
08-25 06:13:28.487 I/cr_CombinedPProvider(24343): #registerProvider() provider:WV.sj@2f87877 isPolicyCacheEnabled:false policyProvidersSize:0
08-25 06:13:28.487 I/cr_PolicyProvider(24343): #setManagerAndSource() 0
08-25 06:13:28.488 I/cr_policy(24343): registerReceiver succeeded after 1ms
08-25 06:13:28.489 I/cr_DisplayManager(24343): Is Display Topology available: false
08-25 06:13:28.503 I/cr_CombinedPProvider(24343): #linkNativeInternal() 1
08-25 06:13:28.504 I/cr_AppResProvider(24343): #getApplicationRestrictionsFromUserManager() Bundle[EMPTY_PARCEL]
08-25 06:13:28.504 I/cr_PolicyProvider(24343): #notifySettingsAvailable() 0
08-25 06:13:28.504 I/cr_CombinedPProvider(24343): #onSettingsAvailable() 0
08-25 06:13:28.504 I/cr_CombinedPProvider(24343): #flushPolicies()
08-25 06:13:28.533 W/chromium(24343): [WARNING:android_webview/browser/cookie_manager.cc:372] Transferring cookies from provisional CookieManager to network service. For issues with the provisional CookieManager, see crbug.com/478873476.
08-25 06:13:28.573 W/cr_media(24343): BLUETOOTH_CONNECT permission is missing.
08-25 06:13:28.573 W/cr_media(24343): getBluetoothAdapter() requires BLUETOOTH permission
08-25 06:13:28.573 W/cr_media(24343): registerBluetoothIntentsIfNeeded: Requires BLUETOOTH permission
08-25 06:13:28.576 D/AudioSystem(24343): onNewService: media.audio_policy service obtained 0xb40000730a10d870
08-25 06:13:28.577 D/AudioSystem(24343): getService: IAudioPolicyService retrieved: 0xb40000730a10d870  cached: 0xb40000730a10d870
08-25 06:13:28.581 V/XGL     (24343): ----------------------------------------------------------------------
08-25 06:13:28.581 V/XGL     (24343): SUMD version compiled date     = 2026-01-09 09:57 - KST
08-25 06:13:28.581 V/XGL     (24343): SUMD version revision number   = 1900168dcb
08-25 06:13:28.581 V/XGL     (24343): SUMD version info              = Driver version: 24.0.534, git hash: 1900168dcb
08-25 06:13:28.581 V/XGL     (24343): ----------------------------------------------------------------------
08-25 06:13:28.581 V/XGL     (24343): Entering: Create
08-25 06:13:28.585 V/XGL     (24343): Exiting: Create
08-25 06:13:28.586 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{e134e6f VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:13:28.587 V/XGL     (24343): ----------------------------------------------------------------------
08-25 06:13:28.588 V/XGL     (24343): SUMD version compiled date     = 2026-01-09 09:57 - KST
08-25 06:13:28.588 V/XGL     (24343): SUMD version revision number   = 1900168dcb
08-25 06:13:28.588 V/XGL     (24343): SUMD version info              = Driver version: 24.0.534, git hash: 1900168dcb
08-25 06:13:28.588 V/XGL     (24343): ----------------------------------------------------------------------
08-25 06:13:28.588 V/XGL     (24343): Entering: Create
08-25 06:13:28.590 V/XGL     (24343): Exiting: Create
08-25 06:13:28.592 I/vulkan  (24343): CreateInfoWrapper::FilterExtension: already have 'VK_KHR_external_fence_fd'.
08-25 06:13:28.597 I/ANGLE   (24343): Version (24.1.307 git hash: 86f99cfe6317), Renderer ((Samsung Xclipse 940) on Vulkan 1.3.279)
08-25 06:13:28.599 W/libEGL  (24343): ANGLE Warn:DisplayVk.cpp:115 (LoadPipelineCacheDataFromDisk): Failed to load pipeline blob cache data from disk. Performance may degrade.
08-25 06:13:28.615 V/XGL     (24343): ----------------------------------------------------------------------
08-25 06:13:28.616 V/XGL     (24343): SUMD version compiled date     = 2026-01-09 09:57 - KST
08-25 06:13:28.616 V/XGL     (24343): SUMD version revision number   = 1900168dcb
08-25 06:13:28.616 V/XGL     (24343): SUMD version info              = Driver version: 24.0.534, git hash: 1900168dcb
08-25 06:13:28.616 V/XGL     (24343): ----------------------------------------------------------------------
08-25 06:13:28.616 V/XGL     (24343): Entering: Create
08-25 06:13:28.619 V/XGL     (24343): Exiting: Create
08-25 06:13:28.626 I/CameraManagerGlobal(24343): Connecting to camera service
08-25 06:13:28.627 D/VendorTagDescriptor(24343): addVendorDescriptor: vendor tag id 15622750491770684145 added
08-25 06:13:28.628 I/cr_AppResProvider(24343): #getApplicationRestrictionsFromUserManager() Bundle[EMPTY_PARCEL]
08-25 06:13:28.628 I/cr_PolicyProvider(24343): #notifySettingsAvailable() 0
08-25 06:13:28.628 I/cr_CombinedPProvider(24343): #onSettingsAvailable() 0
08-25 06:13:28.628 I/cr_CombinedPProvider(24343): #flushPolicies()
08-25 06:13:28.629 D/VendorTagDescriptor(24343): addVendorDescriptor: vendor tag id 8932615658386372252 added
08-25 06:13:28.632 I/CameraManagerGlobal(24343): Camera 0 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client com.huawei.health API Level 1 User Id 0Device Id 0
08-25 06:13:28.632 I/CameraManagerGlobal(24343): Camera 1 facing CAMERA_FACING_FRONT state now CAMERA_STATE_CLOSED for client com.samsung.android.smartface API Level 2 User Id 0Device Id 0
08-25 06:13:28.632 I/CameraManagerGlobal(24343): Camera 2 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client android.system API Level 2 User Id 0Device Id 0
08-25 06:13:28.632 I/CameraManagerGlobal(24343): Camera 20 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client com.sec.android.app.camera API Level 2 User Id 0Device Id 0
08-25 06:13:28.632 I/CameraManager(24343): registerAvailabilityCallback: Is device callback = false
08-25 06:13:28.633 I/CameraManagerGlobal(24343): postSingleUpdate device: camera id 0 status STATUS_PRESENT
08-25 06:13:28.633 I/CameraManagerGlobal(24343): postSingleUpdate device: camera id 1 status STATUS_PRESENT
08-25 06:13:28.633 I/CameraManagerGlobal(24343): postSingleUpdate device: camera id 2 status STATUS_PRESENT
08-25 06:13:28.633 I/CameraManagerGlobal(24343): postSingleUpdate device: camera id 3 status STATUS_PRESENT
08-25 06:13:28.633 I/CameraManagerGlobal(24343): Camera 21 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client com.sec.android.app.camera API Level 2 User Id 0Device Id 0
08-25 06:13:28.633 I/CameraManagerGlobal(24343): Camera 23 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client com.sec.android.app.camera API Level 2 User Id 0Device Id 0
08-25 06:13:28.634 I/CameraManagerGlobal(24343): Camera 3 facing CAMERA_FACING_FRONT state now CAMERA_STATE_CLOSED for client com.samsung.android.sead API Level 2 User Id 0Device Id 0
08-25 06:13:28.634 I/CameraManagerGlobal(24343): Camera 4 facing CAMERA_FACING_FRONT state now CAMERA_STATE_CLOSED for client client.pid<1256> API Level 2 User Id 0Device Id 0
08-25 06:13:28.634 I/CameraManagerGlobal(24343): Camera 52 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client android.system API Level 2 User Id 0Device Id 0
08-25 06:13:28.634 I/CameraManagerGlobal(24343): Camera 56 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client android.system API Level 2 User Id 0Device Id 0
08-25 06:13:28.634 I/CameraManagerGlobal(24343): Camera 58 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client android.system API Level 2 User Id 0Device Id 0
08-25 06:13:28.658 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{e134e6f VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:13:28.658 W/AudioCapabilities(24343): Unsupported mediaType audio/x-ape
08-25 06:13:28.659 W/AudioCapabilities(24343): Unsupported mediaType audio/x-ima
08-25 06:13:28.660 W/AudioCapabilities(24343): Unsupported mediaType audio/mpeg-L1
08-25 06:13:28.660 W/AudioCapabilities(24343): Unsupported mediaType audio/mpeg-L2
08-25 06:13:28.660 W/VideoCapabilities(24343): Unsupported mime video/wvc1
08-25 06:13:28.661 W/VideoCapabilities(24343): Unsupported mime video/x-ms-wmv
08-25 06:13:28.682 W/VideoCapabilities(24343): Unrecognized profile/level 32768/256 for video/mp4v-es
08-25 06:13:28.694 W/AudioCapabilities(24343): Unsupported mediaType audio/x-ape
08-25 06:13:28.694 W/AudioCapabilities(24343): Unsupported mediaType audio/x-ima
08-25 06:13:28.695 W/AudioCapabilities(24343): Unsupported mediaType audio/mpeg-L1
08-25 06:13:28.695 W/AudioCapabilities(24343): Unsupported mediaType audio/mpeg-L2
08-25 06:13:28.695 W/VideoCapabilities(24343): Unsupported mime video/wvc1
08-25 06:13:28.696 W/VideoCapabilities(24343): Unsupported mime video/x-ms-wmv
08-25 06:13:28.706 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{e134e6f VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:13:28.716 W/VideoCapabilities(24343): Unrecognized profile/level 32768/256 for video/mp4v-es
08-25 06:13:28.723 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{e134e6f VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:13:28.731 W/AudioCapabilities(24343): Unsupported mime audio/x-ape
08-25 06:13:28.731 W/AudioCapabilities(24343): Unsupported mime audio/x-ima
08-25 06:13:28.731 W/AudioCapabilities(24343): Unsupported mime audio/mpeg-L1
08-25 06:13:28.731 W/AudioCapabilities(24343): Unsupported mime audio/mpeg-L2
08-25 06:13:28.732 W/VideoCapabilities(24343): Unsupported mime video/wvc1
08-25 06:13:28.732 W/VideoCapabilities(24343): Unsupported mime video/x-ms-wmv
08-25 06:13:28.738 W/VideoCapabilities(24343): Unrecognized profile/level 32768/256 for video/mp4v-es
08-25 06:13:28.740 W/VideoCapabilities(24343): Unsupported mime video/wvc1
08-25 06:13:28.809 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{e134e6f VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:13:36.169 I/WindowManager(24343): WindowManagerGlobal#addView, ty=1002, view=androidx.compose.ui.window.PopupLayout{a9eceff V.E...... ......I. 0,0-0,0 #1020002 android:id/content}, caller=android.view.WindowManagerImpl.addView:167 androidx.compose.ui.window.AndroidPopup_androidKt$Popup$2$1.invoke:196 androidx.compose.runtime.DisposableEffectImpl.onRemembered:4 
08-25 06:13:36.170 D/ViewRootImpl(24343): desktopMode is false
08-25 06:13:36.170 I/ViewRootImpl(24343): dVRR is disabled
08-25 06:13:36.174 D/NativeCustomFrequencyManager(24343): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-25 06:13:36.194 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.compose.ui.window.Api33Impl$$ExternalSyntheticLambda0@c01efd0
08-25 06:13:36.207 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:13:36.208 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:13:37.438 I/Dialog  (24343): mIsDeviceDefault = false, mIsSamsungBasicInteraction = false, isMetaDataInActivity = false
08-25 06:13:37.443 I/DecorView(24343): setWindowBackground: isPopOver=false color=0 d=android.graphics.drawable.ColorDrawable@51f0a7c
08-25 06:13:37.451 I/WindowManager(24343): WindowManagerGlobal#addView, ty=2, view=com.android.internal.policy.DecorView{cb12598 V.E...... R.....I. 0,0-0,0}[MainActivity], caller=android.view.WindowManagerImpl.addView:167 android.app.Dialog.show:544 androidx.compose.ui.window.DialogWrapper$2.invoke:9 
08-25 06:13:37.451 D/ViewRootImpl(24343): desktopMode is false
08-25 06:13:37.451 I/ViewRootImpl(24343): dVRR is disabled
08-25 06:13:37.451 D/NativeCustomFrequencyManager(24343): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-25 06:13:37.457 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Dialog$$ExternalSyntheticLambda4@3fd7e29
08-25 06:13:37.457 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@c1565ae
08-25 06:13:37.472 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:13:37.473 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:13:37.533 I/WindowManager(24343): WindowManagerGlobal#removeView, ty=1002, view=androidx.compose.ui.window.PopupLayout{a9eceff V.E...... ......ID 0,0-555,224 #1020002 android:id/content aid=1073741826}, caller=android.view.WindowManagerGlobal.removeView:654 android.view.WindowManagerImpl.removeViewImmediate:254 androidx.activity.compose.BackHandlerKt$BackHandler$2$1$invoke$$inlined$onDispose$1.dispose:31 
08-25 06:13:37.534 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): null
08-25 06:13:49.851 W/RemoteInputConnectionImpl(24343): requestCursorUpdates on inactive InputConnection
08-25 06:13:49.868 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.view.ImeBackAnimationController@c1a015e
08-25 06:14:10.889 W/.frodo21.reader(24343): Missing inline cache for java.lang.Object androidx.activity.OnBackPressedDispatcher$addCallback$1.invoke()
08-25 06:14:24.215 I/WindowManager(24343): WindowManagerGlobal#addView, ty=1002, view=androidx.compose.ui.window.PopupLayout{b9aaf8d V.E...... ......I. 0,0-0,0 #1020002 android:id/content}, caller=android.view.WindowManagerImpl.addView:167 androidx.compose.ui.window.AndroidPopup_androidKt$Popup$2$1.invoke:196 androidx.compose.runtime.DisposableEffectImpl.onRemembered:4 
08-25 06:14:24.215 D/ViewRootImpl(24343): desktopMode is false
08-25 06:14:24.215 I/ViewRootImpl(24343): dVRR is disabled
08-25 06:14:24.215 D/NativeCustomFrequencyManager(24343): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-25 06:14:24.226 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.compose.ui.window.Api33Impl$$ExternalSyntheticLambda0@ab20666
08-25 06:14:24.235 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:14:24.236 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:14:25.869 I/WindowManager(24343): WindowManagerGlobal#removeView, ty=1002, view=androidx.compose.ui.window.PopupLayout{b9aaf8d V.E...... ......ID 0,0-72,88 #1020002 android:id/content}, caller=android.view.WindowManagerGlobal.removeView:654 android.view.WindowManagerImpl.removeViewImmediate:254 androidx.activity.compose.BackHandlerKt$BackHandler$2$1$invoke$$inlined$onDispose$1.dispose:31 
08-25 06:14:25.869 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): null
08-25 06:14:30.643 I/WindowManager(24343): WindowManagerGlobal#addView, ty=1002, view=androidx.compose.ui.window.PopupLayout{c541f8b V.E...... ......I. 0,0-0,0 #1020002 android:id/content}, caller=android.view.WindowManagerImpl.addView:167 androidx.compose.ui.window.AndroidPopup_androidKt$Popup$2$1.invoke:196 androidx.compose.runtime.DisposableEffectImpl.onRemembered:4 
08-25 06:14:30.643 D/ViewRootImpl(24343): desktopMode is false
08-25 06:14:30.643 I/ViewRootImpl(24343): dVRR is disabled
08-25 06:14:30.644 D/NativeCustomFrequencyManager(24343): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-25 06:14:30.653 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.compose.ui.window.Api33Impl$$ExternalSyntheticLambda0@3e6d0ac
08-25 06:14:30.659 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:14:30.659 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:14:32.454 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:14:32.456 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:14:32.457 D/NativeCustomFrequencyManager(24343): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-25 06:14:37.315 I/WindowManager(24343): WindowManagerGlobal#removeView, ty=1002, view=androidx.compose.ui.window.PopupLayout{c541f8b V.E...... ......ID 0,0-72,88 #1020002 android:id/content}, caller=android.view.WindowManagerGlobal.removeView:654 android.view.WindowManagerImpl.removeViewImmediate:254 androidx.activity.compose.BackHandlerKt$BackHandler$2$1$invoke$$inlined$onDispose$1.dispose:31 
08-25 06:14:37.315 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): null
08-25 06:14:38.303 I/WindowManager(24343): WindowManagerGlobal#addView, ty=1002, view=androidx.compose.ui.window.PopupLayout{27198db V.E...... ......I. 0,0-0,0 #1020002 android:id/content}, caller=android.view.WindowManagerImpl.addView:167 androidx.compose.ui.window.AndroidPopup_androidKt$Popup$2$1.invoke:196 androidx.compose.runtime.DisposableEffectImpl.onRemembered:4 
08-25 06:14:38.303 D/ViewRootImpl(24343): desktopMode is false
08-25 06:14:38.304 I/ViewRootImpl(24343): dVRR is disabled
08-25 06:14:38.305 D/NativeCustomFrequencyManager(24343): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-25 06:14:38.315 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.compose.ui.window.Api33Impl$$ExternalSyntheticLambda0@95e2abc
08-25 06:14:38.322 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:14:38.323 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:14:43.640 I/WindowManager(24343): WindowManagerGlobal#removeView, ty=1002, view=androidx.compose.ui.window.PopupLayout{27198db V.E...... ......ID 0,0-72,88 #1020002 android:id/content}, caller=android.view.WindowManagerGlobal.removeView:654 android.view.WindowManagerImpl.removeViewImmediate:254 androidx.activity.compose.BackHandlerKt$BackHandler$2$1$invoke$$inlined$onDispose$1.dispose:31 
08-25 06:14:43.640 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): null
08-25 06:15:06.464 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{e134e6f VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:15:06.744 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@c1565ae
08-25 06:15:06.745 D/CompatChangeReporter(24343): Compat change id reported: 395521150; UID 10606; state: ENABLED

```
