# นโยบายความเป็นส่วนตัว · Privacy Policy

> อ้างอิงจากโค้ดจริงของ **แมวดำมาเย้ย (GLee Load — Windows v1.0.6)** และ **แมวดำมาเย้ย (GLee Load — Android `com.glee.maewdam`)** · นโยบายฉบับเต็มบนเว็บ: [https://glee-21.firebaseapp.com/privacy.html](https://glee-21.firebaseapp.com/privacy.html)

---

## แมวดำมาเย้ยสำหรับ Windows (GLee Load v1.0.6)
- **ทำงานในเครื่อง 100% ไม่มีล็อกอิน ไม่มีโฆษณา:** ช่องทางสั่งงานในเครื่องฟังเฉพาะ `127.0.0.1` และตรวจสอบโทเค็นประจำเครื่องกับต้นทาง (`Origin`) เสมอ เว็บไซต์อื่นไม่สามารถสั่งงานโปรแกรมได้
- **คุกกี้เฉพาะไฟล์ไม่เก็บถาวร:** เมื่อส่วนขยาย Chrome / Edge ส่งลิงก์ที่ต้องใช้สิทธิ์เข้าสู่ระบบของเบราว์เซอร์ คุกกี้จะถูกส่งใช้ในหน่วยความจำ (RAM) เฉพาะการดาวน์โหลดไฟล์นั้นและลบทิ้งทันที ไม่บันทึกลงดิสก์หรือ `chrome.storage`
- **ตัวนับการใช้งานแบบไม่ระบุตัวตน (ปิดได้ในตั้งค่า):** ส่งเฉพาะจำนวนเหตุการณ์พื้นฐานแบบไม่ระบุตัวตน (เปิดโปรแกรม / โหลดเสร็จ / โหลดพลาด และรหัสภาษา) ไปยัง Google Analytics Measurement Protocol — **ไม่ส่งลิงก์ ชื่อไฟล์ เส้นทางแฟ้ม หรือข้อมูลส่วนตัวใด ๆ เด็ดขาด** สามารถปิดได้ทันทีในแท็บ `ตั้งนิสัยแมว`
- **การเชื่อมต่อภายนอกและการเช็กรุ่นใหม่:** โปรแกรมและ `yt-dlp.exe` เชื่อมต่อตรงไปยังเว็บไซต์ต้นทางของลิงก์ที่ผู้ใช้สั่งเท่านั้น · เมื่อกด **"อัปเดตตัวดึงคลิป"** จะดึงจาก GitHub Releases ของ `yt-dlp/yt-dlp` โดยตรง · **แอปเช็กรุ่นใหม่จาก GitHub วันละครั้ง ไม่ส่งข้อมูลของคุณ ปิดได้ในตั้งค่า**
- *English:* GLee Load for Windows v1.0.6 runs locally on `127.0.0.1` with per-machine token & origin verification, no sign-in, and no ads. Extension cookies are ephemeral in RAM per file and never written to disk. Anonymous basic usage counts (open/done/fail) never include URLs, filenames, paths, or personal data and can be turned off in Settings. The app checks GitHub for updates once a day without sending personal data (also toggleable in Settings).

---

## แอปมือถือ Android — ภาษาไทย

### 1. ไม่มีการล็อกอินและไม่มีโฆษณา
- แอป **ไม่มีระบบสมัครสมาชิก ไม่มีการล็อกอิน Google และไม่เก็บบัญชีผู้ใช้**
- **ไม่มีโฆษณา** และปิดการเก็บรหัสโฆษณาของเครื่อง (Advertising ID / `AD_STORAGE` / `AD_USER_DATA` / `AD_PERSONALIZATION`) ทั้งในโค้ดและไฟล์กำหนดสิทธิ์ของแอป

### 2. ข้อมูลที่เก็บไว้ในเครื่องของคุณเท่านั้น
- ค่าตั้งค่าแอป ประวัติการค้นหา รายการดาวน์โหลด และบันทึกข้อผิดพลาด (Crash log) 20 ครั้งล่าสุด ถูกเก็บไว้เฉพาะในมือถือของคุณ
- ไฟล์วิดีโอและเพลงที่คุณดาวน์โหลดถูกบันทึกไว้ในแฟ้ม `Download` บนมือถือของคุณเอง ไม่ถูกส่งไปเซิร์ฟเวอร์ของ GLee

### 3. ตัวนับการใช้งานและรายงานแอปพัง (ปิดไว้เป็นค่าเริ่มต้น)
- แอปมีสวิตช์ **"ช่วยปรับปรุงแอป"** ซึ่ง **ปิดไว้เป็นค่าเริ่มต้น**
- **เฉพาะเมื่อคุณเปิดสวิตช์นี้เท่านั้น** แอปจะส่งข้อมูลอัตโนมัติแบบไม่ระบุตัวตนไปยัง Google Analytics for Firebase และส่งรายงานเมื่อแอปขัดข้องไปยัง Firebase Crashlytics ได้แก่ การเปิดแอป ระยะเวลาใช้งาน รุ่นแอป รุ่นมือถือ รุ่น Android ประเทศ และบันทึกอาการขัดข้อง
- **ไม่ส่งเด็ดขาด:** ชื่อไฟล์ ชื่อคลิป ลิงก์ คำค้นหา หรือข้อความที่คุณพิมพ์
- **วิธีปิด:** ไปที่ `จูนเครื่อง → ความเป็นส่วนตัว → ช่วยปรับปรุงแอป` เมื่อปิดแล้วแอปจะหยุดส่งทันทีและลบรายงานขัดข้องที่รอส่งออก

### 4. การเชื่อมต่อภายนอกและการเช็กรุ่นใหม่
- **เว็บไซต์ต้นทางของลิงก์:** ลิงก์ที่คุณเปิดหรือดาวน์โหลด แอปเชื่อมต่อกับเว็บไซต์ต้นทางโดยตรง ไม่ผ่านเซิร์ฟเวอร์กลางของ GLee
- **การอัปเดตตัวดึงข้อมูล (`yt-dlp`):** หากคุณกดอัปเดตตัวดึงข้อมูล แอปจะดึงไฟล์รุ่นล่าสุดจากหน้า GitHub Releases ของ `yt-dlp/yt-dlp` โดยตรง
- **การเช็กรุ่นใหม่ของแอป (ตามมาตรฐาน GLee ข้อ 10.2):**
  - **แอปเช็กรุ่นใหม่จาก GitHub วันละครั้ง ไม่ส่งข้อมูลของคุณ ปิดได้ในตั้งค่า**

---

## English (Android)

### 1. No Sign-In & No Ads
- **GLee Load (Android)** has **no account system, no Google sign-in, and no cloud user profile**.
- The app displays **no ads** and explicitly disables Advertising ID collection, ad storage, ad user data, and ad personalization in both code and app manifest.

### 2. Data Stored Only on Your Device
- Your settings, search history, download queue/list, and a short log of the last 20 crashes are stored strictly on your device.
- Downloaded video and audio files are saved directly in your phone's `Download` folder and are never uploaded to GLee servers.

### 3. Usage Statistics & Crash Reports (Opt-In, OFF by Default)
- The **"Help improve the app"** toggle is **OFF by default**.
- **Only when enabled** does the app send Firebase's standard anonymous metrics (app open, engagement time, app version, device model, Android version, country) to Google Analytics for Firebase and crash traces to Firebase Crashlytics.
- **Never collected:** file names, clip titles, URLs, search queries, or anything you type.
- **Turn it off anytime:** `Settings → Privacy → Help improve the app`. Sending stops immediately and any unsent crash reports are deleted.

### 4. External Connections & Update Checks
- **Direct fetching:** Links you open are fetched directly from the website you chose, without routing through any GLee relay server. Updating the bundled `yt-dlp` engine fetches directly from the official `yt-dlp/yt-dlp` GitHub Releases.
- **App update checks:** The app checks GitHub for a new version once a day without sending any of your personal data; this can be turned off in Settings.
- **Full Online Policy:** [https://glee-21.firebaseapp.com/privacy.html](https://glee-21.firebaseapp.com/privacy.html)
