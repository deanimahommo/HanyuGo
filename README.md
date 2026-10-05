# HanyuGo 汉语图学 — Android 2.1

اپلیکیشن آموزش زبان چینی از صفر تا متوسط با رابط فارسی/چینی، Pinyin، تون‌ها، یادسپاری تصویری، مرور فاصله‌دار، تلفظ Mandarin و تمرین نوشتن با انگشت.

## ساخت APK بدون نصب Android Studio

این پروژه برای **GitHub Actions** آماده شده است.

1. وارد GitHub شوید و یک Repository جدید بسازید.
2. فایل ZIP را Extract کنید و همه فایل‌های داخل پوشه `HanyuGo-Android-v2` را در Repository آپلود کنید.
3. تغییرات را روی شاخه `main` یا `master` قرار دهید.
4. به بخش **Actions** بروید و workflow با نام **Build HanyuGo APK** را انتخاب کنید.
5. از **Run workflow** اجرا کنید.
6. بعد از اتمام Build، در صفحه اجرای Workflow قسمت **Artifacts**، فایل `HanyuGo-debug-apk` را دانلود کنید.
7. فایل `app-debug.apk` را روی گوشی Android نصب کنید.

> این Workflow از Java 17، Android SDK 35 و Gradle 8.11.1 استفاده می‌کند.

## باز کردن با Android Studio

پوشه پروژه را با Android Studio باز کنید و Gradle Sync را انجام دهید. برای Build محلی، Android SDK 35 و JDK 17 توصیه می‌شود.

## امکانات نسخه

- ۳۰ درس آموزشی
- کارت‌های نویسه با Pinyin و تون
- معنی فارسی و داستان یادسپاری تصویری
- تلفظ Mandarin با Android Text-to-Speech
- مرور فلش‌کارت
- تمرین نوشتن با انگشت
- XP و پیشرفت
- رابط RTL فارسی در کنار متن چینی
- قابل توسعه برای SRS پیشرفته، HSK 1–4 و محتوای بیشتر

## نکته درباره APK

در این محیط APK نهایی کامپایل و تست نشده است؛ Workflow بالا Build را روی سرور GitHub انجام می‌دهد. این روش برای ساخت APK بدون نصب Android Studio روی کامپیوتر مناسب است.
