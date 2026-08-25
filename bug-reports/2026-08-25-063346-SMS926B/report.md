# Hlásenie problému s článkom

- **čas:** 2026-08-25 06:33:46
- **titulok:** Jak probíhal vývoj pro osmibitová Atari před 45 lety? - Root.cz
- **odkaz:** https://www.root.cz/clanky/jak-probihal-vyvoj-pro-osmibitova-atari-pred-45-lety/?utm_source=rss&utm_medium=text&utm_campaign=rss
- **verzia:** 0.1.107 (107)
- **zariadenie:** samsung SM-S926B, Android 16

## Popis problému od používateľa

root.cz nemá obsah - prečo? RSS feed nic z článku okrem nadpisu neobsahuje? rozparsuj všetko čo mametk dispozícii

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
RAM:         11203 MB celkom, 3075 MB voľných

=== denník aplikácie ===
08-25 06:11:23.743 [logy] odoslané ako 2026-08-25-061121-SMS926B-auto.txt
08-25 06:11:33.078 [app] štart, verzia 0.1.107
08-25 06:11:33.161 [update] výsledok inštalácie: 0
08-25 06:11:33.163 [update] zmazaný balík briefly-107.apk
08-25 06:13:23.676 [nahlad] dotiahnutych 2 nahladov z 2 clankov
08-25 06:15:11.242 [hlásenie] problém odoslaný do bug-reports/2026-08-25-061506-SMS926B
08-25 06:15:25.378 [hero] 97a5cdadb8f59839dafdbcfe5996df4c nahlad=file:///data/user/0/sk.frodo21.reader/files/articles/97a5cdadb8f59839dafdbcfe5996df4c/900.img obrazkov=0/0
08-25 06:15:42.925 [zhrnutie] spúšťam: GEMINI, kľúč 53 znakov, model gemini-3.1-flash-lite
08-25 06:15:46.066 [zhrnutie] gemini odpovedal za 3139 ms
08-25 06:16:30.433 [hero] 581dfb804e6917197fc010764478d9a9 stranka neponuka og:image ani twitter:image
08-25 06:16:30.433 [hero] 581dfb804e6917197fc010764478d9a9 nahlad=ziadny obrazkov=0/0
08-25 06:17:41.845 [hlásenie] problém odoslaný do bug-reports/2026-08-25-061737-SMS926B
08-25 06:17:47.001 [zhrnutie] spúšťam: GEMINI, kľúč 53 znakov, model gemini-3.1-flash-lite
08-25 06:17:50.240 [zhrnutie] gemini odpovedal za 3237 ms
08-25 06:18:32.614 [hero] 7ae2752d3acebc640f79bc6601e9ff86 nahlad=file:///data/user/0/sk.frodo21.reader/files/articles/7ae2752d3acebc640f79bc6601e9ff86/900.png obrazkov=0/0
08-25 06:18:51.928 [zhrnutie] spúšťam: GEMINI, kľúč 53 znakov, model gemini-3.1-flash-lite
08-25 06:18:55.724 [zhrnutie] gemini odpovedal za 3795 ms
08-25 06:19:17.836 [hero] 73fe1ce4ca45d5a0aa6e08f88e52b752 nahlad=file:///data/user/0/sk.frodo21.reader/files/articles/73fe1ce4ca45d5a0aa6e08f88e52b752/900.img obrazkov=0/0
08-25 06:20:01.158 [zhrnutie] spúšťam: GEMINI, kľúč 53 znakov, model gemini-3.1-flash-lite
08-25 06:20:04.440 [zhrnutie] gemini odpovedal za 3281 ms
08-25 06:20:30.952 [hero] 11388a4dcd93130863e3def85ccd29b9 nahlad=file:///data/user/0/sk.frodo21.reader/files/articles/11388a4dcd93130863e3def85ccd29b9/900.img obrazkov=0/0
08-25 06:21:58.752 [nahlad] dotiahnutych 1 nahladov z 1 clankov
08-25 06:24:29.999 [hero] c717e65a544120177c4267321a13a1cd stranka neponuka og:image ani twitter:image
08-25 06:24:30.000 [hero] c717e65a544120177c4267321a13a1cd nahlad=ziadny obrazkov=0/0
08-25 06:25:08.053 [hero] 093d67fc9f7775ecc8c8f86d71ba58fa nahlad=file:///data/user/0/sk.frodo21.reader/files/articles/093d67fc9f7775ecc8c8f86d71ba58fa/900.png obrazkov=0/0
08-25 06:26:37.907 [hero] f7c67cf4fdd3da810c68df124e7a0f62 nahlad=file:///data/user/0/sk.frodo21.reader/files/articles/f7c67cf4fdd3da810c68df124e7a0f62/900.jpg obrazkov=0/0
08-25 06:31:25.098 [zhrnutie] spúšťam: GEMINI, kľúč 53 znakov, model gemini-3.1-flash-lite
08-25 06:31:28.418 [zhrnutie] gemini odpovedal za 3318 ms
08-25 06:31:59.659 [hero] 60fee0469cb4f6eee61eaa76081fb88a stranka neponuka og:image ani twitter:image
08-25 06:31:59.659 [hero] 60fee0469cb4f6eee61eaa76081fb88a nahlad=ziadny obrazkov=0/0


