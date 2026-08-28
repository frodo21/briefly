# Hlásenie problému s článkom

- **čas:** 2026-08-28 19:44:30
- **titulok:** Správy Google
- **odkaz:** https://news.google.com/rss/articles/CBMiigFBVV95cUxQVEZGY19HTGVNazduTHlGeC1mNXRBams0bTdKa3F5QmxCM1VqTWhUTFZLaF85aE91WGdrU1J6eHk2X1kyTkFESFBQMWpuOUxGUk10aUM0TlBNX1hoNGEwTTlDb0R0WjBDWldpajFMa01Kd1VxQnFHNXNKZTVVaTVvNGhSc1ctemNyWHc?oc=5
- **verzia:** 0.1.122 (122)
- **zariadenie:** samsung SM-S926B, Android 16

## Popis problému od používateľa

článok sa vôbec nenancital

## Prílohy

- `page.html` — zobrazený obsah článku v readeri
- `screenshot.png` — snímka obrazovky readeru

## Diagnostika

```
=== Briefly ===
verzia:      0.1.122 (122)
zariadenie:  samsung SM-S926B
android:     16 (API 36)
abi:         arm64-v8a
RAM:         11203 MB celkom, 2695 MB voľných

=== denník aplikácie ===
08-27 22:06:56.992 [logy] odoslané ako 2026-08-27-220654-SMS926B-auto.txt
08-27 22:39:38.292 [app] štart, verzia 0.1.122
08-28 07:20:09.020 [app] štart, verzia 0.1.122
08-28 08:55:19.631 [odkaz] rucne otvoreny https://www.techbyte.sk/2026/08/predavatae-vinted-bazos-instagram-financna-sprava-vie-zistit-zarobili
08-28 08:55:20.023 [hero] f0c3fa194641ae1119adae7b688f909e nahlad=file:///data/user/0/sk.frodo21.reader/files/articles/f0c3fa194641ae1119adae7b688f909e/900.jpg obrazkov=0/0
08-28 08:55:20.027 [extract] f0c3fa194641ae1119adae7b688f909e kvalita=FULL headless=false
08-28 08:55:20.342 [nahlad] dotiahnutych 13 nahladov z 13 clankov
08-28 08:55:21.239 [zhrnutie] spúšťam: GEMINI, kľúč 53 znakov, model gemini-3.1-flash-lite
08-28 08:55:25.470 [zhrnutie] gemini odpovedal za 4231 ms
08-28 08:55:25.639 [nahlad] dotiahnutych 7 nahladov z 7 clankov
08-28 10:32:23.951 [nahlad] dotiahnutych 10 nahladov z 10 clankov
08-28 16:25:34.593 [app] štart, verzia 0.1.122
08-28 16:55:44.796 [app] štart, verzia 0.1.122
08-28 18:10:11.775 [nahlad] dotiahnutych 7 nahladov z 7 clankov
08-28 19:43:08.861 [nahlad] dotiahnutych 5 nahladov z 5 clankov
08-28 19:43:31.822 [extract] 2bb2fa1c74f154e31ac6b078146fa1af google news -> nepodarilo sa rozuzlit, ostava povodny odkaz
08-28 19:43:34.921 [headless] presmerovanie news.google.com -> www.sme.sk
08-28 19:43:36.815 [extract] 2bb2fa1c74f154e31ac6b078146fa1af meta_only: bez konkretneho dovodu
08-28 19:43:55.085 [extract] 98e9346df735ff3347320328ae0dc5c8 google news -> nepodarilo sa rozuzlit, ostava povodny odkaz
08-28 19:44:27.368 [extract] 98e9346df735ff3347320328ae0dc5c8 meta_only: bez konkretneho dovodu


=== logcat ===
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::u32 default.color.primaries = 0
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::u32 default.color.range = 0
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::u32 default.color.transfer = 0
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::u32 input.buffers.max-size.value = 7340032
08-28 19:43:10.910 D/CCodecConfig( 6350):   string input.media-type.value = "video/av01"
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::u32 output.delay.value = 8
08-28 19:43:10.910 D/CCodecConfig( 6350):   Buffer output.hdr-dynamic-info.data = {
08-28 19:43:10.910 D/CCodecConfig( 6350):   }
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::u32 output.hdr-dynamic-info.type = 1
08-28 19:43:10.910 D/CCodecConfig( 6350):   string output.media-type.value = "video/raw"
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::u32 raw.color.matrix = 0
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::u32 raw.color.primaries = 0
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::u32 raw.color.range = 0
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::u32 raw.color.transfer = 0
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.mastering.blue.x = 0
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.mastering.blue.y = 0
08-28 19:43:10.910 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.
08-28 19:43:10.911 W/ColorUtils( 6350): expected specified color aspects (0:0:0:0)
08-28 19:43:10.911 I/CCodec  ( 6350): [c2.exynos.av1.decoder] config->queryConfiguration()
08-28 19:43:10.911 I/CCodec  ( 6350): [c2.exynos.av1.decoder] mCallback->onComponentAllocated() IN
08-28 19:43:10.911 I/CCodec  ( 6350): [c2.exynos.av1.decoder] mCallback->onComponentAllocated() OUT
08-28 19:43:10.913 I/MediaCodec( 6350): media_quality service unavailable, skipping updatePictureProfile
08-28 19:43:10.913 D/CCodec  ( 6350): [c2.exynos.av1.decoder] buffers are bound to CCodec for this session
08-28 19:43:10.913 I/CCodec  ( 6350): Client requested ByteBuffer mode
08-28 19:43:10.913 I/CCodec  ( 6350): appPid(6350) width(1280) height(640)
08-28 19:43:10.913 D/CCodecConfig( 6350): no c2 equivalents for color-format
08-28 19:43:10.913 D/CCodecConfig( 6350): no c2 equivalents for importance
08-28 19:43:10.913 D/CCodecConfig( 6350): no c2 equivalents for flags
08-28 19:43:10.914 D/CCodecConfig( 6350): c2 config diff is   c2::u32 algo.low-latency.value = 1
08-28 19:43:10.914 D/CCodecConfig( 6350):   c2::u32 raw.pixel-format.value = 291
08-28 19:43:10.914 D/CCodecConfig( 6350):   c2::u32 raw.size.height = 640
08-28 19:43:10.914 D/CCodecConfig( 6350):   c2::u32 raw.size.width = 1280
08-28 19:43:10.914 W/ColorUtils( 6350): expected specified color aspects (0:0:0:0)
08-28 19:43:10.914 W/Codec2Client( 6350): query -- param skipped: index = 1107298332.
08-28 19:43:10.914 D/CCodec  ( 6350): client requested max input size 39778, which is smaller than what component recommended (7340032); overriding with component recommendation.
08-28 19:43:10.914 W/CCodec  ( 6350): This behavior is subject to change. It is recommended that app developers double check whether the requested max input size is in reasonable range.
08-28 19:43:10.914 D/CCodec  ( 6350): encoding statistics level = 0
08-28 19:43:10.914 D/CCodec  ( 6350): setup formats input: AMessage(what = 0x00000000) = {
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t height = 640
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t level = 4096
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t max-input-size = 7340032
08-28 19:43:10.914 D/CCodec  ( 6350):   string mime = "video/av01"
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t priority = 0
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t profile = 1
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t width = 1280
08-28 19:43:10.914 D/CCodec  ( 6350):   Rect crop(0, 0, 1279, 639)
08-28 19:43:10.914 D/CCodec  ( 6350): }
08-28 19:43:10.914 D/CCodec  ( 6350): setup formats output: AMessage(what = 0x00000000) = {
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t android._color-format = 291
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t android._video-scaling = 1
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t android._dataspace = 0
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t color-standard = 0
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t color-range = 0
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t color-transfer = 0
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t sar-height = 1
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t rotation-degrees = 0
08-28 19:43:10.914 D/CCodec  ( 6350):   Buffer hdr-static-info = {
08-28 19:43:10.914 D/CCodec  ( 6350):     00000000:  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  ................
08-28 19:43:10.914 D/CCodec  ( 6350):     00000010:  00 00 00 00 00 00 00 00  00                       .........
08-28 19:43:10.914 D/CCodec  ( 6350):   }
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t sar-width = 1
08-28 19:43:10.914 D/CCodec  ( 6350):   Rect crop(0, 0, 1279, 639)
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t width = 1280
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t height = 640
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t max-height = 240
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t max-width = 320
08-28 19:43:10.914 D/CCodec  ( 6350):   string mime = "video/raw"
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t priority = 0
08-28 19:43:10.914 D/CCodec  ( 6350):   Buffer hdr10-plus-info = {
08-28 19:43:10.914 D/CCodec  ( 6350):   }
08-28 19:43:10.914 D/CCodec  ( 6350):   int32_t color-format = 2135033992
08-28 19:43:10.914 D/CCodec  ( 6350): }
08-28 19:43:10.914 I/CCodecConfig( 6350): query failed after returning 16 values (BAD_INDEX)
08-28 19:43:10.915 D/CCodecConfig( 6350): c2 config diff is   c2::u32 raw.max-size.height = 640
08-28 19:43:10.915 D/CCodecConfig( 6350):   c2::u32 raw.max-size.width = 1280
08-28 19:43:10.915 W/ColorUtils( 6350): expected specified color aspects (0:0:0:0)
08-28 19:43:10.915 E/.frodo21.reader( 6350): Failed to query component interface for required system resources: 6
08-28 19:43:10.917 I/CCodec  ( 6350): [c2.exynos.av1.decoder] state->set(STARTING)
08-28 19:43:10.942 W/Codec2Client( 6350): query -- param skipped: index = 1342179345.
08-28 19:43:10.942 W/Codec2Client( 6350): query -- param skipped: index = 1073743886.
08-28 19:43:10.942 W/Codec2Client( 6350): query -- param skipped: index = 1610614798.
08-28 19:43:10.942 W/Codec2Client( 6350): query -- param skipped: index = 1610614821.
08-28 19:43:10.942 D/C2Store ( 6350): debug.c2.use_dmabufheaps set, forcing DMABUF Heaps
08-28 19:43:10.942 D/C2Store ( 6350): Using DMABUF Heaps
08-28 19:43:10.943 D/CCodecBufferChannel( 6350): [c2.exynos.av1.decoder#246] Created input block pool with allocatorID 16 => poolID 17 - OK (0)
08-28 19:43:10.945 I/CCodecBufferChannel( 6350): [c2.exynos.av1.decoder#246] Created output block pool with allocatorID 17 => poolID 17876 - OK
08-28 19:43:10.945 D/CCodecBufferChannel( 6350): [c2.exynos.av1.decoder#246] Configured output block pool ids 17876 => OK
08-28 19:43:10.945 D/CCodecBufferChannel( 6350): [c2.exynos.av1.decoder#246] Configured output usage [0x1]
08-28 19:43:10.945 I/CCodec  ( 6350): [c2.exynos.av1.decoder] state->set(RUNNING)
08-28 19:43:10.947 I/CCodecBufferChannel( 6350): [c2.exynos.av1.decoder#246] 4 initial input buffers available
08-28 19:43:10.950 I/MediaCodec( 6350): setCodecState state(0), called in 6, domain 1, 1
08-28 19:43:10.953 D/CCodecConfig( 6350): c2 config diff is   c2::u32 vendor.sec-dec-output.extra-buffer-num.value = 0
08-28 19:43:10.954 W/ColorUtils( 6350): expected specified color aspects (0:0:0:0)
08-28 19:43:10.954 D/Codec2-OutputBufferQueue( 6350): set max dequeue count 15 from update
08-28 19:43:10.958 D/CCodecConfig( 6350): c2 config diff is   c2::u32 output.delay.value = 16
08-28 19:43:10.959 W/ColorUtils( 6350): expected specified color aspects (0:0:0:0)
08-28 19:43:10.959 D/Codec2-OutputBufferQueue( 6350): set max dequeue count 23 from update
08-28 19:43:10.966 D/CCodecConfig( 6350): c2 config diff is   c2::u32 raw.color.matrix = 1
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::u32 raw.color.range = 1
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::u32 raw.crop.height = 640
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::u32 raw.crop.left = 0
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::u32 raw.crop.top = 0
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::u32 raw.crop.width = 1280
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.mastering.blue.x = 0.131
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.mastering.blue.y = 0.046
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.mastering.green.x = 0.17
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.mastering.green.y = 0.797
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.mastering.max-luminance = 1000
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.mastering.red.x = 0.708
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.mastering.red.y = 0.292
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.mastering.white.x = 0.3127
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.mastering.white.y = 0.329
08-28 19:43:10.966 D/CCodecConfig( 6350):   c2::float raw.hdr-static-info.max-fall = 65536
08-28 19:43:10.966 W/ColorUtils( 6350): expected specified color aspects (1:0:1:0)
08-28 19:43:10.966 D/CCodecConfig( 6350): found invalid HDR static metadata AMessage(what = 0x00000000) = {
08-28 19:43:10.966 D/CCodecConfig( 6350):           int32_t android._color-format = 291
08-28 19:43:10.966 D/CCodecConfig( 6350):           int32_t android._video-scaling = 1
08-28 19:43:10.966 D/CCodecConfig( 6350):           float smpte2086.green.y = 0.797000
08-28 19:43:10.966 D/CCodecConfig( 6350):           int32_t color-standard = 71
08-28 19:43:10.966 D/CCodecConfig( 6350):           int32_t color-range = 1
08-28 19:43:10.966 D/CCodecConfig( 6350):           int32_t color-transfer = 0
08-28 19:43:10.966 D/CCodecConfig( 6350):           float smpte2086.red.y = 0.292000
08-28 19:43:10.966 D/CCodecConfig( 6350):           int32_t width = 1280
08-28 19:43:10.966 D/CCodecConfig( 6350):           float smpte2086.white.y = 0.329000
08-28 19:43:10.966 D/CCodecConfig( 6350):           float smpte2086.white.x = 0.312700
08-28 19:43:10.966 D/CCodecConfig( 6350):           float cta861.max-cll = 0.000000
08-28 19:43:10.966 D/CCodecConfig( 6350):           float cta861.max-fall = 65536.000000
08-28 19:43:10.966 D/CCodecConfig( 6350):           float smpte2086.max-luminance = 1000.000000
08-28 19:43:10.966 D/CCodecConfig( 6350):           float smpte2086.min-luminance = 0.000000
08-28 19:43:10.966 D/CCodecConfig( 6350):           Rect crop(0, 0, 1279, 639)
08-28 19:43:10.966 D/CCodecConfig( 6350):           float smpte2086.red.x = 0.708000
08-28 19:43:10.966 D/CCodecConfig( 6350):           int32_t height = 640
08-28 19:43:10.966 D/CCodecConfig( 6350):           int32_t max-height = 640
08-28 19:43:10.966 D/CCodecConfig( 6350):           int32_t max-width = 1280
08-28 19:43:10.966 D/CCodecConfig( 6350):           string mime = "video/raw"
08-28 19:43:10.966 D/CCodecConfig( 6350):           Buffer output.hdr-dynamic-info.data = {
08-28 19:43:10.966 D/CCodecConfig( 6350):           }
08-28 19:43:10.966 D/CCodecConfig( 6350):           int32_t output.hdr-dynamic-info.type = 1
08-28 19:43:10.966 D/CCodecConfig( 6350):           int32_t priori
08-28 19:43:10.966 D/Codec2-OutputBufferQueue( 6350): set max dequeue count 23 from update
08-28 19:43:10.966 D/CCodecBuffers( 6350): [c2.exynos.av1.decoder#246:2D-BB-Output] popFromStashAndRegister: at 0us, output format changed to AMessage(what = 0x00000000) = {
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t android._color-format = 291
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t android._video-scaling = 1
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t android._dataspace = 134283264
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t color-standard = 71
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t color-range = 1
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t color-transfer = 0
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t sar-height = 1
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t rotation-degrees = 0
08-28 19:43:10.966 D/CCodecBuffers( 6350):   Buffer hdr-static-info = {
08-28 19:43:10.966 D/CCodecBuffers( 6350):     00000000:  00 00 00 00 00 00 00 00  00 00 00 00 00 00 00 00  ................
08-28 19:43:10.966 D/CCodecBuffers( 6350):     00000010:  00 00 00 00 00 00 00 00  00                       .........
08-28 19:43:10.966 D/CCodecBuffers( 6350):   }
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t sar-width = 1
08-28 19:43:10.966 D/CCodecBuffers( 6350):   Rect crop(0, 0, 1279, 639)
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t width = 1280
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t height = 640
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t max-height = 640
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t max-width = 1280
08-28 19:43:10.966 D/CCodecBuffers( 6350):   string mime = "video/raw"
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t priority = 0
08-28 19:43:10.966 D/CCodecBuffers( 6350):   Buffer hdr10-plus-info = {
08-28 19:43:10.966 D/CCodecBuffers( 6350):   }
08-28 19:43:10.966 D/CCodecBuffers( 6350):   int32_t color-format = 2135033992
08-28 19:43:10.966 D/CCodecBuffers( 6350): }
08-28 19:43:10.966 D/CCodecBuffers( 6350): [c2.exynos.av1.decoder#246:2D-BB-Output] updating image-data
08-28 19:43:10.966 D/CCodecBuffers( 6350): [c2.exynos.av1.decoder#246:2D-BB-Output] updating stride = 1280, width: 1280, height: 640
08-28 19:43:10.966 D/CCodecBuffers( 6350): [c2.exynos.av1.decoder#246:2D-BB-Output] updating vstride = 640
08-28 19:43:10.986 I/MediaCodec( 6350): setCodecState state(1), called in 6, domain 1, 1
08-28 19:43:10.986 I/CCodec  ( 6350): [c2.exynos.av1.decoder] state->set(STOPPING)
08-28 19:43:10.987 D/CCodecBufferChannel( 6350): [c2.exynos.av1.decoder#246] MediaCodec discarded an unknown buffer
08-28 19:43:10.987 I/CCodec  ( 6350): [stop][3607] surface -> component
08-28 19:43:10.987 D/CCodecBufferChannel( 6350): [c2.exynos.av1.decoder#246] MediaCodec discarded an unknown buffer
08-28 19:43:10.987 D/CCodecBufferChannel( 6350): [c2.exynos.av1.decoder#246] MediaCodec discarded an unknown buffer
08-28 19:43:10.987 D/CCodecBufferChannel( 6350): [c2.exynos.av1.decoder#246] MediaCodec discarded an unknown buffer
08-28 19:43:10.994 I/CCodec  ( 6350): [c2.exynos.av1.decoder] state->set(ALLOCATED)
08-28 19:43:10.995 I/CCodec  ( 6350): [c2.exynos.av1.decoder] state->set(RELEASING)
08-28 19:43:10.995 D/CCodec  ( 6350): hold CodecLooper(1) until release
08-28 19:43:10.995 I/CCodec  ( 6350): [release][3751] surface -> component
08-28 19:43:11.005 I/CCodec  ( 6350): [c2.exynos.av1.decoder] state->set(RELEASED)
08-28 19:43:11.005 I/MediaCodec( 6350): Codec shutdown complete
08-28 19:43:11.005 I/Codec2Client( 6350): Component destructing
08-28 19:43:11.005 I/hw-BpHwBinder( 6350): onLastStrongRef automatically unlinking death recipients
08-28 19:43:11.007 I/CCodecBufferChannel( 6350): CCodecBufferChannel destructing c2.exynos.av1.decoder#246
08-28 19:43:15.944 D/BufferPoolAccessor2.0( 6350): bufferpool2 0xb40000726a0bde98 : 0(0 size) total buffers - 0(0 size) used buffers - 0/5 (recycle/alloc) - 2/3 (fetch/transfer)
08-28 19:43:15.944 D/BufferPoolAccessor2.0( 6350): evictor expired: 1, evicted: 1
08-28 19:43:20.093 I/Kumiho-Kumiho( 6350): getPackageName: sk.frodo21.reader
08-28 19:43:20.095 I/Kumiho-Kumiho( 6350): getPackageName: sk.frodo21.reader
08-28 19:43:31.375 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@aa5c47a
08-28 19:43:32.029 W/System.err( 6350): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
08-28 19:43:32.029 W/System.err( 6350): SLF4J: Defaulting to no-operation (NOP) logger implementation
08-28 19:43:32.029 W/System.err( 6350): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
08-28 19:43:32.072 I/cr_ChildProcLH( 6350): ScopedServiceBindingBatch.tryActivate: false
08-28 19:43:32.075 I/cr_CombinedPProvider( 6350): #registerProvider() provider:WV.sj@53a3128 isPolicyCacheEnabled:false policyProvidersSize:0
08-28 19:43:32.075 I/cr_PolicyProvider( 6350): #setManagerAndSource() 0
08-28 19:43:32.077 I/cr_policy( 6350): registerReceiver succeeded after 1ms
08-28 19:43:32.080 I/cr_DisplayManager( 6350): Is Display Topology available: false
08-28 19:43:32.118 I/cr_CombinedPProvider( 6350): #linkNativeInternal() 1
08-28 19:43:32.119 I/cr_AppResProvider( 6350): #getApplicationRestrictionsFromUserManager() Bundle[EMPTY_PARCEL]
08-28 19:43:32.119 I/cr_PolicyProvider( 6350): #notifySettingsAvailable() 0
08-28 19:43:32.119 I/cr_CombinedPProvider( 6350): #onSettingsAvailable() 0
08-28 19:43:32.119 I/cr_CombinedPProvider( 6350): #flushPolicies()
08-28 19:43:32.186 W/chromium( 6350): [WARNING:android_webview/browser/cookie_manager.cc:372] Transferring cookies from provisional CookieManager to network service. For issues with the provisional CookieManager, see crbug.com/478873476.
08-28 19:43:32.215 D/ConnectivityManager( 6350): StackLog: [android.net.ConnectivityManager.sendRequestForNetwork(ConnectivityManager.java:4744)] [android.net.ConnectivityManager.registerDefaultNetworkCallbackForUid(ConnectivityManager.java:5469)] [android.net.ConnectivityManager.registerDefaultNetworkCallback(ConnectivityManager.java:5436)] [WV.lm1.e(chromium-SystemWebViewGoogle6432.aab-stable-792219903:37)] [WV.lm1.a(chromium-SystemWebViewGoogle6432.aab-stable-792219903:1)] [org.chromium.android_webview.AwContentsLifecycleNotifier.onFirstWebViewCreated(chromium-SystemWebViewGoogle6432.aab-stable-792219903:19)] [J.N.JJ(Native Method)] [org.chromium.android_webview.AwContents.<init>(chromium-SystemWebViewGoogle6432.aab-stable-792219903:616)] [com.android.webview.chromium.i.run(chromium-SystemWebViewGoogle6432.aab-stable-792219903:298)] [WV.n23.run(chromium-SystemWebViewGoogle6432.aab-stable-792219903:13)] [org.chromium.base.task.PostTask.d(chromium-SystemWebViewGoogle6432.aab-stable-792219903:18)] [WV.o23.a(chromium-SystemWebViewGoogle6432.aab-stable-792219903:18)] [com.android.webview.chromium.WebViewChromiumFactoryProvider.a(chromium-SystemWebViewGoogle6432.aab-stable-792219903:3)] [com.android.webview.chromium.WebViewChromium.init(chromium-SystemWebViewGoogle6432.aab-stable-792219903:149)] [android.webkit.WebView.<init>(WebView.java:474)] [android.webkit.WebView.<init>(WebView.java:389)] [android.webkit.WebView.<init>(WebView.java:370)] [android.webkit.WebView.<init>(WebView.java:356)] [android.webkit.WebView.<init>(WebView.java:345)] [sk.frodo21.reader.extraction.HeadlessFetcher$fetchHtml$result$1$1.invokeSuspend(SourceFile:148)] [kotlin.coroutines.jvm.internal.BaseContinuationImpl.resumeWith(SourceFile:8)] [kotlinx.coroutines.DispatchedTask.run(SourceFile:112)]
08-28 19:43:32.217 D/ConnectivityManager( 6350): StackLog: [android.net.ConnectivityManager.sendRequestForNetwork(ConnectivityManager.java:4744)] [android.net.ConnectivityManager.sendRequestForNetwork(ConnectivityManager.java:4912)] [android.net.ConnectivityManager.registerNetworkCallback(ConnectivityManager.java:5329)] [WV.lm1.e(chromium-SystemWebViewGoogle6432.aab-stable-792219903:86)] [WV.lm1.a(chromium-SystemWebViewGoogle6432.aab-stable-792219903:1)] [org.chromium.android_webview.AwContentsLifecycleNotifier.onFirstWebViewCreated(chromium-SystemWebViewGoogle6432.aab-stable-792219903:19)] [J.N.JJ(Native Method)] [org.chromium.android_webview.AwContents.<init>(chromium-SystemWebViewGoogle6432.aab-stable-792219903:616)] [com.android.webview.chromium.i.run(chromium-SystemWebViewGoogle6432.aab-stable-792219903:298)] [WV.n23.run(chromium-SystemWebViewGoogle6432.aab-stable-792219903:13)] [org.chromium.base.task.PostTask.d(chromium-SystemWebViewGoogle6432.aab-stable-792219903:18)] [WV.o23.a(chromium-SystemWebViewGoogle6432.aab-stable-792219903:18)] [com.android.webview.chromium.WebViewChromiumFactoryProvider.a(chromium-SystemWebViewGoogle6432.aab-stable-792219903:3)] [com.android.webview.chromium.WebViewChromium.init(chromium-SystemWebViewGoogle6432.aab-stable-792219903:149)] [android.webkit.WebView.<init>(WebView.java:474)] [android.webkit.WebView.<init>(WebView.java:389)] [android.webkit.WebView.<init>(WebView.java:370)] [android.webkit.WebView.<init>(WebView.java:356)] [android.webkit.WebView.<init>(WebView.java:345)] [sk.frodo21.reader.extraction.HeadlessFetcher$fetchHtml$result$1$1.invokeSuspend(SourceFile:148)] [kotlin.coroutines.jvm.internal.BaseContinuationImpl.resumeWith(SourceFile:8)] [kotlinx.coroutines.DispatchedTask.run(SourceFile:112)]
08-28 19:43:32.238 W/cr_media( 6350): BLUETOOTH_CONNECT permission is missing.
08-28 19:43:32.238 W/cr_media( 6350): getBluetoothAdapter() requires BLUETOOTH permission
08-28 19:43:32.238 W/cr_media( 6350): registerBluetoothIntentsIfNeeded: Requires BLUETOOTH permission
08-28 19:43:32.241 D/AudioSystem( 6350): onNewService: media.audio_policy service obtained 0xb40000730a10b700
08-28 19:43:32.241 D/AudioSystem( 6350): getService: IAudioPolicyService retrieved: 0xb40000730a10b700  cached: 0xb40000730a10b700
08-28 19:43:32.247 V/XGL     ( 6350): ----------------------------------------------------------------------
08-28 19:43:32.247 V/XGL     ( 6350): SUMD version compiled date     = 2026-01-09 09:57 - KST
08-28 19:43:32.247 V/XGL     ( 6350): SUMD version revision number   = 1900168dcb
08-28 19:43:32.247 V/XGL     ( 6350): SUMD version info              = Driver version: 24.0.534, git hash: 1900168dcb
08-28 19:43:32.247 V/XGL     ( 6350): ----------------------------------------------------------------------
08-28 19:43:32.247 V/XGL     ( 6350): Entering: Create
08-28 19:43:32.252 V/XGL     ( 6350): Exiting: Create
08-28 19:43:32.253 I/cr_AppResProvider( 6350): #getApplicationRestrictionsFromUserManager() Bundle[EMPTY_PARCEL]
08-28 19:43:32.253 I/cr_PolicyProvider( 6350): #notifySettingsAvailable() 0
08-28 19:43:32.253 I/cr_CombinedPProvider( 6350): #onSettingsAvailable() 0
08-28 19:43:32.253 I/cr_CombinedPProvider( 6350): #flushPolicies()
08-28 19:43:32.254 I/CameraManagerGlobal( 6350): Connecting to camera service
08-28 19:43:32.258 D/VendorTagDescriptor( 6350): addVendorDescriptor: vendor tag id 15622750491770684145 added
08-28 19:43:32.258 D/VendorTagDescriptor( 6350): addVendorDescriptor: vendor tag id 8932615658386372252 added
08-28 19:43:32.260 I/CameraManager( 6350): registerAvailabilityCallback: Is device callback = false
08-28 19:43:32.261 I/CameraManagerGlobal( 6350): postSingleUpdate device: camera id 0 status STATUS_PRESENT
08-28 19:43:32.262 I/CameraManagerGlobal( 6350): postSingleUpdate device: camera id 1 status STATUS_PRESENT
08-28 19:43:32.262 I/CameraManagerGlobal( 6350): postSingleUpdate device: camera id 2 status STATUS_PRESENT
08-28 19:43:32.262 I/CameraManagerGlobal( 6350): postSingleUpdate device: camera id 3 status STATUS_PRESENT
08-28 19:43:32.263 V/XGL     ( 6350): ----------------------------------------------------------------------
08-28 19:43:32.263 V/XGL     ( 6350): SUMD version compiled date     = 2026-01-09 09:57 - KST
08-28 19:43:32.263 V/XGL     ( 6350): SUMD version revision number   = 1900168dcb
08-28 19:43:32.263 V/XGL     ( 6350): SUMD version info              = Driver version: 24.0.534, git hash: 1900168dcb
08-28 19:43:32.263 V/XGL     ( 6350): ----------------------------------------------------------------------
08-28 19:43:32.263 V/XGL     ( 6350): Entering: Create
08-28 19:43:32.263 I/CameraManagerGlobal( 6350): Camera 0 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client com.whatsapp API Level 2 User Id 0Device Id 0
08-28 19:43:32.264 I/CameraManagerGlobal( 6350): Camera 1 facing CAMERA_FACING_FRONT state now CAMERA_STATE_CLOSED for client com.samsung.android.smartface API Level 2 User Id 0Device Id 0
08-28 19:43:32.264 I/CameraManagerGlobal( 6350): Camera 2 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client sk.csob.smarttoken API Level 2 User Id 0Device Id 0
08-28 19:43:32.264 I/CameraManagerGlobal( 6350): Camera 20 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client com.sec.android.app.camera API Level 2 User Id 0Device Id 0
08-28 19:43:32.264 I/CameraManagerGlobal( 6350): Camera 21 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client com.sec.android.app.camera API Level 2 User Id 0Device Id 0
08-28 19:43:32.264 I/CameraManagerGlobal( 6350): Camera 23 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client com.sec.android.app.camera API Level 2 User Id 0Device Id 0
08-28 19:43:32.264 I/CameraManagerGlobal( 6350): Camera 3 facing CAMERA_FACING_FRONT state now CAMERA_STATE_CLOSED for client com.samsung.android.sead API Level 2 User Id 0Device Id 0
08-28 19:43:32.264 I/CameraManagerGlobal( 6350): Camera 4 facing CAMERA_FACING_FRONT state now CAMERA_STATE_CLOSED for client client.pid<1256> API Level 2 User Id 0Device Id 0
08-28 19:43:32.264 I/CameraManagerGlobal( 6350): Camera 52 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client android.system API Level 2 User Id 0Device Id 0
08-28 19:43:32.264 I/CameraManagerGlobal( 6350): Camera 56 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client android.system API Level 2 User Id 0Device Id 0
08-28 19:43:32.264 I/CameraManagerGlobal( 6350): Camera 58 facing CAMERA_FACING_BACK state now CAMERA_STATE_CLOSED for client android.system API Level 2 User Id 0Device Id 0
08-28 19:43:32.266 V/XGL     ( 6350): Exiting: Create
08-28 19:43:32.267 I/vulkan  ( 6350): CreateInfoWrapper::FilterExtension: already have 'VK_KHR_external_fence_fd'.
08-28 19:43:32.273 I/ANGLE   ( 6350): Version (24.1.307 git hash: 86f99cfe6317), Renderer ((Samsung Xclipse 940) on Vulkan 1.3.279)
08-28 19:43:32.285 W/libEGL  ( 6350): ANGLE Warn:DisplayVk.cpp:124 (LoadPipelineCacheDataFromDisk): Successfully loaded 0.00693607 MB of blobcache data from disk.
08-28 19:43:32.314 V/XGL     ( 6350): ----------------------------------------------------------------------
08-28 19:43:32.314 V/XGL     ( 6350): SUMD version compiled date     = 2026-01-09 09:57 - KST
08-28 19:43:32.314 V/XGL     ( 6350): SUMD version revision number   = 1900168dcb
08-28 19:43:32.314 V/XGL     ( 6350): SUMD version info              = Driver version: 24.0.534, git hash: 1900168dcb
08-28 19:43:32.314 V/XGL     ( 6350): ----------------------------------------------------------------------
08-28 19:43:32.314 V/XGL     ( 6350): Entering: Create
08-28 19:43:32.318 V/XGL     ( 6350): Exiting: Create
08-28 19:43:32.332 W/AudioCapabilities( 6350): Unsupported mediaType audio/x-ape
08-28 19:43:32.332 W/AudioCapabilities( 6350): Unsupported mediaType audio/x-ima
08-28 19:43:32.332 W/AudioCapabilities( 6350): Unsupported mediaType audio/mpeg-L1
08-28 19:43:32.332 W/AudioCapabilities( 6350): Unsupported mediaType audio/mpeg-L2
08-28 19:43:32.332 W/VideoCapabilities( 6350): Unsupported mime video/wvc1
08-28 19:43:32.333 W/VideoCapabilities( 6350): Unsupported mime video/x-ms-wmv
08-28 19:43:32.340 W/VideoCapabilities( 6350): Unrecognized profile/level 32768/256 for video/mp4v-es
08-28 19:43:32.344 W/AudioCapabilities( 6350): Unsupported mediaType audio/x-ape
08-28 19:43:32.344 W/AudioCapabilities( 6350): Unsupported mediaType audio/x-ima
08-28 19:43:32.345 W/AudioCapabilities( 6350): Unsupported mediaType audio/mpeg-L1
08-28 19:43:32.345 W/AudioCapabilities( 6350): Unsupported mediaType audio/mpeg-L2
08-28 19:43:32.345 W/VideoCapabilities( 6350): Unsupported mime video/wvc1
08-28 19:43:32.345 W/VideoCapabilities( 6350): Unsupported mime video/x-ms-wmv
08-28 19:43:32.351 W/VideoCapabilities( 6350): Unrecognized profile/level 32768/256 for video/mp4v-es
08-28 19:43:32.359 W/AudioCapabilities( 6350): Unsupported mime audio/x-ape
08-28 19:43:32.359 W/AudioCapabilities( 6350): Unsupported mime audio/x-ima
08-28 19:43:32.359 W/AudioCapabilities( 6350): Unsupported mime audio/mpeg-L1
08-28 19:43:32.359 W/AudioCapabilities( 6350): Unsupported mime audio/mpeg-L2
08-28 19:43:32.359 W/VideoCapabilities( 6350): Unsupported mime video/wvc1
08-28 19:43:32.360 W/VideoCapabilities( 6350): Unsupported mime video/x-ms-wmv
08-28 19:43:32.363 W/VideoCapabilities( 6350): Unrecognized profile/level 32768/256 for video/mp4v-es
08-28 19:43:32.364 W/VideoCapabilities( 6350): Unsupported mime video/wvc1
08-28 19:43:34.112 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3142] Received WINDOW_UPDATE for invalid stream 1
08-28 19:43:34.113 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3142] Received WINDOW_UPDATE for invalid stream 3
08-28 19:43:34.113 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3142] Received WINDOW_UPDATE for invalid stream 5
08-28 19:43:34.114 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3142] Received WINDOW_UPDATE for invalid stream 7
08-28 19:43:34.114 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3142] Received WINDOW_UPDATE for invalid stream 9
08-28 19:43:34.115 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3142] Received WINDOW_UPDATE for invalid stream 11
08-28 19:43:34.187 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3142] Received WINDOW_UPDATE for invalid stream 13
08-28 19:43:35.202 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : warmUpIntegrityToken(187810013193)
08-28 19:43:35.203 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : Initiate binding to the service.
08-28 19:43:35.253 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : ServiceConnectionImpl.onServiceConnected(ComponentInfo{com.android.vending/com.google.android.finsky.expressintegrityservice.ExpressIntegrityService})
08-28 19:43:35.253 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : linkToDeath
08-28 19:43:35.656 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : warmUpIntegrityToken(187810013193)
08-28 19:43:35.656 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : Already connected to the service.
08-28 19:43:36.728 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : Leaving the connection open for other ongoing calls.
08-28 19:43:36.728 I/PlayCore( 6350): UID: [10606]  PID: [6350] OnWarmUpIntegrityTokenCallback : onWarmUpExpressIntegrityToken
08-28 19:43:36.765 D/ConnectivityManager( 6350): StackLog: [android.net.ConnectivityManager.unregisterNetworkCallback(ConnectivityManager.java:5579)] [WV.mm1.g(chromium-SystemWebViewGoogle6432.aab-stable-792219903:17)] [WV.cj.b(chromium-SystemWebViewGoogle6432.aab-stable-792219903:3)] [org.chromium.android_webview.AwContentsLifecycleNotifier.onLastWebViewDestroyed(chromium-SystemWebViewGoogle6432.aab-stable-792219903:19)] [J.N.VJ(Native Method)] [WV.of.accept(chromium-SystemWebViewGoogle6432.aab-stable-792219903:17)] [WV.qw.a(chromium-SystemWebViewGoogle6432.aab-stable-792219903:59)] [org.chromium.android_webview.AwContents.k(chromium-SystemWebViewGoogle6432.aab-stable-792219903:50)] [WV.ef.run(chromium-SystemWebViewGoogle6432.aab-stable-792219903:10)] [org.chromium.base.task.TaskRunnerImpl.runTask(chromium-SystemWebViewGoogle6432.aab-stable-792219903:31)]
08-28 19:43:36.765 D/ConnectivityManager( 6350): StackLog: [android.net.ConnectivityManager.unregisterNetworkCallback(ConnectivityManager.java:5579)] [WV.mm1.g(chromium-SystemWebViewGoogle6432.aab-stable-792219903:26)] [WV.cj.b(chromium-SystemWebViewGoogle6432.aab-stable-792219903:3)] [org.chromium.android_webview.AwContentsLifecycleNotifier.onLastWebViewDestroyed(chromium-SystemWebViewGoogle6432.aab-stable-792219903:19)] [J.N.VJ(Native Method)] [WV.of.accept(chromium-SystemWebViewGoogle6432.aab-stable-792219903:17)] [WV.qw.a(chromium-SystemWebViewGoogle6432.aab-stable-792219903:59)] [org.chromium.android_webview.AwContents.k(chromium-SystemWebViewGoogle6432.aab-stable-792219903:50)] [WV.ef.run(chromium-SystemWebViewGoogle6432.aab-stable-792219903:10)] [org.chromium.base.task.TaskRunnerImpl.runTask(chromium-SystemWebViewGoogle6432.aab-stable-792219903:31)]
08-28 19:43:36.839 I/PlayCore( 6350): UID: [10606]  PID: [6350] OnWarmUpIntegrityTokenCallback : onWarmUpExpressIntegrityToken
08-28 19:43:36.839 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : Unbind from service.
08-28 19:43:36.852 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{39e1ca7 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:36.871 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{39e1ca7 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:36.884 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{39e1ca7 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:36.976 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{39e1ca7 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:37.068 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{39e1ca7 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:38.552 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3187] Received HEADERS for invalid stream 23
08-28 19:43:38.553 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3187] Received HEADERS for invalid stream 27
08-28 19:43:38.553 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3187] Received HEADERS for invalid stream 25
08-28 19:43:38.604 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{39e1ca7 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:39.208 D/WindowOnBackDispatcher( 6350): onBackInvoked, callback=androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@aa5c47a
08-28 19:43:39.213 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@913d525
08-28 19:43:40.055 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@aa5c47a
08-28 19:43:40.079 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{4842f75 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:40.114 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{4842f75 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:40.122 I/libbinder.BpBinder( 6350): onLastStrongRef automatically unlinking death recipients for descriptor: '(not cached)'
08-28 19:43:40.130 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{4842f75 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:40.298 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{4842f75 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:40.725 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{4842f75 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:40.774 D/WindowOnBackDispatcher( 6350): onBackInvoked, callback=androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@aa5c47a
08-28 19:43:40.782 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@913d525
08-28 19:43:47.418 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3187] Received HEADERS for invalid stream 31
08-28 19:43:47.419 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3187] Received HEADERS for invalid stream 29
08-28 19:43:52.119 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@aa5c47a
08-28 19:43:52.142 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1ab54d5 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:52.170 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1ab54d5 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:52.187 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1ab54d5 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:52.193 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1ab54d5 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:52.360 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1ab54d5 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:53.375 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1ab54d5 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:53.380 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1ab54d5 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:43:53.386 D/WindowOnBackDispatcher( 6350): onBackInvoked, callback=androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@aa5c47a
08-28 19:43:53.389 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@913d525
08-28 19:43:54.823 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@aa5c47a
08-28 19:43:56.575 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3142] Received WINDOW_UPDATE for invalid stream 17
08-28 19:43:56.635 W/chromium( 6350): [WARNING:net/spdy/spdy_session.cc:3142] Received WINDOW_UPDATE for invalid stream 31
08-28 19:43:58.003 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : requestExpressIntegrityToken(-3962140881353553679)
08-28 19:43:58.004 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : Initiate binding to the service.
08-28 19:43:58.010 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : ServiceConnectionImpl.onServiceConnected(ComponentInfo{com.android.vending/com.google.android.finsky.expressintegrityservice.ExpressIntegrityService})
08-28 19:43:58.011 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : linkToDeath
08-28 19:43:58.027 I/PlayCore( 6350): UID: [10606]  PID: [6350] OnRequestIntegrityTokenCallback : onRequestExpressIntegrityToken
08-28 19:43:58.027 I/PlayCore( 6350): UID: [10606]  PID: [6350] StandardIntegrity : Unbind from service.
08-28 19:44:02.106 I/libbinder.BpBinder( 6350): onLastStrongRef automatically unlinking death recipients for descriptor: '(not cached)'
08-28 19:44:12.888 D/WindowOnBackDispatcher( 6350): onBackInvoked, callback=androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@aa5c47a
08-28 19:44:12.891 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@913d525
08-28 19:44:13.950 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@aa5c47a
08-28 19:44:15.060 D/WindowOnBackDispatcher( 6350): onBackInvoked, callback=androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@aa5c47a
08-28 19:44:15.067 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): android.app.Activity$$ExternalSyntheticLambda0@913d525
08-28 19:44:18.004 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@aa5c47a
08-28 19:44:19.106 I/WindowManager( 6350): WindowManagerGlobal#addView, ty=1002, view=androidx.compose.ui.window.PopupLayout{f5018d2 V.E...... ......I. 0,0-0,0 #1020002 android:id/content}, caller=android.view.WindowManagerImpl.addView:167 androidx.compose.ui.window.AndroidPopup_androidKt$Popup$2$1.invoke:196 androidx.compose.runtime.DisposableEffectImpl.onRemembered:4 
08-28 19:44:19.106 D/ViewRootImpl( 6350): desktopMode is false
08-28 19:44:19.106 I/ViewRootImpl( 6350): dVRR is disabled
08-28 19:44:19.107 D/NativeCustomFrequencyManager( 6350): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-28 19:44:19.123 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): androidx.compose.ui.window.Api33Impl$$ExternalSyntheticLambda0@b4ffb64
08-28 19:44:19.134 W/libc    ( 6350): Access denied finding property "vendor.perf.ems.egg"
08-28 19:44:19.135 W/libc    ( 6350): Access denied finding property "vendor.perf.ems.egg"
08-28 19:44:19.908 I/Dialog  ( 6350): mIsDeviceDefault = false, mIsSamsungBasicInteraction = false, isMetaDataInActivity = false
08-28 19:44:19.915 I/DecorView( 6350): setWindowBackground: isPopOver=false color=0 d=android.graphics.drawable.ColorDrawable@67f8105
08-28 19:44:19.918 I/WindowManager( 6350): WindowManagerGlobal#addView, ty=2, view=com.android.internal.policy.DecorView{c1f33f1 V.E...... R.....I. 0,0-0,0}[MainActivity], caller=android.view.WindowManagerImpl.addView:167 android.app.Dialog.show:544 androidx.compose.ui.window.DialogWrapper$2.invoke:9 
08-28 19:44:19.919 D/ViewRootImpl( 6350): desktopMode is false
08-28 19:44:19.919 I/ViewRootImpl( 6350): dVRR is disabled
08-28 19:44:19.919 D/NativeCustomFrequencyManager( 6350): [NativeCFMS] BpCustomFrequencyManager::BpCustomFrequencyManager()
08-28 19:44:19.935 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): android.app.Dialog$$ExternalSyntheticLambda4@9556fae
08-28 19:44:19.935 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@ffbc14f
08-28 19:44:19.953 W/libc    ( 6350): Access denied finding property "vendor.perf.ems.egg"
08-28 19:44:19.954 W/libc    ( 6350): Access denied finding property "vendor.perf.ems.egg"
08-28 19:44:20.006 I/WindowManager( 6350): WindowManagerGlobal#removeView, ty=1002, view=androidx.compose.ui.window.PopupLayout{f5018d2 V.E...... ......ID 0,0-555,224 #1020002 android:id/content aid=1073741824}, caller=android.view.WindowManagerGlobal.removeView:654 android.view.WindowManagerImpl.removeViewImmediate:254 androidx.activity.compose.BackHandlerKt$BackHandler$2$1$invoke$$inlined$onDispose$1.dispose:31 
08-28 19:44:20.006 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): null
08-28 19:44:21.603 W/RemoteInputConnectionImpl( 6350): requestCursorUpdates on inactive InputConnection
08-28 19:44:21.610 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): android.view.ImeBackAnimationController@604be0d
08-28 19:44:21.717 W/InteractionJankMonitor( 6350): Initializing without READ_DEVICE_CONFIG permission. enabled=false, interval=1, missedFrameThreshold=3, frameTimeThreshold=64, package=sk.frodo21.reader
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): Build configuration failed!
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): java.lang.IllegalArgumentException: Must pass in a valid surface control if only instrument surface; 
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at com.android.internal.jank.InteractionJankMonitor$Configuration.validate(InteractionJankMonitor.java:930)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at com.android.internal.jank.InteractionJankMonitor$Configuration.<init>(InteractionJankMonitor.java:866)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at com.android.internal.jank.InteractionJankMonitor$Configuration.<init>(InteractionJankMonitor.java:0)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at com.android.internal.jank.InteractionJankMonitor$Configuration$Builder.build(InteractionJankMonitor.java:836)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at com.android.internal.jank.InteractionJankMonitor.begin(InteractionJankMonitor.java:384)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.animation.Animator$AnimatorListener.onAnimationStart(Animator.java:768)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.animation.Animator$AnimatorCaller$$ExternalSyntheticLambda0.call(D8$$SyntheticClass:0)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.animation.Animator.callOnList(Animator.java:742)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.animation.Animator.notifyListeners(Animator.java:640)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.animation.Animator.notifyStartListeners(Animator.java:657)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.animation.ValueAnimator.startAnimation(ValueAnimator.java:1360)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.animation.ValueAnimator.start(ValueAnimator.java:1149)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.animation.ValueAnimator.start(ValueAnimator.java:1173)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.view.InsetsAnimationThreadControlRunner.lambda$new$0(InsetsAnimationThreadControlRunner.java:140)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.view.InsetsAnimationThreadControlRunner.$r8$lambda$DLuG7Ht_vy5T5uYr29Rzhu2CZeY(InsetsAnimationThreadControlRunner.java:0)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.view.InsetsAnimationThreadControlRunner$$ExternalSyntheticLambda1.run(D8$$SyntheticClass:0)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.os.Handler.handleCallback(Handler.java:1070)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.os.Handler.dispatchMessage(Handler.java:125)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.os.Looper.dispatchMessage(Looper.java:358)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.os.Looper.loopOnce(Looper.java:288)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.os.Looper.loop(Looper.java:392)
08-28 19:44:21.717 D/InteractionJankMonitor( 6350): 	at android.os.HandlerThread.run(HandlerThread.java:139)
08-28 19:44:27.392 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1c8a2e4 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:44:27.414 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1c8a2e4 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:44:27.479 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1c8a2e4 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:44:27.496 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1c8a2e4 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:44:27.631 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1c8a2e4 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:44:30.696 I/View    ( 6350): setRequestedFrameRate frameRate=-4.0, this=android.webkit.WebView{1c8a2e4 VFEDHVC.. ........ 0,0-1440,2769}, caller=android.view.ViewGroup.setRequestedFrameRate:10045 WV.ue.p:1 WV.sf.h:117 WV.sf.onDraw:7 com.android.webview.chromium.WebViewChromium.onDraw:19 
08-28 19:44:30.906 D/WindowOnBackDispatcher( 6350): setTopOnBackInvokedCallback (unwrapped): androidx.activity.OnBackPressedDispatcher$Api34Impl$createOnBackAnimationCallback$1@ffbc14f
08-28 19:44:30.906 D/CompatChangeReporter( 6350): Compat change id reported: 395521150; UID 10606; state: ENABLED

```
