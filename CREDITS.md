# เครดิตชิ้นส่วนและสัญญาอนุญาต · Third-Party Credits & Licenses

คลัง `G-Lee21/glee-download-extra` เผยแพร่ **ส่วนเสริมโซเชียล แมวดำมาเย้ย (GLee Load Social Add-on)** สำหรับ Windows และ **แมวดำมาเย้ย (GLee Load)** แอปมือถือ Android — **ตรวจสอบครบทุกชิ้นส่วนแล้ว ไม่มีชิ้นส่วนแบบบังคับแจกโค้ดทั้งแอป (GPL / AGPL)**

---

## 1. ส่วนเสริมโซเชียล แมวดำมาเย้ย (GLee Load Social Add-on — Windows) — รุ่นล่าสุด v1.0.5

| ชิ้นส่วน | รุ่น | เจ้าของ | สัญญาอนุญาต | แบบ | ต้นทาง |
|---|---|---|---|---|---|
| yt-dlp (`yt-dlp.exe`) | 2026.10.26 | yt-dlp contributors | The Unlicense | ใช้ได้อิสระ | https://github.com/yt-dlp/yt-dlp |
| QuickJS (`qjs.exe`) | 2025-04-26 | Fabrice Bellard, Charlie Gordon | MIT | ใช้ได้อิสระ | https://bellard.org/quickjs/ |
| FFmpeg & FFprobe (`ffmpeg.exe`, `ffprobe.exe`, `avcodec-63.dll`, `avdevice-63.dll`, `avfilter-12.dll`, `avformat-63.dll`, `avutil-61.dll`, `swresample-7.dll`, `swscale-10.dll`) | `n9.0.2-61-gd59078794d-20261120` (BtbN LGPLv3+ Shared Build: `--enable-version3 --enable-shared`, ไม่มี `--enable-gpl` และไม่มี `--enable-nonfree`) | The FFmpeg developers | **LGPL-3.0-or-later** | แบ่งปันเฉพาะชิ้นส่วน (แยกไฟล์ Shared DLL ไม่แก้ไข) | https://github.com/BtbN/FFmpeg-Builds · https://ffmpeg.org/ |
| ตัวติดตั้งมาตรฐาน GLee (`glee-installer-src` + NSIS 3.x) | 1.0.3 / 3.x | GLee / NSIS | MIT / Apache-2.0 / zlib | ใช้ได้อิสระ | https://nsis.sourceforge.io/ · https://crates.io/ |

---

## 2. แมวดำมาเย้ย (GLee Load — Android APK `com.glee.maewdam`) · Bundled Components

ตรวจรายการชิ้นส่วนในชุดแจกจ่าย (APK) ครบทั้ง 243 รายการแล้ว: **ไม่มีชิ้นส่วน GPL / AGPL** และ **ไม่มีชิ้นส่วน LGPL ในรุ่นปัจจุบัน** (แอปไม่ได้ฝัง FFmpeg ใช้ MediaMuxer ในตัว Android)

