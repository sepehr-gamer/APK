دفتر حساب حرفه‌ای — پروژه ساخت APK اندروید

این فایل ZIP پروژه Android Studio است، نه خود APK نهایی.
ساخت APK در این محیط ممکن نبود چون Android SDK و ابزارهای build نصب نیستند.

روش ساخت APK:
1) Android Studio را روی کامپیوتر نصب کن.
2) این ZIP را Extract کن.
3) در Android Studio گزینه Open را بزن و پوشه daftar-hesab-android را انتخاب کن.
4) اجازه بده Gradle Sync و نصب Android SDK Platform 35 کامل شود.
5) از منوی Build > Build Bundle(s) / APK(s) > Build APK(s) را انتخاب کن.
6) فایل نهایی معمولاً در app/build/outputs/apk/debug/app-debug.apk ساخته می‌شود.

روش ساده‌تر بدون Android Studio:
- پوشه پروژه را به یک مخزن GitHub آپلود کن.
- از تب Actions، گردش کار Build Android APK را اجرا کن.
- پس از پایان، artifact با نام daftar-hesab-debug-apk را دانلود کن و داخل آن app-debug.apk قرار دارد.

نکته‌ها:
- این پروژه یک APK آزمایشی (debug) می‌سازد و برای نصب شخصی مناسب است.
- داده‌های برنامه در فضای محلی WebView روی همان دستگاه ذخیره می‌شوند؛ پیش از حذف برنامه از اطلاعات پشتیبان بگیر.
- گزینه‌های «ذخیره JSON» و «خروجی CSV» پنجره انتخاب محل ذخیره اندروید را باز می‌کنند.
