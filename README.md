# Privacy Policy for Imanvo (ایمانوو)

**Effective Date:** November 2026 (applies to version 1.3 and later)  
**Developer:** Muhammad Iqrar  
**Developer Contact:** muhammadiqrarjrw@gmail.com  
**Repository:** https://github.com/iqrarbaloch145/Imanvo-Quran-Prayer-Times  
**Applicable Platforms:** Huawei AppGallery & Google Play Store

---

## 1. Overview & Privacy Commitment
**Imanvo** ("Faith, Every Day." / "ہر دن، ایمان کے ساتھ") is built with a **Privacy-First, Zero-Tracking** design. We believe personal worship, Holy Quran reading habits, and spiritual supplications should remain private to the individual user.

* **No Accounts Required:** You do not need to register, log in, or provide any personal details to use any feature of Imanvo.
* **No Third-Party Analytics or Trackers:** The app contains no analytics SDKs, no advertising networks, no advertising ID, and no tracking pixels.
* **No Data Selling:** We never sell, lease, or monetize your information under any circumstances.
* **No Developer Server:** Imanvo has no backend of its own. The developer never receives your location, your prayer log, or any other personal data.

---

## 2. Permissions & Data Usage

### A. Location Information (ACCESS_FINE_LOCATION, ACCESS_COARSE_LOCATION)
* **Purpose:** Your location is used only to work out prayer times (Fajr, Sunrise, Dhuhr, Asr, Maghrib, Isha) and the Qibla direction toward the Holy Kaaba in Makkah.
* **Sent to the AlAdhan prayer-times service:** When you are online, your latitude and longitude are sent over an encrypted HTTPS connection to the AlAdhan API (`api.aladhan.com`) to fetch that day's prayer timetable. They are used only for that request. Imanvo does not store them on any server and does not use them for tracking or advertising.
* **City name lookup:** To show your city name, the app asks the phone's built-in Android location service (Geocoder) to turn your coordinates into a city name. This is handled by your phone's system service provider.
* **Offline calculation:** When there is no internet, prayer times and the Qibla direction are calculated entirely on your device.
* **User Control:** Location is optional. You can deny GPS access and choose your city from the built-in list of 140+ cities at any time. In that case only the chosen city's coordinates are used, never your device's position.

### B. Device Sensors (Magnetometer & Accelerometer)
* **Purpose:** Used in real time only to point the Qibla compass. Sensor data is never logged or stored.

### C. Notifications & Alarms (POST_NOTIFICATIONS, SCHEDULE_EXACT_ALARM, RECEIVE_BOOT_COMPLETED, VIBRATE)
* **Purpose:** Delivers optional prayer-time alerts, optional reminders a few minutes before each prayer, and optional Daily Dua reminders.
* **Local Scheduling:** All alerts are scheduled on your device with Android's AlarmManager. They are set up again after the phone restarts. No push servers are used.
* **User Control:** Each prayer alert can be set to sound, silent, or off inside the app, and notifications can be turned off in Android Settings.

### D. Data Stored Only on Your Device
The following stays inside the app's private storage on your phone and is never uploaded:
* Holy Quran bookmarks and last-read Surah and Ayah
* Salah Tracker prayer log and Qada (make-up) counts
* Tasbeeh and custom Dhikr counts
* Learned Names of Allah and morning/evening azkar progress
* Prayer alert, calculation, language, and theme settings
* Downloaded Quran recitation audio files
* Data shown in the home-screen widgets (next prayer, Tasbeeh, Qibla)

### E. Sharing
* When you tap **Share image** on an ayah, the app creates the picture on your phone and hands it to the Android share menu. Nothing is shared unless you choose an app to share it with.
* Shared images and the **Share with family** message include the Imanvo name and a link / QR code to the app's Google Play page. No personal information is added to them.

---

## 3. Third-Party Network Services
Most of Imanvo works offline. When you are online, the app connects to:

| Service | What is sent | Why |
|---|---|---|
| AlAdhan API (`api.aladhan.com`) | Latitude, longitude, date, and calculation method | To fetch accurate daily prayer times |
| islamic.network CDN (`cdn.islamic.network`) | Only the number of the ayah being played or downloaded | To stream or download Quran recitation by Mishary Rashid Alafasy |

All connections use encrypted HTTPS. No name, account, advertising ID, or device identifier is sent. Like any internet service, these providers can see your device's IP address when the app connects to them, under their own privacy policies.

---

## 4. Deleting Your Data
Because everything is stored on your device, you are always in control:
* Delete downloaded audio for any surah from the Quran reader.
* Clear all app data in **Android Settings → Apps → Imanvo → Storage → Clear data**.
* Uninstalling the app removes all of its data from your phone.

There is no copy on any server, so there is nothing else to request or delete.

---

## 5. Children's Privacy
Imanvo is suitable for all ages (Content Rating: Everyone / 3+), but it is not directed at children under 13. We do not knowingly collect personal information from anyone, including children.

---

## 6. Changes to This Policy
If the app's data practices change, this page will be updated and the Effective Date above will change.

---

## 7. Contact & Support
If you have any questions or feedback regarding this Privacy Policy or the application, please contact:
* **Developer:** Muhammad Iqrar
* **Email:** muhammadiqrarjrw@gmail.com
* **Project Link:** https://github.com/iqrarbaloch145/Imanvo-Quran-Prayer-Times