| ชิ้นส่วน | รุ่น | เจ้าของ | สัญญาอนุญาต | แบบ | ต้นทาง |
|---|---|---|---|---|---|
| yt-dlp | 2026.10.26 | yt-dlp contributors | Unlicense | ใช้ได้อิสระ | https://github.com/yt-dlp/yt-dlp |
| yt-dlp-ejs | 0.8.0 | yt-dlp contributors | Unlicense / MIT / ISC | ใช้ได้อิสระ | https://github.com/yt-dlp/ejs |
| QuickJS (`libqjs.so`) | 2025-04-26 | Fabrice Bellard, Charlie Gordon | MIT | ใช้ได้อิสระ | https://bellard.org/quickjs/ |
| Chaquopy | 17.2.0 | Chaquo Ltd | MIT | ใช้ได้อิสระ | https://github.com/chaquo/chaquopy |
| CPython (+ OpenSSL, SQLite, libffi, bzip2, xz) | 3.12.15 | PSF และเจ้าของแต่ละตัว | PSF-2.0 / Apache-2.0 / MIT / BSD / Public Domain | ใช้ได้อิสระ | https://www.python.org/ |
| certifi | 2026.10.23 | Kenneth Reitz | MPL-2.0 | แบ่งปันเฉพาะชิ้นส่วน (ไม่แก้ไข) | https://github.com/certifi/python-certifi |
| AndroidX (Compose BOM, Activity, Lifecycle, WorkManager, Fragment ฯลฯ) | ตาม Gradle | The Android Open Source Project | Apache-2.0 | ใช้ได้อิสระ | https://developer.android.com/jetpack |
| Media3 (ExoPlayer, UI, Session) | 1.11.1 | The Android Open Source Project | Apache-2.0 | ใช้ได้อิสระ | https://github.com/androidx/media |
| Kotlin & kotlinx.coroutines | 2.4.21 | JetBrains | Apache-2.0 | ใช้ได้อิสระ | https://kotlinlang.org/ |
| Coil 3 | 3.6.3 | Coil contributors | Apache-2.0 | ใช้ได้อิสระ | https://github.com/coil-kt/coil |
| OkHttp & Okio | ตาม Coil | Square, Inc. | Apache-2.0 | ใช้ได้อิสระ | https://square.github.io/okhttp/ |
| Guava (`ListenableFuture`) | ตาม Media3 | Google | Apache-2.0 | ใช้ได้อิสระ | https://github.com/google/guava |
| Material Symbols (Rounded) | ตาม Compose | Google | Apache-2.0 | ใช้ได้อิสระ | https://fonts.google.com/icons |
| Firebase Crashlytics | BoM 35.2.0 | Google | Apache-2.0 | ใช้ได้อิสระ | https://github.com/firebase/firebase-android-sdk |
| Google Analytics for Firebase (`play-services-measurement`) | BoM 35.2.0 | Google | Google / Firebase Terms | เงื่อนไขของ Google | https://firebase.google.com/terms |

---

## วิธีขอซอร์สโค้ดของชิ้นส่วน LGPL / MPL · How to Obtain LGPL / MPL Source Code

- **ภาษาไทย:**
  - **ส่วนเสริมโซเชียลสำหรับ Windows (v1.0.5):** แจกจ่าย **FFmpeg และ FFprobe รุ่น LGPLv3+ Shared Build** (`n9.0.2-61-gd59078794d-20261120`, คอมไพล์ด้วย `--enable-version3 --enable-shared` โดยไม่มี `--enable-gpl` และไม่มี `--enable-nonfree`) แยกเป็นไฟล์อิสระและ Shared DLL (`*.dll`) พร้อมไฟล์ข้อความใบอนุญาต `LICENSE-ffmpeg.txt` ใน `%LOCALAPPDATA%\MaewDamPC\social-addon\` โดย **ไม่ได้แก้ไขซอร์สโค้ดต้นฉบับ** ผู้ใช้สามารถสลับเปลี่ยนไฟล์ DLL รุ่น LGPL ที่เข้ากันได้ด้วยตนเอง และดาวน์โหลดซอร์สโค้ดตรงรุ่นจาก https://ffmpeg.org/ และ https://github.com/BtbN/FFmpeg-Builds หรือขอรับชุดซอร์สโค้ดตรงรุ่นได้ภายในอย่างน้อย 3 ปีนับจากวันเผยแพร่ผ่านช่องทางอย่างเป็นทางการของ GLee
  - **แอปมือถือ Android (`com.glee.maewdam`):** รุ่นปัจจุบัน **ไม่มีชิ้นส่วนภายใต้สัญญาอนุญาต LGPL** มีเพียง `certifi 2026.10.23` (MPL-2.0) ซึ่งใช้งานตามต้นฉบับโดยไม่ได้แก้ไข สามารถดูและดาวน์โหลดซอร์สโค้ดต้นทางได้โดยตรงที่ https://github.com/certifi/python-certifi
- **English:**
  - **Windows Social Add-on (v1.0.5):** Ships unmodified **FFmpeg / FFprobe LGPLv3+ Shared Build** (`n9.0.2-61-gd59078794d-20261120`, built with `--enable-version3 --enable-shared`, without `--enable-gpl` or `--enable-nonfree`) as standalone binaries and dynamically linked shared DLLs (`*.dll`) with `LICENSE-ffmpeg.txt` inside `%LOCALAPPDATA%\MaewDamPC\social-addon\`, allowing users to inspect or replace the LGPL shared libraries freely. Exact corresponding source code is available at https://ffmpeg.org/ and https://github.com/BtbN/FFmpeg-Builds, and via written offer for at least three (3) years after release through GLee's official channel.
  - **Android APK (`com.glee.maewdam`):** The current Android release does **not** include any LGPL-licensed components; the only file-level copyleft component is unmodified `certifi 2026.10.23` (MPL-2.0) at https://github.com/certifi/python-certifi.