=== logcat ===
08-25 06:25:34.398 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.414 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.431 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.447 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.465 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.481 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.498 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.650 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.882 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.899 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.914 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.930 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.946 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.964 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:34.980 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:35.000 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:35.013 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:35.030 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:35.047 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:35.063 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:35.080 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:35.097 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:35.114 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:35.131 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:35.146 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{6775d47 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:25:35.581 D/WindowOnBackDispatcher(24343): onBackInvoked, callback=androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:25:35.603 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@dc04411
08-25 06:25:41.813 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:41.814 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:41.926 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:41.927 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:41.947 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:41.948 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:42.124 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:42.128 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:42.139 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:42.140 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:42.151 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:42.152 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:42.457 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:42.458 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:42.636 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:42.637 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:42.999 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:43.000 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:43.645 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:43.647 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:43.731 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:43.731 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:47.556 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:47.559 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:47.900 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:47.901 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.102 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.103 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.224 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.225 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.409 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.411 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.514 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.518 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.540 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.544 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.631 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.633 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.667 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.669 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.701 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:48.703 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:51.538 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:51.539 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:51.546 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:51.547 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:59.982 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:25:59.984 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:00.747 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:00.748 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:25.270 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.view.ImeBackAnimationController@944b648
08-25 06:26:26.712 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:26.713 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:26.836 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:26.837 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:26.841 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:26.842 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:27.570 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:27.571 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:27.902 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:27.903 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:27.909 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:27.910 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:27.911 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:27.911 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:30.321 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@dc04411
08-25 06:26:36.606 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:26:37.816 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:37.817 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:37.886 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:26:37.953 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:38.016 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:38.055 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:38.190 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.294 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.309 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.324 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.343 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.358 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.375 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.391 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.409 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.424 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.441 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.460 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.475 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.494 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.511 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.526 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.643 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.660 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.676 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.693 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.710 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.725 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.743 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:39.759 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.158 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.174 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.190 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.207 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.224 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.240 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.258 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.274 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.290 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.308 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.324 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.341 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.357 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.374 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.391 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.407 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.460 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:40.565 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:41.207 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:41.224 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:26:41.261 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@dc04411
08-25 06:26:41.304 D/BBA2    (24343): setIsFg isFg = false; delayValue 3999ms
08-25 06:31:19.129 D/ViewRootImpl(24343): Skipping stats log for color mode
08-25 06:31:19.141 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:31:19.151 V/XGL     (24343): ----------------------------------------------------------------------
08-25 06:31:19.151 V/XGL     (24343): SUMD version compiled date     = 2026-01-09 09:57 - KST
08-25 06:31:19.151 V/XGL     (24343): SUMD version revision number   = 1900168dcb
08-25 06:31:19.151 V/XGL     (24343): SUMD version info              = Driver version: 24.0.534, git hash: 1900168dcb
08-25 06:31:19.151 V/XGL     (24343): ----------------------------------------------------------------------
08-25 06:31:19.151 V/XGL     (24343): Entering: Create
08-25 06:31:19.168 V/XGL     (24343): Exiting: Create
08-25 06:31:19.180 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:31:19.181 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:31:19.229 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:19.238 I/.frodo21.reader(24343): CollectorTransition concurrent mark compact GC freed 13MB AllocSpace bytes, 86(7360KB) LOS objects, 66% free, 19MB/58MB, paused 322us,2.200ms total 134.005ms
08-25 06:31:19.283 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:19.339 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.view.ImeBackAnimationController@944b648
08-25 06:31:19.346 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:20.033 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:31:20.034 D/WindowOnBackDispatcher(24343): onBackInvoked, callback=android.view.ImeBackAnimationController@944b648
08-25 06:31:21.868 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:21.892 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:21.905 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:21.918 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:21.933 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:21.950 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:21.969 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:21.983 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:21.999 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.018 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.033 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.050 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.065 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.084 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.101 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.115 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.132 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.150 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.165 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.184 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.199 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.215 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.233 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.248 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.267 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.282 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.299 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.315 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.616 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.634 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.649 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.666 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.682 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.698 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.715 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.733 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.750 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.767 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.783 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.801 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.819 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.837 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.853 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.868 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.884 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:22.902 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:24.484 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:28.807 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.726 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.744 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.759 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.775 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.791 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.807 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.824 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.842 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.859 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.874 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.890 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.908 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.925 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.940 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.961 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.974 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:29.991 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.195 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.209 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.226 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.242 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.259 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.275 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.292 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.309 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.326 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.341 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.377 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.392 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.427 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.441 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.459 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.476 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.529 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.543 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.560 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.576 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.593 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.977 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:30.994 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.010 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.028 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.043 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.195 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.294 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.310 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.327 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.343 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.360 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.379 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.429 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.512 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.527 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.561 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.577 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.594 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.611 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.644 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.661 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.677 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.695 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.710 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.763 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.811 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.828 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.912 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.928 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.961 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.977 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:31.994 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.012 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.028 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.079 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.095 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.159 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.175 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.208 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.225 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.242 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.259 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.662 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.678 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.693 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.710 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.729 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.745 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.762 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.778 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.794 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.810 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.827 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.844 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.860 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.877 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.894 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{5ddc330 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:32.903 D/WindowOnBackDispatcher(24343): onBackInvoked, callback=androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:31:32.914 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@dc04411
08-25 06:31:48.806 D/BBA2    (24343): setIsFg isFg = false; delayValue 3999ms
08-25 06:31:49.692 D/ViewRootImpl(24343): Skipping stats log for color mode
08-25 06:31:49.717 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:31:49.718 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:31:50.787 W/RemoteInputConnectionImpl(24343): requestCursorUpdates on inactive InputConnection
08-25 06:31:50.787 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.view.ImeBackAnimationController@944b648
08-25 06:31:52.106 W/JobService(24343): onNetworkChanged() not implemented in androidx.work.impl.background.systemjob.SystemJobService. Must override in a subclass.
08-25 06:31:53.245 I/WM-WorkerWrapper(24343): Worker result SUCCESS for Work [ id=7bd02c2b-c5a9-4d74-9b3a-3f85181e9af9, tags={ sk.frodo21.reader.work.RefreshWorker } ]
08-25 06:31:54.019 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:31:54.020 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:31:57.230 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@dc04411
08-25 06:31:59.098 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:31:59.731 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{f838f1d VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:59.765 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{f838f1d VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:59.797 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{f838f1d VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:59.833 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{f838f1d VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:31:59.983 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{f838f1d VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:01.218 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{f838f1d VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:01.250 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{f838f1d VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:01.317 D/WindowOnBackDispatcher(24343): onBackInvoked, callback=androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:32:01.339 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@dc04411
08-25 06:32:10.098 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:32:10.389 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:32:10.391 I/Kumiho-Kumiho(24343): getPackageName: sk.frodo21.reader
08-25 06:32:12.625 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : warmUpIntegrityToken(608683999913)
08-25 06:32:12.626 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : Initiate binding to the service.
08-25 06:32:12.638 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : ServiceConnectionImpl.onServiceConnected(ComponentInfo{com.android.vending/com.google.android.finsky.expressintegrityservice.ExpressIntegrityService})
08-25 06:32:12.638 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : linkToDeath
08-25 06:32:13.074 I/PlayCore(24343): UID: [10606]  PID: [24343] OnWarmUpIntegrityTokenCallback : onWarmUpExpressIntegrityToken
08-25 06:32:13.074 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : Unbind from service.
08-25 06:32:13.151 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : requestExpressIntegrityToken(-5167749316048473341)
08-25 06:32:13.151 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : Initiate binding to the service.
08-25 06:32:13.156 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : ServiceConnectionImpl.onServiceConnected(ComponentInfo{com.android.vending/com.google.android.finsky.expressintegrityservice.ExpressIntegrityService})
08-25 06:32:13.156 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : linkToDeath
08-25 06:32:13.161 I/PlayCore(24343): UID: [10606]  PID: [24343] OnRequestIntegrityTokenCallback : onRequestExpressIntegrityToken
08-25 06:32:13.161 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : Unbind from service.
08-25 06:32:14.564 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : warmUpIntegrityToken(187810013193)
08-25 06:32:14.564 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : Initiate binding to the service.
08-25 06:32:14.568 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : ServiceConnectionImpl.onServiceConnected(ComponentInfo{com.android.vending/com.google.android.finsky.expressintegrityservice.ExpressIntegrityService})
08-25 06:32:14.568 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : linkToDeath
08-25 06:32:14.690 I/PlayCore(24343): UID: [10606]  PID: [24343] OnWarmUpIntegrityTokenCallback : onWarmUpExpressIntegrityToken
08-25 06:32:14.690 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : Unbind from service.
08-25 06:32:14.889 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : requestExpressIntegrityToken(-1382625569833633765)
08-25 06:32:14.890 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : Initiate binding to the service.
08-25 06:32:14.896 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : ServiceConnectionImpl.onServiceConnected(ComponentInfo{com.android.vending/com.google.android.finsky.expressintegrityservice.ExpressIntegrityService})
08-25 06:32:14.896 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : linkToDeath
08-25 06:32:14.901 I/PlayCore(24343): UID: [10606]  PID: [24343] OnRequestIntegrityTokenCallback : onRequestExpressIntegrityToken
08-25 06:32:14.901 I/PlayCore(24343): UID: [10606]  PID: [24343] StandardIntegrity : Unbind from service.
08-25 06:32:15.218 W/chromium(24343): [WARNING:android_webview/browser/aw_contents_io_thread_client.cc:444] No IoThreadClient associated with parent RenderFrameHost.
08-25 06:32:15.219 W/chromium(24343): [WARNING:android_webview/browser/aw_contents_io_thread_client.cc:444] No IoThreadClient associated with parent RenderFrameHost.
08-25 06:32:15.224 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1573a76 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:15.246 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1573a76 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:15.259 W/chromium(24343): [WARNING:android_webview/browser/aw_contents_io_thread_client.cc:444] No IoThreadClient associated with parent RenderFrameHost.
08-25 06:32:15.380 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1573a76 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:15.397 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1573a76 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:15.464 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1573a76 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:23.746 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1573a76 VFEDHVC.. .F...... 0,0-1440,2769 aid=1073741834}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:24.899 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@dc04411
08-25 06:32:24.914 D/BBA2    (24343): setIsFg isFg = false; delayValue 3999ms
08-25 06:32:47.368 D/ViewRootImpl(24343): Skipping stats log for color mode
08-25 06:32:47.369 D/BBA2    (24343): setIsFg isFg = true
08-25 06:32:47.370 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@f57ec1f
08-25 06:32:47.410 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:32:47.411 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:32:47.420 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1573a76 VFEDHVC.. .F...... 0,0-1440,2769 aid=1073741834}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:47.490 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1573a76 VFEDHVC.. .F...... 0,0-1440,2769 aid=1073741834}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:47.499 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1573a76 VFEDHVC.. .F...... 0,0-1440,2769 aid=1073741834}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:47.515 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1573a76 VFEDHVC.. .F...... 0,0-1440,2769 aid=1073741834}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:32:50.587 I/WindowManager(24343): WindowManagerGlobal#addView, ty=1002, view=androidx.compose.ui.window.PopupLayout{780c5de V.E...... ......I. 0,0-0,0 #1020002 android:id/content}, caller=android.view.WindowManagerImpl.addView:167 androidx.compose.ui.window.AndroidPopup_androidKt$Popup$2$1.invoke:196 androidx.compose.runtime.DisposableEffectImpl.onRemembered:4 
08-25 06:32:50.587 D/ViewRootImpl(24343): desktopMode is false
08-25 06:32:50.588 I/ViewRootImpl(24343): dVRR is disabled
08-25 06:32:50.593 D/NativeCustomFrequencyManager(24343): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-25 06:32:50.605 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.compose.ui.window.Api33Impl$$ExternalSyntheticLambda0@1a35c53
08-25 06:32:50.617 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:32:50.618 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:32:51.625 I/Dialog  (24343): mIsDeviceDefault = false, mIsSamsungBasicInteraction = false, isMetaDataInActivity = false
08-25 06:32:51.630 I/DecorView(24343): setWindowBackground: isPopOver=false color=0 d=android.graphics.drawable.ColorDrawable@766122f
08-25 06:32:51.636 I/WindowManager(24343): WindowManagerGlobal#addView, ty=2, view=com.android.internal.policy.DecorView{5adb43b V.E...... R.....I. 0,0-0,0}[MainActivity], caller=android.view.WindowManagerImpl.addView:167 android.app.Dialog.show:544 androidx.compose.ui.window.DialogWrapper$2.invoke:9 
08-25 06:32:51.636 D/ViewRootImpl(24343): desktopMode is false
08-25 06:32:51.637 I/ViewRootImpl(24343): dVRR is disabled
08-25 06:32:51.637 D/NativeCustomFrequencyManager(24343): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-25 06:32:51.644 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.app.Dialog$$ExternalSyntheticLambda4@d5a4970
08-25 06:32:51.645 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@e7194e9
08-25 06:32:51.665 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:32:51.667 W/libc    (24343): Access denied finding property "vendor.perf.ems.egg"
08-25 06:32:51.720 I/WindowManager(24343): WindowManagerGlobal#removeView, ty=1002, view=androidx.compose.ui.window.PopupLayout{780c5de V.E...... ......ID 0,0-555,224 #1020002 android:id/content aid=1073741835}, caller=android.view.WindowManagerGlobal.removeView:654 android.view.WindowManagerImpl.removeViewImmediate:254 androidx.activity.compose.BackHandlerKt$BackHandler$2$1$invoke$$inlined$onDispose$1.dispose:31 
08-25 06:32:51.721 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): null
08-25 06:33:00.200 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): android.view.ImeBackAnimationController@d83c159
08-25 06:33:11.019 W/.frodo21.reader(24343): Missing inline cache for java.lang.Object kotlinx.coroutines.JobKt__JobKt$invokeOnCompletion$1.invoke(java.lang.Object)
08-25 06:33:46.271 I/View    (24343): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1573a76 VFEDHVC.. .F...... 0,0-1440,2769 aid=1073741834}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-25 06:33:46.542 D/WindowOnBackDispatcher(24343): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@e7194e9

```
