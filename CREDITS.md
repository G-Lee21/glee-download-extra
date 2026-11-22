# เครดิตชิ้นส่วนและสัญญาอนุญาต · Third-Party Credits & Licenses

**แมวดำมาเย้ย (GLee Load)** แอปมือถือ Android (`com.glee.maewdam`) — ตรวจรายการชิ้นส่วนในชุดแจกจ่าย (APK) ครบทั้ง 243 รายการแล้ว: **ไม่มีชิ้นส่วนแบบบังคับแจกโค้ดทั้งแอป (GPL / AGPL)** และ **ไม่มีชิ้นส่วน LGPL ในรุ่นปัจจุบัน** (แอปไม่ได้ฝัง FFmpeg ใช้ MediaMuxer ในตัว Android)

---

## ชิ้นส่วนในตัวแอป (APK) · Bundled Components

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
  - รุ่นปัจจุบันของ **แมวดำมาเย้ย (GLee Load) Android** **ไม่มีชิ้นส่วนภายใต้สัญญาอนุญาต LGPL** (ไม่ได้รวม FFmpeg ไว้ในไฟล์ APK)
  - ชิ้นส่วนแบบ **แบ่งปันเฉพาะชิ้นส่วน** ในรุ่นปัจจุบันมีเพียง `certifi 2026.10.23` (MPL-2.0) ซึ่งใช้งานตามต้นฉบับโดยไม่ได้แก้ไข สามารถดูและดาวน์โหลดซอร์สโค้ดต้นทางได้โดยตรงที่ https://github.com/certifi/python-certifi
  - หากในรุ่นถัดไปมีการเพิ่มชิ้นส่วนภายใต้สัญญาอนุญาต LGPL ซอร์สโค้ดต้นทางและรุ่นที่ใช้จะถูกระบุไว้ในเอกสารนี้พร้อมสิทธิ์ขอรับชุดซอร์สโค้ดตรงรุ่นภายในระยะเวลาอย่างน้อย 3 ปีนับจากวันเผยแพร่รุ่นนั้น ๆ ผ่านช่องทางอย่างเป็นทางการของ GLee
- **English:**
  - The current Android release of **GLee Load** does **not** include any LGPL-licensed components (FFmpeg is not bundled in the APK).
  - The only file-level copyleft component included is unmodified `certifi 2026.10.23` under MPL-2.0, whose exact source code is available at https://github.com/certifi/python-certifi.
  - Should any future release include an LGPL-licensed library, its exact version and upstream corresponding source links will be listed here, with written-offer source availability for at least three (3) years from the release date through GLee's official channel.
